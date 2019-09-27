# textlint-rule-kubernetes-website-ja

----

Kubernetesドキュメントの日本語[翻訳スタイルガイド](https://kubernetes-docs-ja.kibe.la/shared/entries/5efe4fa7-d2a1-4a1d-8bc3-ce7ccdc064a6)のルールを厳守することを目的としています。

## Installation

```
npm install textlint-rule-kubernetes-website-ja
```

and install [textlint](https://github.com/textlint/textlint "textlint") either locally or globally.

## Usage

Via CLI

```
$ npm install textlint textlint-rule-kubernetes-website-ja -g
$ textlint --rule kubernetes-website-ja README.md
```

Via `.textlintrc`

```
{
  "rules": {
    "kubernetes-website-ja": true
  }
}
```

## How to publish

```
$ npm run prepublish
$ npm publish
```

