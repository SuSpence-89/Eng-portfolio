---
layout: post
title: "AI-Assisted Portfolio Website & Digital Autobiography"
description: "A personal engineering portfolio and evolving autobiography developed through AI-assisted coding, requirements planning, hands-on testing, and iterative improvements."
skills:
  - Project Planning
  - Requirements Definition
  - UX Design
  - GitHub Pages & Jekyll
  - AI-Assisted Development
  - Testing & Troubleshooting
main-image: /website-cover.jpg
---

**Personal Project | Ongoing | AI-assisted website development**

## Project Overview

I wanted a place to present my engineering projects, technical background, and professional experience in a way that a conventional résumé couldn't.

As the website developed, I also saw an opportunity to create something more personal: a digital autobiography that I can continue expanding with stories, photographs, and life experiences.

The result is an evolving website hosted through GitHub Pages, using Jekyll, Markdown, HTML, CSS, and JavaScript.

**[Explore the website]({{ '/' | relative_url }})** | **[Read my autobiography]({{ '/about/' | relative_url }})** | **[View the source repository](https://github.com/SuSpence-89/Eng-portfolio)**

## My Role and the Use of AI

This was a collaborative development project involving extensive assistance from ChatGPT.

**AI generated much of the HTML, CSS, JavaScript, and Jekyll code. I do not present that code as something I wrote independently.**

My contributions included:

- Defining the purpose, requirements, priorities, and visual direction of the website.
- Selecting features, deciding how visitors should interact with them, and providing feedback on each iteration.
- Managing the GitHub repository, organizing site content and photographs, and publishing updates.
- Testing deployed pages on desktop and mobile, identifying problems, and working through corrections.
- Writing and refining personal content, including project descriptions and an autobiography.
- Making the final decisions on what to publish, how the site should function, and how it should represent my work.

I see AI as a development tool: useful for implementing ideas quickly, but still requiring clear requirements, review, testing, and judgment.

## Features Developed

### Professional Portfolio

The homepage introduces my experience and links visitors to project pages, technical skills, a résumé, and contact information.

### Interactive Engineering Project Globe

A rotating, draggable visual showcase helps visitors explore projects directly from the homepage.

### Rotating Professional Portraits

The homepage presents a selection of professional photographs, with the active photo maintained during a browsing session.

### Digital Autobiography

My About Me area uses expandable chapter cards, personal storytelling, featured photographs, and optional image galleries.

A separate education chapter provides a longer account of my journey through school, military training, and post-secondary education.

### Navigation and Accessibility

The site includes responsive layouts, reusable Jekyll components, motion-aware styling, and a floating Back-to-Top control.

The mobile navigation and button sizes have been refined through testing.

## Problems Encountered and Lessons Learned

A working website is more than an attractive mock-up.

Several issues required investigation and correction.

### Jekyll Page Not Found — 404 Error

I discovered that an extra space before Jekyll's opening YAML front matter prevented my education page from publishing at its intended address.

Correcting the front matter restored the page.

### Duplicated Homepage Content

A second block of homepage markup had accidentally been appended to `index.html`.

Inspecting the file and removing the duplicate restored the intended layout.

### Component Integration

Reusable photo galleries and a Back-to-Top control needed to be added to the correct Jekyll includes and shared page layout.

This helped me better understand how reusable website components work.

### Visual and Mobile Improvements

I reviewed photographs, hover effects, chapter dropdowns, and mobile controls, requesting refinements based on how the deployed website actually looked and behaved.

These experiences helped me become more comfortable with repository structure, Jekyll templates, change management, troubleshooting, and iterative testing.

## Technology and Development Approach

| Area | Tools and Methods |
|---|---|
| Hosting and deployment | GitHub Pages and GitHub repository workflow |
| Site generation | Jekyll, Liquid templates, Markdown |
| Interface | HTML, CSS, and JavaScript (substantially AI-generated) |
| Asset management | Organized photographs and reusable galleries |
| Development process | Requirements, AI-assisted implementation, manual testing, and iterative refinement |

## Future Development

I plan to keep improving the site as I learn.

Potential additions include:

- Reading progress indicators and chapter navigation.
- Interactive engineering skills explanations.
- Expanded project documentation.
- Additional autobiography chapters and photographs.
- Continued learning in programming and website development.

This website is both a practical portfolio and a long-term personal project.

**The goal isn't to claim that I independently coded an entire website. It's to demonstrate that I can define a useful project, direct the development process, test the result, solve problems, and keep improving a working product.**
