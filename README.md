NES.css@next Proposal
====
cf. https://github.com/nostalgic-css/NES.css/issues/331

This repository is a proposal that allows more flexibility in changing the styles in NES.css using CSS Custom Properties(CSS Variables).

このリポジトリは、CSSカスタムプロパティを使って、NES.cssのスタイルをより柔軟に変更できるようにするためのProposalです。


```html
<button class="nes-btn my-theme">Reiwa</button>
```

```css
.my-theme {
  --nes-color: #554562;
  --nes-border-color: #554562;
  --nes-background-color: #FADBE0;
  --nes-boxshadow-color: #EAADBD;
}
```

![image](https://user-images.githubusercontent.com/5305599/59089476-294a6180-8945-11e9-916c-37eedfec53a4.png)
