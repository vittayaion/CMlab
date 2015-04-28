GitHub Markup
This library is the first step of a journey that every markup file in a repository goes on before it is rendered on GitHub.com:

This library converts the raw markup to HTML. See the list of supported markup formats below.
The HTML is sanitized, aggressively removing things that could harm you and your kin—such as script tags, inline-styles, and class or id attributes. See the sanitization filter for the full whitelist.
Syntax highlighting is performed on code blocks. See github/linguist for more information about syntax highlighting.
The HTML is passed through other filters in the html-pipeline that add special sauce, such as emoji, task lists, named anchors, CDN caching for images, and autolinking.
The resulting HTML is rendered on GitHub.com.
Please see our contributing guidelines before reporting an issue.