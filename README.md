# Human Capital in the Nordic Countries
This GitHub repository hosts files for the project website, and is intended for use only by project team members. The project website can be found at: https://nickforddk.github.io/OpenHCNC/

# Editing the website
The website is constructed with GitHub pages using files written in Markdown (.md). Markdown is simple, providing a minimal amount of formatting using a text-based editor.

## Files
The website's content is located in the main OpenHCNC folder, and the folders \_articles and \_sources. Each Markdown file includes basic instructions to generate the page. At a minimum, this includes the page _title_ and _layout_ (usually "default"). Other prompts that can be included in the instruction block are:
- _subtitle_: An extension of the page title. Particularly relevant for articles.
- _status_: An optional one-word descriptor for articles. Useful for noting that a paper is ["Completed"](https://nickforddk.github.io/OpenHCNC/articles/rivista).
- _cover_: Allows a cover image for the page title. Images must be saved in the assets/images directory. Contact Nick if there's a specific image you want to include!
- _members_: Lists the project team members that are assigned to the relevant item (eg. an article). Individuals are identified by surname, separated by commas and included in square brackets (see below).  

The instruction block starts and ends with three dashes:

```
---
title: "This is the title of a paper"
subtitle: "And it also has a subtitle"
members: [Jensen, Hansen, Christiansen]
---

Here is the first line of text on the page.
```

The page content immediately follows the instruction block as plain text. The page title (along with any subtitle) is coded into the template -- as such, you do not need to manually enter the title in the page content.

## Formatting
The benefit of Markdown is its simplicity: just insert your text, and the template takes care of the rest! There is a limited range of formatting available to structure the text and highlight information.
```
## Heading
### Sub-heading

_Italics_
**Bold**

Here is an unordered list:
- with this dot point
- followed by another dot point
- and a concluding dot point.

Ordered lists are also possible:
1. This is the first point.
2. Note that you can just mark all points as "1."
3. This will still produce a correctly numbered list.
```

Website links and images can also be included:
```
[text for a link](https://www.yourwebsitehere.com)

![description of an image](image.jpg)
````

We also use tables on the HCNC website, particularly to provide an overview of our source material. Tables are the most complicated piece of Markdown coding: essentially, you have to draw the table using text notation. Each row is a new line of text, each column is separated by a vertical pipe (|), while the table header is separated by dashes (---). An example of a table is:
```
| Navn | By | Dato | Arbejd | 
| --- | --- | --- | --- |
| Jens | Hillerød | 23-06 | Kok |
| Hans | Aalborg | 10-07 | Gartner |
```
When the page is generated, you then get:

| Navn | By | Dato | Arbejd | 
| --- | --- | --- | --- |
| Jens | Hillerød | 23-06 | Kok |
| Hans | Aalborg | 10-07 | Gartner |

(Note that you cannot colour table cells.)

A more complete overview of Markdown coding can be found at the [Markdown Guide](https://www.markdownguide.org/cheat-sheet/).
