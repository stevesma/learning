# Google Cloud: Generative AI Leader — Get Tech Certified

**Exam info:** [Google Cloud Generative AI Leader Certification](https://cloud.google.com/learn/certification/generative-ai-leader)

---

## Overview

Started by explaining what GenAI is as a concept (essentially ML, made available by advances in technology over recent years).

**4 primary use cases** - Create, Summarise, Discover, Automate

**Multimodal** - text and images, text and pdf, etc

- **Traditional models** - trained for specific use cases
- **Foundational models** - trained on massive amounts of varied data. Adapt to a wide range of downstream tasks.

## Google Foundational Models

- Gemini - Foundational
- Imagen - Images
- Chirp - Audio

## AI Strategy Considerations

- Strategic Focus
- Exploration
- Responsible AI
- Resourcing
- Impact
- Continuous Improvement

## AI / ML / GenAI Layers

- **AI** - Building or creating machines to do tasks that normally require human intelligence
- **ML** - A subset of AI where machines learn from data to perform specific tasks. Different data creates different models
- **GenAI** - A subset of ML that focuses on creating new content

## Data Quality

**Aspects of data quality:**
- Accuracy
- Completeness
- Representative
- Consistency
- Relevance

**Data Accessibility:**
- Availability
- Cost
- Format

## ML Approaches

- **Supervised** (labelled data - assigns meaning to the data e.g. this is a picture of a cat)
- **Unsupervised** (unlabelled data - the data contains no inherent 'correct' answer)
- **Reinforcement Learning** - model learns through interaction and feedback

**Deep Learning** (subset of ML) - A specific way of teaching computers to learn from data by using artificial neural networks. Deep Learning is the engine behind Foundational generative models.

## Making Data Accessible for AI

- Gather data
  - Pub/Sub (real time), Cloud Storage (unstructured), SQL and Spanner (structured)
- Prepare it (Big Query)
- Train your model (VertexAI)
- Deploy and predict (VertexAI now called Agent Platform)
- Manage your model (Versioning, performance, drift etc)

## Foundation Models

**Types of foundation models:**
- Large Language Models - focus on human language
- Diffusion Models - images and audio/video

**Factors when choosing a model:**
- Modality
- Context Window
- Security
- Availability and resilience
- Cost
- Performance
- Fine-tuning and customisation
- Ease of Integration

**Google Models:**
- Gemini - multimodal, closed code model
- Gemma - local deployments, open source and customisable
- Imagen - high quality images from text descriptions
- Veo - video content based on text descriptions

**Foundation model limitations:**
- Data dependency
- Knowledge cut-off
- Bias
- Fairness
- Hallucinations
- Edge cases

**Techniques to overcome limitations:**
- Prompt engineering
- Grounding (use company data, the internet etc to ground their answer in reality)
- Retrieval-Augmented Generation (RAG)
- Fine-tuning
- Humans in the loop (HITL)

## GenAI Building Blocks

- GenAI applications
- Agents
- Platforms
- Models
- Infrastructure

GenAI Agent is an application that observes the world and takes actions based on what it sees based on tools it has at its disposal.

**Capabilities of AI Agents:**
- Understand and respond to natural language
- Automate complex tasks
- Personalisation

**Conversational vs Workflow Agents**

Agent Platform essentially streamlines the entire ML workflow:
- Infrastructure, models, build/deploy/manage
- Go between Agent Garden and Model training

## Key AI Infrastructure

- High Performance compute - GPUs and TPUs, Hypercomputers
- High Performance storage - Large scale storage. Fast Access
- Networking

## Prompting

**Prompting techniques:**
- zero, one and few shot prompting - essentially giving no, one or several examples to learn from
- providing a persona or role for the agent to impersonate
- prompt chaining - each response builds upon the previous one
  - Set a goal
  - Start the chain
  - Build the chain
  - Observe and analyse

Reusable prompt libraries are useful

**Grounding** - giving the model a source it can go to for verification of its response. RAG is an example of this.
