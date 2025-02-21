<img src="images/Noble-Logo.png" width="250">

## Table of contents

- [Overview](#overview)
- [Problem](#problem)
- [Deployment](#deployment)
- [User Guide](#user-guide)
- [Development](#development)
- [Team](#team)
- [Community Feedback](#community-feedback)

## Overview

Noble is a web app designed to support the medical readiness of Hawaii Air National Guard (HIANG)service members by providing reliable, anonymous, and accessible health information. Noble includes three main features:

- **Frequently Asked Questions (FAQ):** A searchable and sortable database of straightforward answers to common medical questions.

- **Question Compass:** An AI chatbot trained on Air Force Medical Standards and procedures to provide personalized guidance.

- **Ask A Doc:** An anonymous platform for users to submit medical questions when they cannot find answers elsewhere.

## Problem

Medical readiness is essential for maintaining membership in the Hawaii Air National Guard (HIANG), with requirements varying by career field. For instance, flight crew members facestricter medical standards than those in administrative roles. The 154th Medical Group (154 MDG) oversees medical readiness for 2,300 HIANG members, following complex procedures and guidelines. However, concerns about the potential career impacts of disclosing medical issues discourage members from seeking help, even anonymously.

<img src="images/ask-a-doc-box.png" width="250">

Despite implementing an anonymous “Ask a Doc” dropbox for questions, no queries have been submitted in three months, highlighting a lack of trust in the process. Members fear that revealing medical conditions could lead to restrictions or separation from service.

## Deployment

View our V1 website application here: [noble.wiki](https://noble.wiki/)

### V1 Tech Stack

- [Meteor](https://www.meteor.com/)
- [React](https://react.dev/)
- [React Bootstrap](https://react-bootstrap.github.io/)
- [MongoDB](https://www.mongodb.com/)
- [OpenAI](https://openai.com/)
- [TestCafe](https://testcafe.io/)

### V2 Tech Stack

- [Next.js](https://nextjs.org/)
- [tailwindcss](https://v3.tailwindcss.com/)
- [shadcn/ui](https://ui.shadcn.com/)
- [MongoDB](https://www.mongodb.com/)
- [OpenAI](https://openai.com/)

## Activity Badges

**Noble V1:**
[![Noble](https://github.com/AskADock/noble/actions/workflows/ci.yml/badge.svg)](https://github.com/AskADock/noble/actions/workflows/ci.yml)

**Noble V2:**
[![Noble](https://github.com/AskADock/noble-v1-nextjs/actions/workflows/ci.yml/badge.svg)](https://github.com/AskADock/noble-v1-nextjs/actions/workflows/ci.yml)

## User Guide

This section provides a walkthrough of the Noble user interface and its capabilities.

### Landing Page:

The landing page is presented to users when they first visit the site. It provides a brief overview and purpose of the app.

<img src="images/landing.png" width="500">

### Frequently Asked Questions (FAQ):

A searchable and sortable database of straightforward answers to common medical questions. Users can filter based on categories and search by keywords.

<img src="images/FAQ.png" width="500">

### Question Compass:

Meet Noble AI, our chatbot trained on Air Force Medical Standatds and procedutes. It can provide personalized guidance based on the question asked. Noble AI is trained to not answer questions that are not related to its data.

<img src="images/question-compass.png" width="500">

### Ask A Doc:

Couldn't find an answer? Ask A Doc! Use our anonymous platform to submit medical questions. To maintain privacy and security, a passcode system is employed to ensure only service members have access.

<img src="images/ask-a-doc.png" width="500">

## Development

The following describes the development process of our app:

## Milestone 1

Milestone 1 is the reintroduction into the

### Week 1

The team met with the sponsor to discuss the progress of Noble and to gather feedback on the current implementation. During the meeting, the sponsor provided valuable insights into it's currently procedures and plans to further integrate Noble into their workflows.

As of now, Noble was introduced to the 154th Medical Group internally with optimism. It however requires further approval from higher leadership and a workflow plan for answering submitted questions.

The team and the sponsor agreed on several new features and improvements to enhance the user experience and address any existing issues. This collaboration ensures that Noble continues to meet the needs of the Hawaii Air National Guard service members effectively.

### Week 2

Development has officially begun, with the tech stack finalized. After learning about the numerous hurdles of Noble V1, V2 aims to modernize its technologies using Next.js, Tailwind CSS, Shadcn/ui, and MongoDB. This week’s focus will be on transitioning the current V1 Noble public pages to the new tech stack.

During our weekly sponsor meeting, a university student from Colorado State University has reached out and shown interest in joining our team. We will interview them and decide if they can join the team.

## Team

Noble (v.2) is designed and implemented by Rina Ogino, Thomas Rivera, and Tara Walsdorf.

Noble (v.1) is designed and implemented by Lauren Clayton, Rina Ogino, Thomas Rivera, Ryne Stagen, and Brandon Underwood.

## Community Feedback

We are interested in your experience using Noble! Please take a couple of minutes to fill
out the [Noble Feedback Form](https://noble.wiki/feedback).
