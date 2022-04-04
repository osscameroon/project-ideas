# Project ideas

Our goal in the osscameroon community is to build the opensource solutions our country needs.
This Repository is a crowdsourced collection of project ideas submitted by the community and that might require our
amazing pool of contributors to work on.

Checkout the [project ideas](https://github.com/osscameroon/project-ideas/issues) submitted by the community.

## You have an idea

If you have identified a problem Cameroonians are facing on a daily basis,
such as difficulties to find a list of good restaurants and you have an idea of software
that you think might help solve that problem, feel free to [submit a project idea on this repository](https://github.com/osscameroon/project-ideas/issues/new?assignees=&labels=&template=project-idea-template.yaml&title=%5Bedit%5D+Your+Project+name).

Once you have submited your idea, the community will be notified and you will be invited to describe your idea clearly to us.

## You are a developer

If you are a developer looking for a cool open source project to work on, checkout this list of [projects ideas](https://github.com/osscameroon/project-ideas/issues).

The projects have a set of labels that indicates the status and or complexity of the project.

#### Statuses

* Started - *The project is currently under development*
* Done - *The project had a v1 release, and is being actively maintened*
* Stalled - *The project hasn't progressed a lot in a while, and have no active maintainers*

Depending on the status of the project you may decide to join a project that is currently under development,
pick up a project that has not started yet or grab a stalled project to make it move forward.

You have decided wich project to work on ? Feel free, to drop a comment on the issue to let the community know what you intend to do with that project and join the [telegram group](https://t.me/+UpKZh_KXTaTx7JD7) to get faster feedback.


## How to build a project (recommendations)

Building open source solutions can be quite challenging, thus we will try to share few recommendations that we beleive can help you bring a project to fruition.

#### The team
It is important to keep the team working on the initial phase of the project small.
Depending on the complexity of the project the team should be composed of 1 to 3 people.

* For a project that is very simple, meaning that it is not composed of several components, an api + mobile or web user interface for instance, a single developer is enough.

* If your project require several components or services such as a typical, frontend + backend app, you can add an additional developer and split the work between frontend and backend to reduce friction.
The team may also require a designer, in which case he/she will be the 3rd member of that small and effective team.

* It might be possible to have teams of 4 to 5 members, we do not recommend to have teams of more than 3 people but if you insist make
 sure you have at least a person doing the important project management work.

#### The Scope

Incentives to work on an opensource project can evolve over time and it can be difficult to keep your motivation strong to release a project.
Something that can help you move forward is to size the first release of your project to something that can provide the most value in the shortest amount of time.

**Example:**

We wanted to build **jobsika**, a platform that will allow developers to share their salaries, review and rate the experience they had working for companies, but also to find jobs and share their availibilities for jobs.

##### Drop what's unecessary:

The platform could be something that would allow developers to login, edit their
profiles, add a biography, and then drop a review.
We could also allow companies to create and edit a company profile, share job description etc...

You may have understood it already, but it seems that many of the features listed above are not absolutely necessary. We don't need a login system for users to drop salaries and reviews.

##### Focus on providing value:

It is important to limit the features to what provides immediate value to the user.
We built the platform for developers so that they can have an idea of what salaries they could ask,
depending on their work experience. We also wanted them to have a rough sense of how a company threat its developers.

This meant that everything related to company profile and job listing was something that could be added later to the project.

##### Work on small tasks:

We often work on opensource projects on our spare time. Few hours a week for most of us.
Which means that depending on how we scope our tasks, it can take between a week to several months to get a feature completed.

A big advantage of aiming to work on smaller task is that you might end up defining tasks that can be managed in few few hours.
It is very important for your team to see some progress and working on smaller tasks will allow you to see the evolution of the project every week in the best case.

When defining taks or creating issues for your project, we recommend splitting them to the smallest entity possible.
Start defining high level goals or tasks like building the static home page, but then brake it down to,
smaller issues such as:

* Create the search bar static component
* Create a component for a single item on a list
* Create the list component
* Make the search bar dynamic (make the actual search button search something)

	etc...


#### The process

Following the evolution of the project, keeping the communication flowing in the team and setting realistic milestones are crucial for your project to to be completed.

**Track the evolution of project:**

It is important to set a **daily, weekly or monthly catchup** on which you can go through the issues you have created and discuss the evolution of the project.
For **jobsika** we have set a weekly meeting, that was sometimes canceled as some of us were busy during certain periods.

**Be mindful** of other people's time, it is fine for your collaborators to show up on a meeting without having done anything, they were probably busy or not inspired.
What is important is to not lie and be transparent about what you have acomplished. In some cases a contributor won't be productive for about 2 months or not very present,
is motivation to work on the project might be in question and this should be discussed with him/her. He might simply need to quit the project for a while.

**Track issues** using with [GitHub projects](https://docs.github.com/en/issues/trying-out-the-new-projects-experience/about-projects).
You can also set a kanban board to use during daily or weekly catchups.

We use GitHub projects to track [the roadmap](https://github.com/orgs/osscameroon/projects/4) at **osscameroon**. Feel free to check it out for inspiration.


**Keep the communication flowing:**

Once you have formed a team to work on your project, it can be useful to create a chat group for you to share informations, ask for help and discuss about everything related to the project.

For **jobsika** and other project at osscameroon we created telegram groups. Using telegram group help us kick of instant voice chat which is pretty neat.

**Setting realistic milestones:**

As we discussed already, keeping your team motivated is going to be challenging and making sure you see
important results quickly is going to be key.

Developers tend to be very optimistic about how long a task is going to take.
Let's say a developer picks up the implementation of a search bar, in his mind he/she will think it is a 1h work.
If you give him/her 1 week to work on such task he/she might wait for the last hour before the meeting to start working on the actual ticket.
And might realise that he/she did not take into account the `filters` in the search bar. Which means you actually need more time to deliver that essential feature.


We don't have an appropriate solution for that yet,
but something that can help speed things up is to set a milestone that can match the 4-5 hours a week each team member can provide.
Arbitrarily we could say that for a single developer working 5 hours a week implementing a well scoped (removed of unecessary features) home page can be acheived in a month.

You could then expect the home page to be ready at in a month time, but like in 99% of the time this won't be true.
But at least you might have something that is close to a fully functional home page, and iterate.


#### The Architecture

Regarding the architecture of your project, the key word here is **simplicity**.
As developers we often like to work on complicated systems, implement challenging algorithms and use this new fancy devops practices or tools (kubernetes :P ). This are all noble things to thrive for, but they comes with a cost.

When we start a new opensource project we are excited about the problem we want to solve, the challenges we want to face and the things we are going to learn.
This keeps us motivated long enough to release the project, but as long the project is out there and users start submiting feature requests or pointing out bugs.
This incitives are not enough anymore and the nice and fun development, becomes a long term maintainance chore.

Building applications made of multiple components in a microservice architechture
, with a databases and a Saas solution, comes with few operational challenges and costs that should not be overlooked.
The way you architechture or write your code and the technologies you choose might also harm the long term maintaince of your project.

Maintaining an opensource project is a long term commitment. And keeping things simple will considarably improve first time contribution and your motivation to maintain your projects.

**How to keep things simple:**

- **Build a monolith** by default. Sometimes you might want to split your frontend and backend to ease the development in your team. it is totally fine but as the backend is concerned build a monolith.
- **Mono repositories** are crucial to keep your application code at hand. It is easier to know where things happen when they happen in one place :).
- **Avoid Saas**, using subscriptions Saas like [Worpress](), [Firebase]() or something that is not already used by the community can make operational work difficult. If you absolutely need a saas subscription [contact us](), we will probably try to convince you that you don't, but we are opened to change our mind or get it for you.
- **Avoid self managed Databases** as they require a massive amount of operational work. Generally speaking we recommend you design your applicaton using file **databases** like a `yaml` file or `sql-lite`. [camerapps](https://github.com/osscameroon/camerapps.com) is a good example of applicatoin that uses an `yaml` file as DB. We are working on making more use of sql lite.
- **Ask for a managed Database** we aknowledged that for few projects it might be important to spin a database. If you think your application need one come [talk us](), we probably think it doesn't but we are opened.
- **Write code for humans**, write code others will understand, don't try to prove a point by using nested ternaries or comprehensions, complicated OOP design patterns or fancy architechtures. Good patterns and architechture emerge while you writie something simple and functionnal. Code readability and maintainance comes first, keep that in mind.
- **Use automation to enforce Architectural decision**, you can use [GitHub Actions]() to add checks to enforce linting, run unit or integration tests, enforce the use of [conventional commits]() before the code gets merged.
- **Write tests**, please do it will help you architecture your code and maintain it in the future.

#### Deployment

To deploy your application you can we recommend this solutions:

- **Use [GitHub Pages]()** if you are working on a simple frontend application. A collection of restaurants for instance.
- **Docker containers** are the recommended way to package your application. If you have a workflow that generates a Docker image we can use our artifact management system to deploy your application on our servers.
- **Tradional Apache or APM** deployment, we also provide GitHub Action workflows to deploy your application on Apache and APM.


We are currently working improving the automatic deployment of our solutions, you can read [this architecture draft](https://github.com/osscameroon/sami/blob/main/Architecture.md) for our artifact managment system. It is already used to deploy **jobsika**.


### Conclusion
TODO...

TODO - convert the how to build an application part into an article
