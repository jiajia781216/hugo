---
title: compare.Ne
description: Returns the boolean truth of arg1 != arg2 && arg1 != arg3.
categories: []
keywords: []
params:
  functions_and_methods:
    aliases: [ne]
    returnType: bool
    signatures: ['compare.Ne ARG1 ARG2 [ARG...]']
aliases: [/functions/ne]
---

```go-html-template
{{ ne 1 1 }} → false
{{ ne 1 2 }} → true

{{ ne 1 1 1 }} → false
{{ ne 1 1 2 }} → false
{{ ne 1 2 1 }} → false
{{ ne 1 2 2 }} → true
```

You can also use the `compare.Ne` function to compare strings, boolean values, dates, slices, maps, and pages.
