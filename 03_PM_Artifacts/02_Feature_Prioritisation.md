IdeaHub AI - Feature Prioritisation
Product: IdeaHub AI
Team: Team0022
Prioritisation Method: MoSCoW
Status: Initial Product Scope

1. Prioritisation Objective
The purpose of this prioritisation is to define the minimum set of capabilities required for IdeaHub AI to deliver its core product promise:
Convert an enterprise transformation idea or Process Mining observation into a structured, explainable and human-governed opportunity recommendation.

Features have been prioritised based on:
• relevance to the core user problem;
• contribution to the first product wedge;
• dependency on other capabilities;
• ability to demonstrate the role of Artificial Intelligence;
• importance to trust and human accountability; and
• delivery complexity.
The prioritisation does not assume that all valuable capabilities must be included in the initial release.

2. Must-Have Capabilities
These capabilities are essential to demonstrate the core IdeaHub AI product journey.
MH-01 - Opportunity Intake
The user must be able to submit a transformation opportunity using normal business language.
The intake should capture:
• opportunity title;
• process name;
• business problem;
• current pain points;
• affected stakeholder;
• available volume or frequency;
• expected outcome; and
• available supporting evidence.
MH-02 - Process Mining Observation Intake
The user must be able to provide an existing Process Mining or process-analysis observation.
The observation may describe:
• a bottleneck;
• a rework loop;
• extended waiting time;
• repeated exceptions;
• manual hand-offs; or
• another process improvement signal.
IdeaHub AI will treat the observation as an input requiring business qualification rather than as an approved transformation opportunity.
MH-03 - Information Interpretation
IdeaHub AI must interpret the submitted opportunity and identify available information relating to:
• business process;
• stakeholder;
• business problem;
• pain point;
• frequency or volume;
• expected outcome; and
• evidence.
MH-04 - Missing Information Identification
IdeaHub AI must identify material information that is missing from the submission.
The product must not silently invent missing business facts.
MH-05 - Clarification Questions
Where important information is unavailable, IdeaHub AI must generate relevant clarification questions.
The user must be able to:
• provide additional information; or
• continue with the information gap clearly recorded.
MH-06 - Opportunity Classification
IdeaHub AI must classify the opportunity according to the primary transformation need.
Possible classifications include:
• process improvement;
• deterministic automation;
• workflow automation;
• knowledge or information retrieval;
• prediction or classification;
• document intelligence;
• Generative Artificial Intelligence;
• Agentic Artificial Intelligence; and
• further assessment required.
MH-07 - Indicative Value Assessment
The product must provide an indicative assessment of potential business value using defined criteria.
The assessment should consider areas such as:
• business impact;
• process frequency or volume;
• manual effort;
• cycle-time impact;
• customer or employee impact; and
• strategic relevance.
MH-08 - Indicative Feasibility Assessment
The product must provide an indicative feasibility assessment.
The assessment should consider:
• process stability;
• rule clarity;
• data availability;
• data readiness;
• integration complexity;
• technology maturity; and
• human dependency.
MH-09 - Risk Identification
IdeaHub AI must identify material risks associated with the opportunity.
These may include:
• decision consequence;
• privacy;
• security;
• regulatory requirements;
• explainability;
• operational failure; and
• adoption risk.
MH-10 - Intervention Recommendation
IdeaHub AI must recommend an appropriate intervention based on the identified problem and available evidence.
The recommendation may include:
• no intervention;
• further assessment;
• process redesign;
• policy or procedural change;
• deterministic business rules;
• workflow automation;
• Robotic Process Automation;
• Predictive Machine Learning;
• Generative Artificial Intelligence;
• Agentic Artificial Intelligence; or
• a hybrid approach.
The product must not automatically recommend Artificial Intelligence.
MH-11 - Recommendation Rationale
The product must explain:
• why the intervention was recommended;
• what evidence supports it;
• what assumptions remain;
• what information is missing; and
• what risks require further attention.
MH-12 - Evidence and Confidence Status
IdeaHub AI must communicate the quality of the available evidence.
The assessment may use understandable levels such as:
• High;
• Medium; or
• Low.
The product must avoid presenting incomplete information as certain.
MH-13 - Human Review
A human reviewer must review the recommendation before the opportunity receives a final outcome.
The reviewer must be able to:
• accept the recommendation;
• modify the assessment;
• request more information; or
• reject the recommendation.
MH-14 - Override with Rationale
The human reviewer must be able to override the Artificial Intelligence recommendation.
The reason for a modification or rejection must be captured to preserve decision traceability.
MH-15 - Opportunity Outcome
After human review, the opportunity must receive one of the following outcomes:
• Reject;
• Refine;
• Explore;
• Prototype;
• Pilot; or
• Candidate for Prioritisation.
These terms represent possible transformation decisions. They do not predetermine the development approach for IdeaHub AI itself.

3. Should-Have Capabilities
These capabilities add meaningful value but are not required to establish the core product journey.
SH-01 - Opportunity Comparison
Users should be able to compare two or more opportunities across:
• value;
• feasibility;
• risk;
• evidence strength; and
• recommended intervention.
SH-02 - Draft Business Case Summary
IdeaHub AI should generate a concise draft summary containing:
• problem;
• affected stakeholder;
• expected value;
• proposed intervention;
• important assumptions;
• principal risks; and
• recommended next action.
SH-03 - Assessment History
The product should retain earlier versions of the assessment so that changes to inputs, scores and recommendations can be reviewed.
SH-04 - Reviewer Comments
The reviewer should be able to add comments explaining:
• concerns;
• additional evidence;
• requested changes; or
• conditions for progression.
SH-05 - Candidate Backlog View
The product should provide a simple view of opportunities that have been accepted as candidates for further prioritisation.
SH-06 - Source Reference
Where supporting documents or Process Mining findings are provided, the assessment should reference the relevant source.
SH-07 - Decision Audit Trail
The product should record:
• who reviewed the opportunity;
• what decision was made;
• whether the Artificial Intelligence recommendation was changed; and
• why the change was made.

4. Could-Have Capabilities
These capabilities may improve the broader product but are not required for the initial release.
CH-01 - Document Upload
Users could upload:
• process documents;
• Standard Operating Procedures;
• Business Process Model and Notation diagrams;
• workshop notes; or
• assessment reports.
The product could extract relevant information from these sources.
CH-02 - Process Mining Platform Integration
IdeaHub AI could integrate directly with external Process Mining platforms to receive process findings automatically.
CH-03 - Custom Assessment Criteria
Organisations could configure their own value, feasibility, risk and strategic-alignment criteria.
CH-04 - Industry-Specific Assessment Models
The product could provide assessment models tailored to industries such as:
• banking;
• insurance;
• healthcare;
• life sciences; or
• manufacturing.
CH-05 - Portfolio Dashboard
The product could display:
• opportunity distribution;
• transformation-type distribution;
• investment themes;
• risk concentration;
• assessment status; and
• backlog trends.
CH-06 - Collaboration and Approval Workflow
Multiple reviewers could collaborate, provide formal approvals and route opportunities across governance levels.
CH-07 - Recommendation Learning
The product could analyse reviewer corrections and outcomes to improve future recommendations, subject to appropriate governance and data controls.

5. Won’t-Have-for-Now Capabilities
These capabilities are intentionally excluded from the initial product scope.
WH-01 - Full Process Mining Engine
IdeaHub AI will not replace Process Mining platforms or independently perform full process discovery from enterprise event logs.
WH-02 - Autonomous Funding Approval
IdeaHub AI will not authorise budgets or approve transformation investments without human accountability.
WH-03 - Autonomous Solution Implementation
The product will not create and deploy the recommended automation or Artificial Intelligence solution.
WH-04 - Detailed Delivery Estimation
IdeaHub AI will not provide final project cost, schedule, staffing or implementation estimates.
WH-05 - Enterprise Resource Optimisation
The initial product will not allocate delivery teams, funding or enterprise capacity across the transformation portfolio.
WH-06 - Proprietary Foundation Model
We will not train or operate a proprietary foundation model as part of the initial product scope.
WH-07 - Unsupported Return-on-Investment Calculation
The product will not generate financial benefits without evidence supplied or validated by the organisation.
WH-08 - Unrestricted Autonomous Learning
The product will not automatically modify its assessment framework based on reviewer activity without governance and validation.

6. Prioritisation Summary
Priority	Purpose
Must Have	Establish the complete opportunity intake, assessment, recommendation and human-review journey
Should Have	Improve comparison, traceability, collaboration and business-case preparation
Could Have	Support enterprise integration, customisation and portfolio-level use
Won’t Have for Now	Prevent uncontrolled scope expansion and preserve human accountability

The initial product should first prove that IdeaHub AI can structure an opportunity, identify information gaps, provide a credible assessment, recommend an appropriate intervention and support a transparent human decision.
Broader portfolio management, enterprise integrations and autonomous implementation should be considered only after the core opportunity qualification journey has been validated.
