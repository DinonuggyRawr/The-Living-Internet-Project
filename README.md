# The Living Internet: Network & Cybersecurity Academy

**Build Networks. See Connections. Master Security.**

The Living Internet is an interactive 3D networking and cybersecurity educational application developed in Unity and C#. It combines a futuristic cyberpunk environment with hands-on network engineering, interactive lessons, troubleshooting simulations, and defensive cybersecurity investigations.

The goal is simple: **make networking and cybersecurity easier to understand by allowing students to see, build, configure, troubleshoot, and investigate networks instead of only reading about them.**

Designed for beginners and developing IT professionals, The Living Internet bridges the gap between learning networking concepts and applying them through practical experience.

---

## About the Project

Traditional networking and cybersecurity education often relies on textbooks, diagrams, lectures, and command-line demonstrations.

The Living Internet takes a different approach.

What if you could walk through a digital city where buildings represent networking concepts, construct your own virtual networks, watch packets move between devices, investigate suspicious activity, and progressively develop the skills necessary to solve problems independently?

That's the idea behind The Living Internet.

The application blends two interconnected educational experiences with a separate real-world monitoring environment.

## Two Distinct Cities

### Fictional Learning City

A futuristic educational environment containing 13 interactive landmarks dedicated to networking, computing, and cybersecurity.

Students can explore buildings, access educational material, launch simulations, complete challenges, and investigate fictional networks.

The Learning City includes:

- Interactive educational landmarks
- Networking and cybersecurity lessons
- Network Engineering Sandbox
- Simulated device configuration
- Security visualization and investigations
- Educational challenges and assessments
- Guided learning and independent practice

### Internet Observatory

A separate visualization environment representing real monitored websites and network services.

Features include:

- Website availability and health monitoring
- Interactive website buildings
- Service status visualization
- Monitoring history and analytics
- Network relationship visualizations
- A separate Home Network Explorer

The Internet Observatory and fictional Learning City maintain separate data systems to prevent educational simulations from interfering with real monitoring information.

---

## Network Engineering Sandbox

One of the application's primary features is its interactive network engineering environment.

Students can build virtual networks and experiment with configurations in a controlled simulation.

### Features

- Drag-and-drop network topology construction
- Simulated computers, switches, routers, and other devices
- Ethernet connectivity and MAC address learning
- VLAN configuration
- IPv4 addressing, routing, and forwarding
- Simulated DNS, DHCP, and HTTP services
- Visual device configuration
- Simulated IOS-style command-line interface
- Network troubleshooting and diagnostics
- Packet visualization, inspection, and replay
- Undo, redo, and reset operations
- Saveable network configurations and checkpoints
- Guided exercises and independent challenges

The visual interface and simulated CLI operate on shared fictional network state, allowing students to understand how configuration changes affect network behavior.

**All Sandbox networks are simulated. They do not configure physical networking equipment or modify real network settings.**

---

## Cybersecurity Training and Investigation

The Living Internet also includes an interactive defensive cybersecurity training environment.

Students can investigate fictional security incidents, analyze event logs, correlate evidence, and practice defensive decision-making.

### Cybersecurity Features

- Security visualization across the Learning City
- Fictional network boundaries and security controls
- Security monitoring and event logs
- Suspicious activity identification
- Cross-device and cross-building evidence correlation
- Incident timelines
- Defensive response planning
- Containment and recovery exercises
- SOC reporting
- Multi-stage investigation campaigns
- Guided and independent investigation modes

Rather than simply telling students which answer is correct, the application encourages them to examine available evidence, formulate hypotheses, and explain their decisions.

Security exercises use deterministic fictional scenarios and do not attack or modify real networks.

---

## Interactive Network Academy

The Network Academy provides structured educational material for students learning fundamental and advanced networking concepts.

Lessons emphasize visual explanations, experimentation, troubleshooting, and practical understanding.

### Learning Progression

1. **Learn** — Understand a new concept.
2. **Watch** — Observe an interactive demonstration.
3. **Experiment** — Change variables and observe the results.
4. **Practice** — Solve problems with guidance.
5. **Challenge** — Apply knowledge more independently.
6. **Master** — Demonstrate understanding through independent evidence-based assessments.

### Additional Learning Tools

- Interactive 3D and 2D visualizations
- Beginner, intermediate, and advanced learning routes
- Predictions before revealing simulation results
- Misconception-specific feedback
- Visual-to-CLI learning exercises
- Diagnostic reasoning notebook
- Contextual explanations and glossary
- Educational progress tracking
- Optional spaced-retention reviews
- Independent troubleshooting challenges

The educational content is informed by topics found in certifications such as:

- CompTIA Network+
- CompTIA Security+
- Cisco CCNA

**The Living Internet is an independent educational project and is not affiliated with, sponsored by, or endorsed by CompTIA or Cisco.** It is not a substitute for official certification material or hands-on experience with real equipment.

---

## Technology

The application is developed using:

- **Unity 6** — 3D application engine
- **C#** — Application logic and simulation systems
- **Custom networking simulations** — Fictional network behavior and device configuration
- **Unity UI** — Interactive educational interfaces
- **Unity Test Framework** — Automated regression and behavioral testing

The architecture separates real monitoring functionality from
