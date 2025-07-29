# Module 4 Sprint 4

## Federal IT Acquisition, Management, and Software Engineering Practices 

Introduction

You have studied modern software engineering best practices, including DevOps, continuous integration and continuous delivery (CI/CD), DevSecOps, and AI-powered automation. These practices have revolutionized how successful organizations develop and deploy technology solutions. This module examines real federal IT challenges from GAO's 2025 High Risk List to help you apply these modern practices to government acquisition scenarios and understand how effective procurement can prevent systemic IT failures.

---

### The Federal IT Challenge: Context and Scale

**Current State of Federal IT Management**

Federal agencies invest over $100 billion annually in IT, yet much of this spending maintains aging legacy systems rather than implementing innovative solutions. This massive investment has not translated into proportional improvements in citizen services or operational efficiency, creating what the GAO identifies as a persistent high-risk area that requires urgent attention.

Since 2010, GAO has made 1,881 recommendations to federal agencies aimed at improving IT management. As of January 2025, 463 of these recommendations remain unimplemented, indicating systemic resistance to change within government IT operations. In 2025, GAO renamed this high-risk area from "Improving the Management of IT Acquisitions and Operations" to "Improving IT Acquisitions and Management," reflecting the central role that procurement plays in these challenges.

---

### Three Critical Challenge Areas

GAO has identified three challenges that underlie persistent IT problems: strengthening oversight and management of IT portfolios, implementing mature IT acquisition and development practices, and building federal IT capacity and capabilities.

These challenges directly connect to procurement decisions and contract management practices that acquisition professionals control and influence.

#### **Challenge 1: Portfolio Oversight and Management:** 

Traditional procurement approaches often treat IT investments as isolated projects rather than integrated components of a portfolio. This approach leads to duplicative systems, incompatible platforms, and missed opportunities for enterprise solutions.

#### **Challenge 2: Mature Acquisition and Development Practices:** 

Federal acquisitions frequently rely on waterfall methodologies, comprehensive upfront requirements, and traditional contractor relationships that conflict with modern software development best practices.

#### **Challenge 3: Federal IT Capacity and Capabilities:** 

Agencies often lack internal technical expertise to effectively oversee complex IT contracts, leading to inadequate vendor management and poor delivery outcomes.

--- 

### Case Study Analysis: The FAFSA System Modernization

**Procurement Context and Initial Decisions**

The Department of Education's attempt to modernize the Free Application for Federal Student Aid (FAFSA) system provides a revealing case study of how procurement decisions and contract management practices directly impact technical delivery outcomes.

**Contract Award and Structure:** In March 2022, the Department awarded a $121.7 million contract to General Dynamics Information Technology to modernize the FAFSA Processing System. The procurement used traditional approaches with fixed requirements, waterfall delivery expectations, and limited iterative feedback mechanisms.

**Timeline and Mandate Pressures:** Congress mandated system availability by January 1, 2024, creating artificial deadline pressure that influenced both procurement strategy and technical delivery decisions. The contract structure did not adequately account for the complexity of modernizing a 45-year-old system while integrating with IRS data systems.

**Technical Delivery Failures and Acquisition Implications**

**Milestone Management and Oversight:** Twenty-five critical milestones for contract requirements were pushed back by months, signaling early trouble with project management and execution. This pattern indicates inadequate contract performance monitoring and insufficient escalation procedures for addressing delivery risks.

**Quality Assurance and Testing Gaps:** Following deployment, the FSA identified 55 defects in the FPS, with seven categorized as "critical" and 20 remaining unresolved as of August 2024\. FSA told GAO that "they accepted the risk of reducing testing activities because the application cycle was already late and the department was required to launch by the statutory deadline".

This decision reflects fundamental misunderstandings about balancing speed and quality in software delivery—principles that effective procurement structures should embed from contract inception.

**Integration and Data Processing Problems:** The direct IRS data integration, a marquee feature of the new system, failed for approximately 20 percent of applications, necessitating extensive reprocessing. Integration challenges like this are predictable in complex modernization projects and should be addressed through contract requirements for iterative testing and incremental delivery.

**Impact Assessment and Lessons for Procurement Professionals**

**User Impact and Mission Failure:** Over 432,000 fewer students completed the FAFSA compared to the previous year, a 3% decrease with disproportionate impact on lower-income students. The majority of this decrease was attributed to high school seniors and other first-time FAFSA applicants, who experienced a 9% decline in submissions.

Operational Disruption: During the first five months of the FAFSA application cycle, from January to May 2024, the ED's call center received 5.4 million calls; however, only 1.4 million of those calls were answered, meaning nearly three-quarters of calls to ED were left unanswered.

**Recovery Costs and Emergency Measures:** The Department allocated $50 million in federal funding to nonprofit organizations to provide additional support to institutions struggling with the new system, demonstrating how poor initial delivery creates downstream costs that procurement strategies should anticipate and prevent.

--- 

### Modern Acquisition Approaches: Preventing FAFSA-Type Failures

#### Modular Contracting and Incremental Delivery

**Problem with Traditional Approach:** The FAFSA modernization attempted a "big bang" replacement of the entire system, contradicting modern DevOps practices that emphasize incremental delivery and continuous feedback.

**Modern Solution:** Modular contracting breaks extensive IT modernizations into smaller, manageable components that can be delivered independently. Each module undergoes user testing and stakeholder feedback before integration with other elements.

**Practical Application:** Structure contracts to deliver working software increments every 2-4 weeks, with user acceptance testing and stakeholder feedback integrated into each delivery cycle. Include contract clauses requiring demonstrated integration between modules before accepting new functionality.

#### User-Centered Design and Continuous Feedback

**Problem with Traditional Approach:** FSA did not conduct an independent review of the project's processes, products, and risks throughout its life cycle, which limited FSA's ability to identify and address costs and performance risks.

Modern Solution: Embed user research, usability testing, and stakeholder feedback loops directly into contract requirements and payment structures. Require vendors to conduct regular user testing sessions and demonstrate how feedback influences design decisions.

**Practical Application:** Include performance standards that measure user satisfaction, task completion rates, and accessibility compliance—structure payments to reward improvements in user experience metrics rather than simply delivering technical specifications.


#### DevSecOps Integration and Quality Assurance

**Problem with Traditional Approach:** The FAFSA project separated security, testing, and deployment into sequential phases, which prevented the early identification of integration issues and security vulnerabilities.

**Modern Solution:** Require vendors to implement DevSecOps practices with automated testing, continuous security scanning, and integrated deployment pipelines. Include contract language that requires demonstration of these capabilities during the vendor selection process.

**Practical Application:** Establish contract requirements for automated test coverage minimums (e.g., 80% code coverage), security scan frequency (e.g., daily), and deployment automation standards. Include penalties for deploying code that fails automated quality gates.


#### Technical Oversight and Government Capacity Building

**Problem with Traditional Approach:** The Chief Information Officers from both ED and FSA were not involved in governance and oversight activities for the FPS, which is "essential" for successful modernization. Since the FAFSA overhaul began in 2021, there have been six different Education Department CIOs.

**Modern Solution:** Structure contracts to require regular technical reviews with government technical staff, include knowledge transfer requirements, and establish joint government-vendor technical working groups for significant decisions.

**Practical Application:** Require vendors to provide technical training to government staff, document architectural decisions with government review, and establish escalation procedures that involve government technical leadership in delivery decisions.

--- 

### Connecting Modern Practices to Procurement Decisions

**Agile Contract Structures**

DevOps-Enabled Contracting: Use time-and-materials or hybrid contract types that enable iterative delivery while maintaining cost controls through sprint-based budgeting and performance incentives.

Continuous Integration/Continuous Delivery (CI/CD) Requirements: Include contract language requiring automated testing pipelines, deployment automation, and regular delivery cycles. Establish performance standards for deployment frequency, lead time for changes, and mean time to recovery.

**Example Contract Language:** "The contractor shall demonstrate working software increments every two weeks through automated deployment to staging environments. Each increment must pass automated security scans, achieve 85% test coverage, and demonstrate integration with existing system components."

--- 

### Performance-Based Contracting for Quality Outcomes

**User Outcome Metrics**: Replace traditional specification compliance with user-centered performance metrics such as task completion rates, user satisfaction scores, and accessibility compliance measures.

**Technical Quality Standards**: Establish measurable technical quality gates, including automated test coverage, security vulnerability remediation times, and system performance benchmarks.

**Example Performance Standards:**

* User task completion rate: 95% of users complete primary workflows without assistance  
* System availability: 99.9% uptime during business hours with 4-hour maximum downtime for maintenance  
* Security posture: Critical vulnerabilities remediated within 24 hours, high-severity vulnerabilities within 72 hours

--- 

### Risk Management Through Contract Design

**Early Warning Systems:** Establish contract requirements for regular delivery demonstrations, automated quality reporting, and stakeholder feedback collection to identify issues before they become critical failures.

**Escalation and Remediation Procedures:** Include clear procedures for addressing performance issues, technical debt accumulation, and integration challenges through collaborative problem-solving rather than adversarial contract enforcement.

**Exit and Transition Planning:** Require vendors to maintain current system documentation, provide code in government repositories, and create transition plans that ensure service continuity in the event of contract termination.

--- 

### AI-Powered Automation and Federal Acquisition

**Current Trends and Opportunities**

Federal agencies are increasingly integrating artificial intelligence and machine learning into their operations, with agencies establishing Chief AI Officers and implementing AI-powered automation tools. These technologies create new procurement considerations and opportunities.

Automated Requirements Analysis: AI tools can analyze user feedback, support ticket patterns, and system performance data to identify requirements and opportunities for prioritization, informing procurement strategies.

Predictive Analytics for Contract Performance: Machine learning models can analyze historical contract performance data to predict delivery risks, cost overruns, and quality issues before they occur.

Example Applications:

* Utilize natural language processing to analyze user feedback and pinpoint the most critical feature requirements.  
* Implement automated performance monitoring that predicts delivery schedule risks based on velocity trends and quality metrics.  
* Deploy AI-powered testing tools that automatically generate test cases based on user behavior patterns.

--- 

### Procurement Considerations for AI Integration

**Data Rights and Algorithm Transparency:** Establish contract requirements for algorithm explainability, training data documentation, and government rights to inspect and audit AI system decisions.

**Bias Detection and Mitigation:** Include performance standards for algorithmic fairness, bias testing requirements, and remediation procedures for discriminatory outcomes.

**Human Oversight and Control:** Require vendors to maintain human oversight capabilities for AI-powered systems and establish procedures for manual intervention in the event of automated system failures.

---

### Key Takeaways 

1. **Procurement Decisions Drive Technical Outcomes:** Contract structures, performance standards, and oversight approaches directly influence whether IT projects succeed or fail, as seen in the FAFSA modernization.  
2. **Modern Development Practices Require Modern Contracting:** DevSecOps, CI/CD, and agile methodologies need corresponding changes in contract types, performance metrics, and vendor management approaches.  
3. **User-Centered Design Must Be Contractually Mandated:** Successful digital services require continuous user feedback and iterative improvement, which contracts must incentivize and measure.  
4. **Government Technical Capacity Is Essential**: Effective oversight of complex IT modernizations requires internal technical expertise that contracts should help build rather than replace.  
5. **Risk Mitigation Through Early Detection:** Modern contracting approaches emphasize identifying and addressing problems early through automated monitoring, regular delivery cycles, and collaborative vendor relationships.

--- 

### Additional Resources

Federal Guidance and Best Practices

* [GAO High-Risk Series: IT Acquisition and Management](https://www.gao.gov/products/gao-25-107852)  
* [TechFAR Hub: Modern IT Acquisition Practices](https://techfarhub.usds.gov/)  
* [Digital Services Playbook](https://playbook.cio.gov/)

Case Study Materials

* [GAO FAFSA Investigation Reports](https://www.gao.gov/blog/botched-fafsa-rollout-leaves-uncertainty-students-seeking-financial-aid-college)  
* [Department of Education FAFSA Lessons Learned](https://studentaid.gov/)

 

---
## Discussion Instructions

This discussion activity challenges you to apply modern software engineering practices to real federal IT acquisition challenges, using the FAFSA case study and other current examples from GAO's 2025 High Risk List. Your analysis should demonstrate understanding of how contemporary DevOps, CI/CD, and digital transformation practices can address systemic issues that plague federal IT acquisitions.

### Case Study Selection

Choose ONE of the following federal IT challenges for your analysis:

**Option 1: FAFSA System Modernization**

Use the detailed case study from this module, focusing on the $121.7 million General Dynamics contract and the systemic acquisition failures that led to student impact and operational disruption.

**Option 2: IRS Business Systems Modernization**

Examine the ongoing challenges with IRS tax processing system modernization, including the decades-long effort to replace legacy systems and the impact on taxpayer services.

**Option 3: SBA Unified Certification Platform**

Analyze the Small Business Administration's recent attempt to modernize its certification systems, including the deployment challenges and remaining functionality gaps identified by GAO.

**Option 4: Your Agency's Current IT Challenge**

Select a significant IT modernization or acquisition challenge from your own agency experience, applying the same analytical framework used in the FAFSA case study.

---

### Discussion Questions

#### Question 1: Acquisition Strategy Redesign

**Scenario Application**: Apply your selected case study to the threaded case study scenario we've been using throughout this module. How would you restructure the acquisition approach to prevent the failures you've identified?

Specific Analysis Required:

* Contract Structure: How would you modify contract type, performance standards, and payment structures to incentivize modern development practices?  
* Vendor Selection: What evaluation criteria would prioritize vendors with demonstrated DevSecOps and CI/CD capabilities?  
* Oversight Framework: How would you establish government oversight that enables rather than impedes agile delivery methods?  
* Risk Mitigation: What contract mechanisms would provide early warning systems for delivery problems?

**Practical Deliverable:** Design a specific contract clause or statement of work language that addresses one of the root causes you identified in your chosen case study.

**Learning Note:** *Consider how performance-based contracting can incentivize quality outcomes, what role government technical capacity plays in effective oversight, how modular contracting approaches enable iterative delivery, and what contract terms are needed to support DevSecOps integration.*

 

#### Question 2: Building Government Technical Capacity

**Challenge:** Federal agencies often lack internal technical expertise to effectively oversee complex IT contracts, leading to inadequate vendor management and poor delivery outcomes (as demonstrated in the FAFSA case, where CIOs were not involved in governance activities).

**Strategic Response Required:**

* **Capacity Building Strategy:** How would you structure contracts to build government technical capacity rather than simply outsourcing technical decisions?  
* **Knowledge Transfer Requirements:** What specific contract provisions would ensure that government staff gain technical expertise throughout the project lifecycle?  
* **Sustainable Expertise:** How would you address the problem of high turnover in government technical positions (FAFSA had six different CIOs during the modernization period)?  
* **Vendor Partnership Model:** What type of government-vendor collaboration model would maximize learning while maintaining appropriate oversight?

**Practical Application:** Using your threaded case study scenario, design a comprehensive approach for building your agency's internal technical capacity through strategic acquisition planning.

**Learning Note:** *Consider what skills government staff need to effectively oversee modern IT contracts, how to structure vendor relationships that build rather than replace government expertise, what role technical training and certification play in acquisition workforce development, and how to create sustainable technical career paths within government.*

####  Question 3: Performance Measurement and Continuous Improvement

**Industry Context**: Research shows that technical adoption alone doesn't guarantee success—organizational culture, change management, and performance measurement are equally critical for digital transformation success.

**Federal Application Analysis:**

* **Current Challenge:** Why do federal agencies struggle to implement DevOps practices even when contracts require them? (Use specific examples from your chosen case study).  
* **Measurement Framework:** How would you design performance metrics that capture both technical delivery quality and user outcome achievement?  
* **Continuous Improvement**: What contract structures and oversight processes would enable rapid identification and correction of delivery problems?  
* **Cultural Change:** How can acquisition strategies support rather than hinder the cultural changes needed for successful digital transformation?

**Scenario Integration:** Apply your performance measurement framework to the threaded case study, showing how you would track progress and drive continuous improvement throughout the contract lifecycle.

**Learning Note:** *Consider why traditional contract compliance metrics may conflict with agile delivery methods, how to balance accountability with innovation flexibility, what role user feedback should play in contract performance evaluation, and how to structure vendor incentives that promote continuous improvement rather than minimum compliance.*

--- 

### Enhanced Discussion Requirements

**Initial Post Requirements (Due: End of Module 4\)**

Your initial post must include:

1. Case Study Selection and Analysis (300-400 words)  
   * Clearly identify which case study you selected and why  
   * Summarize the key acquisition failures and their root causes  
   * Connect these failures to broader patterns in federal IT acquisition  
2. Question Responses (200-250 words each)  
   * Address all three questions with specific, actionable recommendations  
   * Include at least one concrete example of contract language, evaluation criteria, or oversight procedure  
   * Reference concepts and practices learned throughout the DITAP course

**Peer Engagement Requirements (Due: One week after initial posts)**

Engage meaningfully with at least three classmates' posts by:

1. Comparative Analysis: Compare your approach with classmates who chose different case studies but similar acquisition strategies  
2. Alternative Perspectives: Challenge or build upon classmates' recommendations with specific examples from your experience  
3. Implementation Discussion: Discuss practical challenges of implementing proposed solutions in real federal acquisition environments  
4. Best Practice Synthesis: Identify common themes across different approaches and case studies

**Success Tips**

1. Be Specific: Use concrete examples of contract language, evaluation criteria, or oversight procedures rather than general statements about "better management."  
2. Connect to Acquisition: Every recommendation should clearly show how procurement decisions enable or prevent the desired technical outcomes  
3. Apply Course Concepts: Reference specific DITAP concepts, frameworks, and best practices learned throughout the course  
4. Think Practically: Consider real-world implementation challenges, including budget constraints, regulatory requirements, and political pressures  
5. Learn from Peers: Use peer discussion to refine your understanding and discover alternative approaches to common challenges

---

### Additional Resources for Analysis

Federal Acquisition Context

* [GAO High-Risk Series: IT Acquisition and Management (2025)](https://www.gao.gov/products/gao-25-107852)  
* [TechFAR Hub: Modern Contract Language Examples](https://techfarhub.usds.gov/resources/learning-center/sample-language-for-government-contracts/)  
* [Digital Services Playbook: Acquisition Guidance](https://playbook.cio.gov/)

Technical Best Practices References

* [DevSecOps Implementation Guide for Federal Agencies](https://www.cisa.gov/resources-tools/resources/devsecops)  
* [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)  
* [Federal Cloud Computing Strategy](https://cloud.cio.gov/strategy/)

Case Study Background Materials

* [FAFSA GAO Investigation Reports](https://www.gao.gov/blog/botched-fafsa-rollout-leaves-uncertainty-students-seeking-financial-aid-college)  
* [SBA Unified Certification Platform Report](https://www.gao.gov/products/gao-25-107852)  
* [IRS Modernization Challenges Overview](https://www.gao.gov/products/gao-25-107852)





