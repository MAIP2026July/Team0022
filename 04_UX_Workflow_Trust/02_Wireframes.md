IdeaHub AI - Wireframes
Product: IdeaHub AI
Team: Team0022
Artefact: Initial Product Wireframes

1. Wireframe Objective
These wireframes illustrate the core IdeaHub AI product journey from opportunity submission to human-reviewed transformation decision.
The wireframes focus on:
• structured opportunity intake;
• Artificial Intelligence-assisted interpretation;
• missing-information clarification;
• value, feasibility, risk and evidence assessment;
• intervention recommendation;
• explainable reasoning; and
• Human-in-the-Loop review.
The screens represent an initial product design and may evolve based on user feedback and product validation.

2. End-to-End Screen Flow
flowchart LR
    A[1. Opportunity Intake]
    B[2. AI Interpretation]
    C[3. Clarification]
    D[4. Assessment]
    E[5. Intervention Recommendation]
    F[6. Human Review]

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F

    C -->|Insufficient information| A
    F -->|Request more information| C
    F -->|Modify assessment| D
