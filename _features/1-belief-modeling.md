---
id: about
name: 1. Belief Modeling
heading: 1. Belief
subheading: Modeling.
image: /assets/images/blt_logo.png
alt: "A minimalist and sleek design of a classic hamburger. The logo features a perfectly rounded bun with a glossy top, containing layers of lettuce, a juicy patty, a slice of tomato, bacon, and melted cheese. The colors are soft and pastel-like, giving the logo a modern and clean appearance. The simple yet elegant design focuses on the burger’s shape and proportions, making it instantly recognizable and appealing."
---

Contemporary chatbots largely fail at choosing the appropriate level of confidence when conveying uncertain information. Although there are mathematical ways to address that (e.g., [belief functions](https://www.hds.utc.fr/~tdenoeux/dokuwiki/en/bf)), their comparative utility is yet to be explored.

A new generation of chatbots based on reasoning, or “thinking,” models feature test-time compute scaling. This means that before giving a response, the model produces intermediary output (“reasoning tokens”), [expected to increase](https://doi.org/10.48550/arXiv.2410.13639) the model performance in proportion to the compute resources spent. This has not been the case with the previous generation such as ChatGPT-4o. Test-time compute scaling has a potential to improve Belief Modeling, although convincing evidence is lacking. OpenAI o1, Gemini Thinking, DeepSeek-R1, and Sky-T1, among others, are examples of reasoning models.
