# Module 1 Sprint 3

## Introduction to the Digital Service Tech Bootcamp

Modern government acquisition professionals operate in a rapidly evolving digital environment. Whether you're evaluating a cloud-based platform, reviewing a data-sharing agreement, or procuring custom software development, your work increasingly intersects with key technology concepts that shape how agencies deliver public services.

This module introduces five essential digital service topics—data, software, cloud computing, artificial intelligence, and cybersecurity—with a focus on how these topics directly impact your role as an acquisition professional. 

* Data is the foundation of digital services; it's collected, stored, and analyzed to inform decisions, measure impact, and improve government operations. Procurement supports this by sourcing tools and services for managing and protecting data.  
* Software refers to the programs that run on computers or in the cloud to help agencies operate efficiently. Procurement plays a key role in acquiring, licensing, and maintaining the right software to meet mission needs.  
* Cloud services allow agencies to rent computing power, storage, and tools over the internet instead of maintaining physical servers. Procurement must structure contracts to align with flexible, scalable cloud service models.  
* Artificial Intelligence (AI): AI uses algorithms to analyze data, automate tasks, and generate insights that support faster, smarter decisions. Procurement may support AI initiatives by acquiring ethical, compliant AI tools and ensuring proper data use.  
* Cybersecurity protects government systems and data from threats like hacking or data breaches. Procurement ensures that systems and services meet security standards and include appropriate safeguards.

You don't need to be a technical expert, but understanding the fundamentals will help you write better requirements, evaluate vendor capabilities, and ensure contracts support secure, effective, and user-centered digital services.

The lessons ahead will explain terminology, describe modern delivery models, and highlight practical implications for acquisition planning, vendor engagement, and contract oversight.

---

By the end of this module, you will be able to:

* Describe the differences between structured, unstructured, and semi-structured data, and explain why those distinctions matter for procurement and contract oversight.

* Identify key challenges and modernization needs related to data storage, migration, analytics, and privacy in federal systems.

* Explain the software development lifecycle (SDLC) and modern practices like Agile, DevOps (development and operations), and Continuous Integration and Continuous Delivery (CI/CD), and recognize their relevance in acquisition strategies.

* Differentiate between proprietary and open-source software licenses, and understand the implications of software supply chain security.

* Define cloud computing and distinguish between public, private, community, and hybrid cloud deployment models.

* Explain the differences between Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS), and assess what kind of cloud service model a contract may require.

* Recognize cloud-specific procurement considerations, including pricing models, shared security responsibilities, vendor lock-in risks, and Federal Risk and Authorization Management Program (FedRAMP) compliance.

* Understand the basics of cybersecurity as it applies to acquisitions, including compliance frameworks (e.g., National Institute of Standards and Technology \[NIST\]), identity and access management (IAM), vulnerability management, and Security Incident and Event Management (SIEM).

---

# Digital Service Tech Topic: Data

## What Is Data?

Data is just information that’s been collected and stored (“recorded”). It can come in many forms—numbers in a spreadsheet, written text in emails, pictures, or even audio and video. In government contracting, examples of data include:

* Contractor performance records  
* Purchase histories  
* Budget logs  
* Emails between vendors and agencies

There are three main types:

1. **Structured Data**: Organized in a way that computers can easily process, regardless of whether a human can easily read it, like Excel sheets or databases.  
2. **Unstructured Data**: Organized in a way that humans can easily process, but not organized for computers to process the information, like PDF documents or social media comments.  
3. **Semi-Structured Data**: Somewhere in between, like webpages, which are human readable and are tagged so that computers can easily process them, with varying levels of granularity or structure.

Think of a contracting file that includes emails, PDFs, performance reviews, and a payment history—that’s a mix of structured and unstructured data.

## Key Considerations for Government Systems

As data grows in size and complexity, there are more challenges related to data storage, data transfer, and data processing:

* Old systems may slow down or fail under the weight  
* Data must often be moved between different clouds, networks, or storage areas—which can cause delays or added costs  
* Network upgrades and smarter designs are sometimes needed to keep up with demands  
* New data processing techniques or tradeoffs may be needed as data volumes increase  
* Ensuring data accuracy and forward/backward compatibility for different use cases can become complex

Learn more about data analysis by visiting [this page](https://www.coursera.org/articles/data-analysis-tools). 

These are some of the key challenges that are driving agency modernization efforts today, and are likely to come across your desk as an acquisition professional. 

Modern systems need to move data across clouds, networks, and apps. That creates bottlenecks unless you’ve planned for it.

Old databases weren’t built for the amount of data we use today. That’s like trying to run modern apps on a flip phone— the hardware would struggle to work correctly.

You may want to change data or delete it over time, but there may be practical or legal reasons not to. (E.g., System for Award Management (SAM.gov) “Federal Procurement Reports” from 2007… useful? Not really. But should it be *deleted?* Probably not.) 

As a contracting officer, you will likely encounter a variety of “buzz words”/topics related to data in your work, here are a few that are particularly relevant today: 

* **Data modernization**: The process of updating and transforming data systems, infrastructure and practices to modern, cloud-based formats to enhance accessibility, security and business intelligence.   
* **Data migration**: The process of transferring data from one storage system or computing environment to another.   
* **Data analytics**: The process of collecting, transforming, and organizing data in order to draw conclusions, make predictions, and drive informed decision making.   
* **Data Lake**: A data lake is a centralized repository designed to store, process, and secure large amounts of structured, semistructured, and unstructured data. It can store data in its native format and process any variety of it, ignoring size limits.  
* **ETL (Extract, Transform, Load)**:  A data integration process that combines, cleans, and organizes data from multiple sources into a single, consistent dataset for storage in a data warehouse or other target system.   
* **Data Provenance**: The historical record of data that details data’s origins by capturing its metadata as it moves through various processes and transformations. Data provenance is primarily concerned with authenticity, providing details such as who created the data, the history of modifications, and who made those changes.


## Open Data

Open Data is information that anyone can access, use, and share. In the context of government, this has two dimensions: 

1. The ability for someone to *access* the data  
2.  The legal right for the user to use the data

Generally, Open Data also refers to non-sensitive public information made available in data *formats* that are easy to use, reuse, and republish.

Many government entities, from local to federal to international, provide data sets to data.gov and/or operate their own open data websites so that information generated may be shared and utilized by the public. There are many open data sets, ranging from government operations data (e.g., Federal Procurement Data System (FPDS)) to data “products” (e.g., Census survey data tables).

Outside of government, open data can also refer to a movement to provide open access and use of the massive amounts of projects and data being developed every day in commerce, science, and technology in order to promote progress and innovation, and improve the accountability of both private and public institutions.

Why It Matters to Procurement Officers:

1. **Licensing**: Procurements that potentially involve open data require consideration of the relative intellectual property / data rights.  
2. **Privacy**: Open data can—in some cases—implicate privacy concerns, particularly when combined with other open data sets. Understanding how data is published and ensuring that contracts have adequate remedies for privacy violations is important for contracting officers.  
3. **Efficiency**: Understanding how open data can be used to improve data publication and use can reduce duplication of effort and allow for more efficient use of government and non-government data.

## Data Privacy

Data Privacy means protecting personal or sensitive information so that only people who are supposed to see it can access it. This includes things like social security numbers, health records, or confidential contract data.

Why It Matters to Procurement Officers:

1. **Legal Compliance**: You must follow privacy laws like the Privacy Act of 1974 and agency-specific policies to protect personal information collected during procurement processes.  
2. **Risk Management**: Mishandling private data could lead to security breaches, legal penalties, and loss of public trust.  
3. **Contract Integrity**: Some procurement data may contain sensitive vendor information. Protecting this data ensures fair competition and integrity of the procurement process.

For example, If your office is collecting contractor tax IDs or employee background checks, that data must be stored and shared securely to prevent unauthorized access.

## What Contracting Officers Should Keep in Mind:

* Understand what data your systems hold and how it’s organized.  
* Ask vendors how they handle data—especially if Artificial Intelligence (AI) or analytics are part of the service.  
* Support modernization efforts that improve how data is stored and accessed across departments.

As a contracting officer, you are both a data user and a data steward. You should know:

* What data can and should be **shared openly** (e.g., awarded contracts).  
* What data must be **protected** (e.g., personally identifiable information or confidential business information).  
* The **laws and best practices** that guide both.

---
## Digital Service Tech Topic: Software

### What is software?

Software refers to the instructions, data, or programs that enable computers and digital systems to perform specific tasks. Informally, software tells computer hardware how to do something useful with data. It includes human-readable instructions, known as source code, and machine-readable instructions compiled for the computer to execute.

*CO note: It may be necessary to clarify whether the government can access the source code or compiled software.*

### How is software developed?

Understanding how software is developed helps procurement professionals recognize what they're buying, how to evaluate progress, and what kinds of contract structures best support successful delivery. This section introduces the software development lifecycle, modern methodologies like Agile, the roles involved, and key concepts such as the software supply chain.

The Software Development Lifecycle (SDLC) is the process organizations use to plan, design, develop, maintain, and eventually retire software systems. Approaches to SDLC range from traditional "waterfall" methods, where each phase is completed sequentially, to more modern, iterative approaches like Agile. Agile methodology focuses on building and delivering functional software in small, manageable increments. Different Agile approaches include Scrum, where teams work in short, time-boxed sprints, and Kanban, which emphasizes continuous delivery with strict limits on work in progress to maintain flow.

A central principle of modern software development is the importance of iteration, prototyping, and feedback loops—testing ideas early, learning from users, and continuously improving. For example, the U.S. Digital Service and VA used Agile and iterative development to improve the VA.gov website, releasing updates in small increments based on honest user feedback. They also leveraged open-source libraries and maintained a Software Bill of Materials (SBOM) to track components and ensure security compliance. 

Instead of building everything from scratch, developers commonly use packages and libraries—prewritten code modules created by others—to speed up development and improve reliability. However, this practice introduces potential security, licensing, and maintenance risks. As a result, tools like SBOMs are becoming essential, helping organizations manage their software supply chain more effectively.

### How is software delivered?

Software can be delivered in several ways, depending on user needs, organizational infrastructure, and security considerations. One standard method is running software locally, where it is installed directly on a user's device, such as a laptop or desktop, and does not require a constant internet connection. For example, tools like Microsoft Excel can be installed and run entirely on a user’s local machine without an internet connection. 

In more controlled environments, software may be hosted on-premises, meaning it runs on servers that an organization owns and maintains, often in physical data centers. For instance, the Department of Energy (DOE) operates sensitive, high-performance computing systems in dedicated, on-premises data centers to meet strict security and performance requirements. 

Increasingly, software is delivered as a service, hosted on third-party cloud infrastructure ("other people’s servers") and accessed over the internet. This includes models such as Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS). 

Finally, software can be delivered as an app and downloaded via app stores to user devices. These apps often rely on cloud services to provide real-time data, updates, and functionality while offering a convenient user interface on mobile or desktop platforms.

### How is software updated?

Modern software isn’t built once and left alone—it’s constantly updated to fix bugs, add new features, and improve security. To manage this, software teams use practices that help them make changes quickly and safely.

One common practice is **Continuous Integration** **and Continuous Delivery (CI/CD)**. This means developers regularly add their code to a shared system, where automated tools check the code and prepare it for release. These tools also run tests to ensure the changes don’t break anything. As a result, working software can be updated more frequently and with greater reliability.

To keep track of changes, developers use a **version control system,** the most common one being Git. It helps teams see who made what change, roll back to earlier versions if needed, and collaborate on the same code without overwriting each other’s work. Platforms like GitHub and GitLab build on Git to make this process easier.

Testing is critical to updating software. **Automated testing tools** check for problems every time a change is made. These tests can include basic functionality, how different parts of the system interact, how the software handles heavy use, and whether it meets security standards. Even though many tests are automated, some types of testing—like checking for accessibility or ease of use—still need a human touch.

Before updates reach the end users, the software usually moves through several **environments**. These might include a development environment (where the code is written), a testing environment (where changes are checked), a staging environment (which mimics the live system), and finally, the production environment (used by real users). This process helps catch any issues before the update goes live.

Teams also use techniques like **canary testing** and **feature flags** to manage risk. Canary testing means rolling out a new software version to a small group of users first. If it works well, the update is released more broadly. Feature flags allow developers to turn specific features on or off without changing the code. This helps teams test features gradually or run A/B tests to compare performance.

#### Why Updates Matter—and How They Stay Safe

Frequent updates help agencies respond quickly to user needs and changing requirements. But they also come with tradeoffs. Updates can introduce new problems or confuse users if not communicated well. That’s why finding the right balance between moving fast and keeping systems stable is essential.

Security is another key reason software needs regular updates. Updates often include patches for known vulnerabilities and help systems comply with federal security policies, like **FedRAMP** or **NIST** standards. Agencies should plan for ongoing updates as part of the delivery process, not as an afterthought.

#### How Teams Monitor and Respond to Problems

After software is deployed, teams don’t just walk away—they monitor its performance in real time. They use **monitoring tools** to track uptime, response time, and error rates. Standard tools include Datadog, Prometheus, and AWS CloudWatch. These insights help teams decide when to update or improve the system.

If something goes wrong, teams rely on **incident response plans**. These plans include steps for rolling back bad updates, recovering data, and communicating with stakeholders. Having clear procedures in place helps minimize downtime and protects user trust.

### Considerations around Supply Chain and Licensing

When buying or managing software, it's important to understand what’s behind the hood. Most modern software isn’t built from scratch—it’s assembled from many parts, including third-party libraries, open-source tools, proprietary code, and deployment tools. This collection of components is often referred to as the **software supply chain**.

If agencies or vendors don’t track these components correctly, it can lead to hidden vulnerabilities, licensing conflicts, or even security breaches. For example, the **SolarWinds cyberattack**—a significant event that affected several federal agencies—exploited weaknesses in the software build process. This incident showed how risky it can be when dependencies and tools aren't properly managed or monitored.

One way to manage this risk is through a **Software Bill of Materials (SBOM)**. An SBOM is like a parts list for software—it shows all the libraries, packages, and tools that make up a system. Many federal agencies now require vendor SBOMs because they help track vulnerabilities and support a faster response when issues arise.

Contracting officers and acquisition professionals should also ask vendors about **risk management practices**. Are they scanning for vulnerabilities? Do they patch or replace risky components? Do they follow secure development practices? These questions are essential to ensure that the software delivered is safe and dependable.

Licensing is another key consideration. Software licenses set the rules for how software can be used, shared, or changed. There are two main types: **proprietary licenses** and **open-source licenses**.

**Proprietary licenses** usually come with restrictions and fees. Agencies don’t get access to the source code and must rely on the vendor for support and updates. Common examples include Microsoft Office or Salesforce. In contrast, **open-source licenses** generally allow for more flexibility. They let agencies use, change, and distribute software freely, though some licenses require that changes be shared publicly. For instance, the Apache 2.0 license is relatively permissive, while the GNU General Public License (GPL) has stricter conditions.

These licensing choices affect more than legal compliance—they impact cost, flexibility, and long-term strategy. While open-source tools may reduce licensing costs, they still require investment in support and integration. Open-source software can be customized, while proprietary tools may be harder to adapt. Failure to follow the terms of a license, especially with open-source software, can lead to contract issues or legal trouble.

Finally, agencies should consider the risk of **vendor lock-in**, when switching providers becomes difficult or expensive. This can happen if the vendor uses proprietary formats, doesn’t allow access to data, or doesn’t follow open standards. When reviewing a procurement, it’s worth asking: Does the software use open standards? Will we be able to access and export our data? Could another vendor take over if needed?

By considering these factors, 1102s can make better-informed decisions that reduce risk, support flexibility, and help agencies maintain control over their software assets.

### Service Design and Delivery Standards (21st Century IDEA & USDS Playbook)

Modern software isn’t just about code—it’s about delivering effective services that meet user needs, comply with the law, and adapt over time. The 21st Century Integrated Digital Experience Act (IDEA) and the U.S. Digital Services Playbook set specific expectations for how software supporting government services should be designed and delivered.

Contracting officers should understand these frameworks to write solicitations that support human-centered, standards-compliant digital service delivery.

When federal agencies build or buy digital services, focusing on the people who will use them is critical. This approach is called **Human-Centered Design (HCD)**. It means engaging with users throughout the development process—not just at the beginning or the end—to ensure the product meets their needs. Human-centered design focuses on the needs, behaviors, and feedback of end users of a product or service.

HCD places special emphasis on **accessibility, usability, and continuous feedback**. Digital tools should be easy for everyone, including people with disabilities. That’s where **Section 508 compliance** comes in, requiring things like screen reader compatibility, keyboard navigation, and appropriate color contrast. But accessibility alone isn’t enough—systems should be usable and continually improved based on real-world feedback. Agencies can achieve this by building in regular user testing, collecting performance data, and listening to feedback.

Contracting officers can help by shaping procurements to support these practices. Instead of static, one-time requirements, solicitations should encourage **iterative research and design**. This might mean asking vendors to include user researchers and designers on their teams or to plan for multiple testing and feedback cycles as part of their delivery.

**Modular development** and **API-driven architecture** are other key strategies for building flexible, user-friendly systems. Modular development breaks large systems into smaller, usable parts that can be delivered and improved over time, rather than waiting years for a final product. Meanwhile, **APIs** (Application Programming Interfaces) allow different systems to talk to each other. This makes integrating commercial tools, in-house software, and legacy systems easier, while avoiding vendor lock-in.

Strong **performance and usability standards** are also essential. Systems should respond quickly, handle expected workloads, and navigate easily. Agencies may track things like the number of transactions a system handles each day or how long it takes for a page to load (e.g., 95% of responses under 500 milliseconds).

Finally, **continuous improvement** should be part of any technology investment. This means monitoring systems for performance and problems, collecting data on how users interact with the service, and using that data to guide future updates. Combining **quantitative analytics** (like page views or error rates) with **qualitative research** (like interviews and surveys) gives a fuller picture of how well a system works and how to improve it.

By prioritizing user needs, accessibility, and flexibility, agencies can deliver digital tools that are effective and inclusive. Acquisition professionals play a key role in making that happen.




