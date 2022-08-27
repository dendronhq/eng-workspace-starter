---
id: 10j5u8fhuap5ecqwvo308l9
title: Architecture
desc: ''
updated: 1661564205599
created: 1661563938947
---

```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```
> Source: https://mermaid-js.github.io/mermaid/#/