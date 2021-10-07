# Typographic-library
**Author:** *Šlégl Jan*
## Demo site
Link to **[demo](https://pslib-cz.github.io/2021l4web-typographic-library-SleglJan/)** site for preview.
## Description
Basic style sheet library for use in smaller www projects.
## Implementation
Download style.css and link it to your HTML page by link:css
## Docs
### Typography
Library uses Hind Madurai as text font and Montserrat for headlines. 
#### Usable markdown tags
`<u>`, `<s>`, `<i>`, `<b>`, `<time>`, `<mark>`, `<small>`, `<strong>`, `<em>`, `<a>`
### Blockquotes

standard blockquote syntax is:

```html
<blockquote>
  <p>Quote</p>
  <span class="quote-author">Autor name</span>
</blockquote>
```

### Buttons

#### Works for

`<button>`
`<input class="button">`

Buttons can be disabled by using either 

`<button disabled>`
`<input class="button" disabled>`

### Images
```html
<figure>
 <img src="#" alt="alt">
 <figcaption>Description</figcaption>
</figure>
```
### Darkmode
Darkmode is supported by @mediaquery (prefers-color-scheme: dark), which uses the prefered color scheme set by OS. 
