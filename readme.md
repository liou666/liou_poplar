# Poplar

> 在现有的 poplar 开源库的基础上定制了一些开放性的 api。

A web-based annotation tool for natural language processing (NLP) needs, inspired by [brat rapid annotation tool](http://brat.nlplab.org/).

![screenshot](http://i.v2ex.co/t690JyZS.png)

## Demo

See [https://synyi.github.io/poplar/](https://synyi.github.io/poplar/)

## Quick start

### Install

```shell
npm i liou-poplar
```

or if you'd like to use yarn

```shell
yarn add liou-poplar
```

### Create

```typescript
import {Annotator} from 'liou-poplar'
/**
  * Create an Annotator object
  * @param data          can be JSON or string
  * @param htmlElement   the html element to bind to
  * @param config        config object
  */
new Annotator(data: string, htmlElement: HTMLElement, config?: Object)
```

### More info

View our [API Reference](https://github.com/synyi/poplar/tree/master/doc) here.
