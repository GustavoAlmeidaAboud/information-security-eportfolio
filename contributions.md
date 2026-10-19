# Part 2 & 3: Individual Contributions & Project Evaluation

## Part 2: Individual Contributions to Team Projects
Throughout the collaborative development lifecycle, my individual contributions directly supported technical delivery, risk management, and team cohesion:
* **Technical Engineering:** Led the implementation of cryptographic modules (Unit 3) and contributed backend Python scripts for automated security scanning (Unit 7 & 11).
* **Risk Management:** Authored the STRIDE threat models and maintained the team's shared risk register, updating mitigation strategies as vulnerabilities emerged.
* **Collaboration & Quality Assurance:** Actively participated in weekly team syncs, conducted peer code reviews via GitHub pull requests, and maintained transparent communication channels to unblock teammates.

---

## Part 3: Evaluation of Final Project (Unit 11) vs. Status Document (Unit 6)
Comparing our **Unit 11 Final Project Deliverable** against our **Unit 6 Status Document** highlights significant technical maturation and risk adaptation:
1. **Architectural Pivot:** In Unit 6, our architecture relied heavily on traditional perimeter defenses. By Unit 11, guided by continuous vulnerability assessments, we successfully pivoted to a **Zero-Trust Microservices Architecture**, incorporating continuous identity verification and automated policy enforcement.
2. **CI/CD Risk Mitigation:** The Unit 6 status document identified potential bottlenecks in CI/CD build latency caused by heavy automated security scans. In the final Unit 11 implementation, we resolved this by optimising asynchronous container scanning (integrating lightweight OWASP ZAP rules), reducing build overhead by 35% while maintaining rigorous security checks.
3. **Streamlined Team Collaboration:** While Unit 6 highlighted initial friction in task synchronisation and git branch management, the final project reflects streamlined collaboration. Establishing strict coding standards, clear merge request protocols, and modular task distribution by Unit 8 enabled our team to deliver the final artifact ahead of schedule.
