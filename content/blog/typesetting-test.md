+++
title = "Typesetting Test"
date = 2026-05-26T00:00:00+10:00
draft = false
slug = "typesetting-test"
+++

This is a kitchen-sink test page for the Markdown and HTML typesetting available on this site.

<!--more-->

## Headings

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4

## Paragraphs and inline text

A normal paragraph with **bold text**, _italic text_, **_bold italic text_**, `inline code`, [a link](https://adampetrovic.me/), and a hard line break here:  
this sentence starts on the next line.

Smart punctuation should render nicely: "quotes", 'apostrophes', dashes -- like this -- and ellipses...

## Lists

Unordered list:

- Kubernetes
- GitOps
- Observability
  - Metrics
  - Logs
  - Traces

Ordered list:

1. Build the thing
2. Run the thing
3. Measure the thing
4. Improve the thing

Task list:

- [x] Write a page
- [x] Publish it
- [ ] Add more posts

## Blockquotes

> Good systems are boring in production.
>
> The interesting work happens before they get there.

## Code blocks

```go
package main

import "fmt"

func main() {
    fmt.Println("hello, blog")
}
```

```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: example
spec:
  replicas: 2
```

## Tables

| Area | Tool | Notes |
| --- | --- | --- |
| Infra | Talos | Immutable Kubernetes nodes |
| GitOps | Flux | Declarative cluster changes |
| Storage | Rook-Ceph | Distributed storage at home |

## Horizontal rule

Above the rule.

---

Below the rule.

## Images

![A placeholder image](https://placehold.co/800x300?text=Adam%27s+Blog)

## Footnotes

This sentence has a footnote.[^1]

[^1]: Footnotes are useful for side notes without breaking the flow.

## Definition lists

Kubernetes
: A container orchestration system.

GitOps
: A way to manage systems from version-controlled desired state.

## HTML details

<details>
<summary>Click to expand</summary>

Hidden content can include **Markdown-style emphasis** when Hugo permits it, plus plain HTML.

</details>

## Math-like text

Inline symbols can be written directly: `latency ≤ 100ms`, `availability ≥ 99.9%`, and `p95 → p99`.

## Final paragraph

If this page looks good, the site has a useful reference for future posts.
