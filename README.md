[![Codacy Badge](https://api.codacy.com/project/badge/Grade/ae41749f8e4f44fc97e8e49f1f3c7e4a)](https://www.codacy.com/app/Websecurify/node-codemirror-http?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=websecurify/node-codemirror-http&amp;utm_campaign=Badge_Grade)
[![Follow on Twitter](https://img.shields.io/twitter/follow/websecurify.svg?logo=twitter)](https://twitter.com/websecurify)

# CodeMirror HTTP

HTTP request and response editing module for CodeMirror.

## Usage

```js
var codemirrorHttp = require('codemirror-http');

codemirrorHttp.install(CodeMirror);

editor.setMode('httprequest'); // for http requests
editor.setMode('httpresponse'); // for http responses
```

## Install

	npm install codemirror-http
