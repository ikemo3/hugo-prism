# hugo-prism

[Hugo][]で、[Prism][]を使ったハイライトを実装するテーマコンポーネントです。

## 前提条件

[Theme Components][]を使用するため、[Hugo][] 0.42以上が必要です。

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

http://prismjs.com/download.html#themes=prism&languages=markup+css+clike+javascript+apacheconf+applescript+c+bash+batch+ruby+django+docker+git+go+groovy+java+json+kotlin+latex+lua+makefile+markdown+objectivec+perl+sql+properties+python+swift+vim+yaml&plugins=toolbar+show-language

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
    * SQL
    * Swift
    * vim
    * YAML
* Plugins:
    * Show Language
    * Toolbar(Show Languageが依存)

## ライセンス

MITライセンスです。

[Hugo]: https://gohugo.io/
[Theme Components]: https://gohugo.io/themes/theme-components/
[Prism]: https://prismjs.com/
