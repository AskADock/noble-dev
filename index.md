<img src="images/Noble-Logo.png" width="250">

## Table of contents

- [Overview](#overview)
- [Problem](#problem)
- [Deployment](#deployment)
- [User Guide](#user-guide)
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

### Tech Stack

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

## Team

Noble (v.2) is designed and implemented by Rina Ogino, Thomas Rivera, and Tara Walsdorf.

Noble (v.1) is designed and implemented by Lauren Clayton, Rina Ogino, Thomas Rivera, Ryne Stagen, and Brandon Underwood.

## Community Feedback

We are interested in your experience using Noble! Please take a couple of minutes to fill
out the [Noble Feedback Form](https://noble.wiki/feedback).
