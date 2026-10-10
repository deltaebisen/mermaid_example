```mermaid
flowchart LR
  user@{ img: "https://upload.wikimedia.org/wikipedia/commons/5/5b/Robustness_Diagram_Actor.svg", label: "顧客", h: 60, constraint: "on" }
  login@{ img: "https://upload.wikimedia.org/wikipedia/commons/d/df/Robustness_Diagram_Boundary.svg", label: "ログイン画面", h: 60, constraint: "on" }
  auth@{ img: "https://upload.wikimedia.org/wikipedia/commons/4/44/Robustness_Diagram_Control.svg", label: "認証する", h: 60, constraint: "on" }
  account@{ img: "https://upload.wikimedia.org/wikipedia/commons/3/39/Robustness_Diagram_Entity.svg", label: "ユーザー", h: 60, constraint: "on" }

  user --- login
  login --> auth
  auth --> account

  classDef default fill:none,stroke:none
```