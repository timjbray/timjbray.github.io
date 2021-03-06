---
layout: post
title: File > New Project
---

I've been starting quite a few new software projects lately - *yea*! 

It's given me a chance to reflect on how to do things right from the start. But what is right? And how do we navigate all the great technology choices we have today?

## What is right?

I like to have a solid methodology and rules. This helps to generate results that are predictable and repeatable. For example, I quite like the [12 Factor App](https://12factor.net) methodologies, and _mostly_ follow the factors. 

While I don't really believe in absolutes, but here are some of my some of my non-negotiables* in software projects:

- Modern architectures - break that project up, don't build another monolith. I'm also a fan of evolutionary architecture, design for change.
- Modern languages - I like to choose modern languages, but not bleeding edge. Don't want to start a new project on legacy. But don't want to build something where it may be impossible to get help or build a team around - when the project inevitably succeeds :-) 
- Code formatters, linters & static analysis - use these to reduce style issues and improve code quality 
- Modern Platforms - choose platforms that are going to accelerate development. I don't want to be building anything that can be pulled 'off-the-shelf'.
- API languages - how are all the services going to talk to each other? There are some cool options now. SOAP is not one of them ;-)
- Source control service - In my first coding job, source control was managed by using different disks and folders: `backup #1`, `latest backup` etc. It was a nightmare, luckily was able to convince the boss there was a better way. Now it's not whether to use source control, or what type of source control (ie use Git), it's just about what service to use and what extras it provides.
- Issue tracking software - some great options here these days, it's also included in most source control services. I like to have the git comments link back to issues and stories.
- Documentation - somewhere to write doco - internal & external. Nuff said.
- CI/CD - It should be super easy to get changes tested and deployed to production through pipelines. It's amazing how much this improves outcomes by encouraging regular delivery of small pieces of functionality. The DevOps mindset.
- Monitoring - Need to know when there are issues and how the app is performing. There are now so many great tools and services to choose from here.

> It's amazing how much this improves outcomes by encouraging regular delivery of small pieces of functionality. The DevOps mindset.

(*) _Rules are there to be broken, I just try to consciously balance the trade-offs. I've recently chosen a range of technologies that I didn't have much experience with and somewhere very new. Mostly because I wanted to learn, improve my skills and I expect the technology to gain popularity._

## Bias for action

There are dozens of good options for every one of the above. It's easy to get distracted on research. Especially since I've suffered from my previous choices. This time I won't make that mistake (I'll just make another one instead...)

I value researching - reading, talking to people, playing around & prototyping. Plus research is easy and fun! But it's also easy to blow days or weeks figuring out the perfect option and be no closer to selecting the right tech that will be pivotal for a new project. 

After I have a certain level of confidence in a technology or direction, I prefer to make a start and learn along the journey. I also like to asses the choices regularly - especially when it early enough to change direction.

My bias for action has bitten me a few times recently. Where I've jumped in and started designing, architecting and building before I fully understood the technology. Most of the issues that arose are easy fixes, I just could've saved a little time and hassle with a better understanding.

## Be happy with the choices

It's easier to change technology choices now than ever before. 

The Cloud, micro services, React/Angular/Vue components, shared packages (npm/gems etc) and interoperability between systems makes it easier to swap out parts of a platform than ever before. 

## It's all secondary

> ...they are secondary to having the right processes, culture, automation & measurement.

While choosing great technologies and tools will help a project succeed, I've found they are secondary to having the right processes, culture, automation & measurement. These enable that consistent quality and delivery. Building the right product in the right way. 

