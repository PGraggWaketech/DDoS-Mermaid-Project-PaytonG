```mermaid
sequenceDiagram
participant Attacker
participant BotNet
participant WebServer
participant Firewall

Attacker->>BotNet: send activation command
BotNet->>WebServer: millions of pings
WebServer->>Firewall: Oh god help please stop this
Firewall->>WebServer: absolutely not
```