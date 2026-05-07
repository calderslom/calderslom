### Hi, I'm Aidan – here's a quick debrief of who I am and what I'm up to:

Recent CS grad with a focus on backend and distributed systems. I care about correctness and clarity — in code and in systems design. Strongest in Java and C, with a statistics and data visualization background I'm looking to develop further.

Looking for backend or data-adjacent roles in the **BC Interior** (West Kootenays / Okanagan) or remote positions open to BC-based candidates.

## Tech I am familiar with

**Languages**
<br>

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Haskell](https://img.shields.io/badge/Haskell-5D4F85?style=flat&logo=haskell&logoColor=white)
![XML](https://img.shields.io/badge/XML-005FAD?style=flat&logo=xml&logoColor=white)


**Backend & Data**
<br>

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat&logo=apache&logoColor=white)

**Frontend (I know it, I just don't love it)**
<br>

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)

**Tools**
<br>

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)


## Projects

### Distributed IRC-Style Chat System

A fault-tolerant and scalable chat system built in Java (JDK 21) and deployed via Docker. The platform features gossip-based message replication with vector timestamp ordering, dynamic client routing, and automatic failure recovery through a Primary/Replica addressing layer. The system is designed to be "operator-free" allowing nodes to scale horizontally and integrate into the live network without manual configuration, while clients automatically reconnect and resync upon server failure.

Originally developed as a university group project (CPSC 559), I designed the custom IPC protocol used to coordinate state synchronization an service discovery between chat servers, primary addressing nodes, and replicas. The Primary/Replica addressing layer uses synchronous replication and a Bully-based leader election algorithm to enforce state integrity and prevent data loss during failover. To manage high client concurrency, I developed the networking layer using Java NIO with non-blocking, selector-based socket handling.

Post-submission, I branched the repository and independently invested 60+ hours stabilizing the system. My refinements focused on resolving fundamental bugs in leader election and failover recovery, in addition to migrating to Docker’s internal DNS and implementing dynamic service discovery. This stabilized the system, automated horizontal scaling, and eliminated dependencies on hardcoded IPs.


`Java` `JDK 21` `Java NIO` `Docker` `Gradle` `Distributed Systems`

→ [View repo](https://github.com/calderslom/distributed-chat)

---

### Farrier Business Database & Web App
A full-stack CRUD application for a Farrier to manage their clients, horses, and records, including medical history, shoeing protocols, and invoices. I designed the database schema in collaboration with a real business owner, translating his professional requirements into a structured 3NF model that supports both the practitioner and their clients.

The backend logic was built using PHP and MySQL, utilizing stored procedures for automated workflows and triggers to enforce consistent user provisioning and data integrity so that the system requires less direct maintenance. 

Originally developed as a group-project, I made the following improvements post submission:
- Refactored core features to meet evolving client needs by replacing external image dependencies with local storage and redesigned invoicing to support dynamic line items.
- Modernized the system by containerizing the stack with Docker and automated database initialization to enable straightforward remote hosting (e.g. AWS ECS) and provided seed data and an injection script for testing and demonstration.


`PHP` `MySQL` `Apache` `HTML` `Full Stack`

→ [View repo](https://github.com/calderslom/equiterra)

---

### Human–Food Interaction Research
Two-semester independent research project on how people interact with food through technology. Accepted as a [poster presenter at GI'25(Graphics Interface 2025)](https://graphicsinterface.org/), the longest-running conference in computer graphics and HCI in Canada.

→ [Download the PDF](https://aidanslomanportfolio.wordpress.com/wp-content/uploads/2026/04/bites-and-bytes_cpsc502.pdf)

---

## A bit more about me

- Based in Calgary, hoping to relocate to the BC Interior (Okanagan / Kootenays) — also open to remote roles anywhere in Canada
- Interested in the intersection of data and systems
- Open to new grad backend, data engineering, or systems roles
- Always up for a chat about mountain biking, snowboarding, or cars (anything with an engine honestly).

---

## Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aidan-sloman)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:calder.sloman@alumni.ucalgary.ca)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=aboutdotme&logoColor=white)](https://aidanslomanportfolio.wordpress.com/)
