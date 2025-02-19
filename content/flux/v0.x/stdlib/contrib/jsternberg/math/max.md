---
title: math.max() function
description: >
  `math.max()` returns the maximum value within the array.
menu:
  flux_0_x_ref:
    name: math.max
    parent: contrib/jsternberg/math
    identifier: contrib/jsternberg/math/max
weight: 301
---

<!------------------------------------------------------------------------------

IMPORTANT: This page was generated from comments in the Flux source code. Any
edits made directly to this page will be overwritten the next time the
documentation is generated. 

To make updates to this documentation, update the function comments above the
function definition in the Flux source code:

https://github.com/influxdata/flux/blob/master/stdlib/contrib/jsternberg/math/math.flux#L36-L40

Contributing to Flux: https://github.com/influxdata/flux#contributing
Fluxdoc syntax: https://github.com/influxdata/flux/blob/master/docs/fluxdoc.md

------------------------------------------------------------------------------->

`math.max()` returns the maximum value within the array.



##### Function type signature

```js
(values: [A]) => A where A: Numeric
```

{{% caption %}}For more information, see [Function type signatures](/flux/v0.x/function-type-signatures/).{{% /caption %}}

## Parameters

### values
({{< req >}})
Array of values.



