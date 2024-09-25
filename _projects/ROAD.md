---
layout: page
title: ROAD website
description: Profesisonal website I've done for ROAD, an education startup
importance: 1
category: work
---

I built the website from complete scratch, primarily using AWS to host the entire site, you can visit the site [here](https://www.road.edu.vn/). Aside from the informational pages on the website, I have also developed two more advanced functions:

# [Road to Uni](https://www.road.edu.vn/road-to-uni)

This feature allows students to search, pick, and choose universities based on different criteria. Our database covers most universities in Vietnam, except the area near Hanoi capital.

{% include figure.liquid loading="eager" path="assets/img/road-to-uni.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}

**Currently, this function has been deprecated.**

# [STEM](https://www.road.edu.vn/stem)

This active function allows teachers to upload their STEM curriculum for students, as well as download materials from other teachers. The website includes filters that allow teachers to refine their searches based on different criteria, such as:

- Grade level (10, 11, 12)
- High school
- Subject
- Length of the curriculum

Additionally, teachers can use the autocomplete search feature to quickly find their desired files.

{% include figure.liquid loading="eager" path="assets/img/stem.png" title="example image" class="img-fluid rounded z-depth-1" %}

# My Journey in Building This Website

## Joining the Team

When I first joined the team, I had absolutely no clue how to put a website on the internet. All I knew at the time was some basic HTML, CSS, and JavaScript. I had no idea how a frontend connects to a backend. When I read about APIs, I could understand the concept logically, but I had no clue how to implement one in real life.

## Learning Full-Stack Development

My first instinct was to find a channel that teaches full-stack development quickly. I needed to figure out how to get a dynamic website published to the internet since I couldn’t use a static one due to the special functionalities required. That’s when I came across this [MERN stack series](https://www.youtube.com/watch?v=98BzS5Oz5E4&list=PL4cUxeGkcC9iJ_KkrkBZWZRHVwnzLIoUE).

## Starting with the MERN Stack

I picked up the stack pretty fast. I didn’t even consider using SQL because the course didn’t cover it, and I mistakenly thought that only certain databases could go with certain frameworks. While learning the MERN stack, I stumbled upon a video titled something like "Every Developer Needs to Know What Docker Is." So after finishing the MERN stack, I also learned Docker to avoid missing out and being left behind.

## Getting the Website Online

Once I had the tech stack working locally, it was time to figure out how to put it online and deal with domains. I started by searching how to publish a website on the internet, but most of what I found was about using GitHub or other static file hosting services. I eventually discovered services that host dynamic websites, and the first option I tried was Vercel. It was super fast and incredibly easy – you just link your repo, and voilà, the website is live! The only downside was the weird-looking URL, but it was online!

## Diving into AWS

While that was cool, I felt like I wasn’t learning anything about how websites are actually published on the internet by using Vercel. So, I decided to do as much manual work as possible to learn the real process. I chose AWS, mainly because it's so popular. Man, I must say, I suffered a lot! I probably struggled more with getting AWS services to work together than with fixing bugs on the website. There were so many new concepts for me: EC2, Route 53, S3, IAM, domain names, DNS, record types... It took a lot of time to make all these pieces work together, but I’m glad I did it. By pushing through the challenges, I really learned how to put a website online – understanding DNS, IP addresses, SSL certificates, and all the other details.

## Using Docker for Deployment

After getting AWS to work, I used Docker to deploy the app on our EC2 instance. At the time, it seemed like the right choice. Everyone on the internet (or so I thought) was using Docker to deploy their services. Docker was supposed to eliminate the "it doesn’t work on my machine" problem. I hadn’t actually encountered that problem myself, but it sounded cool, so I gave it a try.

## Optimizing the Deployment Process

As the website grew more complex, I noticed that the deployment process was taking around 2 minutes, which felt pretty long. I started thinking, "What if I just install Git on the EC2, pull the new code changes, and run them directly?" So I did exactly that, and it reduced the build time to about 30 seconds. Amazing! From this, I learned the importance of choosing the right tool for the right job.
