---
title: "What did you think of our service during the time you used it?"
date: 2019-11-02T09:45:05-07:00
draft: false
---

This section also addresses: "Briefly explain a challenge you experienced in setting up this site and how you solved it."

### Awesome service 
I thought the service was really impressive! Here are some specifics:

- The integration with Github was soooo smooth. I even tore down the original repo I’d connected to Netlify to see what it would be like to reconnect a new repo. The process was so easy and took very few clicks. Really nice. 
- Adding a `netlify.toml` file with a redirect was very straightforward thanks to the docs. 

### Challenge: Using logs to zero in on an environment variable
I ran into an issue where the Hugo template I used required a certain minimum Hugo version in the development environment. I didn’t hit this snag locally—only on deploy. The ability to see logs was essential for troubleshooting. I was able to Google the error message in the log and was taken to a Netlify forum post by someone who ran into the same issue. That post pointed to docs about setting environment variables, so I was able to add a `HUGO_VERSION` variable and keep going.

### Idea: Automatically update env variable and rebuild
The build snag I ran into made me wonder if there’s a way to automatically check if the build failure is due to an env variable issue, automatically set the correct variable, and rebuild? Maybe there are too many possible cases and it abstracts too much from the user, but just a thought.

### Question: Redirects
I used a `netlify.toml` file because I wasn't sure how to use a `_redirects` file. How would I get that file into `public/` without a build script that included `hugo` and something like `cp _redirects public/_redirects`?



