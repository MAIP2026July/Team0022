IdeaHub AI - Product Strategy & Opportunity Framing
1. Product Vision
Our vision is to help enterprise transformation teams make faster, more consistent and more explainable decisions about which process improvement, automation and Artificial Intelligence opportunities deserve further investment.
IdeaHub AI will bring together two sources of transformation opportunities:
1. ideas submitted by business stakeholders; and
2. improvement signals identified from existing processes through Process Mining or process analysis.
The product will help convert these inputs into structured opportunities, assess them consistently, recommend an appropriate intervention and provide a transparent rationale for human review.
IdeaHub AI is intended to support transformation decision-making rather than replace the people accountable for those decisions.

2. Target Users
Primary User - Transformation Analyst / Automation or AI Centre of Excellence Analyst
The primary user receives ideas or process improvement signals and converts them into structured transformation opportunities.
The primary user needs to:
• understand the actual business problem;
• identify missing information;
• evaluate potential business value;
• assess feasibility and risks;
• compare opportunities consistently; and
• recommend whether the opportunity should progress.
Decision-Maker - Transformation or Centre of Excellence Lead
The decision-maker reviews the assessment and determines whether the opportunity should be rejected, refined, investigated further or added to the candidate transformation backlog.
Supporting Stakeholders
Other stakeholders may include:
• business idea submitters;
• process owners;
• business analysts;
• Process Mining analysts;
• solution architects;
• Artificial Intelligence specialists;
• risk and compliance reviewers; and
• portfolio or investment governance teams.
The needs and decision rights of these stakeholders are different, and IdeaHub AI will not treat them as one generic user group.

3. Jobs to Be Done
Transformation Analyst
When I receive an incomplete transformation idea or process improvement signal, I want to understand and assess it using consistent criteria so that I can create a defensible recommendation without repeatedly reconstructing the assessment manually.

Transformation Lead
When multiple transformation opportunities compete for limited funding and delivery capacity, I want comparable information about their value, feasibility, risk and evidence so that I can prioritise opportunities more transparently.

Process Owner
When my existing process experiences delays, rework, exceptions or high manual effort, I want potential improvement opportunities identified and explained in business terms so that I can decide whether further transformation assessment is justified.

Governance Reviewer
When an opportunity is recommended for further investment, I want to understand the evidence, assumptions, risks and human overrides behind the recommendation so that I can make an informed decision.

4. Opportunity Framing
Enterprise transformation teams may receive opportunities through workshops, emails, spreadsheets, assessments and discussions with business stakeholders.
At the same time, existing processes may contain improvement opportunities that have not yet become formal transformation ideas.
These can include:
• repeated bottlenecks;
• rework loops;
• long waiting times;
• excessive manual hand-offs;
• high exception volumes; and
• repetitive activities.
Process Mining can help expose these patterns, but a process finding does not automatically establish that an organisation should invest in fixing it.
The finding must still be translated into a business opportunity and evaluated for:
• business value;
• feasibility;
• risk;
• data readiness;
• implementation complexity;
• available evidence; and
• the suitability of different intervention approaches.
IdeaHub AI therefore focuses on the decision between discovery and investment.
Our opportunity is to improve how raw ideas and process findings become structured, comparable and governance-ready transformation opportunities.

5. Role of Process Mining
Process Mining will act as an additional discovery input to IdeaHub AI.
We do not intend to build a complete Process Mining platform as part of the Minimum Viable Product.
Instead, IdeaHub AI may consume a Process Mining observation such as:
A process contains repeated approval loops, resulting in longer waiting time and additional manual work.

IdeaHub AI will help translate the observation into assessable questions such as:
• What business outcome is affected?
• How frequently does the issue occur?
• What is the impact of the delay or rework?
• Is the root problem caused by process design, policy, technology, data or another constraint?
• Would removing or redesigning the activity solve the problem?
• Is automation or Artificial Intelligence actually required?
This allows Process Mining to support opportunity discovery while IdeaHub AI focuses on qualification and decision support.

6. Intervention Strategy
IdeaHub AI will not assume that Artificial Intelligence is the correct answer to every transformation opportunity.
Depending on the problem and available evidence, the product may recommend:
1. no intervention;
2. further assessment;
3. process redesign;
4. policy or procedural change;
5. deterministic business rules;
6. workflow automation;
7. Robotic Process Automation;
8. Predictive Machine Learning;
9. Generative Artificial Intelligence;
10. Agentic Artificial Intelligence; or
11. a hybrid approach.
This is important because the product is intended to improve transformation decisions rather than maximise the number of Artificial Intelligence use cases.

7. First Wedge
Our first product wedge will be:
AI-assisted qualification of one enterprise transformation opportunity, optionally supported by a Process Mining observation.

The first wedge will deliberately avoid enterprise-wide portfolio optimisation.
A user will provide:
• an opportunity or process observation;
• a description of the current problem;
• basic process context;
• available volume or frequency information;
• the expected business outcome; and
• available supporting evidence.
IdeaHub AI will:
1. interpret the submission;
2. identify important missing information;
3. generate clarification questions;
4. structure the opportunity;
5. provide an indicative value, feasibility and risk assessment;
6. suggest the most appropriate intervention;
7. explain the rationale and important assumptions; and
8. present the recommendation to a human reviewer.
The human reviewer will make the final decision.

8. Build vs Buy vs Partner / API
For the Minimum Viable Product, we recommend a hybrid sourcing approach.
Build
We should own and design the product-specific capabilities that differentiate IdeaHub AI:
• opportunity intake workflow;
• assessment framework;
• intervention taxonomy;
• deterministic scoring and thresholds;
• human-review workflow;
• explainability;
• audit trail; and
• decision logic.
Buy / Consume through an Application Programming Interface
We do not propose training a foundation model.
An existing Large Language Model may be consumed through an Application Programming Interface for capabilities such as:
• understanding unstructured opportunity descriptions;
• extracting relevant information;
• identifying information gaps;
• generating clarification questions;
• drafting opportunity summaries; and
• generating recommendation explanations.
Partner
A future enterprise implementation may integrate with existing Process Mining platforms or enterprise workflow platforms rather than rebuilding those capabilities.
For the prototype, these integrations can be represented using synthetic Process Mining findings and mocked interactions.
Rationale
The product's differentiation lies in the transformation qualification framework, intervention decision logic, explainability and governance workflow rather than ownership of a foundation model or Process Mining engine.
Using existing model capabilities also allows us to test the product concept before investing in specialised Artificial Intelligence infrastructure.

9. Strategic Scope Boundary
In Scope for the Initial Product
• idea-led opportunity intake;
• Process Mining observation intake;
• AI-assisted interpretation;
• missing-information identification;
• clarification;
• opportunity classification;
• indicative value, feasibility and risk assessment;
• intervention recommendation;
• explanation of rationale and assumptions;
• human review and override; and
• candidate backlog recommendation.
Out of Scope
• building a complete Process Mining engine;
• automatic integration with all enterprise applications;
• autonomous funding decisions;
• autonomous implementation of recommended solutions;
• detailed project estimation;
• enterprise-wide resource optimisation;
• production financial modelling;
• training a proprietary foundation model; and
• production-scale deployment.
These boundaries keep the first product focused on validating the transformation opportunity qualification decision.
