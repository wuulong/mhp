# Idea Generation Workflow

This workflow facilitates creative idea generation for hackathon projects by leveraging the powerful problem-solving methodologies available in the CIS module. It is designed to guide users through various creative techniques to spark innovation and develop novel solutions.

## Purpose

To provide a structured approach for hackathon participants to brainstorm and generate a wide range of ideas, focusing on creative and innovative solutions.

## How it Works

This workflow acts as a specialized wrapper around the `cis/problem-solving` workflow. When invoked, it implicitly guides the underlying system to prioritize and present problem-solving methods from the 'creative' category (e.g., Assumption Busting, Random Word Association, Six Thinking Hats) as defined in `cis/workflows/problem-solving/solving-methods.csv`.

## Usage

To initiate an idea generation session, simply invoke this workflow. The system will then guide you through a series of prompts and techniques to help you brainstorm and refine your ideas.

```
workflow idea-generation
```

## Output

The output of this workflow will be a markdown file (e.g., `hackathon-ideas-YYYYMMDD.md`) containing a summary of the brainstorming session and a list of generated ideas.
