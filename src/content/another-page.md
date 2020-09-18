import ColorSquare from "./components/color-square.js"

# Another page

This is just another page to test navigation between pages.

Here’s a test of including a custom MDX component:

<p>
  <ColorSquare color="rgba(243, 128, 32, 1.0)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.9)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.8)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.7)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.6)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.5)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.4)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.3)"/>
</p>

Here’s the part of the code from this very Markdown file used to make that happen:

```md
---
filename: another-page.md
---
import ColorSquare from "./components/color-square.js"

<p>
  <ColorSquare color="rgba(243, 128, 32, 1.0)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.9)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.8)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.7)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.6)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.5)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.4)"/>
  <ColorSquare color="rgba(243, 128, 32, 0.3)"/>
</p>
```

Here’s a test of a button link:

<Link className="Button Button-is-docs-primary" to="/">Go back home</Link>

Here’s some **bold** text.
