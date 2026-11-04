# Architecture
```
┌──────────────────────────────────────────────────────────────┬─────────────────────┐
│ Orchestration                                                │ Governance          │
│                                                              │                     │
│   Agents                 Workflows                           │ • Cost              │
│                                                              │ • Accuracy          │
├──────────────────────────────────────────────────────────────┤ • Performance       │
│ Gateway                                                      │ • Resilience        │
│                                                              │ • Security          │
│   Model GW              MCP GW              A2A GW           │ • Compliance        │
│                                                              │ • Evaluation        │
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
