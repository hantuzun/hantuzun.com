---
draft: true
date: 2020-10-28T15:36:39+03:00
lastmod: 2020-10-29T15:36:39+03:00
title: "Blockchain, Cryptocurrencies and Distributed Ledger Technologies"
slug: blockchain-cryptocurrencies-dlt
series: The Science of Blockchain
tags:
- development
- go
- fast-execution
- blogging
---

This is the post summary. The posts begin with a summary that is written just after the TOML header. A special tag ` !--more--` in angle brackets is used to mark the end of summaries.

 <!--more--> 
 -----------

 Continue writing with normal text after the summary. Do not forget to put the horizontal line by using `---`. This document is displaying the capabilities of this static site generator. Therefore, many headings are following.

## Amazing features

### Sidenotes

I'm going through such a pain for the sake of sidenotes.{{% sidenote "sn-example" %}}This is a sidenote! Let's get this a little bit longer so we can see how it performs in multiple lines.{{% /sidenote %}} Then, we continue with a new sentence.

### Tweets

Tweets are displayed when JavaScript is disabled. If JavaScript is enabled, they're displayed in a card format by executing JavaScript from Twitter.

Here's an example tweet: 

{{< tweet 1321860314661531648 >}}

Here's an example of a tweet thread: 

{{< tweet 1321833643355099138 >}}

Use the following syntax in double curly brackets for embedding tweets:

```
< tweet $tweet_id >
```

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
![Example](/images/examples/han.jpg)

**.png:**
![Example](/images/examples/tron.png)

**.svg:**
![Example](/images/examples/nikkei.svg)

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

Here's a simple[^bignote] footnote,[^another] and here's a longer one.[^bignote] Use sidenotes or margin notes unless you need to have a very long footnote. {{% sidenote "sn-example" %}}This is a sidenote!{{% /sidenote %}} As you can see the numberings of sidenotes and footnotes/endnotes are not designed to work together yet.

[^another]: This is a first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

### Tables

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

Alignment:

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |


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

