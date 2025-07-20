# Module 4 Sprint 2

## Using Value-Based Metrics and Modern Incentives in Federal Agile Procurement

As federal procurement professionals, one of your critical responsibilities in agile software development contracts is establishing effective performance monitoring and value-driven project management practices. This module explores modern approaches to metrics and incentives that align with the latest industry practices and federal guidance.

In today's digital service environment, data collection and monitoring are foundational to success. They provide visibility into both team performance and product value delivery, allowing you to make informed decisions about contract management. As noted in the [Digital Services Playbook Play 12](https://playbook.cio.gov/#play12), using data to drive decisions is essential in modern federal procurement.

Why is measuring value delivery critical in an agile environment?

The answer goes beyond traditional compliance monitoring. In agile procurement, effective metrics help you:

1. Validate that government resources are delivering maximum value to end users  
2. Support evidence-based decision making about contract extensions or modifications  
3. Identify and address potential issues before they impact project success  
4. Ensure alignment between contractor performance and agency mission objectives

### Modern Metrics for Agile Federal Procurement

#### Value Stream Metrics

Value stream metrics focus on measuring how efficiently work moves from concept to deployment, aligning with the business outcomes that matter to your agency. These metrics have evolved from traditional project tracking to focus on actual value delivery:


#### DevOps Research and Assessment (DORA) Metrics

The [DORA framework](https://dora.dev/), established by Google Cloud's DevOps Research team, has become the industry standard for measuring software delivery performance. These metrics measure both velocity and stability:

1. **Deployment Frequency** - How often code is deployed to production  
2. **Lead Time for Changes**- How long it takes from code commit to deployment  
3. **Change Failure Rate** - Percentage of deployments causing failures in production  
4. **Failed Deployment Recovery Time** - How long it takes to restore service after a failed deployment

DORA metrics provide a balanced view of both speed and quality, helping procurement officers assess whether contractors are delivering at an appropriate pace while maintaining necessary quality standards.

#### Value Stream Mapping Metrics

These metrics examine the entire flow of value from idea to production:

1. **Flow Time** - Total time from request to delivery  
2. **Flow Efficiency** - Percentage of Flow Time where work is actively being done  
3. **Flow Load** - Amount of work in progress simultaneously  
4. **Flow Velocity** - Number of items completed per time period  
   

Including these metrics in your performance monitoring helps identify bottlenecks, reduce waste, and optimize the delivery process.

#### Product Value Metrics

Modern procurement also focuses on measuring the actual value delivered to users, not just the delivery process:

1. **User Adoption Rate**- Percentage of target users actively using the system  
2. **User Satisfaction**- Often measured through usability surveys or Net Promoter Score  
3. **Business Value Delivered** - Quantifiable improvements in mission capability or efficiency  
4. **Defect Density** - Number of defects relative to size of functionality  
   

These metrics help ensure that contractor performance is evaluated based on meaningful outcomes rather than just outputs.

#### Team Health and Collaboration Metrics

Successful agile contracts require effective collaboration between agency personnel and contractors:

1. **Sprint Completion Rate** - Percentage of committed user stories completed during iterations  
2. **Team Velocity Consistency**- Stability of team output over time  
3. **Cross-Team Dependencies** - Number and impact of dependencies between teams  
4. **Issue Resolution Time** - Speed of addressing and resolving blockers  
   

### Tools for Tracking Modern Metrics

Today's federal procurement officers have access to a wide range of tools that can provide visibility into both contractor performance and value delivery. Consider which of these might be appropriate for your specific acquisition:

#### DevOps and Value Stream Management Platforms

Modern DevOps platforms provide integrated metrics dashboards that can track DORA metrics and value stream performance:

* GitHub Actions/GitHub Enterprise  
* GitLab CI/CD  
* Azure DevOps  
* CircleCI  
* Jenkins

Many of these tools have federal-ready versions that comply with security requirements and can be included as GFE (Government Furnished Equipment) in contracts.

#### Agile Project Management Tools

These platforms help track team performance and collaboration metrics:

* Jira Government Cloud  
* Azure Boards  
* Monday.com Government  
* ServiceNow  
* Rally Software


#### User Research and Analytics Tools

These tools help measure actual usage and user value:

* Google Analytics for Government  
* Mixpanel  
* Qualtrics  
* UserZoom


When selecting tools, prioritize those that:

1. Support approved federal security standards (FedRAMP, etc.)  
2. Provide API access for custom reporting needs  
3. Enable appropriate access controls for different stakeholders  
4. Support GSA's open data initiatives when appropriate

### Modern Incentive Structures for Agile Contracts

Traditional incentives often focus solely on cost control or schedule adherence. Modern agile contracts require incentives that drive value delivery while maintaining appropriate contractor accountability.

Another option you can use to gauge the success of your project, as well as motivate the contractor, is incentives. As an acquisition professional, you are familiar with incentives like Award Fee or Incentive Fee. These and others can be applied to digital service acquisitions, but they must be applied correctly to be effective. If they are added in a haphazard way to quickly add a performance plan to an acquisition, they could cause more harm than good. So, as we consider incentives as a gauge for success, let’s first look at if they are needed or not.

*  [Award Term:  The Newest Incentive](http://www.wifcon.com/anal/analaterm.htm): This first article describes what an award term incentive is and the advantages and disadvantages associated with it.  
*  [The Award Term Incentive:  A Status Report](http://www.wifcon.com/anal/analaterm2.htm): This article is a reexamination of award term incentives a few years later. Here, Mr. Edwards looks more closely at what content is written in an award term.  
    

There are two types of incentives: Monetary and Non-Monetary. Monetary incentives include some form of financial increase for the contractor, and non-monetary incentives come in the form of recognition, building a partnership, and so forth.

As you consider whether an incentive is a good option for you, consider the following:

* What do you actually want to incentivize?  
* Are you assigning incentives for things that are above the expected quality and on-time delivery?  
* Who is actually getting the award? Is it the company, or the people doing the work? What about sub-contractors? Some companies look negatively on the employees if they do not achieve the incentive and do not pass down the award. If the people you are working with do not get a promised award, it can hinder your efforts to gain the contractor's trust.  
    

#### Value-Based Monetary Incentives

Consider these contemporary approaches to monetary incentives in agile contracts:

1. **Value-Stream Performance Incentives** Structure award fees or incentives around improvements in value stream metrics such as deployment frequency and lead time for changes. For example:  
   * Base award fee ranges on achievement of specific DORA metric benchmarks  
   * Provide graduated incentives for moving from "medium" to "high" or "elite" performer status  
   * Tie award term extensions to sustained performance improvements  
2. **User Adoption and Satisfaction Incentives Link** incentives to measurable user outcomes:  
   * Bonus payments for exceeding user adoption targets  
   * Award fee pools tied to user satisfaction scores  
   * Incentives for reducing user-reported defects over time  
3. **Sprint-Based Performance Incentives** Rather than traditional milestone-based incentives, consider:  
   * Award term contracts "where the contractor earns an extension after the Government determines that the contractor's performance is excellent"  
   * Incentives "for completing all (or a certain percentage of) sprint cycles with 100% client acceptance"  
   * Performance-based payments tied to consistent velocity over multiple sprints  
4. **Team Stability Incentives** Consider "incentivizing what we most want: consistency and repeatability of the development process" since stable teams produce better outcomes. Incentivize contractors to:  
   * Maintain core team stability throughout the contract  
   * Minimize turnover of key personnel  
   * Invest in ongoing skills development of team members

#### Effective Non-Monetary Incentives

Non-monetary incentives can be just as powerful as financial ones in motivating contractor performance:

1. **Increased Autonomy** High-performing teams can earn:  
   * Greater flexibility in technical implementation decisions  
   * Streamlined approvals for certain types of changes  
   * Reduced oversight requirements  
2. **Recognition and Visibility** Consider:  
   * Opportunities to showcase work at agency or government-wide events  
   * Recognition in agency communications  
   * Case studies highlighting successful practices  
3. **Future Opportunities**  
   * Consideration for expanded scope in related work  
   * Eligibility for specialized contract vehicles  
   * Partnership on innovation initiatives  
4. **Knowledge Sharing**  
   * Access to specialized training or resources  
   * Participation in communities of practice  
   * Opportunities to contribute to agency standards or playbooks

## Implementation Guidance for Procurement Professionals

### Selecting the Right Metrics

When selecting metrics for your agile contract:

1. Focus on a small number of high-impact metrics (5-7 maximum)  
2. Ensure metrics are objective and measurable  
3. Include both process metrics (how work is done) and outcome metrics (what value is delivered)  
4. Establish realistic baseline expectations before setting targets  
5. Plan for regular review and refinement of metrics as the project evolves  
   

### Structuring Effective Incentives

When designing incentives:

1. Align incentives with genuine value delivery, not just compliance activities  
2. Make sure incentives are "tied to the process and to the release of functional code"  
3. Consider using shorter performance periods with more frequent evaluation  
4. Structure incentives to encourage collaboration rather than competition  
5. Ensure incentives reach the actual team members performing the work  
   

### Contract Administration Considerations

1. Establish clear processes for metrics collection and verification  
2. Define the cadence for metrics review (typically aligned with sprint or release cycles)  
3. Document how metrics will inform contract decisions  
4. Train CORs specifically on agile metrics evaluation  
5. Create feedback mechanisms to share performance insights with contractors

## Discussion Prompt (optional)

For your DITAP discussion assignment, consider a digital service acquisition that you have worked on or heard about and analyze how modern metrics and incentives could be applied:

1. Briefly describe the digital service acquisition you've selected.  
2. Select 3-5 metrics from this module that would be most valuable for that acquisition and explain why you chose them.  
3. Design an incentive structure (monetary, non-monetary, or both) that would effectively motivate contractor performance in your selected acquisition.  
4. Explain how you would implement these metrics and incentives in the contract structure and administration.  
   

**Definition of Done:** Your post should address all four elements above in sufficient detail to demonstrate your understanding of modern metrics and incentives in agile procurement. Additionally, respond to at least two classmates' posts with substantive feedback or additional insights.

## Additional Resources

**Official Guidance**

* [TechFAR Hub Contract Types for Agile Development](https://techfarhub.usds.gov/solicitation/contract-design/)  
* [Digital Services Playbook](https://playbook.cio.gov/)  
* [GAO Agile Assessment Guide](https://www.gao.gov/assets/gao-20-590g.pdf)

**Tools and Templates**

* [DORA Metrics Quick Assessment Tool](https://dora.dev/quickcheck/)  
* [Sample Agile Contract Language](https://techfarhub.usds.gov/resources/learning-center/sample-language-for-government-contracts/)

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

### 1\. Which of the following best describes the role of a government team in a multi-vendor digital services environment?

 *(Select one)*  
 A. Enforcing strict competition between vendors  
 B. Monitoring each vendor individually with no coordination  
 C. Acting as a Delivery Marketplace Architect to support shared outcomes  
 D. Leaving vendors to figure things out on their own

**Correct Answer: C**

---

### 2\. What is the purpose of joint retrospectives and quarterly program reviews (QPRs)?

 *(Select all that apply)*  
 ☐ Track individual vendor contract compliance  
 ☐ Surface system-wide blockers and risks  
 ☐ Co-design improvements across teams  
 ☐ Celebrate delivery wins and analyze what went wrong

**Correct Answers: B, C, D**

---

### 3\. Which of the following is a good example of *vendor self-organization*?

 *(Select one)*  
 A. Waiting for the CO to assign tasks  
 B. Forming a working group to align on shared DevOps tools  
 C. Competing with other vendors to block their progress  
 D. Ignoring dependencies between contracts

**Correct Answer: B**

---

### 4\. Imagine you are reviewing a recurring delivery issue that impacted three vendors. What’s the best next step?

 *(Short answer)*

*\[Your response here\]*

**Example of acceptable answer:** “Host a joint root cause analysis to understand what happened and agree on system-level improvements.”

---

## Knowledge Check: Managing a Multi-Vendor Environment

### 1. Multiple Choice

**Which of the following best describes the role of a government team in a multi-vendor digital services environment?**  
*(Select one)*

- [ ] Enforcing strict competition between vendors  
- [ ] Monitoring each vendor individually with no coordination  
- [x] Acting as a Delivery Marketplace Architect to support shared outcomes  
- [ ] Leaving vendors to figure things out on their own

> ✅ Correct! The government’s role in a multi-vendor environment is to act as a Delivery Marketplace Architect—supporting coordination, reducing duplication, and guiding teams toward shared outcomes.

---

### 2. Select All That Apply

**What is the purpose of joint retrospectives and quarterly program reviews (QPRs)?**  
*(Select all that apply)*

- [ ] Track individual vendor contract compliance  
- [x] Surface system-wide blockers and risks  
- [x] Co-design improvements across teams  
- [x] Celebrate delivery wins and analyze what went wrong

> ✅ Correct! QPRs and retrospectives help identify systemic risks, improve coordination, and reflect on both successes and failures—driving continuous improvement.

---

### 3. Multiple Choice

**Which of the following is a good example of *vendor self-organization*?**  
*(Select one)*

- [ ] Waiting for the CO to assign tasks  
- [x] Forming a working group to align on shared DevOps tools  
- [ ] Competing with other vendors to block their progress  
- [ ] Ignoring dependencies between contracts

> ✅ Correct! Self-organization happens when vendors proactively coordinate, like forming a working group to align on DevOps tools and practices.

---

### 4. Short Answer

**Imagine you are reviewing a recurring delivery issue that impacted three vendors. What’s the best next step?**

📝 *Your Response:*  


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





