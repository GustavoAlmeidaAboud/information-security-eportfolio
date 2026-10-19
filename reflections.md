# Part 4: Critical Reflection (Rolfe et al., 2001)

## 1. What? (Description of Experience)
Over the duration of this module, our team embarked on a comprehensive security engineering project designed to identify, mitigate, and manage information system vulnerabilities within a simulated enterprise environment. As part of this team, my responsibilities spanned threat modeling (Unit 2), secure coding implementations (Unit 3 & 7), incident response planning (Unit 8), and final artifact delivery (Unit 11). Throughout the 12 units, we maintained an active e-portfolio documenting our developmental trajectory, weekly discussions, and collaborative milestones. 

A critical juncture in this journey occurred during Unit 6, where our mid-term status document exposed a glaring misalignment between our theoretical threat models and our practical implementation velocity. We had underestimated the complexity of integrating automated static code analysis (SAST) into our continuous integration (CI/CD) pipeline, resulting in build failures and team anxiety. Confronted with mounting technical debt and strict project timelines, we had to re-evaluate our technical stack, redistribute responsibilities, and adopt a more agile, modular approach to security risk management.

## 2. So What? (Analysis and Interpretation)
Reflecting on this critical incident and the broader module experience, I recognise profound lessons regarding technical execution, security governance, and human factors in development teams. 

First, regarding **Security and Risk Management**, I initially viewed risk assessment as a static compliance exercise—a checklist of vulnerabilities (such as the OWASP Top 10) to be ticked off. However, the practical challenges of Unit 7 and Unit 9 demonstrated that security is a dynamic, socio-technical process. As Whitman and Mattord (2021) emphasise, effective risk management requires continuous threat intelligence synthesis and a deep understanding of operational context. When our CI/CD pipeline broke under strict SAST rules, I felt a strong emotional response of frustration and urgency. This anxiety initially tempted me to bypass security controls or disable strict rules to achieve a green build—an ethical hazard that directly mirrors real-world developer friction and "shadow IT" bypasses (Kirlappos and Sasse, 2012). Analysing this reaction through the lens of human-in-the-loop security (Cranor, 2008), I realized how cognitive fatigue and workflow pressures often drive developers to trade security for usability or speed.

Second, reflecting on **Team Collaboration and Professional Conduct**, our early struggles with git branch conflicts and communication silos in Units 4 and 5 highlighted the fragility of team dynamics under pressure. By adopting structured peer review protocols and transparent risk registers, we transformed our team culture from isolated task execution to collaborative problem-solving. This experience underscored the principles of the BCS Code of Conduct (BCS, 2022), particularly the professional duty of care, competence, and public interest. Cybersecurity professionals cannot operate in a vacuum; technical security controls are useless if they alienate development teams or cause operational paralysis.

## 3. Now What? (Actionable Outcomes and Future Development)
The insights gained from this module will fundamentally shape my future practice as a computing and cybersecurity professional:
* **Integration of "Shift-Left" Security:** Moving forward in software development projects, I will advocate for integrating security considerations from inception ("Shift-Left" security) rather than treating security as an afterthought. I have learned that security tools must be carefully tuned to minimise false positives, preventing developer alert fatigue that leads to security bypasses.
* **Empathy in Security Governance:** Recognizing the psychological and operational friction developers face, I will adopt a collaborative approach to risk management—acting as an enabler of secure development rather than a punitive gatekeeper.
* **Continuous Professional Growth:** I plan to apply the rigorous threat-modeling (STRIDE) and incident response frameworks experienced in this module to real-world organisational settings. Furthermore, I will continue refining my e-portfolio maintenance habits as a mechanism for lifelong professional reflection and portfolio demonstration.

---

## References
* British Computer Society (BCS) (2022) *BCS Code of Conduct*. Swindon: BCS, The Chartered Institute for IT. Available at: https://www.bcs.org/membership-and-registrations/become-a-member/bcs-code-of-conduct/ (Accessed: 19 October 2026).
* Cranor, L.F. (2008) 'A framework for reasoning about the human in the loop', *Proceedings of the 1st Conference on Usability, Psychology, and Security (UPSEC '08)*. San Francisco, CA, 14 April. Berkeley: USENIX Association, pp. 1–15.
* Kirlappos, I. and Sasse, M.A. (2012) 'Security education against phishing: a modest proposal for a major rethink', *IEEE Security & Privacy*, 10(2), pp. 24–32.
* Rolfe, G., Freshwater, D. and Jasper, M. (2001) *Critical reflection in nursing and the helping professions: a user’s guide*. Basingstoke: Palgrave Macmillan.
* Whitman, M.E. and Mattord, H.J. (2021) *Principles of information security*. 7th edn. Boston: Cengage Learning.
