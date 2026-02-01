# Important Information for SECCDC | Spring 2026

## Competition Schedule for Spring 2026 - SECCDC

```
╔════════════════╦═════════════════════════════╦════════════════╗
║      Date      ║           Event             ║      Time      ║
╠════════════════╬═════════════════════════════╬════════════════╣
║  Feb 02, 2026  ║  Test Environment Released  ║  6:00 PM EST   ║
╟────────────────╫─────────────────────────────╫────────────────╢
║  Feb 03, 2026  ║   Test Environment Closed   ║  6:00 PM EST   ║
╟────────────────╫─────────────────────────────╫────────────────╢
║  Feb 07, 2026  ║          Pre-Brief          ║  8:40 AM EST   ║
╟────────────────╫─────────────────────────────╫────────────────╢
║  Feb 07, 2026  ║  Virtual Qualifiers Begin   ║  9:00 AM EST   ║
╟────────────────╫─────────────────────────────╫────────────────╢
║  Feb 07, 2026  ║   Virtual Qualifiers End    ║  5:00 PM EST   ║
╟────────────────╫─────────────────────────────╫────────────────╢
║  Feb 07, 2026  ║           Debrief           ║  5:15 PM EST   ║
╚════════════════╩═════════════════════════════╩════════════════╝
```

## Competition Communication

- SECCDC Discord: [https://discord.gg/4Hvcyh5q9j](https://discord.gg/4Hvcyh5q9j)
- SECCDC Mattermost Server (Internal Environment Only): [https://10.250.250.5/](https://10.250.250.5/)

## Important Sections in Team Packet
### Service Requirements

- On Linux-based machines, bta will run as a systemd service called “bta”. It will run and must run with full root privileges.
- On BSD-based machines, bta will and run as a rc.d service called “bta”. It will run and must run with full root privileges.
- On Windows-based machines, bta will run as a Windows Service called “BTA”. It will run and must run with full SYSTEM privileges.

### Network Requirements

On all operating systems, BTA will require outbound network access so that it can reach 10.250.250.11 on port 443 and 169.254.169.254 on port 80. BTA will periodically reach out to communicate with these locations. It must be able to reach out to these locations without going through a proxy.

### Competition Network Information

```
|     **IP**    | **Hostname** |
|:-------------:|:------------:|
|  10.250.5X.10 |   frontier   |
|  10.250.5X.11 |    drifter   |
|  10.250.5X.12 |    mustang   |
|  10.250.5X.13 |    praire    |
|  10.250.5X.14 |    cactus    |
|  10.250.5X.15 |   governor   |
| 10.250.5X.250 |    sunset    |
| 10.250.5X.252 |    sunrise   |
```

### Off-Limits 

The following machines will not be managed by Blue Team and should not be interfered with or blocked:
- Default Gateway 10.250.1XX.1
- AWS Artifacts 10.250.1XX.2-3

### Scored Users

- alexisj

#### Scored Administrative Users



#### Scored Normal Users