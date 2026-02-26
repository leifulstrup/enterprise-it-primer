---
title: Mermaid Contrast Sandbox
search:
  exclude: true
hide:
  - navigation
  - tags
---

# Mermaid Contrast Sandbox

This page is intentionally isolated for fast Mermaid contrast experiments.
It is not linked in the main navigation.

## Test A: Control (current baseline behavior)

```mermaid
graph TD
    A[Dark blue node] --> B[Dark red node]
    style A fill:#15468A,stroke:#15468A,color:#ffffff
    style B fill:#D8213B,stroke:#D8213B,color:#ffffff
```

## Test B: Explicit text color with classDef

```mermaid
graph TD
    A[Dark blue + explicit text] --> B[Dark red + explicit text]
    C[Light node + dark text]

    classDef darkBlue fill:#15468A,stroke:#15468A,color:#ffffff;
    classDef darkRed fill:#D8213B,stroke:#D8213B,color:#ffffff;
    classDef lightNode fill:#f5f7fa,stroke:#9aa4b2,color:#111111;

    class A darkBlue;
    class B darkRed;
    class C lightNode;
```

## Test C: Mixed fills (dark and light in one diagram)

```mermaid
graph LR
    D[Dark fill] --> E[Light fill] --> F[Dark fill]

    classDef dark fill:#2c3e50,stroke:#2c3e50,color:#ffffff;
    classDef light fill:#ffffff,stroke:#b0b7c3,color:#111111;

    class D dark;
    class E light;
    class F dark;
```

## Test D: `htmlLabels: false` experiment

```mermaid
%%{init: {'flowchart': {'htmlLabels': false}}}%%
graph TD
    A[Dark fill + htmlLabels false] --> B[Light fill + htmlLabels false]

    classDef dark fill:#15468A,stroke:#15468A,color:#ffffff;
    classDef light fill:#ffffff,stroke:#b0b7c3,color:#111111;

    class A dark;
    class B light;
```

## Test E: Inline HTML color in label text

```mermaid
graph TD
    A["<span style='color:#ffffff'>Inline white label</span>"] --> B["<span style='color:#111111'>Inline dark label</span>"]
    style A fill:#15468A,stroke:#15468A
    style B fill:#ffffff,stroke:#b0b7c3
```

## Test F: Force a single label color (white) via Mermaid CSS variables

<div style="--md-mermaid-label-fg-color:#ffffff; --md-mermaid-node-fg-color:#ffffff;" markdown>

```mermaid
graph LR
    A[Dark fill forced white text] --> B[Light fill also forced white text] --> C[Dark fill forced white text]
    style A fill:#15468A,stroke:#15468A
    style B fill:#ffffff,stroke:#b0b7c3
    style C fill:#2c3e50,stroke:#2c3e50
```

</div>

## Expected Outcome

- Dark-filled nodes should be readable with white text.
- Light-filled nodes should remain readable with dark text.
- This page can be used as the first iterative validation target before touching production content.
- If Test D works, `htmlLabels: false` is a viable path.
- If Test E works, inline label markup could be a tactical fallback for specific nodes.
- If Test F works, it confirms this setup can enforce one label color per diagram scope, but not per-node adaptive contrast.
