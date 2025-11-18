| [home page](https://joannachang1028.github.io/JoannaChang-dataviz-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# Outline

## 1. High-Level Summary

Artificial intelligence (AI) has rapidly transitioned from a specialized technology to a mainstream tool influencing how people work, learn, communicate, and make decisions. The number of AI tool users worldwide has grown dramatically since 2020, demonstrating widespread adoption across the general population.

At the same time, AI skills have become increasingly important for employers. In fact, two-thirds of U.S. leaders report that they would not hire someone who lacks AI literacy. This shift underscores the urgency for individuals to improve their AI skills—not only to stay competitive professionally, but also to enhance personal efficiency and problem-solving.

However, data shows a significant gap between how Americans currently use AI and how they want AI to support them. While many adults use AI for simple tasks, they express a strong desire for AI to assist with deeper functions such as complex decision-making, personal well-being, and productivity enhancement.

This final project aims to tell a clear data-driven story that answers:
- How AI became integrated into everyday life
- How people use AI today
- What people wish AI could do for them
- Ways individuals can maximize AI’s benefits
- Practical tools people should learn to improve efficiency in both work and daily life

The project will conclude by challenging readers:
“Are you truly using AI effectively—or just casually?”

## 1.2 Project Structure (Story Arc)

Section 1 — AI Is Already Everywhere
- Evidence: Rapid global growth of AI tool users from 2020–2031
- Visualization: Line chart showing millions of users worldwide (2020–2031)
- Message: AI has already become a universal tool
- Source: Statista. (July 1, 2025). Number of AI tool users worldwide from 2020 to 2031 (in millions). Retrieved November 18, 2025, from https://www.statista.com/forecasts/1449844/ai-tool-users-worldwide

Section 2 — Employers Expect AI Skills
- Evidence: 67% of U.S. leaders would not hire someone without AI skills
- Visualization: Bar chart visualizing employer expectations
- Message: AI literacy is now a professional requirement
- Citation: Fleck, A. (January 15, 2025). 2 in 3 Leaders Would Not Hire Someone Without AI Skills [Digital image]. Retrieved November 18, 2025, from https://www.statista.com/chart/33761/knowledge-workers-on-hiring-someone-with-ai-skills/

Section 3 — The AI Gap: Usage vs. Expectations
- Actual Usage: What Americans Do with AI
  - Visualization: Chart showing where U.S. adults intend to use generative AI (primarily simple tasks)
  - Citation: Activate. (October 10, 2023). Intention of generative artificial intelligence (GAI) usage by adults in the United States as of August 2023, by type [Graph]. Retrieved November 18, 2025, from https://www.statista.com/statistics/1461998/usa-generative-ai-usage-intention-by-type/
- Desired Support: What Americans Wish AI Could Do
  - Visualization: Chart showing Americans want AI to assist with productivity, decision-making, and personal well-being
  - Citation: Richter, F. (November 7, 2025). How Americans Want AI to Support Them [Digital image]. Retrieved November 18, 2025, from https://www.statista.com/chart/35426/how-americans-want-ai-to-support-them/
- Message: There is a clear disconnect between how Americans actually use AI (simple tasks) and how they wish AI would help (advanced support & decision-making). This “AI usage gap” becomes the central narrative turning point.

Section 4 — What AI Tools Should You Learn?
- To close the gap and help people (graduate student) live more efficiently and effectively, the project will recommend essential AI tools across three categories:

  1. AI as a Co-Creator
     - Master in Prompt Engineering (ChatGPT/Claude/Gemini)
       - Few shots
       - Chain of Thoughts

  2. AI for Note-taking 
     - Notion AI
     - Fathon AI

  3. AI for Job Application
     - Simplify Copilot
     - ChatGPT: prompt-engineering for customizing resume and cover letter

- Final message: A recommended, practical learning path for readers (tools + short exercises) and the call-to-action: “Are you truly using AI effectively—or just casually?”

# The data

## 2.1 Overview of the Dataset

Primary dataset:
- American Trends Panel (ATP) Wave 152 — Pew Research Center

This nationally representative dataset provides insights on how U.S. adults perceive, use, and interact with AI. It offers strong methodological reliability and high sample validity.

Methodological details:
- Field dates: Aug 12–18, 2024
- Sample size: n = 5,410
- Response rate: 91%
- Margin of error: ±1.6 percentage points
- Oversampled groups: Hispanic men, non-Hispanic Black men, non-Hispanic Asian adults
- Interviews conducted online (n = 5,195) and by phone (n = 215)
- Languages: English and Spanish
- Weighted to U.S. adult population proportions

Dataset link:
https://www.pewresearch.org/dataset/american-trends-panel-wave-152/

## 2.2 How I Plan to Use the Data

The dataset includes a rich set of questions about AI familiarity, AI usage habits, trust, helpfulness, and frequency of interaction. I will use the following questions to build key visualizations:
- How much have you heard about AI chatbots?
- Have you ever used an AI chatbot like ChatGPT, Gemini, or Copilot?
- Overall, how helpful have AI chatbots been for you?
- How often do you interact with AI?
- How much control do you feel you have over whether AI is used in your life?

These data points will be used to:
- Build current AI usage fact charts
- Support each section of the story arc
- Illustrate behavioral differences and perceptions across demographic groups
- Highlight gaps in adoption and expectations (the “AI usage gap”)

# Initial sketches

Note: These sketches will be hand-drawn or digitally drawn and uploaded as images to the GitHub repository. The descriptions below outline what each sketch will visualize.

Sketch 1 — Global AI User Growth (Line Chart)
- X-axis: Years 2020–2031
- Y-axis: Millions of AI tool users
- Rapid upward trend
- Message: “AI has entered everyone’s life”

Sketch 2 — Employer Expectations (Bar Chart)
- Bar 1: 67% “Would NOT hire without AI skills”
- Bar 2: 33% “Would hire”
- Message: “AI literacy affects your employability”

Sketch 3 — AI Usage vs. Desired Support (Dual Charts)
- Left chart: What Americans currently use AI for (simple tasks like quick answers, content generation)
- Right chart: What Americans want AI to help them with (productivity, decision-making, well-being)
- A gap highlighted visually to emphasize the turning point of the narrative

Sketch 4 — Recommended AI Tools (Grid Layout)
- A 3×3 icon-style grid representing:
  - Co-creation tools
  - Workflow automation tools
  - Decision/learning tools
- Each icon accompanied by one sentence on how to get started and one quick tip

Sketch 5 — Final Call-to-Action Panel
- Centered text:
  “Are you truly using AI effectively—or just casually?”
- A short checklist beneath with three actionable next steps:
  1. Try one co-creation prompt per day for a week
  2. Automate one small workflow
  3. Use an AI tool to support one personal decision and reflect on outcomes

# Method and Medium

For the final deliverable, I will use:
- Shorthand
  - To create an interactive, scroll-based narrative
  - To integrate text, visuals, and design elements seamlessly
- Tableau
  - To produce polished, interactive data visualizations
  - To embed charts directly into Shorthand
  - To ensure visual clarity and consistency

All datasets, cleaned data files, and final charts will be stored in this GitHub repository with proper citations. Visual assets (sketches and exports) will be committed to a designated assets/ directory.

The final website will be a fully interactive narrative that combines:
- Embedded Tableau charts
- Static PNG/SVG exports (for cross-platform compatibility)
- Short explainer text blocks and interactive call-to-action elements

## References
- Statista. (July 1, 2025). Number of AI tool users worldwide from 2020 to 2031 (in millions). Retrieved November 18, 2025, from https://www.statista.com/forecasts/1449844/ai-tool-users-worldwide
- Fleck, A. (January 15, 2025). 2 in 3 Leaders Would Not Hire Someone Without AI Skills [Digital image]. Retrieved November 18, 2025, from https://www.statista.com/chart/33761/knowledge-workers-on-hiring-someone-with-ai-skills/
- Activate. (October 10, 2023). Intention of generative artificial intelligence (GAI) usage by adults in the United States as of August 2023, by type [Graph]. Retrieved November 18, 2025, from https://www.statista.com/statistics/1461998/usa-generative-ai-usage-intention-by-type/
- Richter, F. (November 7, 2025). How Americans Want AI to Support Them [Digital image]. Retrieved November 18, 2025, from https://www.statista.com/chart/35426/how-americans-want-ai-to-support-them/
- Pew Research Center. American Trends Panel (ATP) Wave 152 dataset. https://www.pewresearch.org/dataset/american-trends-panel-wave-152/

## AI acknowledgements
I used AI to help organize and proofread the text in this document.

All substantive research decisions, data selection, analysis plans, and visualization choices were made by me. AI assistance was limited to editing and drafting text; no AI was used to generate data or perform analysis without my oversight. I have reviewed and edited all text produced with AI for accuracy and voice consistency.
