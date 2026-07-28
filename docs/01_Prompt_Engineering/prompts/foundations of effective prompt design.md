**1. Naive Prompt**
Example: Write a test plan.

Problem:
No context
No audience
No format
No quality expectations

**2. Engineered Prompt**

Example for AIQEP

You are a Senior Software Quality Engineer.

Create a software test plan for an automotive ECU firmware project.

Context:
The software follows ASPICE SWE.4 and ISO 26262.

Include:
• Scope
• Test Objectives
• Test Strategy
• Entry Criteria
• Exit Criteria
• Risks
• Deliverables

Present the output in Markdown.

Notice how the prompt specifies role, context, instructions, and output format.

**3. Four Building Blocks**
This is one of the most important concepts in the course.
| Building Block       | Purpose                | AIQEP Example                                   |
| -------------------- | ---------------------- | ----------------------------------------------- |
| **Instruction**      | What the AI should do  | Create a CAPA report                            |
| **Context**          | Background information | Automotive software project following ISO 26262 |
| **Input Data**       | Information to analyse | Audit findings, defect list, FMEA               |
| **Output Indicator** | Expected format        | Markdown table with priority and owner          |

**4. Iterative Refinement**
Instead of accepting the first answer:

Version 1

Create a CAPA.

↓

Version 2

You are an ISO 9001 Lead Auditor.

Create a CAPA using the supplied audit findings.

Classify actions as:

Immediate

Corrective

Preventive

Return the output as a Markdown table.

↓

Version 3

Add risk rating.

Assign owner.

Suggest verification method.

Include due date.

This refinement process improves both quality and usability.
