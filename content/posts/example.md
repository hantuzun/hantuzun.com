---
draft: true
date: 2020-10-28T15:36:39+03:00
lastmod: 2020-10-29T15:36:39+03:00
slug: example
title: "Example Post: On Blockchains, Cryptocurrencies and More"
series: The Science of Blockchains
tags:
- development
- go
- fast-execution
- blogging
hasMath: true
---

This is the post summary. The posts begin with a summary that is written just after the TOML header. A special tag ` !--more--` in angle brackets is used to mark the end of summaries.

 <!--more--> 
 -----------

 Continue writing with normal text after the summary. Do not forget to put the horizontal line by using `---`. This document is displaying the capabilities of this static site generator. Therefore, many headings are following.

## Amazing features

### Sidenotes

I'm going through such a pain for the sake of sidenotes.{{% sidenote "sn-example" %}}
This is a sidenote!
{{% /sidenote %}}Then, we continue with a new sentence.

### Marginnotes

There's also marginnotes, notes without numbers.
{{% marginnote "mn-example" %}}
This is a margin note. Let's get this a little bit longer so we can see how it performs in multiple lines.
{{% /marginnote %}}

### $\TeX$ formulas!

Use `$ ... $` or `\\( ... \\)` for some inline math. For instance,
$e^{i \pi} = -1$ where \\(\sqrt{-1} = i \\).

The following syntax gets you blocks:
```tex
$$
\boldsymbol{\sigma}_{t+1} \equiv \Upsilon(\boldsymbol{\sigma}_t, T)
$$
```

$$
\boldsymbol{\sigma}_{t+1} \equiv \Upsilon(\boldsymbol{\sigma}_t, T)
$$

If Markdown parsing is messing up your $\TeX$ formulas, capture the block in any kind of HTML tags, such as `tex`! Below is an example code and its output:

```tex
<tex>
$$
n(\mathfrak{I}, i) \equiv \begin{cases}
() & \text{if} \quad \mathfrak{I} = \varnothing \\
c(\mathfrak{I}, i) & \text{if} \quad \lVert c(\mathfrak{I}, i)\rVert < 32 \\
\texttt{\small KEC}(c(\mathfrak{I}, i)) & \text{otherwise}
\end{cases}
$$
</tex>
```

<tex>
$$
n(\mathfrak{I}, i) \equiv \begin{cases}
() & \text{if} \quad \mathfrak{I} = \varnothing \\
c(\mathfrak{I}, i) & \text{if} \quad \lVert c(\mathfrak{I}, i)\rVert < 32 \\
\texttt{\small KEC}(c(\mathfrak{I}, i)) & \text{otherwise}
\end{cases}
$$
</tex>

TODO: Note that the equivalent parenthesis is problematic. 

**Supported TeX functions:**

We use $\KaTeX$ for displaying formulas. The current version included is `0.12.0`.

Note to myself: As new versions are created, update the library and this section.

Here's the supported $\TeX$ subset of $\KaTeX$: https://katex.org/docs/support_table.html

Make sure to have the following attribute to break long URLs like these.
```css

html {
    word-wrap: break-word;
}
```
### Figures

Below, we have an example of a regular width figure:

{{< figure
  src="/images/posts/example/exports-imports.png"
  class="class param"
  title="The image title."
  caption="This is the image caption."
  label="mn-export-import"
  attr="Image attribution"
  attrlink="https://www.pixsy.com/academy/image-user/correctly-attribute-images/"
  alt="alt"
 >}}
{{< section "end" >}}

Below, is a full-width figure:

{{< figure
  src="/images/posts/example/napoleons-march.png"
  type="full"
  label="mn-napoleonic-wars"
  title="Napoleonic wars"
  caption="This is the image caption."
  attr="Image attribution"
  attrlink="https://www.pixsy.com/academy/image-user/correctly-attribute-images/"
  alt="Napoleonic wars"
 >}}
{{< section "end" >}}

{{< figure
  src="/images/posts/example/pepe.jpg"
  type="margin"
  class="class param"
  label="mn-rhino"
  caption="\"This isn't a pepe\""
  label="mn-export-import"
 >}}
{{< section "end" >}}
And now we exhibit a margin figure with this paragraph. Carefully place your newlines in this case because an unintended paragraph could cause the margin figure to displace.

Margin figures could be useful for including unnecessary images such as memes .


### Newthoughts

<span class="newthought">In his later books</span>, Tufte starts each
section with a bit of vertical space, a non-indented paragraph, and the first few words of the sentence set in small caps.
For this we use a span with the class `newthought`, as demonstrated at the beginning of this paragraph.


### Tweets

Tweets are displayed when JavaScript is disabled. If JavaScript is enabled, they're displayed in a card format by executing JavaScript from Twitter. Do Not Track(DNT) is enabled.

Here's an example tweet: 

{{< tweet 1321860314661531648 >}}

Here's an example of a tweet thread: 

{{< tweet 1321833643355099138 >}}

Use the following syntax in double curly brackets for embedding tweets:

```
< tweet $tweet_id >
```

## YouTube videos

You an embed YouTube videos. Privacy enhanced mode is used.
{{< youtube ZJthWmvUzzc >}}

---

## Markdown Basics (h2)

Do not use h1 (`#`) in your texts. h1 is reserved for the titles only.

### Heading level 3

Heading level 3. Tufte recommends not to use h4 and further.

## Line breaks

You can use two or more spaces (commonly referred to as “trailing whitespace”) for line breaks in nearly every Markdown application, but it’s controversial. It’s hard to see trailing whitespace in an editor, and many people accidentally or intentionally put two spaces after every sentence. For this reason, you may want to use something other than trailing whitespace for line breaks.

Fortunately, there is another option supported by nearly every Markdown application: the <br> HTML tag.

## Font styles

A *cat* meow. Love **is**bold. This is really ***very***important text.	

## Blockquotes

> Dorothy followed her through many of the beautiful rooms in her castle.

With multiple paragraphs:

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

Nested:

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### With Other Elements
Blockquotes can contain other Markdown formatted elements. Not all elements can be used — you’ll need to experiment to see which ones work.


> **The quarterly results look great!**
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

### Lists

**Ordered lists:**

1. First item
2. Second item

**Unordered Lists:**

- First item
- Second item
- Third item
- Fourth item

**Adding Elements in Lists:**

To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab, as shown in the following examples.

Paragraphs
*   This is the first list item.
*   Here's the second list item.

    I need to add another paragraph below the second list item.
    > A blockquote would look great below the second list item.
    ```html
    <html>
      <head>
        <title>Test</title>
      </head>
    ```
    - Indented item
    - Indented item

*   And here's the third list item.

### Horizontal rule

---

Try to put a blank line before...

---

...and after a horizontal rule.

### Links
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

### Formatting links
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).

### Images

**.jpg:**
![Example](/images/posts/example/han.jpg)

**.png:**
![Example](/images/posts/example/tron.png)

**.svg:**
![Example](/images/posts/example/nikkei.svg)

### Escaping Characters
To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\\) in front of the character.

\* Without the backslash, this would be a bullet in an unordered list.

### HTML

To use HTML, place the tags in the text of your Markdown-formatted file. Below is an example using em tags:

This <em>em-word</em> is italic.

---

## Markdown Extensions
<!-- Source https://www.markdownguide.org/extended-syntax/ -->

### Endnotes (TODO)

Use sidenotes or margin notes unless you need to have a very long footnote.{{% sidenote "sn-example" %}}Did you forget what a sidenote is?{{% /sidenote %}} However, you may need to use endnotes in some cases. For instance, I wanted to include an elegant piece of code at the following endnote.[^bignote] As you can see the numberings of sidenotes and endnotes are not working in harmony yet.

[^bignote]: Let's have a function to calculate the Fibonacci series here.

    ```clojure
    (def fib-seq
        (lazy-cat [0 1] (map + (rest fib-seq) fib-seq)))

    user> (take 15 fib-seq)
    (0 1 1 2 3 5 8 13 21 34 55 89 144 233 377)
    ```

    From WikiBooks [Clojure Programming](https://en.wikibooks.org/wiki/Clojure_Programming/Examples/Lazy_Fibonacci).

### Tables

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

Alignment:

| <-     | x      | ->     |
| :---   | :----: | ---:   |
| Orange | Fig    | Banana |
| Plum   | Pear   | Kiwi   |


### Syntax highlighting

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Strikethrough
~~The world is flat.~~ We now know that the world is round.


### Task lists (TODO)

- [x] All things that I've done
- [ ] Removing dots from task lists

### Emojis 😃

🧘🏻‍♂️, 🌍, 🍞, 🚗, 📞, 🎉, ♥️,

### Auto URL 

http://www.example.com

Could be disabled with backticks: `http://www.example.com`

