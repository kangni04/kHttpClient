# kHttpClient

## 描述

Promis+XHR 实现 HTTP 请求结束

## 文件说明

```shell
├── .kHttpClient.js                 # kHttpClient.js

```

## 使用指南

```bash
1、引入文件kCas.js
import kCas from './kCas';

2、调用方法
import 'kHttpClient' from 'kHttpClient';

kHttpClient.get()

```

## 文件以及文件里面的方法说明

`kHttpClient.js`

```bash
/**
 * @param {string} url,必传
 * @param {object} data = { params = {}},必传
 */
 调用 kHttpClient.get()

 /**
 * @param {string} url,必传
 * @param {object} data = {},必传
 */
 调用 kHttpClient.post()

同时兼容了表单提交

```
