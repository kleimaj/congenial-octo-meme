# Why HTML Emails

Emails entail design, development, and marketing. Low risk, high reward.

Litmus is great for testing email campaigns.

### HTML and CSS for Email

Older versions of outlook switched from Internet Explorer to Word for rendering HTML an CSS

#### What Works

- Basic HTML
- Basic CSS
- Table-based design
- Simple semantics (for accessibility)

#### What Doesn't

- Float-based designs
- CSS grid-based designs
- Javascript
- A lot of CSS

### Email-Friendly HTML

_Use these for most things_:
Basic, non-structural containers: **div, span**
Headings: **h1 - h6**
Other text: **p, strong, em**
Images: **img**

> Images must be hosted, for `<img src/>` tags. Src attribute can't be a relative path in an email.

### Email-Friendly CSS

- ~~Linked stylesheets~~
- Embedded styles
- Inline styles

For text:
**color, font-faily, font-size, font-style, font-weight, line-height, text-align**

For block-level elements:
**margin, padding, width, max-width**

## Email Best Practices

#### Links & Buttons

- Use descriptive links
- Embrace link conventions
- Don't use images for buttons

> Use [Buttons.cm](https://buttons.cm/) to create bulletproof html email buttons!

#### Images in Email

**Some guidelines**:

- Make images responsive by default
- Use alternative text
- Stick to the standbys: **jpg, png, gif**
