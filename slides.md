cat >> slides.md <<'EOF'

<!--
background: url('https://raw.githubusercontent.com/21f3000473-svg/marp-slides/main/assets/test-bg.png')
background-size: cover
background-position: center
-->

# Background Image Slide

This slide demonstrates a background image loaded from the repository's raw URL.

EOF

<!--
background: url('https://raw.githubusercontent.com/21f3000473-svg/marp-slides/main/assets/test-bg.png')
background-size: cover
background-position: center
-->

# Background Image Slide

This slide confirms that a background image is included using a raw GitHub URL.



---
marp: true
theme: default
paginate: true
footer: 'Contact: 21f3000473@ds.study.iitm.ac.in'
---

<!--
_customTheme: |
  :root {
    --primary: #0b67a3;
    --accent: #ff7a59;
    --muted: #6b7280;
  }
  section { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial; }
  h1 { color: var(--primary); }
  .code-block { border-radius: 8px; padding: 1rem; background: rgba(0,0,0,0.04); }
-->

# Product Documentation — SDK v1.2

**Technical Writer:** Paresh  
<div class="author">Contact: 21f3000473@ds.study.iitm.ac.in</div>

---

<!--
background: url('assets/hero-bg.png')
background-size: cover
background-position: center
class: title-slide
-->

# High-level overview

Short bullet points introducing the product, its scope, and audience.

---

## Algorithmic complexity example

Block equation:

$$
T(n) = 2T(n/2) + \Theta(n) \Longrightarrow T(n) = \Theta(n\log n)
$$

Inline: $O(n\log n)$

---

## Code sample

```js
const sdk = new ProductSDK({ apiKey: process.env.PROD_API_KEY });
await sdk.init();
<!--
background: url('assets/test-bg.png')
background-size: cover
background-position: center
-->

# Background image slide

This slide demonstrates a background image stored in `assets/test-bg.png`.
