---
title: "markdown showcase"
date: 2022-02-25 # publish date
startDate: 2022-02-25T08:15:00 # start timestamp of event
endDate: 2022-02-25T14:14:00 # end timestamp of event
tags: ["markdown"]
draft: false
output: ["json", "html"]
type: log
---

Hugo is using [Goldmark](https://github.com/yuin/goldmark) as markdown handler, which is compliant to Commonmark.

Also see [markdown guide](https://www.markdownguide.org/extended-syntax/#task-lists)

## some markdown examples

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

- [x] foo
  - [ ] bar
  - [x] baz
- [ ] bim

1. foo
2. bar
3) baz

### My Great Heading {#custom-id}

~~The world is flat.~~ We now know that the world is round.

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

Code blocks and syntax highlight
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

back to [Heading IDs](#heading-ids)

Gone camping! :tent: Be back soon.

That is so funny! :joy:

[Here](https://gist.github.com/rxaviers/7360908) is a list of emoji you can use.

Another [list](https://gist.github.com/BenjaminHoegh/708c78c55553c9d897ef35446c4339dd)

:de:

I need to highlight these ==very important words==.

H~2~O

X^2^

automatic link

http://www.example.com

disbled automatic link

`http://www.example.com`

