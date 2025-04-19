---
date: '2025-04-18T20:51:47+02:00'
draft: false
tags: ['AI', 'Frontend', 'Avalanche']
title: 'How I created a landing page in 30 minutes'
---

As a developer working on a new backcountry skiing app, I faced the challenge of quickly creating a landing page to introduce the product and start building a community. My app, designed to help skiers navigate the Norwegian mountains safely, isn’t ready yet, but I wanted to have something live that would allow people to sign up for a waitlist and get excited about the upcoming launch. With everything else going on, I needed to get the landing page up and running in the quickest, most efficient way possible—ideally within 30 minutes.

## Why I Needed a Landing Page

Even though the app is still in development, having a landing page seemed like an important step. Not only would it allow me to gather interest from potential users, but it also provided a way for me to collect email addresses for a waitlist. This would let me stay connected with early adopters and offer them exclusive perks once the product launches.

The core features of the app are:

- AI-based Avalanche Warning forecasts to help skiers stay safe
- Safety tips from varsom.no, which is a trusted resource for backcountry travelers
- Weather forecasts for all of Norway powered by OpenMeteo

Since the app isn’t fully built yet, I didn’t need a complex website. A simple landing page with some basic information and a signup form was all I needed to start gathering interest and building momentum.

## Getting the Job Done with ChatGPT

I knew I wanted to use Next.js for the landing page because it’s a framework I’m comfortable with and can quickly deploy. I also wanted something visually appealing, so I decided to incorporate ShadCN, a design system that works well with Next.js. I didn’t want to spend hours writing code from scratch or figuring out design details, so I decided to ask for help. That’s when I turned to ChatGPT.

I asked ChatGPT to provide me with all the instructions and code to get a basic landing page up and running as quickly as possible. The request was simple:

> <i>“I want to create a landing page for an application that will help backcountry skiers traverse the Norwegian mountains safely. The app will feature AI-based avalanche warnings, safety tips, and weather forecasts. The page should allow people to sign up for a waitlist. I’d like to use Next.js with ShadCN. Give me all the instructions and code to deploy this as quickly as possible.” </i>

ChatGPT responded with a clear, step-by-step guide on how to set everything up, including the exact code needed to create a functional landing page. This was exactly what I needed to get moving fast.

## Deploying the Landing Page

The next step was deployment. I wanted something quick, free, and easy to set up, so I chose Vercel. Vercel integrates perfectly with GitHub, making it simple to push updates whenever I need to make changes.

The process was straightforward:

 1. I created a GitHub repository for the landing page.
 2. I pushed the code to GitHub.
 3. I connected the repository to Vercel, which automatically deployed the landing page.

In just a few minutes, I had a live page at [https://boreas-landing.vercel.app] and it looked just how I wanted: simple, clean, and easy to use. The signup form was integrated with FormFree, a free service that handles email collection. Everything was working smoothly.

## The Pros and Cons of Using AI for This Task

The major advantage of using ChatGPT to build this landing page was the speed. Instead of spending hours on research and coding, I was able to get everything set up in about 30 minutes. The instructions and code snippets were practical and clear, allowing me to focus on the bigger picture of my project rather than getting bogged down in details.

That said, I also realized a potential downside. Since I wasn’t manually writing every line of code, I didn’t scrutinize everything ChatGPT suggested. This can lead to issues down the line, especially with security. For a simple landing page like mine, this wasn’t a huge concern, but it’s something I’ll need to be more mindful of in future projects—especially when dealing with more complex apps or sensitive data.

## Conclusion

Creating the landing page for my backcountry skiing app turned out to be a much quicker and easier task than I expected. Thanks to ChatGPT, I was able to get it up and running in under 30 minutes, allowing me to focus on other parts of the project while still getting some early engagement from potential users. The ability to quickly deploy a functional website using tools like Next.js and Vercel is something I’ll definitely continue using for future projects.

That being said, while the speed and convenience were great, I learned that I need to be more careful when using AI-generated code, especially when security is involved. For now, though, the landing page is doing exactly what it’s supposed to: generating interest and collecting email addresses. And that’s a win in my book.

You can check out the live landing page [here](https://boreas-landing.vercel.app).
