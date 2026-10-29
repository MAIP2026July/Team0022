IdeaHub AI - User Journey, Human Review and Trust Design
Product: IdeaHub AI
Team: Team0022
Primary User: Transformation Analyst / Automation or AI Centre of Excellence Analyst
Decision User: Transformation Lead / Centre of Excellence Lead

1. Design Objective
IdeaHub AI is intended to support transformation decisions rather than make autonomous investment decisions.
The user experience must therefore help users:
• understand what information has been provided;
• identify what information is missing;
• distinguish evidence from Artificial Intelligence interpretation;
• understand why an intervention has been recommended;
• recognise uncertainty;
• challenge or modify the assessment; and
• retain human accountability for the final decision.
The product should optimise for informed decision-making rather than simply producing recommendations quickly.

2. End-to-End User Journey
The core IdeaHub AI journey consists of seven stages.
Stage 1 - Opportunity Intake
The Transformation Analyst starts with either:
Idea-led entry
A transformation idea submitted by a business stakeholder.
or
Process-led entry
A Process Mining or process-analysis observation indicating a possible improvement opportunity.
The user provides available information such as:
• business process;
• problem description;
• affected stakeholder;
• current pain point;
• frequency or volume;
• expected outcome; and
• available evidence.
The product does not require every field to be complete before beginning the assessment.

Stage 2 - AI Interpretation
IdeaHub AI interprets the submission and creates a structured opportunity summary.
The summary identifies:
• process;
• stakeholder;
• business problem;
• pain point;
• expected outcome;
• evidence provided; and
• any information interpreted from the submitted narrative.
Before continuing, the user can review and correct the interpretation.

Stage 3 - Information Gap Identification
IdeaHub AI checks whether important information is missing.
Examples may include:
• process frequency;
• transaction volume;
• manual effort;
• current cycle time;
• affected users;
• business impact;
• data availability; or
• system dependencies.
The product should not invent missing business information in order to complete the assessment.

Stage 4 - Clarification
IdeaHub AI generates focused clarification questions.
Example:
Current process volume has not been provided. Approximately how many cases are processed per month?

The user can:
• provide the missing information;
• mark the information as unknown; or
• continue while accepting the information gap.
Continuing with missing information may reduce evidence confidence.

Stage 5 - Opportunity Assessment
IdeaHub AI presents an assessment across four areas:
Business Value
How significant is the potential business improvement?
Feasibility
How practical is the proposed transformation based on process, data, technology and integration considerations?
Risk
What business, privacy, security, regulatory, operational or adoption risks require attention?
Evidence Strength
How much of the assessment is supported by available information versus assumptions or missing evidence?
The assessment should clearly identify where confidence is limited.

Stage 6 - Intervention Recommendation
IdeaHub AI recommends an intervention such as:
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
The recommendation must include a concise explanation.
Example:
Recommended Intervention: Workflow Automation + Generative AI Assistance
The process contains repeatable approval steps that can be handled through workflow automation, while exception handling requires interpretation of unstructured information.
Agentic Artificial Intelligence is not recommended at this stage because the available evidence does not demonstrate a need for autonomous multi-step decision-making.

This explanation helps ensure that Artificial Intelligence is not recommended simply because Artificial Intelligence capability is available.

Stage 7 - Human Review and Decision
The Transformation Lead or authorised reviewer receives:
• opportunity summary;
• value assessment;
• feasibility assessment;
• risk assessment;
• evidence status;
• recommended intervention;
• assumptions;
• information gaps; and
• recommendation rationale.
The reviewer can:
1. Accept
2. Modify
3. Request More Information
4. Reject
If the reviewer modifies or rejects the recommendation, the reviewer should provide a reason.
Possible final opportunity outcomes include:
• Reject;
• Refine;
• Explore;
• Prototype;
• Pilot; or
• Candidate for Prioritisation.
Artificial Intelligence supports the decision.
The human reviewer remains accountable for the final outcome.

3. Human-in-the-Loop Design
Human-in-the-Loop is not included merely as a generic control.
Human intervention is required where human judgement materially improves the decision.
Human Review Point 1 - Interpretation
The user can correct IdeaHub AI's understanding of the opportunity before assessment.
Human Review Point 2 - Missing Information
The user decides whether:
• additional evidence should be supplied;
• information can remain unknown; or
• the assessment should stop until the information becomes available.
Human Review Point 3 - Assessment
The user can challenge:
• value assessment;
• feasibility assessment;
• risk assessment; and
• evidence status.
Human Review Point 4 - Intervention Recommendation
The reviewer can accept or override the recommended intervention.
Human Review Point 5 - Final Opportunity Decision
Only an authorised human reviewer can determine whether the opportunity progresses.

4. Trust Design Principles
Principle 1 - Do Not Hide Missing Information
If important information is unavailable, IdeaHub AI should say so.
An explicit information gap is preferable to an invented assumption.

Principle 2 - Separate Evidence from AI Interpretation
The user should be able to distinguish between:
• information supplied by the user;
• information supplied by supporting evidence;
• Artificial Intelligence interpretation; and
• unresolved information gaps.

Principle 3 - Explain Recommendations
IdeaHub AI should not only state:
Agentic AI recommended.

The product should explain why that approach is appropriate and why simpler alternatives are insufficient.

Principle 4 - Avoid False Precision
IdeaHub AI should avoid presenting unsupported numbers such as:
Expected benefit: 37.8%

unless the number is supported by evidence.
Where evidence is limited, qualitative assessments such as High, Medium or Low may be more appropriate.

Principle 5 - Allow Challenge and Override
Users must be able to disagree with Artificial Intelligence.
The product should treat human disagreement as useful information rather than as an error.

Principle 6 - Preserve Decision Traceability
The product should retain enough information to understand:
• what was submitted;
• what IdeaHub AI recommended;
• what evidence was available;
• which assumptions existed;
• what the human reviewer changed; and
• the final decision.

5. Uncertainty Design
IdeaHub AI should communicate uncertainty as part of the normal product experience.
High Evidence Confidence
Use when the key facts required for the initial assessment are available.
The product can provide a stronger recommendation while still allowing human review.
Medium Evidence Confidence
Use when some important information is available but one or more uncertainties remain.
The product should:
• highlight the missing evidence;
• explain the potential effect on the recommendation; and
• encourage human review.
Low Evidence Confidence
Use when critical information is unavailable or contradictory.
The product should avoid presenting a strong recommendation.
Possible behaviour includes:
• asking additional clarification questions;
• recommending further assessment; or
• indicating that sufficient evidence does not currently exist.

6. Example Trust Presentation
An IdeaHub AI assessment may display:
Recommendation
Workflow Automation + Generative AI Assistance
Evidence Confidence
Medium
Why?
The process is repetitive and contains structured approval rules, supporting workflow automation.
Exception handling includes unstructured supplier correspondence, where Generative AI may provide additional value.
Evidence Gap
Current exception volume has not been confirmed.
Important Assumption
Existing workflow systems provide suitable integration interfaces.
Risk
Generated exception summaries must be reviewed before they are used for payment-related decisions.
Human Decision Required
Yes

This structure makes uncertainty and human accountability visible rather than hiding them behind a recommendation score.

7. Fallback Behaviour
IdeaHub AI should have defined behaviour when it cannot make a reliable assessment.
Missing Information
Ask for clarification or record the gap.
Contradictory Information
Highlight the contradiction and request review.
Insufficient Evidence
Recommend further assessment rather than produce a strong transformation recommendation.
Unsupported Financial Benefit
Do not generate the benefit.
Request additional evidence.
High-Risk Opportunity
Require appropriate human review before progression.
AI Service Unavailable
The opportunity information should remain available for later assessment or manual review rather than being lost.

8. UX Principle
The core user-experience principle for IdeaHub AI is:
Make the reasoning visible enough for the user to make a better decision, without requiring the user to understand how the underlying AI model works.

The product should encourage calibrated trust rather than either blind acceptance or complete distrust of Artificial Intelligence.
