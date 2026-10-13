# Google Cloud: Generative AI Leader — Get Tech Certified

**Exam info:** [Google Cloud Generative AI Leader Certification](https://cloud.google.com/learn/certification/generative-ai-leader)
**Trainer:** Julien Matthieu Moreau
**Date:** 13 October 2026

---

## Overview

Started by explaining what GenAI is as a concept (essentially ML, made available by advances in technology over recent years).

- **4 primary use cases** - Create, Summarise, Discover, Automate
- **Multimodal** - text and images, text and pdf, etc
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

- **Deep Learning** (subset of ML) - A specific way of teaching computers to learn from data by using artificial neural networks. Deep Learning is the engine behind Foundational generative models.

## Making Data Accessible for AI

- Gather data
  - Pub/Sub (real time), Cloud Storage (unstructured), SQL and Spanner (structured)
- Prepare it (Big Query)
- Train your model (VertexAI)
- Deploy and predict (VertexAI - now has Agent Builder / Agent Garden layered on top as part of Google's agent platform direction, but Vertex AI still exists)
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
- Gemini - multimodal, closed source (proprietary)
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
- Zero, one and few shot prompting - essentially giving no, one or several examples to learn from
- Providing a persona or role for the agent to impersonate
- Prompt chaining - each response builds upon the previous one
  - Set a goal
  - Start the chain
  - Build the chain
  - Observe and analyse

- Reusable prompt libraries are useful

**Grounding** - giving the model a source it can go to for verification of its response. RAG is an example of this.

## Google workspace suite

Went through how AI integrates natively with Workspace - mail, docs, slides etc. Fairly obvious examples.

## Gem

Essentially a Gemini chat agent that has custom instructions for reuse. Name, Description, Instructions, Tools, Knowledge, Defaults.

## NotebookLM

Personalised AI research partner. Deep Research focus. Grounds in specific sources.

## Gemini for Google Cloud

Essentially Gemini integrated into the Google Cloud suite:
- Gemini in Cloud Assist
- Gemini in Big Query
- Gemini in Code Assist
- Gemini in Colab Enterprise
- Gemini in Databases
- Gemini in Looker
- Gemini in Security

## Components of a Generative AI Agent

- Foundational model
- Tools
- Reasoning loop

## Sampling parameters and settings

- Token count
- Temperature - creativity of the model - higher temperature, more creative but more unpredictable. Lower temp, more deterministic.
- Top K - lets the model choose randomly from the top 'k' of words in terms of possibilities (this is less common in modern models)
- Top P (nucleus sampling) - The cumulative probability threshold that defines the pool of candidate tokens sampled during text generation. A higher value increases diversity; a lower value keeps output more focused and predictable.
- Safety settings - allows you to filter out things you don't want to expose
- Output length - max length of the generated text

## ReAct

- Reason and Act - Think, Act, Observe, Respond
- Can have multiple Think Act Observe loops before a Respond happens
- Claude Code's tool-use loop (read, edit, bash, verify) is a direct implementation of this.

## Exam

- 90 minutes, 50-60 questions, multiple choice. Can mark questions to review later.
- Tip: go quick through the lot, then revisit where unsure. Sometimes the later questions trigger thoughts about the answer to priors.
- No incorrect penalty - you just don't get the point. Thus - answer all questions ;)
