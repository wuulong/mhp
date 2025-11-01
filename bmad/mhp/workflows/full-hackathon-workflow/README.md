# Full Hackathon Orchestration Workflow

This workflow provides a comprehensive orchestration of the entire hackathon process, guiding teams from the initial kickoff to the final retrospective. It ensures seamless collaboration between all core MHP workflows by defining a logical sequence of execution.

## Purpose

To streamline the hackathon experience by automating the progression through key stages: kickoff, idea generation, solution development, presentation preparation, and retrospective. This workflow ensures that all necessary steps are followed and that the outputs from one stage can inform the next.

## How it Works

This workflow sequentially invokes the following MHP sub-workflows:

1.  **Hackathon Kickoff (`hackathon-kickoff`)**: Initiates the hackathon, including problem definition, initial brainstorming, team role assignment, and project planning.
2.  **Idea Generation (`idea-generation`)**: Facilitates creative idea generation for hackathon projects, leveraging methodologies from the CIS module.
3.  **Solution Development (`solution-development`)**: Guides teams through the iterative development of their solution, covering design, implementation, testing, and optimization.
4.  **Presentation Preparation (`presentation-prep`)**: Assists teams in preparing persuasive presentations, demos, and technical documentation for their final showcase.
5.  **Hackathon Retrospective (`hackathon-retrospective`)**: Conducts a review of the hackathon process, summarizing lessons learned and planning for future improvements.

The orchestration assumes that a higher-level system will manage the flow of information between these workflows, potentially by passing file paths or explicit instructions based on their respective outputs.

## Usage

To initiate the full hackathon process, simply invoke this workflow.

```
workflow full-hackathon-workflow
```

## Output

The primary output of this orchestration workflow will be a summary markdown file (e.g., `full-hackathon-summary-YYYYMMDD.md`) that consolidates key information and outcomes from each stage of the hackathon. Individual reports from each sub-workflow will also be generated in the designated output folder.
