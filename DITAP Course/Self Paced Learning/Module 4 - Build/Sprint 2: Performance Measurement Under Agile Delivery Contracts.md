# Module 4 Sprint 2

## Using Value-Based Metrics and Modern Incentives in Federal Agile Procurement

### Why Modern Metrics Matter More Than Ever

Federal agencies now deliver digital services at unprecedented scale and speed. Citizens expect government services to work as well as commercial apps they use daily. Traditional procurement metrics, focused on requirements compliance and schedule adherence, don't capture whether we're delivering value to users.

Modern metrics help you answer the questions that matter:

* Are citizens able to accomplish their goals more easily?  
* Is the system reliable and secure?  
* Are we delivering value continuously, not just at the end?  
* Can we respond quickly when users' needs change?

You need metrics that work in today's environment, which includes remote teams, cloud-native development, continuous deployment, and user-centered design. This module demonstrates how to measure what matters and create incentives that drive tangible outcomes.

### DevOps Research and Assessment (DORA) Metrics 

The DevOps Research and Assessment framework remains the gold standard, but federal applications require additional context:

1. **Deployment Frequency**  
   * **What it measures:** How often your team releases new features or fixes  
   * **Why it matters:** Frequent deployments mean faster value delivery and reduced risk  
   * **Federal context:** Factor in approval processes and security requirements  
   * **Target:** Elite performers deploy multiple times per day; start with weekly goals  
       
       
2. **Lead Time for Changes**  
   * **What it measures:** Time from code commit to production deployment  
   * **Why it matters:** Shorter lead times mean faster response to user needs  
   * **Federal context:** Include security scanning and compliance checks  
   * **Target:** Less than one week for most changes  
3. **Change Failure Rate**  
   * **What it measures:** Percentage of deployments that cause production issues  
   * **Why it matters:** Quality matters as much as speed  
   * **Federal context:** Define "failure" clearly \- service outages, security issues, user impact  
   * **Target:** Less than 15% failure rate  
4. **Failed Deployment Recovery Time**  
   * **What it measures:** Time to restore service after a failed deployment  
   * **Why it matters:** Resilience is critical for government services  
   * **Federal context:** Include incident response and communication requirements  
   * **Target:** Less than one hour for most issues

### User-Centered Metrics

These metrics focus on actual user experience and mission impact:

1. **Digital Service Standard Compliance**  
   * Accessibility (Section 508\) compliance rate  
   * Mobile responsiveness across devices  
   * Page load times under 3 seconds  
   * Plain language readability scores  
2. **User Success Metrics**  
   * Task completion rates for key user journeys  
   * Time to complete common tasks  
   * User satisfaction scores (surveys, feedback)  
   * Support ticket volume and resolution time  
3. **Operational Excellence**  
   * System uptime and availability  
   * Security incident response time  
   * Data accuracy and completeness  
   * Backup and disaster recovery testing

**Team Performance Metrics**

These help you assess contractor team health and collaboration:

1. **Sprint Predictability**  
   * Percentage of sprint commitments completed  
   * Velocity consistency over time  
   * Scope creep within sprints  
2. **Collaboration Quality**  
   * Stakeholder meeting attendance and participation  
   * Code review completion rates  
   * Documentation quality and completeness  
   * Knowledge sharing between team members

### Tools for Modern Federal Procurement Oversight

**Government-Approved DevOps Platforms**

Choose tools that meet federal security requirements:

**Cloud-Native Options:**

* **AWS GovCloud** with native CI/CD pipelines  
* **Azure Government** with DevOps integration  
* **Google Cloud for Government** with source control

**FedRAMP-Authorized Tools:**

* **GitHub Government** (widely used, good metrics dashboards)  
* **GitLab Dedicated** (comprehensive DevOps platform)  
* **ServiceNow** (for broader IT service management)

**Project Management and Collaboration**

**Recommended for Federal Use:**

* **Jira Government Cloud** (most common for agile tracking)  
* **Microsoft 365 Government** (integrated project management)  
* **Slack for Government** (team communication)  
* **Zoom for Government** (meetings and demos)

**User Research and Analytics**

**Privacy-Compliant Options:**

* **Digital Analytics Program** (government-wide web analytics)  
* **Touchpoints** (OMB-approved user feedback collection)  
* **UserTesting Government** (usability research)  
* **Qualtrics Government** (surveys and feedback)

**Selection Criteria:**

* FedRAMP authorization or equivalent  
* Support for government security requirements  
* API access for custom reporting  
* Integration with existing agency tools  
* Cost-effectiveness for government use

### Modern Incentive Structures for Agile Contracts

**Designing Effective Incentives for Agile Contracts**

**Before Adding Incentives, Ask:**

* What specific behavior or outcome do you want to encourage?  
* Will the incentive motivate the people doing the work?  
* Are you rewarding above-and-beyond performance, not basic expectations?  
* How will you measure success fairly and objectively?

**Modern Monetary Incentives**

**1\. Value Delivery Incentives:** Structure payments around user outcomes, not just deliverables:

* **User Adoption Bonuses:** Extra payment when usage exceeds targets  
* **Performance Improvement Awards:** Bonuses for measurable improvements in key metrics  
* **Quality Excellence Fees:** Awards for consistently low defect rates

**Example:** "Contractor receives $25,000 bonus for each quarter where user task completion rate exceeds 85% and user satisfaction scores exceed 4.0/5.0."

**2\. Continuous Delivery Incentives** Reward sustainable development practices:

* **Sprint Consistency Awards:** Bonuses for meeting sprint commitments over time  
* **Deployment Frequency Bonuses:** Rewards for maintaining a regular release cadence  
* **Recovery Time Excellence:** Awards for the quick resolution of production issues

**Example:** "Contractor receives award fee of 5% of quarterly payments for maintaining deployment frequency of at least weekly with less than 10% failure rate."

**3\. Team Stability Incentives** Encourage keeping good people on the project:

* **Retention Bonuses:** Payments for keeping key team members throughout the contract  
* **Knowledge Transfer Awards:** Bonuses for effective onboarding and documentation  
* **Skill Development Incentives:** Support for team training and certification

**Example:** “Contractor receives a $10,000 bonus if 85% or more of the originally proposed team members in labor categories X, Y, and Z remain continuously assigned to the project throughout the base period, with no more than two unplanned substitutions.”

**Effective Non-Monetary Incentives**

**1\. Increased Autonomy** \- High-performing teams earn more flexibility:

* Streamlined approval processes for routine changes  
* Greater technical decision-making authority  
* Reduced reporting requirements

**2\. Recognition and Growth**

* Opportunities to present at government conferences  
* Case studies highlighting successful practices  
* Participation in government-wide communities of practice

**3\. Future Partnership Opportunities**

* Consideration for follow-on work or expansions  
* Eligibility for innovative contract vehicles  
* Partnership on pilot programs or new initiatives

**4\. Professional Development**

* Access to government training and resources  
* Opportunities to contribute to agency standards  
* Participation in cross-agency working groups

### Implementation Guidance 

Designing incentives is a team effort. The program office, product manager, and COR bring delivery insight to define what matters and how to measure it. The CO helps translate that into contract language. Together, they create realistic incentives that support mission success.

**Selecting the Right Metrics**

When selecting metrics for your agile contract:

1. Focus on a small number of high-impact metrics (5-7 maximum)  
2. Ensure metrics are objective and measurable  
3. Include both process metrics (how work is done) and outcome metrics (what value is delivered)  
4. Establish realistic baseline expectations before setting targets  
5. Plan for regular review and refinement of metrics as the project evolves  
   

**Structuring Effective Incentives**

When designing incentives:

1. Align incentives with genuine value delivery, not just compliance activities  
2. Make sure incentives are "tied to the process and ~~to~~ the release of functional code."  
3. Consider using shorter performance periods with more frequent evaluation  
4. Structure incentives to encourage collaboration rather than competition  
5. Ensure incentives reach the actual team members performing the work  
   

**Contract Administration Considerations**

1. Establish clear processes for metrics collection and verification  
2. Define the cadence for metrics review (typically aligned with sprint or release cycles)  
3. Document how metrics will inform contract decisions  
4. Train CORs specifically on agile metrics evaluation  
5. Create feedback mechanisms to share performance insights with contractors

### Implementing Modern Metrics and Incentives

**Setting Up Your Metrics Program**

**Week 1: Establish Baseline**

* Meet with the contractor to review available data  
* Select 5-7 key metrics that align with mission goals  
* Set up data collection and reporting processes  
* Establish realistic initial targets

**Month 1: Refine and Adjust**

* Review initial data collection  
* Adjust metrics based on what's valuable  
* Train COR on metrics interpretation  
* Establish a regular review schedule

**Quarterly: Strategic Review**

* Assess overall trends and patterns  
* Adjust targets based on team maturity  
* Consider adding or removing metrics  
* Plan incentive payments or adjustments

**Common Implementation Mistakes to Avoid**

1. **Too Many Metrics:** Focus on what matters most, not everything you can measure  
2. **Conflicting Incentives:** Ensure metrics don't work against each other  
3. **Unrealistic Targets:** Set achievable goals that motivate improvement  
4. **Ignoring Context:** Consider team maturity, technical debt, and external factors  
5. **Set-and-Forget:** Regularly review and adjust metrics as the project evolves

**Sample Contract Language**

**For Metrics:** "Contractor shall provide monthly reports including: (1) DORA metrics dashboard showing deployment frequency, lead time, change failure rate, and recovery time; (2) User satisfaction scores from monthly surveys; (3) Sprint completion rates and velocity trends; (4) System uptime and performance metrics."

**For Incentives:** "Contractor may earn award fees up to 10% of quarterly payments based on: (1) User task completion rates exceeding 80% (3% award fee); (2) Deployment frequency of at least weekly with \<15% failure rate (3% award fee); (3) User satisfaction scores exceeding 4.0/5.0 (2% award fee); (4) Sprint commitment achievement rate exceeding 85% (2% award fee)."

### Discussion Prompt (optional)

For your DITAP discussion assignment, consider a digital service acquisition that you have worked on or heard about and analyze how modern metrics and incentives could be applied:

Choose a digital service your agency currently uses or is developing. This service could be:

* A citizen-facing website or application  
* An internal system or tool  
* A data collection or reporting system  
* A mobile app or service

**Your Task:**

1. **Identify the Service** (2-3 sentences)  
   * What does it do, and who uses it?  
   * What mission outcome does it support?  
2. **Select Metrics** (3-5 metrics)  
   * Choose from the metrics covered in this module  
   * Explain why each metric would be valuable for this specific service  
   * Consider both technical and user-centered metrics  
3. **Design Incentive Structure**  
   * Create one monetary and one non-monetary incentive  
   * Explain how each incentive would motivate better performance  
   * Consider how to measure success fairly  
4. **Implementation Plan**  
   * How would you collect and verify the metrics?  
   * What tools would you use?  
   * How often would you review performance?  
   * What would you do if performance doesn't meet targets?

   

**Due Date:** Your discussion post is due by the end of the current module, **\[DATE\].**

**Definition of Done:** Your post should address all four elements above in sufficient detail to demonstrate your understanding of modern metrics and incentives in agile procurement. Additionally, respond to at least two classmates' posts with substantive feedback or additional insights.

### Additional Resources

**Official Guidance**

* [TechFAR Hub Contract Types for Agile Development](https://techfarhub.usds.gov/solicitation/contract-design/)  
* [Digital Services Playbook](https://playbook.cio.gov/)  
* [GAO Agile Assessment Guide](https://www.gao.gov/assets/gao-20-590g.pdf)  
* [Section 508 Compliance Guide](https://www.section508.gov/)   
* [FedRAMP Marketplace](https://marketplace.fedramp.gov/) 

**Metrics and Measurement**

* [DORA State of DevOps Report](https://dora.dev/research/)   
* [Digital.gov Analytics](https://digital.gov/guides/dap/)   
* [Federal User Experience Program](https://digital.gov/communities/user-experience/) 


  
**Tools and Templates**

* [DORA Metrics Quick Assessment Tool](https://dora.dev/quickcheck/)  
* [Sample Agile Contract Language](https://techfarhub.usds.gov/resources/learning-center/sample-language-for-government-contracts/)  
* [U.S. Web Design System](https://designsystem.digital.gov/)   
* [Cloud.gov](https://cloud.gov/)  
* [Code.gov](https://code.gov/) 



---
## Post-Award Multi-Vendor Management

Managing a multi-vendor environment in digital services isn’t just a contractual obligation—it’s a leadership responsibility to shape a healthy, productive, and outcomes-focused ecosystem. When multiple vendors are delivering interdependent components, the government’s role evolves from individual contract manager to Delivery Marketplace Architect (yes, you can get a fancy digital service-esque title too\!). 

Your job is to design and sustain the structures—both contractual and cultural—that enable multiple vendors to build toward a shared outcome. Good architecture prevents bottlenecks, supports knowledge flow, and ensures no one vendor becomes the single point of failure.

**This includes:**

* **Structuring transparency** so vendors understand the pipeline of opportunities, task order priorities, and evaluation timelines.  
* **Designing fair, responsive processes** that prevent vendor lock-in and reward meaningful performance, not just incumbency.  
  **Fostering conditions for collaboration** between vendors rather than competition that becomes detrimental.  
* **Curating opportunities for feedback**, continuous improvement, and shared accountability across the ecosystem.

A well-architected delivery marketplace creates the conditions for strong performance, reduced procurement lead times, and continuous improvement—not because vendors are forced to compete, but because the environment inspires quality, trust, and shared success.

Quarterly reviews and joint retrospectives are part of this architecture. These are not just status updates—they are intentional moments where vendors can:

* Raise systemic blockers  
* Recommend procurement or performance process improvements  
* Share engineering or delivery challenges that may affect multiple teams  
* Co-design ways to improve coordination and reduce rework

You’re building more than just contracts—you’re engineering a delivery ecosystem that is resilient, adaptable, and continually optimizing over time. 

### Building the Post-Award Multi-Vendor Strategy

| Element | Practice | Impact |
| ----- | ----- | ----- |
| Governance Hub | Center of Excellence–style team with vendor \+ gov reps | Aligned goals, fast issue resolution |
| Inter-vendor Collaboration | Self-organized working groups, shared tools & practices | Better integration, reduced duplication |
| Retrospectives & QPRs | Joint learning moments, vendor-led feedback | Process improvement & delivery acceleration |
| Joint Root Cause Analysis | Data-driven, transparent reviews | Less blame, more system improvement |
| Procurement Velocity | Targeted TO lead times & pre-positioned templates | Faster delivery starts, less administrative drag |
| Incentive Structures | Award terms, performance bonuses, QASP collaboration metrics | Reward quality and partnership behavior |

### Element:

#### 1\. Ecosystem Governance for Scaled Delivery

Just as commercial organizations like Salesforce have implemented a *Center of Excellence (CoE)* to oversee delivery consistency and platform alignment, government agencies can adopt a similar structure—tailored to the modular contracting environment.

A federal version of a CoE includes:

* Program leads (Product Owners, Technical Leads)

* Contracting stakeholders (CO, COR)

* Vendor delivery managers or SCRUM leads

* Security, compliance, and infrastructure representatives (when applicable)

This team becomes the **multi-vendor governance hub**, accountable for:

* Establishing shared delivery principles and cadence

* Coordinating overlapping timelines and technical dependencies

* Tracking ecosystem-wide delivery health, risks, and blockers

* Updating documentation, practices, and templates based on collective experience

**Benefits:**

* Reduces siloed decision-making

* Enables faster resolution of system-wide issues

* Fosters a shared identity between agency and vendor teams

**Case Study: Salesforce’s Community of Excellence**

Salesforce developed its [*Community of Excellence*](https://www.salesforce.com/blog/build-effective-center-of-excellence/?utm_source=chatgpt.com) to bring cohesion and shared accountability across a complex, multi-vendor delivery environment. Rather than rely solely on top-down oversight, Salesforce created structured forums where delivery partners could meet regularly, exchange insights, surface systemic challenges, and propose improvements to the overall delivery process. These sessions were not just updates—they were designed to foster trust, transparency, and continuous improvement. By encouraging vendors to collaborate—even while competing—Salesforce built a culture where partners felt invested in the success of the entire platform, not just their slice of work. The result was faster issue resolution, better cross-team alignment, and a stronger sense of shared purpose across the delivery ecosystem

#### 2\. Vendor Self-Organization Around Shared Challenges

One of the advantages of a mature, well-managed vendor ecosystem is that teams can begin to **self-organize** around shared engineering or delivery problems. Rather than waiting for direction from government staff, vendors can form cross-vendor working groups to solve problems together.

Examples:

* **Shared DevOps practices:** Vendors agree on pipelines, environments, and approval flows.  
* **Interdependent APIs:** Front-end and back-end vendors collaboratively align interface contracts.  
* **Security enhancements:** Teams propose shared logging or authentication standards across services.

Agencies should **create space for this collaboration**:

* Facilitate regular inter-vendor engineering syncs  
* Assign liaisons or shared technical advisors who float between teams  
* Reward knowledge-sharing in QASP or performance evaluations

#### 3\. Retrospectives and Quarterly Reviews

Retrospectives are not just for internal teams—they’re also essential across the vendor ecosystem.

**Retrospectives:**

* Occur after major delivery cycles or system releases  
* Include all vendors \+ government stakeholders  
* Focus on delivery friction, missed assumptions, or blocked work

**Quarterly Program Reviews (QPRs):**

* Review overall roadmap progress  
* Surface risks across contract vehicles  
* Invite vendors to propose:  
  Procurement process improvements  
  * Changes to performance expectations  
  * Innovations or discovery ideas  
* Encourage vendors to take ownership of ideas that benefit the whole ecosystem.

#### 4\. Collaborative Problem Resolution (Not Blame Culture)

Multi-vendor environments inevitably encounter breakdowns. A healthy system doesn’t eliminate failure—it learns from it faster.

Instead of finger-pointing:

* Emphasize joint root cause analysis (RCA): All involved vendors and stakeholders participate in uncovering what went wrong and why.

* Use data-driven retrospectives: Rely on logs, velocity metrics, backlog records—not assumptions or hearsay.

* Document findings transparently: Avoid confidentiality silos unless required.

* Reinforce psychological safety: People should feel safe owning mistakes in pursuit of the mission.

**Suggested RCA Structure:**

1. What happened?

2. What should have happened?

3. What led to the deviation?

4. What systemic issues enabled it?

5. What do we change going forward?

Add these outputs to shared governance documentation and review regularly in the CoE or program office meetings.

#### 5\. Procurement Agility and Performance Incentives

A critical measure of multi-vendor maturity is the ability to issue and award task orders quickly and fairly.

* Set goals by complexity:

  * Low-risk TOs: \~3 weeks

  * Moderate TOs: ≤ 3 months

  * Complex TOs: ≤ 6 months

  * Avoid dragging out modular awards for a year+

* Reduce friction: Pre-plan templates, slim down evaluation requirements, use oral evaluations, and delegate task order planning when possible.

* Incentivize quality:

  * Consider award term extensions for vendors with exceptional technical performance and inter-vendor collaboration.

  * Use incentive fees for specific behaviors (e.g., mentoring smaller firms, contributing shared tools, cross-vendor fixes).

### Additional Options to Improve Management

Here's a list of additional elements that would strengthen your multi-vendor management architecture:

#### Operational Structures

* **Vendor Onboarding Playbook:** Standardize how new vendors are brought into the ecosystem, including shared tools, security protocols, performance expectations, and definitions of success.

* **Role Clarification Across Teams:** Clearly define how the COR, CO, PO, vendor team leads, and agency stakeholders interact to avoid duplicated or dropped responsibilities.

* **Team Topologies:** Map how vendor teams are structured—e.g., platform team vs. feature teams—and clarify interdependencies.

#### Governance and Oversight

* **Joint Governance Board or Review Panel:** Include rotating vendor representation to increase transparency and co-ownership of improvement ideas.

* **Integrated Risk Registers:** Maintain a centralized view of delivery risks that’s updated collaboratively across vendors and agency leadership.

* **Standardized Task Order Evaluation Criteria:** Reduce variance and the perception of favoritism by using consistent scoring templates and rubrics across awards.

#### Delivery Alignment

* **Shared Product Vision:** All vendors should understand the end goals of the platform or service. Consider using a roadmap wall or “North Star” artifact reviewed quarterly.

* **Backlog Coordination**: Create a shared high-level backlog where features are broken into modular chunks that can be distributed and sequenced across vendors.

* **Dependency Mapping:** Maintain a live dependency matrix across vendors to avoid blockers, duplications, or sequencing issues.

#### Performance Management

* **QASP Metrics for Team Collaboration:** Include metrics for cooperation, responsiveness, joint planning, and support of other vendors.

* **Vendor Self-Assessments:** Let vendors assess their own performance quarterly before retrospectives to promote self-awareness and improvement.

* **Performance Leaderboard or Radar Chart:** Visualize delivery metrics (velocity, quality, collaboration, responsiveness) across vendors for internal government visibility.

#### Culture & Incentives

* **Psychological Safety Practices:** Encourage agencies to model transparency and ownership when issues arise (no scapegoating).

* **Win-Together, Learn-Together Sessions:** Celebrate successful joint releases or key deliveries, with time built in for failure analysis without blame.

* **Performance-Based Incentives:** Use award terms, incentive fees, or task order preference for vendors who consistently collaborate well or exceed delivery goals.

## Summary

Managing multi-vendor digital service contracts isn’t just about awarding and administering discrete scopes of work—it’s about curating a collaborative, high-performing delivery ecosystem. When government teams treat vendors as strategic partners, foster a culture of transparency and fairness, and create structures for joint accountability, the results are faster delivery, better products, and a healthier vendor marketplace. From onboarding and coordination to retrospectives and incentives, every touchpoint offers an opportunity to reinforce shared goals and reduce friction. By embracing the role of a ***Delivery Marketplace Architect*****,** agencies can shape a multi-vendor environment that is adaptive, resilient, and continuously improving—not in spite of its complexity, but because of how intentionally it’s managed.

---
## Knowledge Check: Managing a Multi-Vendor Environment


1\. Multiple Choice

**Which of the following best describes the role of a government team in a multi-vendor digital services environment?**  
*(Select one)*

- [ ] Enforcing strict competition between vendors  
- [ ] Monitoring each vendor individually with no coordination  
- [x] Acting as a Delivery Marketplace Architect to support shared outcomes  
- [ ] Leaving vendors to figure things out on their own

> Correct! The government’s role in a multi-vendor environment is to act as a Delivery Marketplace Architect—supporting coordination, reducing duplication, and guiding teams toward shared outcomes.

---

2\. Select All That Apply

**What is the purpose of joint retrospectives and quarterly program reviews (QPRs)?**  
*(Select all that apply)*

- [ ] Track individual vendor contract compliance  
- [x] Surface system-wide blockers and risks  
- [x] Co-design improvements across teams  
- [x] Celebrate delivery wins and analyze what went wrong

> Correct! QPRs and retrospectives help identify systemic risks, improve coordination, and reflect on both successes and failures—driving continuous improvement.

---

3\. Multiple Choice

**Which of the following is a good example of *vendor self-organization*?**  
*(Select one)*

- [ ] Waiting for the CO to assign tasks  
- [x] Forming a working group to align on shared DevOps tools  
- [ ] Competing with other vendors to block their progress  
- [ ] Ignoring dependencies between contracts

> Correct! Self-organization happens when vendors proactively coordinate, like forming a working group to align on DevOps tools and practices.

---

4\. Short Answer

**Imagine you are reviewing a recurring delivery issue that impacted three vendors. What’s the best next step?**

*Your Response:*  

> **Example of acceptable answer:** “Host a joint root cause analysis to understand what happened and agree on system-level improvements.”

> Tip: Look for systemic issues rather than blaming individual vendors. Consider facilitating a retrospective or coordination session to resolve blockers collaboratively.



---
## Warranties in Agile Development Readings 

As you wrap up Sprint 2, we’re shifting focus to warranties—an important but often overlooked tool in managing performance under agile contracts. The readings below will help you understand how warranties work in federal acquisitions and how they can be used in agile software projects. You’ll learn about the rules in the FAR and explore ways to make sure each part of an iterative product works together. 

### Federal Acquisition Regulation Framework

**Article:** [FAR Subpart 46.7 \- Warranties](https://www.acquisition.gov/far/subpart-46.7)

**Summary:** This official resource outlines the fundamental warranty provisions in federal acquisition. The FAR establishes that warranties are discretionary tools available to Contracting Officers. The regulation defines various warranty types, including warranties of conformance to specifications and warranties of merchantability. It also addresses considerations for commercial items, remedies for breach of warranty, and warranty administration responsibilities.

**Key Takeaways to Address:** 

* What is the legal framework for warranties in federal acquisitions?   
* When should a Contracting Officer consider using a warranty?   
* What are the primary limitations of traditional warranty approaches when applied to software development?

---

The following readings discuss using warranties in Agile development projects. When reading, think about how these techniques can be adopted by your agency:  

**Article:** [The Beauty and Terror of Agile Software Development](https://www.mintz.com/insights-center/viewpoints/2866/2021-03-24-beauty-and-terror-agile-software-development) 

This article discusses contracting challenges in agile development and recommends including warranties that specify "each iteration will work with all other iterations" and "the final product will conform to expectations set out in each SOW" It addresses the unique challenges of warranties in iterative development.

**Key Takeaways to Address:** 

* How can warranties ensure that iteratively developed components will work together in the final system?   
* What language can be used to ensure each sprint's deliverables integrate with previous work?   
* How should warranty periods be structured when system components are delivered through different contracts with varying timelines?

---
**Article:** [Warranties and Liabilities](https://github.com/kristenjernigan/kj-liatest/blob/6eed5df9334353e6fb50c3a350e21dfcdc6bcdaf/Media/Module%204/Chapter_7_-_Warranties_and_Liabilities.pdf) (excerpt from Contracts in Agile Software Development)

In this reading, warranties and liability are compared in traditional contracting to agile contracting. Think about the differences and considerations for each type. 

**Key Takeaways to Address:** 

* Since agile projects typically don't develop comprehensive specifications upfront, what alternative documentation should be used to define warranty scope?  
* Should warranties start after each iteration/sprint, after final acceptance, or use a hybrid approach?  
* How do you define "good enough" software that can be accepted and moved to warranty coverage?  
* What minimal documentation is needed despite the agile principle of "working software over comprehensive documentation"?

## Discussion (Optional)

**Based on the warranty readings, post your response to the following questions:**

* In agile development, when features are created iteratively, what type of language can you use in the warranty to ensure that the vendor is responsible for the outcome of the entire project?  
* Warranties for agile development can be difficult to establish due to the iterative nature. What can you do in both the acquisition strategy phase and the contract administration phase to ensure that you are fully protected by warranty?





