# Building a Fitness App with GitHub Copilot agent mode for Mergington High School

## OctoFit Tracker application story for Mergington High School

Paul Octo has been a passport office document verification case workder for over 8 years. Despite his enthusiasm and creative approach to document validation , he's been increasingly concerned about farudulant documents and incorrect details by applicants while filling up the application.  

Paul  inspired to create a solution to overcome the problem. He wanted something that would:

1. Make document validation reliable and easy. 
2. Allow him to validate the application details occuracy against data available in documents.
3. Provide confidence score by comparing the data from documents and application. 

## The Birth of AI OCR Anomoly Detector

Paul initially sketched his idea on a notepad during lunch breaks. He envisioned an app where case workder could upload case documents, earn case will be assigned unique case id,as a case workder with only basic coding knowledge, the technical aspects seemed daunting.
That's when he approached Jessica Cat, the head of Mergington High's IT department. Jessica recommended basing the passport case validation application, which was documented in `docs/mona-high-school-fitness-tracker.md`. She saw potential in adapting the Monafit Tracker's structure and features to meet Mergington High School's needs.

### Technical Planning Phase

Before starting development, Paul and Jessica carefully reviewed the Monafit Tracker's repository and documentation. This provided a solid foundation for OctoFit Tracker, ensuring compliance with technical standards and leveraging proven design patterns.
Together, Paul and the IT team identified key requirements for OctoFit Tracker:

### User Experience Goals

- Simple, intuitive interface designed specifically for teenagers
- Quick activity logging to minimize friction
- Social features that respect student privacy
- Gamification elements to maintain engagement

### Technical Specifications

- Mobile-responsive web application (accessible on school Chromebooks and personal devices)
- Secure authentication based on Monafit Tracker's implementation
- Activity verification system to prevent cheating

## Current Development Status

Paul and Jessica have set up a GitHub Codespace environment and are making remarkable progress with GitHub Copilot agent mode. By adapting the Monafit Tracker's structure, the OctoFit Tracker prototype already includes:

- A functional user registration system
- Basic activity logging for running, walking, and strength training
- The beginning framework for team competitions
- A simple dashboard showing student progress

## Next Steps for Paul

With the basic infrastructure in place, Paul is now focused on:

1. Developing an engaging point system that fairly compares different types of activities
2. Creating motivational challenges that appeal to different student interests
3. Building a notification system that encourages consistency without being intrusive
4. Designing reports that help him identify students who might need additional support or motivation

The IT department has been impressed with how GitHub Copilot agent mode has accelerated development, allowing Paul to focus on the educational aspects while the AI handles much of the technical implementation. Jessica Cat has been particularly pleased with how OctoFit Tracker leverages the Monafit Tracker's foundation to meet Mergington High School's unique requirements.

### Workshop Overview

In this workshop, you'll:

1. Set up a development environment using **GitHub Codespaces**
2. Use **GitHub Copilot** to accelerate development across multiple technologies
3. Build key components of the **OctoFit Tracker** app with the help of Copilot agent mode
4. Learn best practices and prompting techniques for working with **GitHub Copilot agent mode**

### Application Features

**OctoFit Tracker** will include:

- User profiles
- Activity logging and tracking
- Team creation and management
- A competitive leaderboard
- Personalized workout suggestions

### GitHub Copilot Chat

These are the current models supported for GitHub Copilot Chat.

- Claude Sonnet 3.5 (Preview)
- Claude Sonnet 3.7 (Preview)
- Claude Sonnet 3.7 Thinking (Preview)
- Gemini 2.0 Flash (Preview)
- GPT-4o
- o1 (Preview)
- o3-mini (Preview)

#### [LLM models explained](https://docs.github.com/en/copilot/using-github-copilot/ai-models/changing-the-ai-model-for-copilot-chat#ai-models-for-copilot-chat-1)

![GitHub Copilot Chat models](https://github.com/user-attachments/assets/f2f8d0bd-366b-4ecf-b88d-d092ae7b8b10)

#### Prompt engineering

- [GitHub documentation prompt engineering](https://docs.github.com/en/copilot/using-github-copilot/prompt-engineering-for-github-copilot)
- [How to use GitHub Copilot: Prompts, tips, and use cases](https://github.blog/2023-06-20-how-to-write-better-prompts-for-github-copilot/)
- [Using GitHub Copilot in your IDE: Tips, tricks, and best practices](https://github.blog/2024-03-25-how-to-use-github-copilot-in-your-ide-tips-tricks-and-best-practices/)
- [A developer's guide to prompt engineering and LLMs](https://docs.github.com/en/copilot/using-github-copilot/prompt-engineering-for-github-copilot#:~:text=A%20developer%E2%80%99s%20guide%20to%20prompt%20engineering%20and%20LLMs)
- [GitHub Copilot: The Agent Awakens](https://github.blog/news-insights/product-news/github-copilot-the-agent-awakens/#agent-mode-available-in-preview-%f0%9f%a4%96)

### OctoFit tracker fitness application technology stack

We'll be using a modern web application stack:

- **Frontend**: React.js
- **Backend**: Python with Django REST Framework
- **Database**: MongoDB
- **Development Environment**: GitHub Codespaces

### Workshop Structure

1. **Introduction**
   - Overview of OctoFit Tracker app concept
   - GitHub Copilot Chat models

2. **Setup of Prerequisites**
   - Setting up GitHub Codespaces
   - Ensure GitHub Copilot and Copilot Chat extensions are up to date

3. **Rapid Prototyping with GitHub Copilot agent mode**
   - Creating project structure
   - Generating boilerplate code
   - Implementing basic models, serializers, URLs, and views

4. **Building Core Features**
   - Activity logging API
   - Team management
   - Leaderboard functionality

5. **Frontend and Backend Development**
   - Setting up React components
   - Implementing responsive UI
   - Connecting to backend APIs
   - Python Django business logic
   - MongoDB data layer
