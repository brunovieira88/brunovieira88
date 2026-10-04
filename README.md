# Bruno Vieira

Software Engineering student at Universidade de Aveiro. Backend and distributed systems - from Spring Boot services to an HTTP server written in C.

---

### Projects

**[MIRC - Flood Early-Warning System](https://github.com/1Mii/IES-Project)**
Platform that ingests sensor data, computes flood risk, and maps it for citizens and Civil Protection.
React 19 · Spring Boot · Keycloak (OAuth2/OIDC) · PostgreSQL + PostGIS · Docker Compose · Traefik
Real-time ingestion pipeline, risk-calculation service, geospatial queries, crowdsourced incident reports, role-based dashboards.

**[ReverseProxyRS](https://github.com/bernardo125/ReverseProxyRS)**
Asynchronous multi-protocol reverse proxy built from scratch — HTTP, gRPC and WebSocket behind a single port.
Python · asyncio · aiohttp · gRPC · Protocol Buffers · Docker SDK
Round-robin and least-connections balancing per service, priority queue across protocols, Docker-events service discovery that adds and drops backends live, health checker that evicts failing endpoints, and a `/_proxy/stats` endpoint with queue-wait and latency metrics.

**[PortScape](https://github.com/brunovieira88/PortScape)** · [live demo](https://brunovieira88.github.io/PortScape/)
Turns an nmap scan into an interactive 3D city: each device is a building, height is open ports, colour is risk.
Java 21 · Spring Boot · React 19 · Three.js · PostgreSQL · Testcontainers
Rule-based risk model with explainable scores, CVE lookup against the NVD and CISA KEV, MAC-based device identity and baseline diffing, scans restricted to private networks, 442 tests.

**[Passport Fraud Detector](https://github.com/brunovieira88/passport-fraud-detector)**
Probabilistic pipeline that flags fraudulent passports and links forgery networks.
MATLAB · Python
Naïve Bayes classification, counting Bloom filter for O(1) blacklist lookups, MinHash for similarity clustering.

**[Multithreaded Web Server](https://github.com/brunovieira88/WebServerSO)**
HTTP server written from scratch.
C · pthreads · TCP/IP sockets
Thread-pool concurrency, mutex synchronization, manual memory management, HTTP parsing.

---

### Stack

**Languages**

![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white) ![C](https://img.shields.io/badge/C-%2300599C.svg?style=flat&logo=c&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=dotnet&logoColor=white) ![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white) ![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat&logo=mathworks&logoColor=white)

**Backend & Web**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-59666C?style=flat&logo=hibernate&logoColor=white) ![REST](https://img.shields.io/badge/REST-005571?style=flat&logo=openapiinitiative&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat&logo=socketdotio&logoColor=white) ![OAuth2 / OIDC](https://img.shields.io/badge/OAuth2_%2F_OIDC-EB5424?style=flat&logo=auth0&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white) ![React](https://img.shields.io/badge/React-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%234479A1.svg?style=flat&logo=postgresql&logoColor=white) ![PostGIS](https://img.shields.io/badge/PostGIS-008bb9?style=flat&logo=postgresql&logoColor=white) ![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat&logo=timescale&logoColor=black) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?style=flat&logo=redis&logoColor=white) ![Cassandra](https://img.shields.io/badge/Cassandra-%231287B1.svg?style=flat&logo=apachecassandra&logoColor=white) ![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)

**Infra**

![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white) ![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat&logo=traefikproxy&logoColor=white) ![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat&logo=keycloak&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=flat&logo=git&logoColor=white)

---

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://bruno-vieira.vercel.app/index.html) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bruno-vieiraaa/) [![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:bv721706@gmail.com)
