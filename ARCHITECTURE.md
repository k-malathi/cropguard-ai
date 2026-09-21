# CropGuard AI — System Architecture

## Overall Architecture

```text
                    CROP DATA
                       │
                       ▼
                ┌─────────────┐
                │ AI DETECTION│
                └──────┬──────┘
                       │
                       ▼
                ┌─────────────┐
                │ RISK ENGINE │
                └──────┬──────┘
                       │
                       ▼
              ┌─────────────────┐
              │ DECISION AGENT  │
              └────────┬────────┘
                       │
                       ▼
             ┌──────────────────┐
             │ LOCALIZED        │
             │ CONTAINMENT      │
             └────────┬─────────┘
                      │
                      ▼
                FARMER ALERT
                      │
                      ▼
               FEEDBACK / LEARN
