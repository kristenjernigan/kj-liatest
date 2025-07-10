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


#### DevOps Research and Assessment (DORA) Metrics:

The [DORA framework](https://dora.dev/), established by Google Cloud's DevOps Research team, has become the industry standard for measuring software delivery performance. These metrics measure both velocity and stability:

1. **Deployment Frequency** - How often code is deployed to production  
2. **Lead Time for Changes**- How long it takes from code commit to deployment  
3. **Change Failure Rate** - Percentage of deployments causing failures in production  
4. **Failed Deployment Recovery Time** - How long it takes to restore service after a failed deployment

DORA metrics provide a balanced view of both speed and quality, helping procurement officers assess whether contractors are delivering at an appropriate pace while maintaining necessary quality standards.

#### Value Stream Mapping Metrics:

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


