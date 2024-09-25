
---
mermaid
sequenceDiagram
participant Attacker
participant BotNet
participant WebServer
participant Firewall
---

sequenceDiagram
    Attacker->>BotNet: Initates flood traffic
    BotNet->>Attacker: Declines the traffic
    create participant Firewall
    Attacker->>Firewall: Try's to send traffic again but is quickly taken note of by the firewall
    Attacker-xCarl: Try's one more attack towards the victim but is blocked by the firewall.
    BotNet->>Attacker: Identifies the issue with help from the firewall and removes the attacker from the server

  
