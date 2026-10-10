```mermaid
flowchart LR
  user@{ img: "https://raw.githubusercontent.com/deltaebisen/mermaid_example/main/actor.svg", label: "顧客", h: 60, constraint: "on" }
  login@{ img: "https://raw.githubusercontent.com/deltaebisen/mermaid_example/main/boundary.svg", label: "ログイン画面", h: 60, constraint: "on" }
  auth@{ img: "https://raw.githubusercontent.com/deltaebisen/mermaid_example/main/control.svg", label: "認証する", h: 60, constraint: "on" }
  account@{ img: "https://raw.githubusercontent.com/deltaebisen/mermaid_example/main/entity.svg", label: "ユーザー", h: 60, constraint: "on" }

  user --- login
  login --> auth
  auth --> account

  classDef default fill:none,stroke:none
```
