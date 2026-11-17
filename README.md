# problem-to-place
An AI agent skill for translating user-provided business problems into relevant geospatial solution use cases

# Overview
Problem to Place is an AI SKILL.md that provides an AI agent with instructions for identifying geospatial use cases embedded in a business issue. You describe a situation, drop in a link or upload a document, and it translates everyday business questions into a set of relevant "where" questions followed by a set of conceptual solution use cases.

# What It Does
The skill analyzes the business issue you provide and develops a short list of plain-English "where" questions.
Recommends the data, tools, and methods to answer each one.
Proposes conceptual solution use cases to consider implementing.
Suggests one clear next step to get started.

# The Framework
Every problem is viewed through four modes of analysis and six types of geographic contexts (the geographic lens matrix):
For more information, review this article about the geospatial lens matrix: https://www.linkedin.com/pulse/geospatial-solution-canvas-simple-tool-translating-business-lewin

Four modes of analysis:

Describe — what is it now?
Diagnose — why is it that way?
Predict — what's coming?
Prescribe — what should we do?

Six geographic contexts:

Location — where are things?
Scale — how big or what shape are they?
Route — how do things move between places?
Distribution — are things spread out or clumped together?
Proximity — what's near what?
Correlation — do conditions in one place relate to conditions somewhere else?

Each question you get back carries a compact tag (for example, Distribution + Describe) so you learn the framework over time without it taking over the response.

# How To Use It
Describe a business problem, paste a link, or upload a document.
Add context if you have it: your goal, the regions involved, what data you already hold, the type of use cases you want to focus on (e.g. AI agents)
Receive a structured response with the geography in your problem, key "where" questions, conceptual solution use cases and a first step.
Ask for more depth on any question or solution. Responses stay short by default.

# What You Get Back
Responses are structured as follows:
Overview — one short paragraph on where place matters in your problem (or an honest note if it doesn't)
Key Geospatial Questions — three to six plain-English "where" questions, each with a framework tag and a concrete way to answer it
Solution Use Cases (Conceptual) — three to six specific conceptual use cases, including at least one agent-mediated option when it genuinely adds value
Next Step — one concrete first move, not the whole project

# Solution Patterns
Beyond classic GIS solution patterns (maps, dashboards etc.), the lens will consider agent-mediated solutions. These include:

Conversational spatial agents that run analysis on demand from natural-language questions.
Background monitoring agents that watch spatial data and alert the right people with context.
Embedded spatial reasoning inside tools you already use.
Hybrid solutions where a dashboard serves power users and an agent serves everyone else.

# Modifications
To focus the agent on a specific type of result, just ask for it. For example, if you want the agent to focus on providing agentic AI use cases ask it to focus on AI agent use cases only.

# Good To Know
It works best when you share your goal and any constraints up front.
Responses are short by design. Ask for depth whenever you want it.
For a large or many-themed document, it will ask whether you want one overall analysis or a theme-by-theme breakdown.

# Installation
Download the problem-to-place.zip file. Contained in the zip file is a SKILL.md describing the agent instructions, an asset folder with the geosaptial lens matrix (Excel file), and a resources folder containing the .md version of the geospatial lens matrix which the SKILL.md instructions refer to.
Load the .zip file into your AI agent platform as a skill and use. 
Enjoy!

# Important Note on AI-Generated Content
This software is licensed under the MIT License, users must note that the core functionality relies on artificial intelligence. 
- **No Guarantee of Originality:** AI-generated use cases may accidentally mimic existing patented ideas, trademarks, or copyrighted strategies. 
- **No Guarantee of Feasibility:** The AI may suggest concepts that are technically impossible, economically unviable, or unsafe to build.
- Always perform independent legal, technical, and market due diligence before acting on any generated concept.

# Security Notice 
This skill processes external user-provided links and documents. To protect against indirect prompt injection, ensure your AI agent is running in a sandboxed environment with strict tool and network restrictions.
