Problem Statement: Build an agent that takes a campaign brief, generates multiple ad copy variations, creates image generation prompts for each , calls image generation API, evaluates copy-image coherence, and packages best combinations with A/B testing.

Solution:

🤖 Overview
An end-to-end AI Ad Campaign Generator that automates the complete advertising creation process. From campaign brief to A/B testing recommendations, this system leverages AI to create professional-grade ad variations with intelligent quality scoring.

🎯 What It Does
Transforms product details into complete ad campaigns
Generates multiple creative variations automatically
Evaluates ad quality with coherence scoring
Provides data-driven A/B testing strategies
Supports both prototyping and production modes
🚀 Features
🎭 Dual Generation Modes
🤖 OpenAI Mode: Real AI-powered generation using GPT-3.5 Turbo

🎪 Mock Mode: Context-aware prototyping without API costs

📊 Complete Campaign Pipeline
Step	Feature	Description
1	Campaign Brief	Collects product details, audience, and goals
2	Ad Copy Generation	Creates multiple headline/body/CTA variations
3	Image Prompt Creation	Converts text ads to visual descriptions
4	Coherence Scoring	Evaluates text-image alignment (1-10 scale)
5	A/B Testing Plan	Generates segment-wise testing strategies
🛡️ Enterprise Ready
✅ Robust error handling with graceful degradation
✅ Input validation and data type safety
✅ Cost optimization with token management
✅ Extensible architecture for new AI providers
