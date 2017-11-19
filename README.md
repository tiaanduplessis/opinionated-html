<div align="center">
    <img width="80%" src="title.png" alt="opinionated HTML">
</div>
<p align="center">A opinionated guide to writing clean and concise HTML markup</p>

## Application

- Use [semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp) elements.
- Use the least amount of markup possible while maintaining standards and semantics. Thus omit needless elements.

## Spacing

- Use consistent number of characters for indentation e.g. 4 spaces
- Do not mix spaces and tabs.
- Use only one level of indentation for each level of element nesting.

## Meta

- Use the HTML5 doctype at the start of each HTML file to enforce standards mode.
- Always include the `html`, `head` and `body` tags.
- Include the language attribute on `html` tag.
- Always include the following meta tags:
    - Character encoding e.g. `<meta charset="utf-8">`
    - Document compatibility e.g. `<meta http-equiv="x-ua-compatible" content="ie=edge">`
    - Viewport meta tag e.g. `<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">`
- See [list](https://gethead.info/) of all available tags for document head.

## Format

- Tag names should always be lowercase.
- Use valueless boolean attributes e.g. `checked` instead of `checked="checked"`.
- Always use double quotes for attribute values.
- Do not add trailling slash for self-closing tags.
- Omit uneeded attributes e.g. `type` attribute of `script` tags.
- Always include closing tags, even if they are optional e.g. `body`.
- Split elements with large number of attributes over lines for readability.

## Attributes

- Element attributes should be added in the following order:
    1. `id`
    2. `class`
    3. `name`
    4. `data-*`
    5. All other attributes

## License

Licensed under the MIT License.