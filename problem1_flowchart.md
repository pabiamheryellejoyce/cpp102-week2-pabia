```mermaid
flowchart TD
    A([Start]) --> B[/Input Length/]
    B --> C[/Input Width/]
    C --> D[Area = Length × Width]
    D --> E[/Display Area/]
    E --> F([End])
```

```mermaid
flowchart TD
    A([Start]) --> B[/Input Number/]
    B --> C {Number > 0?}
    C -- Yes --> D[Display "Positive"]
    C -- No --> E{Number < 0?}
    E -- Yes --> F[Display "Negative"]
    E -- No --> G[Display "Zero"]
    D --> H([End])
    F --> H
    G --> H
```

```mermaid
flowchart TD
    A([Start]) --> B[/Input Grade 1/]
    B --> C[/Input Grade 2/]
    C --> D[/Input Grade 3/]
    D --> E[Average = G1 + G2 + G3 / 3]
    E --> F[/Display Average/]
    F --> G([End])
```
