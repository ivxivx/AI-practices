# Architecture
```
┌──────────────────────────────────────────────────────────────┬─────────────────────┐
│ Entry Point                                                  │ Governance          │
│                                                              │                     │
│   Apps    APIs    Browsers   CLIs                            │ • Cost              │
│                                                              │ • Accuracy          │
├──────────────────────────────────────────────────────────────┤ • Performance       │
│ Orchestration                                                │ • Resilience        │
│                                                              │ • Security          │
│   Agents                 Workflows                           │ • Compliance        │
│                                                              │ • Evaluation        │
├──────────────────────────────────────────────────────────────┤                     │
│ Gateway                                                      │                     │
│                                                              │                     │
│   Model GW              MCP GW              A2A GW           │                     │
│                                                              │                     │
├───────────────────────────────┬──────────────────────────────┤                     │
│ Reasoning                     │ Action                       │                     │
│                               │                              │                     │
│   Models                      │   Tools        Skills        │                     │
│                               │                              │                     │
├───────────────────────────────┴──────────────────────────────┤                     │
│ Data                                                         │                     │
│                                                              │                     │
│   Vector DB              Relational DB           Graph DB    │                     │
│                                                              │                     │
└──────────────────────────────────────────────────────────────┴─────────────────────┘
```
