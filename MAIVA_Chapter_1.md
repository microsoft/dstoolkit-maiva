<p><img src="./media/Titel Graphic.png" 
alt="A screen shot of a computer Description automatically generated" /></p>

## Table of Contents

[Introduction](#introduction)

- [How to use this playbook](#how-to-use-this-playbook)
- [Why GitHub](#why-github)

[Context for MAIVA](#context-for-maiva)

- [What good looks like](#what-good-looks-like)
- [Why is it so hard to achieve? (Lessons learned)](#why-is-it-so-hard-to-achieve-lessons-learned)

[Enabling the change](#enabling-the-change)

- [Executive role in culture](#executive-role-in-culture)
- [Systems thinking underpinning culture](#systems-thinking-underpinning-culture)
- [Being a data-driven culture](#being-a-data-driven-culture)
- [Approach to change management](#approach-to-change-management)

[Framework to Industrialize AI](#framework-to-industrialize-ai)

- [MAIVA – AI strategy and platform planning](#maiva-ai-strategy-and-platform-planning)
- [MAIVA – Innovation, Intake, Experimentation](#maiva-innovation-intake-experimentation)
- [MAIVA – the AI platform, the data platform, and the data (perpetual data strategy)](#maiva-the-ai-platform-the-data-platform-and-the-data-perpetual-data-strategy)
- [MAIVA – Develop, Deploy & Operationalize AI/ML Use Case](#maiva-develop-deploy-operationalize-aiml-use-case)

[MAIVA Operating model process and roadmap](#maiva-operating-model-process-and-roadmap)

[Security & Responsible AI considerations in AI governance](#security-responsible-ai-considerations-in-ai-governance)

[Economics of governance framework (or the opportunity cost)](#economics-of-governance-framework-or-the-opportunity-cost)

[Roles Supporting MAIVA](#roles-supporting-maiva)

- [The ongoing framework](#the-ongoing-framework)
- [The inaugural build](#the-inaugural-build)

[Resources](#resources)

[Gratitude for contributors](#gratitude-for-contributors)

# Introduction

## How to use this playbook

As AI technologies rapidly evolve, companies increasingly struggle to
realize the expected returns from investment in AI. It is not unusual
to expect 10x return on AI that improves the current processes or over
50x return on AI that drives new business models. But none of that
return can be realized if the investment in AI is ‘stuck’ in
pre-production Proof of Concept (PoC) or Minimum Viable Product (MVP) state. 
This playbook is designed to suggest some best practices for successful AI initiatives at scale.

 This playbook will provide:

- Context for industrializing AI within the enterprise

- A framework that covers key structures to industrialize AI

- The technical architecture(s) that serve the framework

- Economic considerations of the framework and various technologies

- Guidelines for resourcing the initial creation of the framework as
  well as resourcing for the on-going process

- Recommendations for managing change: change in the operating
  processes, change in skills, change in decision governance

- Resources that may provide additional help

Use this playbook as a guide to define your company’s unique path to
industrializing AI. Please clone this playbook in your own GitHub
environment to make it your own. And, as you learn and grow, consider
sharing back to the playbook.

## Why GitHub

This is also a question of ‘why open source’. We have been on this
journey of rapidly evolving AI for a few years. We have seen many
patterns that are common, regardless of technology, though some of
these patterns are accelerating. Our purpose is to enable people and
organizations to achieve more. Sharing openly, as in the tradition of
OpenAI itself, is essential to enabling every organization to realize
optimal value from their investment in AI.

GitHub is widely used and richly powerful. It is a tool for
technologists but is also readily used by laity. Because
industrializing AI is a framework that requires direct participation
from both the technologists and the business, GitHub is a great tool
to enable this team.

And GitHub helps build community. We hope that with each clone, there
is opportunity for feedback and improvement of the playbook itself.

# Context for MAIVA

Artificial intelligence (AI) is transforming every industry and creating
new opportunities for innovation and growth. To realize the full
potential of AI, organizations need to adopt a systematic and scalable
approach to *industrialize AI*. This playbook illustrates a
comprehensive framework to manage AI investments through a cycle of:

- An important starting point is a well-defined **intake and triage
  process** to assess and prioritize AI investments or use cases. This
  process should include a broad set of stakeholders from across the
  business, functional areas and technology areas. The balance to strike
  is to be structured enough to avoid investing in ideas whose time has
  either passed or it is too soon to work while being open enough to get
  the diamond in the rough, the magic hiding among the muck.

- **Experimentation and learning** are essential to prioritizing the
  right AI investment ideas. This is where a PoC might have some
  important contributions.

- An **agile, product management** approach to development brings
  discipline and focus to each AI initiative.

- Remember that value lives in production. If the AI initiative does not
  conclude with **deployment to a production environment**, the intended
  return cannot be realized. This is not to say that PoC’s have no
  value; rather it is to say that PoCs are not the vehicle to ROI.

- **Scale value** can take considerable time; set expectations properly.
  Sometimes deployment into production is just a first step to global
  impact.

- **Monitoring AI, measuring performance** and building systematic
  **feedback loops** between users and developers will drive the
  expected return and keep investments on the intended track.

- **Securing AI** is fundamental to ensure that Return on Investment (ROI) expectations are not
  adversely impacted by unsecure AI applications that can either be
  misused or that provide compromised responses.

We will also provide a point of view about the operational implications
of an AI governance framework as well as the role that privacy and
responsible AI policies play. Suggested architectures will be provided
and we will dig into the economics of industrializing AI. We will close
the playbook with recommendations on resourcing the roadmap to enable
the governance framework and to manage it thereafter.

## What good looks like

Value from AI is realized after a solution is deployed to production and
used at scale. Innovating is important; scaling the outcome of
innovation is the challenge of the day. Managing a portfolio of
initiatives through deployment and scale will be essential to drive
return and mitigate risk and underperformance.

Companies need a framework through which the portfolio of AI initiatives
can be prioritized, developed with consistency, and governed
post-deployment. We think about this framework as *industrializing AI*:
creating a systemic approach to ideation, intake, experimentation,
prioritization, development and deployment, and governance and
performance monitoring.

<img src="./media/graphic 1 - 2024-01-25 .png" 
alt="A screen shot of a computer Description automatically generated" />

Through this framework each AI initiative will have a common journey
within a structured operating model of strategy/planning, data &
platforming, AI use case development, performance measurement and
monitoring to provide feedback loops to developers.

## Why is it so hard to achieve? (Lessons learned)

There are many obstacles blocking scale value from AI investments:

- Getting stuck in PoC’s that do not get beyond demos. The lesson here
  is to commit to driving a return from the investment in AI. 
  
- Indeed, all too often, AI initiatives are built without defining measurable
  results for success and without feedback loops from users to
  developers. If performance is not defined and monitored, how can
  anyone know what success looks like? The lesson here is to define,
  implement and measure KPIs at every stage and every activity of the
  process and bring those insights for retrospective through the
  feedback loop. Having AI investments pop up in every corner of the
  organization is diffused chaos and makes it challenging to funnel
  investment in a controlled way. The lesson here is to enable
  governance and determine where centralization makes sense.

- Overlooking the underlying business process can mean that deployed AI
  is not delivering optimal results. The lesson here is to bring a
  disciplined approach to change management.

- Having AI investments entirely controlled within the confines of IT
  means that the business that will be impacted is not involved in
  ideating, prioritization or in the design of the user experience. The
  lesson here is to fully partner with the business and contionuously involve 
  the business to drive adoption throughout the entire process,
  from inception to production.

- ‘Shadow’ IT groups within the business cannot deliver optimal
  technical results to the business without access to the enterprise
  infrastructure and platforms. The lesson here is to partner with IT to
  ensure optimal outcomes and long-term maintenance of AI products.

- Loss of IP, loss of data and harmful outcomes from AI initiatives are
  all significant risks for which mitigation can drive up costs and risk
  of reputational damage is potentially existential. And because
  security, privacy and responsible AI are domains with scope beyond any
  given line of business or functional area, these policies should be
  enterprise-wide. The lesson here is that these policies are essential
  to the AI governance framework but are not created within the
  framework.

- Skilling continues to be a perennial challenge; data science and data
  experts can be scarce resources. The lesson here is that upskilling
  resources in both the lines of business and IT will help to mitigate
  and optimize results over the long term.

To address some of these lessons learned, the Finance organization in
Microsoft adopted this approach to ground their investments in AI and
drive optimal change:

<img src="./media/graphic 2- 2024-01-25 .png" 
alt="A screenshot of a computer Description automatically generated" />

# Enabling the change

<p align="centre"><img src="./media/IDC.png"
alt="A screenshot of a computer Description automatically generated" /></p>

A recent study from IDC shares the attributes of enterprises considered
to be leaders in AI; the inference is that taking the lead with AI is as
much an art as it is science. The art of successful AI investment comes
through executive leadership, a data-driven culture and effective change
management. To build successful models, one must be willing to
experiment and iterate. One must be willing to fail and learn from
failure; this is the cultural attribute that defines companies that lead
with AI. The willingness to fail and to learn from failure… and the
leadership that enables experimentation and learning from failure. At
Microsoft we call this having a growth mindset. And we have built our
culture around it.

Change management is the key to enabling the digital culture and will be
heavily dependent upon the role of executive leadership, systems
thinking and being data driven.

## Executive role in culture

The executive role in shaping the culture cannot be overstated and
should extend to a clear commitment to culture from the entire
leadership. If there is any hesitation or ambivalence, this will
permeate the organization and diminish agility. The key attributes of
culture of companies that lead with AI are agility, experimentation,
focus on learning. The executive community of the organization must be
seen to value and exemplify these attributes. The role of the executive
community in shaping culture cannot begin and end with a communications
plan; it must include explicit display of their own curiosity and
willingness to try again and again in order to learn. And the executive
community must elevate and applaud those examples of failure that lead
to valuable insight.

## Systems thinking underpinning culture

As you will see through this document, we strongly encourage defining
the business problem to be solved before defining the technical
capability. AI investments must take a more wholistic approach to
deliver successful results. Systems thinking is an approach to problem
solving that considers complex systems as a whole and as such can be an
important enabler of AI initiatives. Systems thinking will ask us to
understand the interdependencies and relationships between different
parts of a system and how changes in one might impact the whole. We
consider the business ecosystem (culture, organization, policy, process)
and the technical infrastructure of the enterprise to both be parts of
the system. Systems thinking helps teams anticipate and mitigate
potential risks and unintended consequences of changes in culture,
process *and* technology.

The goal of systems thinking is to enable enterprise teams to establish
a systemic approach to improving business capabilities by deploying and
operating AI solutions in production and realize value through scale.

## Adopting a data-driven culture 

Being data-driven is the foundation for leading in the era of AI. Agile
experimentation leads to successful outcomes because it uses data to
define the hypothesis and data to measure the outcome. The company that
is data-driven uses data as the starting point of strategy, operations,
and market growth. This puts a great deal of importance on the quality,
completeness and fidelity of data. This requires a strong and
well-focused data strategy that is perpetual and perennial; it must be
considered in every AI initiative and updated with every shift in the
system.

## Approach to change management

<img src="./media/graphic 3 2024-01-25 .png" 
alt="A black background with text and icons Description automatically generated with medium confidence" />

#  Framework to Industrialize AI

The following diagram illustrates an enterprise framework to
industrialize AI and accelerate value. The process involves intake,
experimentation, evaluation, and prioritization of the newly raised AI
initiative. Once prioritized, the AI platform will require some set up
or enhancements before development and deployment of each AI use case.
And then the performance of the deployed AI is monitored and outcomes
are measured both to provide assurance of intended performance and to
provide visibility to future drift. The cycle is closed with feedback
loops from the users to developers driving continuous value.

<img src="./media/graphic 4- 2024-01-25 .png" 
alt="A screenshot of a computer Description automatically generated" />

Let’s dig into each area of MAIVA.

## MAIVA – AI strategy and platform planning

The AI strategy will be defined by the business strategy and expected
outcomes from investment in AI. The AI strategy should be reviewed
yearly during annual business planning though the size of investments,
often spanning multiple years, would benefit from stability in the AI
strategy across planning cycles. It is also a good idea to organize a
mid-year, state-of-the-AI strategy review, and surface insights about
the positives and challenges faced in that first half of the year.

Part of the AI strategy will include executive sponsorship of the
portfolio framework to ensure the appropriate involvement across the
enterprise, to ensure that investments are optimal, and to ensure that
the expected returns are realized.

Successfully industrializing AI will require an operating model that
involves organizational structure, product scope and process structure,
as well as an underlayment of security and responsible AI. The goal is
to enable AI initiatives through a consistent and controlled
cross-functional process, ensuring alignment between business objectives
and technical execution while mitigating risk and executing responsibly.

The operating model of industrialized AI is built on common policies for
security and responsible AI, data strategy, and data privacy and access
policies. Platforming of data and AI will, likewise, serve as a
foundational enabler for the operating model; but, platforms will shift
and expand as use cases extend into multiple business areas.

The operating model underlying MAIVA will be the blueprint for
successful execution and optimized return from AI investments. The key
components in that blueprint include the people, process and
technologies involved:

- The people serving on the governing board will come from
  cross-functional areas of the business and cross-domain technical
  teams. Participants will include representatives from business teams,
  finance, marketing, and product teams to articulate the business
  outcomes from AI. The data, infrastructure and AI technology teams
  should also be represented. And, security and responsible AI should
  have seats at the board.

- The process will involve a singular intake process with common scoping
  and evaluation criteria, a consistent experimentation process through
  which the potential viability and success of a proposed initiative
  might be refined, an agreed upon prioritization approach to identify
  the sequencing of initiatives, an agile development and deployment
  process that is grounded in production deployment, and finally an
  agreed approach to performance measurement and response.

- The data platforms and AI platforms. These will not be universal. In
  other words, there will not be one data platform or one AI/ML platform
  for all initiatives. But they should be more enduring than any single
  use case or initiative. Scale of AI requires that the components are
  spread across multiple use cases; otherwise, the cost is prohibitive.

- Similarly, the data strategy will cover multiple initiatives, but will
  not be universal. Generally, there will be a family of business
  processes that will rely upon the same sets of data. These will be
  enabled by a common data strategy. For example, in the Finance
  function, there will be procurement processes and payment processes
  that could all be automated with AI and these will involve the same
  sets of data and, therefore, they will rely on the same data strategy.

- The tools that will be required to industrialize AI will drive
  reporting across the process from intake through to deployment.
  The process will include measuring performance and use of models as well 
  as the return on investment for the business as measured against original targets. 
  Tools required will also include the specific AI technologies to build and deploy models.
  And, of course, as mentioned, the data platform and AI/ML platform will
  be key among the technology required.

There are several policies that should be determined outside of the
MAIVA operating model and that are foundational enablers for moving
initiatives through the governance process. Security, data privacy and
access control, and responsible AI are all policies that should enable
key principles for how investments decisions are made.

## MAIVA – Innovation, Intake, Experimentation 

Experimentation and intake are the start of successful innovation. It is
important to start right. The goal is strong alignment between the
business strategy and the return expected from qualified and prioritized
use cases. Experimentation at the front end will identify expected
return, feasibility, and risk mitigation.

<img src="./media/graphic 5- 2024-01-25 .png" 
alt="A diagram of a diagram Description automatically generated" />

This approach requires a series of nested cycles of experimentation:
build/deploy - monitor – feedback – use case iteration.

- As each use case is being considered, there may be additional
  experimentations required to validate return and basic feasibility. The
  output of these small cycles of experimentation will be the proposed
  AI initiatives to consider in the intake process.

- The intake process will consider newly proposed AI initiatives as well
  as recommended improvements on existing AI, recommendations coming
  back from monitoring and feedback.

- The intake process should deliver a prioritized list of use cases for
  AI investment - both new use cases and enhancements to already
  deployed use cases. As the intake process evolves, this prioritized
  list becomes the managed portfolio of AI initiatives.

- For prioritized AI investments, each use case will iterate through
  planning, design and development until the successful use case can be
  deployed and added to the portfolio of managed AI use cases. This is
  the AI lifecycle described below.

**Lifecycle of an AI Investment**

<img src="./media/graphic 6- 2024-01-25.png" 
alt="A diagram of a product scope Description automatically generated" />

**MAIVA – Experimentation**

As an AI initiative approaches intake, it may need refinement and some
deeper exploration to assess the potential return and feasibility, both
of which will impact prioritization.

An experimentation should start with a clear definition of scope and
expected outcomes and key results. These quantified results will become
the hypotheses of experimentation. Also defined will be the specific
user persona and their user stories. As the hypotheses are tested, the
experiment should define the expected feasibility, expected return, and
viability if developed and deployed to production.

Consider the maturity of data and AI capabilities to address feasibility
and viability of the use case. Is the data complete; is the data
consistent; is the data accurate… all will be involved in the scope of
the use case and iteration through experiments.

As experiments are meant to quickly demonstrate potential value, the AI
experiments are often PoCs built with tools that may not be the tool-of
choice for an enterprise-scale AI solution. These tools are quicker to
build on and more flexible because they do not require the same degree
of risk mitigation and security that an enterprise-scaled AI solution
would require. This allows for rapid experimentation.

## MAIVA – the AI platform, the data platform, and the data (perpetual data strategy)

**AI/ML Platform**

To industrialize AI at scale requires a common development and
deployment approach across a business area whose processes are grounded
in common data. The platform should be flexible and extensible enough to
allow for scale beyond any given business area. As each use case is
taken on, early activity will be to assess the viability of the platform
and the data to serve the specific use case. If AI has previously been
enabled in the business area, then the platform and data are most likely
ready for subsequent use cases. The platform and the data will need to
be reviewed and revised for use cases that serve ‘new’ business areas,
areas that have not implemented AI. In that case, an additional data
strategy should be considered.

A great strategy is to prioritize the business area(s) with the most to
gain – greatest efficiencies and cost savings or greatest incremental
revenue – from AI. Those areas can anchor in a common platform and
common data strategy. As the capability grows, additional lines of
business can be taken on, likely with changes to the platform and data.

The AI platform should be enabled with the following:

- Tooling required for data acquisition and to facilitate
  experimentation and to train data required in the use case.

- Configurable deployment and operationalization capabilities that
  include responsible AI, explainability, transparency and
  interpretability.

- Deployment automation code for creating a sandbox environment with
  standardized libraries, development patterns, unit testing, and smoke
  testing, and that allows the data science teams to collaborate across
  operational support teams.

The AI platform may be built around MLOps for Databricks or MLOps for
Synapse or yet another MLOps capability. Where generative AI is a
technical capability, LLM Ops will be considerably different and the AI
platform will need to accommodate this. There is a section later in the
playbook that illustrates architectural considerations for MLOps and
LLMOps.

**Data Platform**

Value and outcomes from complex AI solutions are dependent upon a modernized data platform. Typically, the data platform is not a single entity. Indeed, in any given business unit or functional group, there are multiple sources of data and multiple stores of data. And, in most business units, there are multiple enterprise apps, multiple platforms and multiple sources of data, that continue to grow more complex environment. As organic growth occurs, as acquisitions occur, as re-organizations occur, the breadth of data sources change, leaving the business unit with increasingly complex data space. 
Now multiply this scenario across every business unit and function in the enterprise. It is this built-in complexity that underpins the need for a robust data strategy.

Industrializing AI will require a governed platform and a strategy to manage complex data. Data modernization within a platform to serve AI is the foundational requirement of MAIVA.

**Data Strategy**

A robust data management and governance capability is crucial for leveraging AI technologies and gaining a competitive edge through an AI-driven transformation. This capability spans people, process, and platform (technology). Therefore, an organization's data strategy should reflect this comprehensive approach. In the context of AI, an organization's data strategy should:
- Focus on clearly identified high-impact business outcomes and AI use cases.
- Iteratively enhance data handling across people, process, and platform (**the three P’s to success**) with a systems-thinking approach, focusing on holistic and progressive improvement.
- Keep in mind that AI transformation with a data-driven operation is a long-term process that requires patience, resilience, and sustained focus.

Data strategy is essential to successfully industrialize AI, bringing together People, Process and Platform to harness data's full potential for innovation and growth, not as a byproduct of, but instead, the driving force for innovation and growth.  

<img src="./media/graphic 22-2024-06-10.png" 
alt="Figure 1. Framework to generate business value from data" />


## People
The People pillar of Data Strategy aims to create an environment where data and AI are not just tools but are central to the organization's culture and a way of operating. It's about creating a culture that values data, embraces AI, and prioritizes continuous learning and adaptation. An intelligence-driven culture leverages data and AI as core to operations, prizes data as a valuable resource, promotes making it widely accessible across the organization and actively utilizing it to inform decisions. It also promotes integration of AI technologies into various workflows, using AI to automate repetitive tasks, enhance human capabilities, and generate actionable insights.

An intelligence-driven culture is characterized by its emphasis on a data-centric approach. This approach prioritizes data collection, analysis, and utilization in decision and action taking. It ensures that data is not just considered valuable but is also made readily available to all levels within the organization. This availability of data is crucial to making informed decisions. By ingraining data-driven insights into decision-making processes, an organization can foster a culture that is truly intelligence-driven.

AI integration is another key aspect of an intelligence-driven culture. In such a culture, AI technologies are not standalone tools but are integrated seamlessly into various aspects of the organization's operations. AI is used to automate tasks, augment human capabilities, and generate valuable insights. Through this approach, organizations can leverage AI to gain a competitive advantage, improve performance, and foster growth.

Another critical aspect of an intelligence-driven culture is its focus on continuous learning and adaptation. Such a culture encourages experimentation, learning from failures, and iterative improvement based on data-driven feedback. An intelligence-driven culture understands that transformation is not a one-time event but an ongoing journey. By fostering a culture of continuous learning, organizations can become more resilient and adaptable, thriving in an environment that is increasingly data-driven and intelligence-centric.

## Process
The Process pillar of Data Strategy should focus on the objective of centrally governing data but with federated aspects for business and AI agility. The design should aim to remove bottlenecks with data lifecycle management and enabling appropriate data access. Several critical processes need to be considered in this context, these include data lifecycle management, which oversees data from collection to disposal; data lineage, ensuring traceability and transparency; data classification, data quality, and data product ownership - to maintain data integrity and reliability; Data Security Operations management, protecting data from threats; continuous review and alignment, ensuring data strategies remain relevant and aligned with business goals; and cost management, tracking and managing the costs associated with data. Collectively, these processes support the creation of an intelligence-driven culture where data and AI are integral to the organization’s operational fabric, driving business outcomes.

## Platform
The Platform pillar of a successful Data Strategy should prioritize scalability and the provisioning of shared enterprise services that support self-service automation. This requires a robust technology solution that integrates a data analytics platform with Machine Learning and AI.
A fundamental quality of this pillar is flexibility, particularly in terms of interoperability with various data sources and connectors. This allows for easy integration with a wide array of data systems, both common and bespoke. It's essential that the platform enables data visualization, discovery, and business intelligence, and is compatible with DevOps and associated automation processes.
The platform should scale with the growth of the organization and workloads, managing increasing data volumes and complexity without compromising performance, functionality, or security. The platform should enable a federated data product approach to mitigate challenges around resourcing and team capacity.

## What to Consider when Establishing or Modernizing a Data Strategy
This section will explore the main elements of a data strategy as they manifest within each of the three essential pillars: People, Process, and Platform. The goal is to provide some insights on how to develop organizational capacity with Data and AI. These elements are data acumen, data governance and operations, federated compute, shared services, data sources and enterprise services. 

<img src="./media/graphic 23-2024-06-10.png" 
alt="Figure 2. Conceptual architecture of an Enterprise Data Strategy, encompassing People, Process and Platform" />

## Data Acumen
Data acumen is a crucial skill set for any organization aspiring to leverage Artificial Intelligence for business growth and innovation. It is the collective proficiency in understanding and applying data-related concepts and skills, spanning from foundational knowledge to domain-specific insights.
Developing a robust data acumen within an organization involves multiple facets, each contributing to the overall capacity to harness data effectively. It's not just about understanding the technical aspects of data management; it's about how data can influence business decisions and drive organizational growth.

Building data acumen within an organization requires a strategic and comprehensive approach. Here are some key initiatives to build data acumen:
1. To build **Foundational Concepts and Skills** ensure team members understand data terminology, structures, and formats. Teach them fundamental statistical concepts and ethical considerations related to data and AI usage. 
1. Advanced **Technical Competencies** to equip teams with the tools and skills they need to manipulate and visualize data effectively. This may involve technical training for data extraction, transformation, and loading (ETL) as well as for creating meaningful data visualizations. Familiarize them with cloud platforms for data storage, processing, and analytics.
1. Foster **Domain-Specific Knowledge** for your industry, the business processes, and the role data plays in decision making.
1. Promote a culture that values **Data-Based Decision Making**. Teach team members how to formulate hypotheses, design experiments, and analyse results.
1. Encourage cross-functional communication and **collaboration** to break down silos and ensure that data insights are shared and acted upon across the organization.
1. Foster **Continuous Learning** and curiosity about emerging technologies, tools, and best practices.
1. As AI becomes more prevalent, it's important to understand its ethical implications. Embed **Responsible AI**, considering factors like fairness, transparency, and bias.

## Data Governance and Operations
Data governance and operations play a pivotal role in managing the availability, usability, integrity, and security of the data used in an organization. This comprises of establishing standards, policies, and processes to ensure data is managed in a consistent, secure, and compliant manner.
the "data product" is a trusted, reusable data asset, registered and catalogued. A **Data Product mindset** involves defining clear roles such as data product owners (Data Publishers), data owning teams (Data Producers), and data consumers. By treating data as a product, businesses can focus on high-impact business use cases, package data for easy comprehension and usage, reduce compliance and user access risks, control data sprawl and costs, and maintain trust with stakeholders.
To build a strong data governance and operations capability, the following key areas need to be addressed:

1. **Data mapping** tools offer a visual representation of the data landscape, showing the flow from source to target systems. **Lineage** tools track data from its origin through transformations, helping identify dependencies and impacts of changes in the data structure.
1. Tools to ensure **Data Quality**:  accuracy, completeness, and consistency of data are crucial. These provide capabilities like data profiling, cleansing, validation, matching, and monitoring.
1. **Compliance** tools to ensure alignment with legal, contractual, and business rules automate the process of compliance checking and reporting.
1. Tools enforcing **access and security** controls, ensuring data privacy, and protection against data breaches are integral. These may include encryption tools, intrusion detection systems, and identity and access management solutions.
1. Tools to collect, organize, and display data about data (**metadata**) help make data more understandable and usable.
1. A searchable repository (**Data Catalog**) of data products makes it easier to find and understand data. These tools typically provide metadata, usage information, and data samples.
1. Tools to manage the flow of data through its lifecycle (**Data Lifecycle** (DLM)), from creation and initial storage to obsolescence and deletion. These tools provide capabilities like data classification, retention, archiving, and deletion.

## Federated Compute
Federated Compute is a computational capacity that enables data distribution and processing across various systems or locations while retaining centralized control. It achieves this by bringing computation to the data, a significant shift from the traditional model of moving data to computation. This method proves advantageous in big data applications, such as Machine Learning and Analytics, where data transfer can be expensive and time-consuming. Data APIs facilitate this process, serving as connectors between various data sources and computing nodes, thus enabling efficient access, processing, and utilization of data across different systems and locations.
Designing or modernising a data platform with federated compute involves several key considerations:
1. With federated compute, data remains at its source, which can help in meeting data privacy regulations. However, it's critical to ensure that any computations or transformations performed don't inadvertently compromise data privacy. Security measures should be in place to protect the data during computation.
1. Organization needs a robust and reliable network infrastructure to facilitate efficient data communication between different nodes in a federated computing setup. Any network latency or downtime can significantly impact the performance of transformation pipelines, analytical tools, and ML/AI services.
1. A well-defined data governance policy is essential to manage data access, usage, and quality. This is especially important in a federated environment where data is distributed across multiple locations.
1. The system should be designed to handle growth in data volume, velocity, and variety.
1. The components of the federated compute system should be interoperable, meaning they can work together seamlessly. This includes transformation pipelines, analytical tools, and ML/AI services, which need to be able to access and process data from various sources.
1. The organization needs to possess or develop the necessary skillsets to implement and manage federated compute environments. This includes understanding of distributed computing, data privacy and security, and the specific tools and platforms being used.
1. The selection of tools and platforms for transformation pipelines, analytical services, and ML/AI services is important. These tools should support federated computing, be scalable, and be easy to integrate with existing systems.
1. The performance of the Federated Compute system should be monitored and optimized regularly.

## Shared Services
Shared Services are key data estate services that are managed centrally and assist with creating, launching, and administering applications and data in a data platform setting. They help organizations simplify data management processes, eliminate duplication, and make data use more efficient and effective by providing common tasks and services, leveraging best practices and methods.
The key Shared Services that should be considered when establishing or modernising a data platform are listed below:
1. **Self-Service Metadata-Driven Ingestion** to enable automated, metadata-driven data ingestion, reducing the need for manual coding and simplifying the process of data ingestion for data engineers and other users.
1. **Data Standardization** to ensure that data is converted into a common format, making it easier to leverage across the organization. This may involve operations like converting data to common units, standardizing number of decimal places etc.
1. **Data Merging** to combine data from different sources into a single, unified view, providing a more complete and accurate picture of the data.
1. **Data Intelligence** as a way of using AI and machine learning to enrich the data and provide insights.
1. **Enterprise data models** to provide high-level representations of an organization's data in 3nf, helping to facilitate data management tasks such as data integration, data governance, and data quality.
1. **Data Products** to provide trusted, curated data assets that are built within the data platform, such as datasets, tables, reports, predictive models, and AI-powered applications. These data products will be cataloged for easy discovery and re-use.

## Data Sources
Data Sources are the repositories of information that feed into the AI-driven data strategy. These repositories, whether they exist on-premises or in the cloud, provide diverse types of data ranging from transactional, historical, or master data, which can be harnessed for AI applications. They can be structured in various formats such as Data Lakes, Data Warehouses, Data Marts, Lake Houses or File Shares, each offering different data storage and processing capabilities. Data sources may also be exposed through REST API (often used for SaaS applications), or via message-oriented sources (such as Message Queues or Publish-Subscribe Systems) for near/real-time data streaming applications. Careful consideration of what data should be ingested into the datalake should be taken, landing only the data that will help solve the use case. 

## Enterprise Services
Enterprise Services are the operations and infrastructure within any organization aiming to leverage data for AI-based innovation and growth. These services include DevOps, a practice that combines development and operations to shorten the system development life cycle and provide continuous delivery with high software quality. CI/CD/CT, or Continuous Integration, Continuous Delivery, and Continuous Testing, which are practices designed to improve and expedite the software delivery process. Identity Services, which ensure secure and efficient user access management across the organization. Operational Monitoring and Logging, to oversee system performance, identify issues, and maintain a comprehensive record of system activities for troubleshooting and analysis. Security Services, to protect sensitive information and systems from cyber threats, ensuring data integrity and availability. Enterprise Services underpin not only the Data Platform, but also other technical platforms within an enterprise, they are fundamentally important for data-driven innovation.

## Data Product Mindset
Adopting a data product mindset is key.  Adopting a product mindset is important to the success of an enterprise data strategy because it helps accelerate the adoption and scale of AI. A data product is a trusted, reusable data asset that empowers users with an intelligence-driven culture.  
It requires data product owners (Data Publishers) who are responsible for defining objectives and key results for the product.  It requires data owning team(s), producers that execute on the plan with an agile approach and lastly data consumers who use these data products to create business value. By treating data as a product, businesses can focus their data initiatives on clearly identified high-impact business use cases, and organize, structure, and package data in a way that makes it easy to understand, analyse, and use. This helps to reduce clutter and compliance risk, promote data engineering reuse, control data sprawl and cost, and maintain trust with customers, partners, and employees. 
One example of a data product is a customer analytics report that provides insights into customer behaviour and preferences. This data product would be a logical entity that draws relationships to data and other metadata, is made available for broad consumption, and is aligned to the domain of business functions and goals. It is optimized for readability, decoupled from the operational/transactional application, and adheres to central interoperability standards. A data product mindset is essential in building a strong foundation for data-driven decision making and innovation. 

## Operationalize 
In this era of AI, companies need to change the way they operate and have systems thinking underpinning the culture. They need to have data and AI acumen and become stewards of the data.  They need a data strategy to generate business value from their data. They need to make data & analytics a permanent discipline that sits in the business and, as is the case with their AI strategy, they need strong leadership with a clear mandate on how we will succeed.  It's not just about collecting data but having a plan to fully harness its potential. 
As we navigate this transformative era, remember that data is not just a resource, but a strategic imperative in the realm of AI.  A clear data strategy that is centered on business use case enablement is crucial for companies to become data driven in this AI-driven world. 

## Logical architecture for modern data platform
<img src="./media/graphic 24-2024-06-10.png" 
alt="Figure 3. Logical data architecture image" />

This architecture is designed to be federated, meaning that each Data Landing Zone operates semi-autonomously, yet under a common set of governance and operational principles. To ensure quality and reliability, each zone follows a medallion (bronze, silver, and gold) architecture, with each level signifying a higher degree of data maturity and trustworthiness.
In this model, the Shared Services Data Landing Zone acts as the central hub for integration with primary data sources. In contrast, Domain Landing Zones consume data products from the Shared Services Zone and transform or enrich these products according to specific domain requirements. This approach allows each domain to produce its own derivative data products, including experiments, reports, models, and more.
It's important to note that the logical architecture described here is technology-agnostic. The aim is to provide a flexible framework that can be realized using a variety of technologies, depending on the unique needs and existing infrastructure of each organization.

## Business Outcomes and Use Cases

Start with well-defined business problem and then identify the AI use cases that will solution the problem and measure their impact. Use Objectives and Key Results (OKRs) to define the vision, success factors, and stakeholders for each use case. Assess the current and desired data estate and identify the people, process, and platform capabilities needed to enable the use cases. This shows the gaps and opportunities to develop a roadmap for the capability plan that supports the company's strategy.
Use a data strategy framework to guide the data capabilities design. Focus on the use case-specific needs rather than generic solutions to avoid scope and cost mismatches. For example, address data quality issues within the use case context rather than broadly.
Create a data strategy working group to coordinate data activities across the organization. This group should include experts, stakeholders, and representatives from relevant business units and teams who work together and have clear responsibilities and outcomes.
Instead of a data Center of Excellence (COE), be a center of enablement. Learn from each use case and apply the lessons to the next one.
Representatives from the MAIVA Governance Council should be present in this working group, at a minimum the Chief Data Scientist. Likewise, representatives from this group should be present on the MAIVA Governance Council to drive the development and execution of data-related activities and initiatives, being the champions for common programs which focus on shaping and implementing strategies related to data management, usage, and governance. 

 
A data strategy needs to be a gradual and flexible journey that prioritizes outcomes over perfection, and aligns people, process and platforms to unleash the power of data for innovation and growth.

AI is a major transformation that depends on showing the business value of not only AI but also the data that powers it. To scale up AI, you need to build value from the data that drives it.

## MAIVA – Develop, Deploy & Operationalize AI/ML Use Case

**Strategic Outcomes Enabled by the Journey of Every Use Case**

<img src="./media/graphic 7- 2024-01-25 .png" 
alt="A screenshot of a computer screen Description automatically generated" />

As stated, the enterprise strategy informs the line of business strategy
which in turn informs the portfolio of AI investments. Each AI
investment or use case takes a product management approach involving
data, agile and iterative development, AI/ML practices, and deployment.
Model lifecycle management will establish a standard for model
development, training, pipeline management (collect, organize, analyze,
and infuse), and deployment.

All use cases are operationalized with feedback loops from users and
performance monitoring to track outcomes from the investment in AI. This
operationalization is the key to realizing the expected return from AI
investment.

**Platform, Develop & Deploy: The AI accelerators to get the flywheel
started**

One consideration for prioritizing AI use cases is *optimal* return; in
other words highest outcome for the least cost. Across AI there are
patterns that are commonly repeated in synonymous use cases. For
example, revenue forecasting in a finance operations department uses the
same time-series classification model as required in retail to predict
order volume or demand. Or setting up the environments required to
execute similar AI initiatives is another example of commonly repeated
patterns. The code that is required in the common patterns is being
harvested to create assets that will accelerate the execution of AI
initiatives. These accelerators have been curated in the [Data Science
Toolkit](https://www.ds-toolkit.com/).

The [Data Science Toolkit](https://www.ds-toolkit.com/) on GitHub, is a
growing library of pre-configured and re-usable AI accelerators that
help improve the consistency, speed and ability of data science teams to
implement common AI-based use cases. API management and configuration
guidelines facilitate the publication of models as data products, with
consistent, security-enhanced, and compliant endpoints. These
accelerators offer an excellent starting point or inaugural use case for
the MAIVA framework, simplifying the development and deployment of the
use case to broaden the focus to governance and operationalization of
AI.

<img src="./media/graphic 9- 2024-01-25 .png" 
alt="A screenshot of a computer Description automatically generated" />

It is important to compartmentalize the core AI technical capabilities
required to support the different lines of business. Whilst there are
strong, frequent and necessary interactions between the technical and
business teams, the core platform capabilities need to be rolled out and
implemented in the enterprise with the view of providing consistency
across the lines of business at the platform level.

**MAIVA – Operationalization**

Operationalization is the final stage for every use case.
Operationalization is the driver of enduring value from AI governance.
It is important to establish best practices and tools to test, deploy,
manage, and monitor models in the enterprise production environments.
The goal should be to reduce and avoid “technical debt” in AI-based
applications.

The picture below shows the iterative cycle that enterprise teams follow
to structure their delivery of ML and AI solutions across Process,
Platform and People:

<img src="./media/graphic 8- 2024-01-25 .png" 
alt="A diagram of a business value Description automatically generated" />

The lifecycle for AI resources must be managed consistently with all
other on-premises and cloud resources within a CI/CD environment.

Disciplined operationalization will enable rapid, reliable, consistent,
secure and safe deployment of AI / ML at scale. There is tremendous
value to be gained from a well-defined approach to operationalization;
the return on use cases will be higher and the costs to scale will be
optimized.

Operationalization within this framework will involve a standardized
approach to lifecycle management, a common platform for governance and
monitoring of AI, standardardized performance and usage monitoring, as well as
any technical engineering standards that underlie enablement of the use
case.

The platform will enable integration of the workflow and application,
feature stores, model repository and orchestration, and the platform
will enable scale through data pipelines and containers common across
multiple use cases within the line of business. The platform will also
drive reproducible and responsible models that are transparent and
explainable.

Similarly, standard performance monitoring will include:

- Performance of each model, monitoring for accuracy and continued
  fidelity

- Performance of each model for outcome and return

- Portfolio reporting to understand adoption of all models

- The user experience of each model should include feedback from the
  user to the development team.

**MLOps & LLMOps & GenAIOps**

With the rapid evolution of AI solutions and services,
operationalization is not a unilateral capability. MLOps will diverge
from all generative AI ops; but even among generative AI,
operationalization will be different. At the moment, what makes this
challenging at the enterprise level is that most enterprise-grade use
cases enable complex solutions that involve multiple AI disciplines:
machine learning, cognitive services and generative AI. All the more
reason to have a disciplined and rigorous approach.

Machine Learning models can be deployed alongside the AI services that
wrap them and the applications and consume them as part of a unified
release process. Development and Data Science teams need to follow a
structured ML Ops process that will enable the following activities in
the enterprise:

- Develop & train model(s) with reusable ML pipelines

- Package model(s) using containers to capture runtime dependencies for
  inference

- Validate model behaviour – functionally, in terms of responsiveness,
  in terms of regulatory compliance

- Deploy model(s) - to cloud & edge, for use in real-time / streaming /
  batch processing

- Monitor model behaviour & business value, know when to replace /
  deprecate a stale model

Below is a diagram that illustrates the sequence of these MLOps
activities:

<img src="./media/MLOpsActivities.png"
alt="A diagram of a model Description automatically generated" />

The goal is to accelerate the adoption of ML/AI in software solutions
and fast delivery of intelligent software.

**GenAI and Operationalization**

The advent of generative AI is changing operationalization of AI.
Indeed, the technology is evolving so quickly that there is not yet a
standard for operationalization of all genAI capabilities.

All AI capabilities share a common goal in operationalization to
streamline the product lifecycle that consists of design, development,
deployment and operations of AI use cases. The commonalities include but
are not limited to the need for best practices and iterative approaches
to development, evaluation and deployment, scalability, the need for
performance monitoring to drive continuous improvement. Additionally,
because of genAI, there is growing attention towards ensuring the
ethical creation and use of AI-generated content, managing the
unpredictability of generative models, balancing creativity with
accuracy, among others. Operationalization of genAI extends beyond the
traditional scope of MLOps to address the distinct challenges and
ethical considerations intrinsic to GenAI.

Currently emerging is an operationalization approach to large language
models (LLM) or LLMOps. The diagram below summarizes the shift that is
currently happening between MLOps and LLMOps.

**Paradigm Shift from MLOps to LLMOps**

<img src="./media/graphic 10- 2024-01-25 .png"
alt="A screenshot of a computer program Description automatically generated" />

As generative AI continues to evolve, standards for operationalization
of each discipline will also evolve. Meanwhile as these standards
emerge, we can illuminate what we know about the lifecycle of generative
AI use cases.

**GenAI Lifecycle**

<img src="./media/graphic 12- 2024-01-25 .png"
alt="A computer screen with text and colorful arrows Description automatically generated" />

This diagram presents the lifecycle of GenAI which consists of the
following phases:

**1. Scope & Foundational GenAI:** understand a business use case,
collect requirements, and select the appropriate foundational models,
such as large language models, small language models or other generative
AI models and services. These could include Azure OpenAI APIs, Llama-2,
Phi-2, Falcon, DALL-E 2, etc.

**2. Data Governance and Management:** focus on the data, including data
cleaning and enrichment, representation of data as the knowledge (e.g.
chunking and vectorization for Retrieval Augmented Generation (RAG)
scenario), and ensure adherence to data governance principles.

**3. Customize:** enrich AI models with domain-specific grounding data
and select or optimize various information retrieval approaches, such as
text search, vector search, or hybrid search. Include fine-tuning of the
GenAI model and/or combining the model with other AI techniques, as well
as refining the model based on the overall solution evolution.

**4. Prompt Engineering and Refinement:** engineer prompts (zero-shot,
one-shot, few-shot, chain of thought) and the prompt refinement based on
user feedback and solution evolution. It is a critical step for
preparing the GenAI model to perform the tasks it will be used for,
ensuring that the interactions with the model are as effective and
relevant as possible. [GenAIOps with Prompt
Flow](https://github.com/microsoft/llmops-promptflow-template) is a
template and guidance for building GenAI-infused applications. It offers
centralized code hosting, lifecycle management, variant and
hyperparameter experimentation, A/B deployment, many-to-many
dataset/flow relationships, multiple deployment targets, comprehensive
reporting, BYOF (bring-your-own-flows), configuration-based development,
local and cloud-based experimentation, prompt evaluation, endpoint
testing, and optional Human-in-loop validation. It supports both simple
and complex GenAI-infused apps and is highly customizable.

**5. Experiment & Evaluate:** execute the GenAI flow with additional
data or services to evaluate responses from the AI against ground truth
or context relevance. Depending on the use case, it may involve
benchmarking different models, chunking methods, information retrieval
approaches and prompts.

**6. Continuous Integration (CI), Continuous Evaluation (CE), and
Continuous Deployment (CD):** maintain code quality with engineering
best practices and manage the promotion of GenAI flows to higher
environments. Attention is also given to security measures that include
implementing safeguards against the generation of harmful or biased
content, securing the prompt data against unauthorized access, and
ensuring that the system is secured against potential adversarial
attacks.

**7. Monitor:** monitor performance metrics (quality, ethics, model
security) for the GenAI flow, detect the emergence of potential
inappropriate outputs, communicate to stakeholders, review and act upon
end-user feedback, while ensuring active human oversight.

**8. Deployment & Inferencing:** package and deploy the GenAI flow as a
scalable container for making predictions, secure model access, and
enable blue/green deployment with traffic routing control for testing
the GenAI flow.

# MAIVA Operating model process and roadmap

A governance framework is the foundation of managing a portfolio of AI
investments.

The operating model will include the people, the process and the
technology involved in governing AI.

A governing body of cross-functional, cross-line-of-business
representatives will drive the operating model. The basic function of
the governance council will be to **intake** AI use cases,
**prioritize** those use cases that will be built, and to **monitor**
the performance and return from investments in AI. **Governance**
function will also include alignment to **strategy**, adherence to
**responsible AI** and **security** policies of the enterprise, line of
business **data strategy** and **platform roadmap**, and line of
business **change management.**

<img src="./media/graphic 13- 2024-01-25 .png"
alt="A screenshot of a computer Description automatically generated" />

The governance board should meet on a regular basis and should include
stakeholders from each business unit, functional areas and product unit.
Key technology stakeholders will include the owners of the data and
platforms serving the business unit and functional areas.

MAIVA intake will evaluate and prioritize both new AI initiatives and
those that were deployed and should now be enhanced. New AI initiatives
have demonstrated potential outcomes and feasibility through
experimentation. As existing AI initiatives mature, they will need to be
amended, for example retraining machine learning models to mitigate and
avoid drift. New work intake and existing work maintenance both require
investment of time and resources; therefore, they should both be
prioritized.

Before meeting, the board of stakeholders should review the scope,
feasibility, scale and potential return and risk from each initiative
proposed. There should be a preliminary decision from each set of
stakeholders on each investment decision. If all are aligned, then the
investment proposal’s ranking will be defined before the intake meeting.
The meeting agenda should be to discuss initiatives for which there is
not yet alignment on priority and to set the overall prioritization
across new and existing AI initiatives.

The output of the intake process will be a prioritized list of AI
investments.

To establish MAIVA’s operating model requires on-going, cross-enterprise
commitment and the road map is long-term. The inaugural ‘build’ of the
framework will establish the rhythm and the enablers. Organizational
enablers, i.e. setting up the intake process and monitoring and
establishing key changes such as a common approach to experimentation
and product lifecycle will be driven with change management. The goal is
to have an established intake rhythm and prioritization process that is
driven by the monitoring and feedback from operations.

There will also be technical enablement required to get platforms
established, baseline policies gathered, and the data required.
Additionally, this will establish the collaboration environment for data
scientists to engage with the support engineers monitoring the
production environments. The goal is to have the required platform, data
and collaboration environment for the initial product build or use case.

With organizational and technical enablers in place, the first use
case(s) can be put through the system. Their outcomes and key results
quantified and experimentation conducted to drive prioritization through
intake will be completed. The design and development will include the
appropriate accelerators to enable consistency, and the deployment will
demonstrate the expected outcome. Iteration will get through to
successful deployment. The target here is to provide demonstration of
expected value and the a roadmap to fully deployment.

The inaugural build will also establish the operational enablers,
including performance monitoring, reporting and anomaly detection and
alerting. The target here is to establish clear lines of feedback to the
intake, closing the cycle of the MAIVA system.

<img src="./media/graphic 14- 2024-01-25 .png" />

# Security & Responsible AI considerations in AI governance

As the enterprise looks to drive governance of AI investments, it will
be important to establish policies to set common boundaries and mitigate
risk. It is well known that AI will not always be accurate or will not
always be correct. Thus, the potential for unexpected outcomes means
that there should be guardrails defined to protect the company and the
public from unintended consequences.

Microsoft has developed a set of human-centered principles to guide the
responsible design, development, and deployment of AI technologies and
ML as well as the responsible use of AI. These principles are fairness,
reliability and safety, privacy and security, inclusiveness,
transparency, and accountability. We have established governance of
these principles and supporting standards within the Office of
Responsible AI and we have expanded awareness and use of these
principles in our products, services and commercial lines of business.

<img src="./media/graphic 15- 2024-01-25 .png"/>

The principles and standards of responsible AI use and development
should be established by a separate and centralized enterprise
organization and its impact should reach all lines-of-business in order
to insure that there is a common foundation and like approach across the
enterprise. Thus, the responsible AI standards will not be created and
managed within the MAIVA governance framework, but the MAIVA governance
framework will be dependent upon the responsible AI standard and should
align closely.

The
[Microsoft-RAI-Impact-Assessment-Template.pdf](https://blogs.microsoft.com/wp-content/uploads/prod/sites/5/2022/06/Microsoft-RAI-Impact-Assessment-Template.pdf)
may be helpful in this endeavor. There are links to additional resources
in the Resources section of this document.

**Security**

Security includes the policies, the standards, and the controls that
ensure confidentiality, integrity, and accessibility of AI assets and
data. Similar to responsible AI principles, security policies and
standards should be defined outside of this AI prioritization and
governance framework; but the use cases that are prioritized should each
be subject to these policies and standards.

Security will focus on data security, platform security, application
security, and network security.

- **Data security**: This covers the protection of data from
  unauthorized access, modification, disclosure, or destruction. It
  includes encryption, masking, anonymization, pseudonymization, and
  tokenization of the data, as well as access control, authentication,
  authorization, and auditing of the data.

- **Platform security**: This covers the protection of the AI platform
  and the data platform from unauthorized access, modification,
  disclosure, or destruction. It includes encryption, hardening,
  patching, and updating of the platform, as well as access control,
  authentication, authorization, and auditing of the platform.

- **Application security**: This covers the protection of the AI models
  and applications from unauthorized access, modification, disclosure,
  or destruction. It includes encryption, signing, testing, and
  validation of the models and applications, as well as access control,
  authentication, authorization, and auditing of the models and
  applications.

- **Network security**: This covers the protection of the network and
  communication channels from unauthorized access, modification,
  disclosure, or destruction. It includes encryption, firewall, VPN, and
  SSL/TLS of the network and the communication channels, as well as
  access control, authentication, authorization, and auditing of the
  network and the communication channels.

# Economics of governance framework (or the opportunity cost)

The economics of AI governance are straightforward: standardize the
approach to AI development and manage the portfolio of AI investments
for return and feasibility in the context of risk and compliance all to
optimize return. Increase return, reduce cost, reduce risk, drive
efficiencies – the classic optimization recipe.

The economics of AI are driven by operating costs and capital expense;
but with the advent of cloud-based compute and software-as-a-service,
operating costs are an increasingly larger part of this economy than
capital expense.

- Operating expenses

  - Licensing

  - Consumption/service fees

  - Maintenance

  - Network cost

  - Platform cost

  - Apps (falls into licensing)

  - Labor

- Capital expense

  - Smaller as cloud is primary platform, service and data store

As indicated at the outset, the art behind AI comes from culture, from
people and process. AI governance should seek to create a culture of
financial responsibility whilst ensuring proper governance in the
delivery process and operational activities.

A culture of financial responsibility is one in which each workload team
is equipped and motivated to make prudent financial decisions across the
product lifecycle. It drives the team to proactively seek out and
implement strategies to enhance efficiency and reduce unnecessary
expenses.

Some considerations in the context of efficiency and economics of AI
governance:

- Efficiency quotient

  - Standards – both tools and practices – will reduce costs and speed
    time to launch. Multiple tools may be available, but all options
    will be standard.

  - Best-in-class tools minimize the need to develop custom solutions
    for planning, development, testing, collaboration, and continuous
    integration and continuous delivery (CI/CD).

  - Standard processes & practices in software development and data
    science drive efficiency

  - Buy vs build – if there is a product on the market that serves the
    need, reflects future potential and is not relatively prohibitive in
    licensing fees… it will be more efficient to buy. Build brings cost
    of ownership (build, maintenance, possibly capex)

  - Standardize app design patterns

  - Standardize testing approach. Shift-left approach to testing by
    performing unit testing early and often throughout the development
    process. Frequent testing in each development environment helps
    developers gain confidence in their applications.

  - follow DevSecOps practices as part of an enterprise standard
    operating procedures. 

  - Standard metrics for software performance and AI performance

- Amplify the value

  - Skill non-technical resources with no-code/low-code technologies to
    empower them to innovate.

- Manage technical debt –

  - Implement standards and guidelines that help address technical
    debt. 

  - Adopt a mindset that elevates the evaluation of technical debt in
    the application team's deliverables.

  - This motivates teams to consider and address technical debt
    regularly to avoid accumulation.

  - Technical debt should be addressed as a regularly recurring task in
    the product backlog.

# Roles Supporting MAIVA

## The ongoing framework

Given the process illustrated in the Operating Model section, there will
be several roles required as aligned to the primary components of the
framework:

<img src="./media/graphic 20- 2024-01-31 .png"
alt="A screenshot of a computer Description automatically generated" />

Required roles, filled by specific resources

| **MAIVA – Governance Role**            | **Perenial Governance Resource**                                    | **Ad Hoc Resource per use case**                                                |
|----------------------------------------|---------------------------------------------------------------------|---------------------------------------------------------------------------------|
| Program management                     | Line of business executive sponsor                                  |                                                                                 |
|                                        | Line of business program management (may be more than one resource) |                                                                                 |
|                                        | Business Analyst(s)                                                 |                                                                                 |
|                                        | Technical / Platform management                                     |                                                                                 |
|                                        | Technical/ LOB data management                                      |                                                                                 |
|                                        |                                                                     | Change management architect                                                     |
| Platform & experimentation             | Several architects: security, AI, UX/UI                             | (Use case specific feature teams)                                               |
|                                        |                                                                     | (Use case specific program management teams)                                    |
|                                        |                                                                     | (use case specific Data scientists, ML engineers, data engineers feature teams) |
|                                        |                                                                     |                                                                                 |
| Per use case - enablement / deployment |                                                                     | Data scientists, ML engineers, data engineers (feature teams)                   |
|                                        |                                                                     | App developers(s) (feature teams)                                               |
|                                        |                                                                     | Product management                                                              |
| Operationalization                     | DevOps engineer                                                     |                                                                                 |
|                                        |                                                                     | Data scientist, data engineers, data analysts                                   |
| Advisory                               | Security                                                            |                                                                                 |
|                                        | Responsible AI                                                      |                                                                                 |
|                                        | Privacy                                                             |                                                                                 |
|                                        | Legal                                                               |                                                                                 |
|                                        | Finance                                                             |                                                                                 |
|                                        | HR                                                                  |                                                                                 |
|                                        | CX                                                                  |                                                                                 |
|                                        |                                                                     |                                                                                 |

## The inaugural build

The purpose of the inaugural build will be to (1) establish the MAIVA
governance operating model and (2) drive the operating model through the
first few use cases. The inaugural build will include:

- Definition and gathering of the governance board

- Definition of the governance process and frequency

- Communications strategy

- Identification of the first use cases to bring through intake

- The first prioritized roadmap

- Design, development and deployment of the first one to three use cases

- Build of the Performance monitoring tools and feedback loops

- Operationalization of the first use case(s)

- Roadmap to refine governance

This will require all of the resources identified in the table above.
Additionally, this will require a **lead business architect**, a **lead
technical architect** and a **lead change management architect**
together providing product leadership in the first or inaugural build;
consider appointing the change management architect to as lead for the
inaugural build. Supporting these three architects may be additional
resources within their domains or consultants to support this inaugural
build. Supporting the inaugural build, a communications manager to
develop a strategy that supports change management and executes
communication to employees will be essential. Additionally, project
management support will be required to structure the inaugural build
project and execution.

<img src="./media/graphic 21- 2024-01-31 .png"
alt="A screenshot of a computer Description automatically generated" />

# Resources

- [Data Science Toolkit](https://www.ds-toolkit.com/)

- [Microsoft AI MVP
  Book](https://www.amazon.com/Microsoft-AI-MVP-Book-Practical/dp/1676417982)

- [Azure Data and AI Architect Handbook: Adopt a structured approach to
  designing data and AI solutions at scale on Microsoft
  Azure](https://www.amazon.com/gp/product/1803234865/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)

- [Microsoft Solutions Playbook
  (internal)](https://internal.playbook.microsoft.com/playbook/)

- [GenAI Customer Investigation
  Tutorial_Sept2023.pptx](https://microsoft.sharepoint.com/:p:/r/teams/CSEGlobalPrograms/ISE%20Upskilling/Tutorial%20Content/GenAI%20Customer%20Investigation%20Tutorial_Sept2023.pptx?d=w4b06290afc43411c98fabc2568a0d805&csf=1&web=1&e=sHIy3s&isSPOFile=1)

<!-- -->

- [The new era of AI](https://www.microsoft.com/en-us/ai)

- [Empowering Responsible AI
  Practices](https://www.microsoft.com/en-us/ai/responsible-ai)

- [<u>Microsoft-RAI-Impact-Assessment-Template.pdf</u>](https://blogs.microsoft.com/wp-content/uploads/prod/sites/5/2022/06/Microsoft-RAI-Impact-Assessment-Template.pdf)

- [Responsible AI BDM_EBC FY23 Dec 2023 final.pptx
  (sharepoint.com)](https://microsoft.sharepoint.com/:p:/s/ResponsibleAI/EeP8p0Ez_UJMvLM2mn8G_x8Byap7ppZwsgRDnZP2NlF40w?e=zFH9jv)

- [Microsoft
  Security](https://www.microsoft.com/en-us/security/business)

- [Security development lifecycle
  guide](https://learn.microsoft.com/en-us/azure/well-architected/security/secure-development-lifecycle).

# Gratitude for contributors

Many thanks and much appreciation to the following for their
contributions and oversight of this effort!

- Willie Ahlers
- Francois Magnin
- Kimberly O'Donoghue
- Ricardo Sousa
- Sofia Noejovich
- Mike Swantek
- Erica Lawrie
- Karsten Strøbæk
- Rick Hines
- Todd Ray
- Philip Carpenter
- Ravi Thoutireddy
- Liana Napalkova
- Michele Usuelli
- Amit Tyagi
- Carlo Binda
