# Heading

Headings can be created using \#.

Number of \# defines the level of heading.

\# - h1

\#\# - h2

\#\#\# - h3

\#\#\#\# - h4

\#\#\#\#\# - h5

\#\#\#\#\#\# - h6

# Paragraph

By default whatever we write in markdown is a paragraph. And to have line breaks in it, add 2 spaces and return.  
Without 2 spaces, text won't appear in new line even if there will be line breaks in the markdown file.

# Emphasised Text

To create bold text, use the following:

- \*\*{text}\*\* - **double asterisk**
- \_\_{text}\_\_ - **double underscore**

To create bold text, use the following:

- \*{text}\* - _single asterisk_
- \_{text}\_ - _single underscore_

# Quotes

Put **>** in the beginning to create a quote.

> This is a quote.  
> Add 2 spaces, and a newline to get line breaks in quote.

# Code Styles and blocks

Tilde can be used to generate code blocks.

\`ctrl + c\` - `ctrl + c`

For multi-line, use 4 spaces.

    # comment
    function greet() {
      console.log('hello')
    }

Another way is to use 3 tidle sign with optional programming language name.

```js
function greet() {
  console.log("hello");
}
```

# Ordered and unorderd list

Unordered list can be created using:

- \*

* \-

- \+

Ordered list can be created using:

1. \1.
2. \2.
3. \3.

Number value doesn't matter. It can be repeated use of 1.

Nesting can also be done by adding 2 spaces and then using list syntax again.

- JavaScript
  - React
  - Vue
  - Angular

Line breaks can be added using 2 spaces and a return.

# Horizontal line

Horizontal line can be created using 3 or more asterisks, dashes, or underscore.

- \---
- \*\*\*
- \_\_\_

# Links

Normal links:  
\[label](link) - [Google](https://www.google.com)

Referenced links:  
\[label][ref] - [Google][google]  
\[ref]: (link) "title"

[google]: https://www.google.com "Google"

Another way is to wrap the link or email in < and >  
\<link/email> - <https://www.google.com>

# Images

Normal image:  
\![alt]\(src)  
![demo](https://placehold.co/100)

Referenced image:  
\![alt][ref]  
\[ref]: link "alt"

![Demo][imgRef]

[imgRef]: https://placehold.co/100 "Demo"

# HTML

HTML works inside markdown. So, if something is not achievable via markdown, one can use inline HTML.

<input />

Above is the input box generated using input tag.

# Tablef

\| head1 \| head2 \|  
\| ----- \| -----: \|  
\| val \| val \|  
\| val \| val \|

Colon can be used for column alignment.  
Default is left align. Colon in the end means right align, in the begining and end means center align.

| Name | Age | Occupation |
| ---- | --: | :--------: |
| John |  30 | Programmer |
| Jane |  27 |   Tester   |
