# Database Security Analysis: MariaDB vs. MongoDB

This project presents a hands-on comparative analysis of the default security configurations of two major database systems: MariaDB (SQL) and MongoDB (NoSQL).

The goal was to evaluate how a standard installation of each database handles critical security controls and to identify potential weaknesses that would need to be addressed in a real-world, sensitive data environment, such as healthcare.

---

### Key Activities

* **Environment Setup:** Installed and configured both MariaDB and MongoDB servers on a local machine.
* **Authentication Hardening:** Implemented and configured modern, secure authentication mechanisms (`ed25519` for MariaDB and `SCRAM` for MongoDB).
* **Security Testing:** Conducted a series of five distinct tests against both databases, evaluating their handling of invalid logins, account locking, password expiry policies, and basic injection attacks.
* **Analysis & Recommendations:** Analyzed the results of the tests to compare the usability and security trade-offs of each system and provided specific recommendations for hardening their default configurations.

### Technologies & Tools
* **Databases:** MariaDB, MongoDB
* **Authentication:** ed25519, SCRAM
* **Languages:** SQL, MongoDB Query API (MQL)
* **Protocols:** The principle of least privilege, CIA Triad (Confidentiality, Integrity, Availability)

---

### [View the Full Technical Report](./Database Security Hardening & Analysis (MariaDB vs. MongoDB).pdf)
