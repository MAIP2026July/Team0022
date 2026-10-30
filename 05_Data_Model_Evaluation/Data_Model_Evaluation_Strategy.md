IdeaHub AI - Data, Model & Evaluation Strategy
Product: IdeaHub AI
Team: Team0022
Artefact: Data, Model and Evaluation Strategy

1. Strategy Objective
IdeaHub AI uses Artificial Intelligence where interpretation of unstructured business information can improve transformation opportunity assessment.
However, the complete product should not depend on Artificial Intelligence for every decision.
Our proposed approach combines:
• Artificial Intelligence for interpretation, extraction, clarification and recommendation support;
• deterministic logic for defined scoring, thresholds and governance rules; and
• human judgement for final transformation decisions.
The objective is therefore not to maximise the use of Artificial Intelligence, but to use the appropriate mechanism for each product decision.

2. AI Problem Definition
IdeaHub AI contains multiple Artificial Intelligence tasks rather than one single AI problem.
AI Task 1 - Information Extraction
The product should extract relevant information from an unstructured opportunity description.
Examples include:
• business process;
• stakeholder;
• business problem;
• pain point;
• expected outcome;
• process frequency or volume;
• evidence provided; and
• known constraints.
This converts an unstructured business narrative into information that can be assessed consistently.

AI Task 2 - Missing Information Detection
IdeaHub AI should identify critical information that has not been provided.
Examples may include:
• current process volume;
• manual effort;
• cycle time;
• affected users;
• data availability;
• system dependencies; or
• evidence supporting the expected benefit.
The product should identify the gap rather than invent the missing information.

AI Task 3 - Clarification Question Generation
Based on the identified information gaps, IdeaHub AI should generate focused questions that improve the assessment.
Questions should be directly relevant to the opportunity rather than generic questionnaires.

AI Task 4 - Opportunity Classification
The product should classify the primary transformation need.
Possible classifications include:
• process improvement;
• deterministic automation;
• workflow automation;
• knowledge or information retrieval;
• prediction or classification;
• document intelligence;
• Generative Artificial Intelligence;
• Agentic Artificial Intelligence; or
• further assessment required.

AI Task 5 - Intervention Recommendation
IdeaHub AI should recommend an appropriate transformation approach using the available evidence and defined assessment framework.
The product should consider simpler alternatives before recommending more complex Artificial Intelligence approaches.

AI Task 6 - Explanation Generation
IdeaHub AI should explain:
• why the intervention was recommended;
• what evidence supports the recommendation;
• what assumptions were made;
• which information remains unavailable; and
• which risks require attention.
The explanation supports human review rather than replacing it.

3. Role of Deterministic Logic
Artificial Intelligence will not control every part of the assessment.
Deterministic logic is more appropriate for:
• defined score calculations;
• mandatory assessment criteria;
• governance conditions;
• approval requirements;
• decision-state transitions;
• hard thresholds; and
• mandatory escalation conditions.
For example, if an organisation defines that opportunities involving regulated personal information require a privacy review, this should be implemented as an explicit control rather than left entirely to a language model.

4. Human Decision Role
Human users remain responsible for:
• validating business context;
• confirming important evidence;
• correcting Artificial Intelligence interpretation;
• challenging value, feasibility or risk assessments;
• overriding intervention recommendations;
• accepting or rejecting opportunities; and
• approving progression into the transformation backlog.
IdeaHub AI is therefore designed as a decision-support product.

5. Data Strategy
5.1 Input Data
IdeaHub AI may receive information from:
• opportunity descriptions;
• process descriptions;
• business pain-point descriptions;
• user-provided process metrics;
• Process Mining findings;
• business documents;
• process maps;
• Standard Operating Procedures;
• workshop notes; and
• previous opportunity assessments.
Not all of these inputs are required for every opportunity.

5.2 Process Mining Data
Process Mining can provide evidence relating to:
• process variants;
• waiting time;
• bottlenecks;
• rework;
• repeated exceptions;
• manual hand-offs; and
• conformance deviations.
IdeaHub AI does not need to perform full Process Mining itself.
It can consume a Process Mining observation and translate it into a candidate opportunity for further qualification.

5.3 Data Quality
The assessment should consider whether required information is:
• available;
• complete;
• current;
• relevant;
• reliable; and
• supported by evidence.
Poor data quality should reduce the confidence of the recommendation rather than be hidden by Artificial Intelligence-generated assumptions.

5.4 Synthetic Data
Synthetic or illustrative opportunity data may be used during product development and evaluation where real enterprise information is unavailable or confidential.
Synthetic data must be clearly identified as synthetic.
It should not be presented as evidence of real customer behaviour, benefits or product performance.

5.5 Sensitive Enterprise Information
Transformation opportunities may contain:
• confidential process information;
• operational metrics;
• system names;
• employee information;
• customer information;
• commercially sensitive information; or
• regulatory data.
A production version of IdeaHub AI would therefore require appropriate controls for:
• access;
• data minimisation;
• retention;
• privacy;
• security; and
• permitted use.

6. Ground Truth and Human Reference
IdeaHub AI recommendations involve judgement.
There may not always be one universally correct transformation intervention.
Therefore, evaluation should not assume that a single human answer automatically represents absolute ground truth.
Instead, representative scenarios can be independently assessed by experienced reviewers.
The comparison can examine:
• whether the business problem was interpreted correctly;
• whether important information gaps were identified;
• whether the proposed intervention is reasonable;
• whether simpler alternatives were considered;
• whether the rationale is understandable; and
• whether important risks were identified.
Where reviewers disagree, the disagreement itself should be analysed rather than automatically treating one assessment as incorrect.

7. Baseline Alternative
The primary baseline for IdeaHub AI is the existing manual opportunity-assessment approach.
A simplified baseline may include:
1. opportunity submitted through email, workshop or spreadsheet;
2. analyst manually reviews the description;
3. analyst contacts the business for missing information;
4. analyst records assessment details in a spreadsheet or template;
5. analyst estimates value and feasibility;
6. analyst proposes an intervention;
7. reviewers discuss the opportunity; and
8. a decision is recorded manually.
This baseline is important because IdeaHub AI must demonstrate value compared with the current process rather than simply demonstrate that Artificial Intelligence can generate an assessment.

8. Alternative Non-AI Product
A stronger comparison is also possible against a structured digital form with deterministic scoring.
Such a system could:
• collect mandatory information;
• calculate predefined scores;
• route opportunities;
• create a backlog; and
• enforce governance rules.
This alternative may be sufficient where opportunities are highly structured and assessment rules are stable.
IdeaHub AI becomes more relevant when transformation opportunities are:
• described using varied business language;
• incomplete;
• supported by unstructured evidence;
• ambiguous;
• dependent on contextual clarification; or
• open to multiple possible intervention approaches.
This comparison will help determine whether Artificial Intelligence creates sufficient incremental value.

9. Model Strategy
We do not initially propose training a proprietary foundation model.
An existing Large Language Model can support:
• semantic interpretation;
• extraction;
• clarification;
• classification;
• recommendation drafting; and
• explanation generation.
Product-specific value should come from:
• the opportunity-assessment framework;
• intervention taxonomy;
• defined decision logic;
• evidence handling;
• Human-in-the-Loop workflow; and
• governance.
This reduces the need for significant model-development investment before the product concept has been validated.

9.1 Model Independence
Where practical, IdeaHub AI should avoid unnecessary dependence on one specific model provider.
The product logic should separate:
• product workflow;
• assessment framework;
• deterministic rules; and
• language-model interaction.
This can make future model replacement or comparison easier.
However, model portability should be validated rather than assumed because different models may behave differently.

10. Evaluation Strategy
Evaluation will occur at three levels.
Level 1 - AI Task Quality
Evaluate whether IdeaHub AI correctly:
• extracts information;
• identifies gaps;
• generates useful clarification questions;
• classifies the opportunity;
• recommends a reasonable intervention; and
• explains the recommendation.

Level 2 - Human Decision Support
Evaluate whether reviewers:
• understand the assessment;
• find the recommendation useful;
• can identify the evidence and assumptions;
• can challenge incorrect recommendations; and
• retain control over the final decision.

Level 3 - Product Outcome
Evaluate whether the product improves:
• assessment effort;
• assessment completeness;
• decision consistency;
• decision traceability; and
• quality of the transformation opportunity backlog.
Detailed product metrics are maintained separately in:
03_PM_Artifacts/05_Success_Metrics.md

11. Representative Evaluation Scenarios
Evaluation should include different types of opportunities rather than only straightforward Artificial Intelligence candidates.
Representative scenarios should include:
Scenario 1 - Rules-Based Automation
A stable, repetitive process with clear deterministic rules.
Expected product behaviour:
IdeaHub AI should avoid force-fitting Generative or Agentic Artificial Intelligence.

Scenario 2 - Generative AI Opportunity
A workflow that contains significant unstructured information requiring interpretation, summarisation or generation.
Expected product behaviour:
IdeaHub AI should identify where Generative Artificial Intelligence creates value and where human review remains necessary.

Scenario 3 - Agentic AI Opportunity
A multi-step workflow involving controlled coordination across systems or activities.
Expected product behaviour:
IdeaHub AI should assess whether autonomy creates sufficient additional value and identify required controls.

Scenario 4 - Process Redesign
A process contains unnecessary or outdated steps.
Expected product behaviour:
IdeaHub AI should recommend redesign rather than automating waste.

Scenario 5 - Insufficient Information
The opportunity description lacks important evidence.
Expected product behaviour:
IdeaHub AI should request clarification or recommend further assessment rather than fabricate information.

Scenario 6 - Process Mining Finding
Process Mining identifies repeated rework, waiting time or another process issue.
Expected product behaviour:
IdeaHub AI should convert the observation into a candidate business opportunity and assess whether intervention is justified.

Scenario 7 - Persuasive but Weak Opportunity
The submission uses strong Artificial Intelligence terminology but provides weak evidence of business value.
Expected product behaviour:
IdeaHub AI should assess the opportunity based on evidence rather than the sophistication of the language used.

12. Go / Revise / Stop Decision Logic
The evaluation should support three possible product decisions.
GO
Continue investment when evidence suggests that IdeaHub AI:
• interprets opportunities usefully;
• identifies meaningful information gaps;
• provides credible intervention recommendations;
• supports explainable human decisions; and
• demonstrates potential improvement over the manual or rules-only baseline.
REVISE
Revise the product when:
• the product creates some value but important weaknesses remain;
• recommendations require frequent correction;
• assessment criteria are unclear;
• users do not understand the rationale; or
• important opportunity types are handled inconsistently.
STOP / REFRAME
Reconsider the product thesis when:
• a structured non-AI system provides comparable value;
• Artificial Intelligence does not materially improve opportunity qualification;
• reviewers cannot trust or understand the recommendations;
• required enterprise data cannot be used responsibly; or
• the operating cost and governance burden outweigh the expected value.

13. Evaluation Principle
The central evaluation principle for IdeaHub AI is:
The product should be evaluated on whether it improves transformation decision quality, not on whether the underlying Artificial Intelligence appears sophisticated.

A simpler product that supports better decisions is preferable to a more advanced Artificial Intelligence solution that creates additional uncertainty without sufficient business value.
