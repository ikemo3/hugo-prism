# hugo-prism

[Hugo][]で、[Prism][]を使ったハイライトを実装するテーマコンポーネントです。

## 前提条件

[Theme Components][]および[Hugo Pipes][]を使用するため、
[Hugo][] 0.43以上が必要です。

## テンプレートへの組み込み方法

テンプレートに以下の2つの記述を追加してください。

```
{{- partialCached "prism-css" . }}
```

```
{{- partialCached "prism-js" . }}
```

## 対応している言語

現在は、自分が個人的に使う可能性があるもののみにしています。

https://prismjs.com/download.html#themes=prism&languages=markup+css+clike+javascript+apacheconf+applescript+c+bash+batch+ruby+django+docker+git+go+groovy+java+json+kotlin+latex+markdown+lua+makefile+objectivec+perl+sql+properties+scss+python+typescript+swift+yaml+vim&plugins=toolbar+show-language+copy-to-clipboard

* Core
* Themes: Default
* Languages:
    * Markup
    * CSS
    * C-like
    * JavaScript
    * Apache Configuration
    * AppleScript
    * Bash
    * Batch
    * C
    * Django/Jinja2
    * Docker
    * Git
    * Go
    * Groovy
    * Java
    * JSON
    * Kotlin
    * LaTeX
    * Lua
    * Makefile
    * Markdown
    * Objective-C
    * Perl
    * .properties
    * Python
    * Ruby
    * Sass (Scss)
    * SQL
    * Swift
    * TypeScript
    * vim
    * YAML
* Plugins:
    * Show Language
    * Toolbar(Show Languageが依存)
    * Copy to Clipboard Button

## ライセンス

MITライセンスです。

[Hugo]: https://gohugo.io/
[Hugo Pipes]: https://gohugo.io/hugo-pipes/
[Theme Components]: https://gohugo.io/themes/theme-components/
[Prism]: https://prismjs.com/
