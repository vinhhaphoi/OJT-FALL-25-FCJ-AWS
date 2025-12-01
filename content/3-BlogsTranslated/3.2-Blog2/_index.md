---
title: "Blog 2"
date: "2025-12-01"
weight: 1
chapter: false
pre: " <b> 3.2. </b> "
---

# Amazon Nova Lite enables Bito to offer a free tier option for its AI-powered code reviews

### Choosing a cost-effective model for a free tier offering

To offer a free tier option for AI Code Review Agent, Bito needed a foundation model (FM) that would provide the right level of performance and results at a reasonable cost. Offering code review for free to its potential customers would not be free for Bito, of course, because it would be paying inference costs. To identify a model for its Free Plan, Bito carried out a 2-week evaluation process across a broad range of models, including the high-performing FMs on [Amazon Bedrock](https://aws.amazon.com/bedrock/), as well as OpenAI GPT-4o mini. The Amazon Nova models—fast, cost-effective models that were recently introduced on Amazon Bedrock—were particularly interesting to the team.

At the end of its evaluation, Bito determined that Amazon Nova Lite delivered the right mix of performance and cost-effectiveness for its use cases. Its speed provided fast creation of code review summaries. However, cost—a key consideration for Bito’s Free Plan—proved to be the deciding factor. Ultimately, Amazon Nova Lite met Bito’s criteria for speed, cost, and quality. The combination of Amazon Nova Lite and Amazon Bedrock also make it possible for Bito to offer the reliability and security that their customers needed when entrusting Bito with their code. After all, careful control of code is one of Bito’s core promises to its customers. It doesn’t store code or use it for model training. And its products are SOC 2 Type 2-certified to provide data security, processing integrity, privacy, and confidentiality.

### Implementing the right models for different tiers of offerings

Bito has now adopted Amazon Bedrock as its standardized platform to explore, add, and run models. Bito uses Amazon Nova Lite as the primary model for its Free Plan, and Anthropic’s Claude 3.7 Sonnet powers its for-pay Teams Plan, all accessed and integrated through the unified Amazon Bedrock API and controls. Amazon Bedrock provides seamless shifting from Amazon Nova Lite to Anthropic’s Sonnet when customers upgrade, with minimal code changes. Bito leaders are quick to point out that Amazon Nova Lite doesn’t just power its Free Plan—it inspired it. Without the very low cost of Amazon Nova Lite, they wouldn’t have been able to offer a free tier of AI Code Review Agent, which they viewed as a strategic move that would enable it to expand its enterprise customer base. This strategy quickly generated results, attracting three times more prospective customers to its Free Plan than anticipated. At the end of the 14-day trial period, a significant number of users convert to the full AI Code Review Agent to access its full array of capabilities.

Encouraged by the success with AI Code Review Agent, Bito is now using Amazon Nova Lite to power the chat capabilities of its offering for [Bito Wingman](https://bito.ai/product/wingman/), its latest AI agentic technology—a full-featured developer assistant in the integrated development environment (IDE) that combines code generation, error handling, architectural advice, and more. Again, the combination of quality and low cost of Amazon Nova Lite made it the right choice for Bito.

### Conclusion

In this post, we shared how Bito—an innovative startup that offers a growing portfolio of AI-powered developer agents—chose Amazon Nova Lite to power its free tier offering of AI Code Review Agent, its flagship product. Its AI-powered agents are designed specifically to make developers’ lives easier and their work more impactful:

- **Amazon Nova Lite enabled Bito to meet one of its core business challenges**—attracting enterprise customers. By introducing a free tier, Bito attracted three times more prospective new customers to its generative AI-driven flagship product—AI Code Review Agent.
- **Amazon Nova Lite outperformed other models during rigorous internal testing**, providing the right level of performance at the very low cost Bito needed to launch a free tier of AI Code Review Agent.
- **Amazon Bedrock empowers Bito to seamlessly switch between models as needed** for each tier of AI Code Review Agent—Amazon Nova Lite for its Free Plan and Anthropic’s Claude 3.7 Sonnet for its for-pay Teams Plan. Amazon Bedrock also provided security and privacy, critical considerations for Bito customers.
- **Bito shows how innovative organizations can use the combination of quality, cost-effectiveness, and speed** in Amazon Nova Lite to deliver value to their customers—and to their business.

“Our challenge is to push the capabilities of AI to deliver new value to developers, but at a reasonable cost,” shares Amar Goel, co-founder and CEO of Bito. “Amazon Nova Lite gives us the very fast, low-cost model we needed to power the free offering of our AI Code Review Agent—and attract new customers.”

Get started with Amazon Nova on the [Amazon Bedrock console](https://console.aws.amazon.com/bedrock/). Learn more Amazon Nova Lite at the [Amazon Nova product page](https://aws.amazon.com/nova/).

### About the authors

**Eshan Bhatnagar** is the Director of Product Management for Amazon AGI at Amazon Web Services.

**Amar Goel** is Co-Founder and CEO of Bito. A serial entrepreneur, Amar previously founded PubMatic (went public in 2020), and formerly worked at Microsoft, McKinsey, and was a software engineer at Netscape, the original browser company. Amar attended Harvard University. He is excited about using GenAI to power the next generation of how software gets built!
