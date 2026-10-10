```mermaid
flowchart LR
  login@{ img: "https://raw.githubusercontent.com/deltaebisen/mermaid_example/main/boundary.svg", label: "ログイン画面", h: 60, constraint: "on" }
  auth@{ img: "https://raw.githubusercontent.com/deltaebisen/mermaid_example/main/control.svg", label: "認証する", h: 60, constraint: "on" }
  account@{ img: "https://raw.githubusercontent.com/deltaebisen/mermaid_example/main/entity.svg", label: "ユーザー", h: 60, constraint: "on" }

  login --> auth
  auth --> account

  classDef default fill:none,stroke:none
```