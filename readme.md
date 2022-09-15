# `vite build` output with vite 3.0.9 (Same output for `vite build --watch`)

```
(function(e){typeof define=="function"&&define.amd?define(e):e()})(function(){"use strict";var e=document.createElement("style");e.innerHTML=`._card_1ycsi_1{padding:2em}
`,document.head.appendChild(e);const n="_card_1ycsi_1",d={card:n};console.log(n)});
```

# `vite build ` output with vite 3.1.0

```
(function(n){typeof define=="function"&&define.amd?define(n):n()})(function(){"use strict";const n="_card_1ycsi_1",e={card:n};console.log(n)});
```

# `vite build --watch` with vite 3.1.0
```
const c = "_card_1ycsi_1";
console.log(c);
ine.amd?define(n):n()})(function(){"use strict";const n="_card_1ycsi_1",e={card:n};console.log(n)});
```
