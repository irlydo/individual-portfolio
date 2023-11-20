# Individual Portfolio

## Contents

- [What is a Developer Portfolio?](#what-is-a-Developer-Portfolio?)
- [Why am I building one now?](#why-am-I-building-one-now?)
- [How do I make one?](#how-do-I-make-one?)
- [How do I deploy my site to the internet?](#how-do-I-deploy-my-site-to-the-internet?)
- [Where can I find examples or inspiration?](#where-can-I-find-examples-or-inspiration?)

## What is a Developer Portfolio?

A Developer Portfolio is a website that showcases your skills, experience and work to prospective employers. It
is similar in ways to a portfolio that an artist or photographer might create - they collate some example projects to
show what sort of work they do. It's also a bit like a CV, as there will be aspects of talking about yourself and
your background; but instead of just talking about your work, you can show what you've built!

## Why am I building one now?

- You will need a portfolio to find/get a job as it will help you to stand out.
- It is easier to build one now since the frontend course material will still be fresh on your minds.
- It is great practice for the skills you have been learning.
- This will also prepare you for when you gain access to Boolean's Career Services, as they can help you to refine
  the portfolio.

## How do I make one?

The best way is to build one yourself! This way, even the portfolio site itself is a demonstration of your skills
and experience.

First, plan your portfolio! Do some research on designs, think about what content you want to include, structure the
very high-level layout of the site, etc.

Next, build it! What you use to build it is up to you, and it will generally be one of:

- A static website using just HTML, CSS and JS;
- A React Single Page App (SPA) - i.e. it has no routing;
- A React app with routing.

> At this stage, it is NOT advised to build something with a new language or framework. Save this for the projects
> that you want to showcase in the portfolio!

In terms of the content to include, at a very high level, you will want to include:

- **Biography/Self-Intro** - a paragraph or two about you.
- **Tech Stack** - the languages/technologies that you have experience with.
- **Education / Experience** - only those that are relevant to coding / the line of work you want to go into.
- **Projects** - sites/apps that you have built.
  - Include a short description of what it does; the tech you used; and a link to the GitHub repo.
  - EITHER include a link to the deployed online version OR add screenshots, short clips, GIFs, etc.
  - Avoid including exercises from the course or apps built from tutorials.
  - Challenges from the course could be included as these involved less guidance but having something unique would
    still be better to help you stand out from the crowd.
  - You will also have time to build and add more later!

For more ideas/detail, read through the relevant sections of
[this e-book](https://www.joshwcomeau.com/effective-portfolio/download-book/).

## How do I deploy my site to the internet?

There are various approaches, and it depends on what sort of site/application you have built.

- **Static Website** - The simplest solution is to host it on [GitHub Pages](https://pages.github.com/). This is
  nice and simple, and will allow you to link your GitHub repos to GitHub pages,
  which will then host the site/project for you.
- **React Single Page App (SPA)** - If you have a React app with no routing, then there are two options: You can either:
  1. Use GitHub Pages as above, but you will also need to include the `gh-pages` package. Follow the instructions
     provided [here](https://blog.logrocket.com/deploying-react-apps-github-pages/) but bear in mind the following:
     - Where they use `create-react-app` (CRA), you should use `vite` (CRA is an obsolete React project initialiser)
     - You should check out additional setup instructions for `vite`
       [here](https://vitejs.dev/guide/static-deploy.html#github-pages)
  2. Use Netlify, as per the instructions below for "React with Routing".
- **React with Routing** - If you have routing, then this is the best approach. It is also a good option if you have 
  a React SPA with no routing. It requires a bit of setup so follow the guides carefully!
  - [Freecodecamp tutorial](https://www.freecodecamp.org/news/how-to-deploy-react-router-based-app-to-netlify/)
    - It is NOT advised to use the "Drag and Drop the Build Folder in Netlify" approach
    - The "How to Deploy an App to Netlify from a GitHub Repository" approach is better
    - Beware that this is from 2021 so some things may have changed
  - [Netlify instructions](https://docs.netlify.com/integrations/frameworks/vite/#deploy-your-vite-project-with-netlify-cli)
    - These are the official Netlify instructions for deploying a React app built using `vite`
    - It involves installing their Command Line Interface (CLI), which is a programme that you run from your 
      terminal / GitBash.
  > Whichever Netlify  guide you follow, be sure to do the steps fo adding a `_redirects` file to enable both React SPA 
  > and React with Routing apps to work properly. 
 
## Where can I find examples or inspiration?

Here are some sites to check out:

- https://webflow.com/blog/web-developer-portfolio-examples
- https://www.freecodecamp.org/news/15-web-developer-portfolios-to-inspire-you-137fb1743cae/
- https://www.behance.net/?tracking_source=typeahead_search_direct&search=portfolio%20cv%20developer
