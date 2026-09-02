Tech English OS

Personal Project · MVP

Tech English OS is a client-side web application created from a real career need: preparing for technology interviews in English with content connected to Systems Analysis, observability, troubleshooting, software development, documentation and technical communication.

Live demo

https://flaviaprogs.github.io/tech-english-os/

Why I built it

Generic English study tools did not fully match the vocabulary and situations I wanted to practice for my professional context. I created this MVP to combine language learning with scenarios that appear in technology roles and interviews.

The project is also a practical software-development exercise: I use the product while studying, identify friction points, iterate on the experience and evolve the implementation.

Main features

Guided onboarding and English level assessment

Daily study flow with progression rules

Technical vocabulary and expressions

Flashcards and quizzes

Grammar and reading practice

Listening exercises using browser speech synthesis

Speaking practice using the Web Speech API when supported

HR interview simulator

Systems Analyst technical interview practice

Career-story practice for explaining projects and troubleshooting

Technical documentation exercises

Mistake review and progress tracking

Import/export of local progress

Responsive interface for desktop and mobile

Current architecture

The current MVP is intentionally lightweight and runs entirely in the browser.

HTML

CSS

Vanilla JavaScript

Web Speech API

localStorage for local persistence

GitHub Pages for static deployment

No backend or authentication is required in this version. User progress stays in the browser unless the user exports it manually.

Technical approach

The application uses a state object persisted in localStorage to manage study progress, completed exercises, interview practice, skills and mistakes. Speech synthesis is used for English listening exercises, and supported browsers can use speech recognition for speaking practice.

Some interview scores are local heuristic estimates based on content coverage and answer structure. They are learning signals, not language certification or a replacement for human evaluation.

Project focus

The content is intentionally connected to technology scenarios such as:

Systems Analysis

React and Node.js

APIs

Incident response

Troubleshooting

Networks

Monitoring and observability

Logs, metrics and traces

Technical documentation

Communication with recruiters and engineering teams

Roadmap

Split the single-file MVP into a modular frontend architecture

Add persistent backend storage and authentication

Improve accessibility and automated testing

Add richer interview feedback

Expand personalized study paths

Improve cross-browser speech support

Create dedicated public demo and personal-study modes

Status

This is a personal MVP under active development and experimentation.
