---
title: upcase
---

Makes each character in a string uppercase. It has no effect on strings which are already all uppercase.

Input
```liquid
{{ "Parker Moore" | upcase }}
```

Output
```text
PARKER MOORE
```

Input
```liquid
{{ "APPLE" | upcase }}
```

Output
```text
APPLE
```
