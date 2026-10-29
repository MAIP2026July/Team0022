IdeaHub AI - Success Metrics
Product: IdeaHub AI
Team: Team0022
Measurement Scope: Product, AI and Business Outcomes

1. Measurement Objective
IdeaHub AI should not be considered successful merely because it can generate assessments or recommend Artificial Intelligence opportunities.
The product should demonstrate that it helps enterprise transformation teams make opportunity assessments that are:
• faster;
• more complete;
• more consistent;
• easier to explain;
• appropriately governed; and
• useful for transformation decision-making.
The success framework therefore combines:
1. business and product outcome metrics;
2. AI quality metrics;
3. Human-in-the-Loop metrics; and
4. guardrail metrics.

2. North Star Outcome
The primary product outcome is:
Improve the quality and efficiency of transformation opportunity qualification while preserving human accountability.

We will assess this through a combination of time, completeness, reviewer agreement, recommendation usefulness and governance measures rather than relying on one metric alone.

3. Business and Product Metrics
M-01 - Opportunity Qualification Time
Purpose: Measure whether IdeaHub AI reduces the effort required to structure and initially assess an opportunity.
Measure:
Time required to move from initial opportunity submission to a review-ready initial assessment.
Desired Direction: Lower
A lower time is valuable only if assessment quality is maintained.

M-02 - Clarification Cycles
Purpose: Measure whether IdeaHub AI identifies missing information early.
Measure:
Number of clarification rounds required before an opportunity is considered sufficiently complete for initial assessment.
Desired Direction: Lower
A reduction may indicate that missing information is being identified earlier in the workflow.

M-03 - Assessment Completeness
Purpose: Determine whether the assessment contains sufficient information for review.
Measure:
Percentage of required assessment dimensions containing either:
• supporting evidence;
• a documented assumption; or
• an explicit information gap.
Desired Direction: Higher
The product should prefer an explicit information gap over an invented fact.

M-04 - Reviewer Usefulness Rating
Purpose: Determine whether the assessment helps the reviewer make a decision.
Measure:
Reviewer rating of the usefulness of:
• opportunity summary;
• value assessment;
• feasibility assessment;
• risk identification;
• intervention recommendation; and
• recommendation rationale.
Desired Direction: Higher

M-05 - Decision Traceability
Purpose: Determine whether an opportunity decision can be understood later.
Measure:
Percentage of reviewed opportunities containing:
• original input;
• important assumptions;
• evidence status;
• Artificial Intelligence recommendation;
• human decision; and
• override rationale where applicable.
Desired Direction: Higher

4. AI Quality Metrics
M-06 - Information Extraction Accuracy
Purpose: Determine whether IdeaHub AI correctly interprets submitted opportunity information.
Measure:
Agreement between information extracted by IdeaHub AI and information identified by a human reviewer for fields such as:
• process;
• stakeholder;
• business problem;
• pain point;
• expected outcome; and
• available evidence.
Desired Direction: Higher

M-07 - Missing Information Detection
Purpose: Determine whether IdeaHub AI identifies important information gaps.
Measure:
Agreement between the information gaps identified by IdeaHub AI and those identified by a human reviewer.
Desired Direction: Higher

M-08 - Intervention Recommendation Agreement
Purpose: Determine whether the suggested intervention is credible.
Measure:
Percentage of opportunities where an experienced reviewer agrees with the recommended intervention or considers it a reasonable alternative.
Desired Direction: Higher
The objective is not to force complete agreement.
Reviewer disagreement is useful evidence when it reveals missing context or weaknesses in the assessment logic.

M-09 - Recommendation Explainability
Purpose: Determine whether reviewers understand why the recommendation was produced.
Measure:
Reviewer assessment of whether the rationale clearly explains:
• evidence used;
• important assumptions;
• missing information;
• recommended intervention; and
• material risks.
Desired Direction: Higher

5. Human-in-the-Loop Metrics
M-10 - Human Override Rate
Purpose: Measure how frequently reviewers modify or reject the Artificial Intelligence recommendation.
Measure:
Percentage of reviewed opportunities where the final human decision differs materially from the Artificial Intelligence recommendation.
Interpretation:
A high override rate may indicate:
• weak Artificial Intelligence recommendations;
• missing business context;
• unclear assessment criteria; or
• insufficient evidence.
A very low override rate should not automatically be considered positive because it could also indicate over-reliance on Artificial Intelligence.
The reason for the override is therefore more important than the percentage alone.

M-11 - Override Reason Distribution
Purpose: Understand why human reviewers disagree with IdeaHub AI.
Possible reasons may include:
• incorrect interpretation;
• missing context;
• inappropriate intervention;
• incorrect assessment;
• risk concern;
• additional evidence;
• strategic consideration; or
• reviewer preference.
Repeated override patterns should inform future product improvement.

M-12 - Reviewer Confidence
Purpose: Determine whether reviewers feel sufficiently informed to make the final decision.
Measure:
Reviewer rating of confidence in making a decision after reviewing the IdeaHub AI assessment.
Desired Direction: Higher
The objective is confidence based on evidence and transparency, not blind trust in Artificial Intelligence.

6. Process Mining Metrics
Process Mining is an opportunity-discovery input rather than the entire IdeaHub AI product.
The important measure is therefore not how many process findings are produced.
M-13 - Finding-to-Opportunity Conversion
Purpose: Determine whether Process Mining observations can be converted into meaningful transformation opportunities.
Measure:
Percentage of reviewed Process Mining findings that can be translated into a clearly defined business opportunity suitable for further assessment.
Desired Direction: Higher, subject to quality.
A high conversion rate is not desirable if weak process observations are converted into unnecessary transformation initiatives.

M-14 - Business Relevance of Process Findings
Purpose: Determine whether process findings represent material business problems.
Measure:
Reviewer assessment of whether the identified process issue warrants further transformation consideration.
Desired Direction: Higher

7. Guardrail Metrics
IdeaHub AI should not improve efficiency by creating unacceptable decision risk.
The following guardrails are therefore required.
G-01 - Unsupported Business Facts
IdeaHub AI should not invent:
• process volumes;
• financial benefits;
• employee effort;
• system capabilities;
• implementation cost; or
• other unsupported business facts.
Desired Direction: Minimise
Where information is unavailable, the product should identify the gap explicitly.

G-02 - Complex-Technology Force-Fit
The product should not recommend Generative Artificial Intelligence or Agentic Artificial Intelligence where a simpler intervention adequately addresses the identified problem.
Measure:
Reviewer identification of recommendations where unnecessary technological complexity was introduced.
Desired Direction: Minimise

G-03 - High-Risk Recommendation Without Human Review
Opportunities involving significant business, privacy, security, regulatory or operational consequences must not bypass appropriate human review.
Desired Direction: Zero accepted cases without required review.

G-04 - Unexplained Recommendation
The product should not provide a transformation recommendation without a rationale indicating the evidence and assumptions supporting it.
Desired Direction: Minimise

G-05 - Hidden Information Gap
A recommendation should not present strong confidence when critical information required for the assessment is missing.
Desired Direction: Minimise

8. Initial Evaluation Approach
We will initially evaluate IdeaHub AI using representative transformation opportunity scenarios.
The scenarios should include:
• a traditional automation opportunity;
• a Generative Artificial Intelligence opportunity;
• an Agentic Artificial Intelligence opportunity;
• a process-redesign opportunity;
• a weak or low-value opportunity;
• an incomplete opportunity requiring clarification; and
• an opportunity originating from a Process Mining observation.
The same opportunities can be reviewed independently by a human reviewer and by IdeaHub AI.
The comparison will focus on:
• information extracted;
• gaps identified;
• assessment quality;
• recommended intervention;
• explanation quality; and
• human corrections.
Any scenarios created specifically for demonstration or evaluation will be identified as synthetic.

9. Measurement Principles
The following principles will guide product measurement:
Measure Outcomes, Not AI Activity
The number of Artificial Intelligence calls, generated recommendations or processed ideas does not by itself demonstrate product value.
Avoid False Precision
We will not define arbitrary percentage targets without evidence.
Initial evaluation will establish a baseline from which meaningful thresholds can later be determined.
Evaluate by Segment and Scenario
Overall averages should not hide poor performance in important opportunity types or high-risk scenarios.
Human Disagreement Is Evidence
Reviewer overrides and corrections are not automatically failures.
They provide evidence about where the product requires additional context, clearer rules or improved Artificial Intelligence behaviour.
Protect the Product Purpose
Efficiency improvements should not come at the cost of explainability, human accountability or responsible transformation decisions.

10. Success Decision
IdeaHub AI should be considered promising for further investment if initial evaluation shows that the product:
• structures transformation opportunities more effectively;
• identifies important missing information;
• produces credible intervention recommendations;
• provides understandable reasoning;
• supports rather than replaces human judgement;
• helps reviewers make more consistent decisions; and
• does not introduce unacceptable governance or decision risk.
If these conditions are not demonstrated, the product should be revised before broader investment is considered.
