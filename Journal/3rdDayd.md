# Planning your next Software Project

![Software Planning](../Images/3.jpg)

**NOTE:** *I'm currently studying software development and Agile, and this blog is a journal of what I just learned about Planning a software product. If you found something is not quite right, please let me know, I love learning from people!*

Maybe you once got an idea about a software that you're excited about, but during development phase, you noticed how entangled your project became, and it's hard to keep track of things or even see your progress.

Or maybe you're like me who always wants to jump right into code once an idea pops up into our head.

Here is when a good planning; and maybe some research; should be first thought of.

So how do we start planning?

## Understand what you're going to build

This might not make sense at first glance, but this helps us outline the different parts of our software.

Let's say we want to build a bug tracker.

From this idea, we break it down to different features or high-level requirements, which will serve as a bird's eye view of what's coming our way.

For a bug tracker, we might list out the following:

- A. Log-in/Sign-up (Authentication and Authorization)
- B. Dashboard
- C. User Profile
- D. Tasks Section

This rough sketch will serve as the foundation of our early project.

We can add more heare, but it's better to keep things simple at first and just focus on the core of our project. Additional features can just be added once our product is already up and running.

From there, we break down each requirements into narrower requirements of our software.

For example:

|          Feature         | Area | Description |
|--------------------------|------|-------------|
| Navbar | All | Holds navigation links to different parts of the bug tracker |
| Footer | All | Holds more links to other parts of the website |
| Sign-up (Email/password) |  A   | Users can create their account using email and password,and will automatically become the admin of his organization. This user must invite other people to the organization and assign them their role, such as developer, tester, product owner, etc. |
| Sign-up (OAuth) | A | Users can also create their account via third party OAuth providers such as Google, Facebook, and GitHub. Users will also be automatically become the admin of his organization and must invite the team members and assign them their roles. |
| Sign-Up (Invited) | A | An invited user can sign up via email or OAuth providers. Invited users can't create their own organization, and is only limited to things based on the assigned role to him, but the admin can also assign the invited user as admin and gain the same privilages. |
| Dashboard | B | Shows a quick summary of the... |
| ... | ... | ... |

From high-level requirements, we started to break it down to narrower requirements. It's important to break things out so that we understand from the start what we're building. On this stage also, you might uncover something about your rough list of high-level requirements, so you can backtrack a little bit and re-think what you want to build and what would be it's features. Those things are totally up to you, your idea, and imagination.

The important thing here is that we should understand our software, we specify a list of the things our software will be made of, and the list that we will came up with will serve as guide to our development journey.

## Start simple

![Start simple](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/j3hxv2db3e2b1frcqokj.jpg)

When you're starting to plan the software, don't forget to just start simple. It is because you should test out first the viability of your idea, and your goal is to have that proof of concept, that your idea is plausible.

A barebones app is enough from the beginning, just to prove that our idea is doable. And from there, we can just add features later that will define and shape our app. Remember that we can branch out features further down the road.

So start small, have a list of rough ideas or features of your project, and have that proof of concept that shows that our idea is actually doable. From that, we can build incrementally our software from idea to real world product (perhaps even sell or make money from it! Isn't that a good idea?)

### The MVP (prototype your idea)

![Minimum Viable Product](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ydbb2bl5uawqokexnzut.jpg)

MVP or Minimum Viable Product is a very common word in the startup world, but we can use this idea to model and build our first prototype or proof of concept.

The idea here is like what I said above, start simple and define the core of your software, and build that first as a proof of concept.

The important reason why we want to prototype is to experiment and test our idea, whether it is trualy worth developing it to a full fledge software, or maybe uncover potential pitfalls that awaits us further down our development phase. Maybe our idea might breech copyright, or can be later too expensive, or we need to think about how the backend infrastructure of our software should be like. But remeber that when you encountered these potential pitfalls, it doesn't necessarily mean we abandon the project, because we absolutely will encounter at least one of them, it's just a way for us to be prepared early on to find the solution to the problem and be proactive rather than reactive.

So start small, prototype the idea, have a proof of concept that the idea is actually doable, and experiment things from there. Maybe you realize that this side project has a potential to brew a million-dollar start-up company, who knows? It's in this prototyping phase is when you'll understand your software and it's possibilities and pitfalls.

It's better to start somewhere and simpler, than too complex and never having that software at all.

## Product (or project) Roadmap

![Product Roadmap](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4x5v1omieseuhp29lg5s.jpg)

The product roadmap is a nice visual representation or guide of how you plan to develop the software overtime.

This is when you limit or set time of how long to develop each of the requirements you list down.

When estimating the deadline, you must consider the complexity or difficulaty of the task and be honest to yourself (or your team if you have other people on this project) based on your skills, experience, or maybe other external factors, on how long it will take before you deliver the feature and meet the goal.

But why set a deadline?

There are a lot of benefits of setting a deadline, like having that rough idea of when you can realize that your idea is already a fully functional software, or it can also be milestones of your project that you can celebrate for each one you achieve, etc.

The important thing here is that deadlines guide us on development so that we can arrive to our final goal. Because without setting when we target a feature is expected to be completed gives us that illusion that we can build continuously even unnecessary features that will prolong the prototyping, and we may neven arrive to that first prototype software.

So start a target date, and commit to it. You'll be glad along the way to see your progress and your idea to start to come to life.

## Backlog

Backlog refers to the tasks that are needed to be done.

Those tasks shall come from the requirements we specify or narrowed down.

If you're familiar to Agile methodology of software development, you may consider those high-level requirements (the one on the table above) as the Product backlog. By the way, those reqirements are usually (or should be) in the form of user stories. (You can search more about what a user story is in case you're not aware).

Since the requirements on the product backlog are very abstract and high-level, we should take one and further brake it down into smaller and doable chunks of tasks. Again, in Agile, more specifically Scrum, this is called as the Sprint backlog (where a sprint is a timebox of about 1-4 weeks of development phase, aiming to accomplish all the tasks from the sprint backlog).

The tasks on the sprint backlog will be the source of the todos to be listed on our [Kanban](https://dev.to/menard_codes/software-development-through-kanban-28d0) board. These tasks are more narrow and doable, such as connecting to a mongoDB database, etc.

Combining the todos in Sprint backlog and a deadline of about 1-4 weeks makes us feel like working on a real software development team or company with an Agile approach to development, but just imagine how productive you'll become with this approach compared to absolutely no plan at all.

## Final Thoughts

Building our next software project is exiting and challenging. Planning earlier can save us a lot of time and headache along the road. Software development can be easier if we plan things out before we start, because a good planning gives us a clear picture of our development journey.

Also, we don't necessarily need to start complex. It is ideal that we begin simple and small, then gradually build it from the ground up. Prototype it, build the proof of concept, and improve it later. Remember that phones didn't started as smartphones, they began as huge boxes that allows you to call someone, and it gradually improve over time until it became the sophisticated smartphones today.

Hopefully this helps, and goodluck for your next project!

## My link

Follow me on [Twitter](twitter.com/menard_codes)!
