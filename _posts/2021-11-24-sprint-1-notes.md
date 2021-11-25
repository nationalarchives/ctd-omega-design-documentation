---
layout: post
title: "Sprint 1 Notes (8th Nov - 19th Nov)"
---

Sprint 1 (aligned with Sprint 21 of the Project Omega overall) began on 8th November and ended on Friday 19th November when we reported with the rest of the team in the Show and Tell.

## About the project

Over the next 4 months we’ll be scoping out a replacement for the PROCAT Editorial system - the editing interface used to manage record data within The National Archive catalogue. The work will involve a broad range of user research, business process analysis, user interface prototyping, and user testing in the pursuit of a modern, efficient new interface that will leverage Project Omega’s rich new data model. You can read a bit more about the scope of what we’re doing in [this post on The National Archives blog](https://blog.nationalarchives.gov.uk/procat-evolution-designing-a-new-editorial-system/).

## Project team

- Faith Lawrence (TNA - Product Manager)
- Alex Green (TNA - Service Owner)
- Julius Welby (TNA - Data Analyst)
- Susannah Baccardax (TNA - Delivery Manager)
- Jay Spanton (Torchbox - UX / Service Lead)
- Annie Lewis (Torchbox - User Research Lead)
- Lindiwe Makgalemele (Torchbox - User Research)
- Nick Lee (Torchbox - Interaction Design Lead)
- Thibaud Colas (Torchbox - Accessibility Lead)
- Paul Vetch (Torchbox - SME, Client Partner)

## What we’ve done

- So far we’ve undertaken 6 stakeholder interviews and seven user interviews, some of which in the course of an onsite visit.
- We had a technical introduction to Project Omega’s data model with Technical Architect Adam Retter, focussing on the challenges of moving from the existing 7-tier System of Arrangement to a more flexible, not inherently hierarchical structure and the potential for leveraging the flexibility of the new graph data model
- We’ve also had the opportunity to have an initial conversation with TNA Digital Director John Sheridan about the project and its objectives.

## What we’ve learned

- The extent to which the as-is PROCAT Editorial platform presents some very real challenges for The National Archive team on a day to day basis, in part by observing archivists working in the system (and demonstrating the shadow systems they’ve had to develop as ‘coping strategies’).
- Beginning to develop a full picture of what TNA staff need to do day to day abstracted from the context of the as-is platform (i.e., business process analysis). Because project Omega is a ground-up rebuild of a new system we want to encourage users to think about a future where the technology supports, rather than constrains, the way they work.
- In advance of the UI prototyping, we’ve been assessing relevant accessibility guidelines. In addition to WCAG 2.1 AA we are considering the relevance of [ATAG 2.0](https://www.w3.org/TR/ATAG20/), since management features will impact the accessibility of TNA’s catalogue for end users. For example, if editors wanted to use table formatting to describe a record, we want to make sure those tables are accessible to screen reader users.
- An initial review of brand guidelines

[![Screenshot of a color contrast matrix from Contrast Grid, with color palette from the brand guidelines](images/nationalarchives-brand-guidelines-contrast-grid.png)](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%23FFFFFF%0D%0A%2326262A%0D%0A%23D9D9D6%0D%0A%23F9F7E2%0D%0A%23FAD3D4%0D%0A%238C9694%0D%0A%23B2A38E%0D%0A%23F9E1BC%0D%0A%23DDE5D5&es-color-form__tile-size=compact&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18)

_Above: Testing the contrast of different color combinations from the brand guidelines with [Contrast Grid](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%23FFFFFF%0D%0A%2326262A%0D%0A%23D9D9D6%0D%0A%23F9F7E2%0D%0A%23FAD3D4%0D%0A%238C9694%0D%0A%23B2A38E%0D%0A%23F9E1BC%0D%0A%23DDE5D5&es-color-form__tile-size=compact&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18)_

## What’s next

- Synthesising what we’ve learned from the interviews so far and carrying out initial analysis (we’re using Dovetail to help with this)
- We’ll be having a range of end-to-end demos of PROCAT Editorial to ensure we’re completely familiar with as-is functionality, some of which is known only to a very small number of users
- We’ll be meeting with in-house design, accessibility and front-end leads to pre-align on relevant standards and ensure we’re capitalising on any existing pattern libraries, tools, etc.
- Producing a draft mapping of user roles and functionality as an initial output from the first two sprints
