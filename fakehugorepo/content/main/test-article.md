---
title: "The Test Article"
authors:
  - Nicholas Kross
date: 2021-01-15
draft: False
tags: ["hi"]
summary: "A test article."
---
# Hi there!
Below is the picture. Notice how it works in `hugo server`, but *not* in `hugo`.


![Example image](/static/random_public_domain.jpg)
When building on Windows 10 (yes, with the extended version of Hugo), I get an error:

```
C:\......\fakehugorepo>hugo
Start building sites …
Total in 3335 ms
Error: Error copying static files: open C:\......\fakehugorepo\public\static\random_public_domain.jpg: Access is denied.
```
