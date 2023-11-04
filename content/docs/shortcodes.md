---
title: "Shortcodes"
date: 2023-11-04T18:56:11+01:00
draft: false
weight: 100
---

Hugo permite utilizar shortcodes, pequeños snippets de códigos que Hugo renderizara utilizando una plantilla. Nos sirven para insertar videos de youtube o tweets, por ejemplo.

# Video de Youtube

```
{{</* youtube zMf_xeGPn6s */>}}
```

Resultado:

{{< youtube zMf_xeGPn6s >}}

---

# Tweet

```
{{</* tweet user="reactjs" id="1636441676506906626" */>}}
```

Resultado:

{{< tweet user="reactjs" id="1636441676506906626" >}}
