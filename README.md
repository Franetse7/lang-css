<!-- NOTE: README.md is generated from src/README.md -->

# @codemirror/lang-css [![NPM version](https://img.shields.io/npm/v/@codemirror/lang-css.svg)](https://www.npmjs.org/package/@codemirror/lang-css)

[ [**WEBSITE**](https://codemirror.net/) | [**ISSUES**](https://github.com/codemirror/dev/issues) | [**FORUM**](https://discuss.codemirror.net/c/next/) | [**CHANGELOG**](https://github.com/codemirror/lang-css/blob/main/CHANGELOG.md) ]

This package implements CSS language support for the
[CodeMirror](https://codemirror.net/) code editor.

The [project page](https://codemirror.net/) has more information, a
number of [examples](https://codemirror.net/examples/) and the
[documentation](https://codemirror.net/docs/).

This code is released under an
[MIT license](https://github.com/codemirror/lang-css/tree/main/LICENSE).

We aim to be an inclusive, welcoming community. To make that explicit,
we have a [code of
conduct](http://contributor-covenant.org/version/1/1/0/) that applies
to communication around the project.

## API Reference
<dl>
<dt id="user-content-css">
  <code><strong><a href="#user-content-css">css</a></strong>() → <a href="https://codemirror.net/docs/ref#language.LanguageSupport">LanguageSupport</a></code></dt>

<dd><p>Language support for CSS.</p>
</dd>
<dt id="user-content-csslanguage">
  <code><strong><a href="#user-content-csslanguage">cssLanguage</a></strong>: <a href="https://codemirror.net/docs/ref#language.LezerLanguage">LezerLanguage</a></code></dt>

<dd><p>A language provider based on the <a href="https://github.com/lezer-parser/css">Lezer CSS
parser</a>, extended with
highlighting and indentation information.</p>
</dd>
<dt id="user-content-csscompletion">
  <code><strong><a href="#user-content-csscompletion">cssCompletion</a></strong>: <a href="https://codemirror.net/docs/ref#state.Extension">Extension</a></code></dt>

<dd><p>CSS property and value keyword completion.</p>
</dd>
</dl>
