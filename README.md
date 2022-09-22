# VikeLabs W2022 Kickoff Starterpack

Welcome to VikeLabs! This repository is here to help you get you (or your team) started on the right foot for the 2022 season. This repository contains a few things:

- Instructions on how to approach starting a project.
- Basic example of a web application using TypeScript, React, and Next.js.

## What is VikeLabs?

> VikeLabs is a student-run organization at the University of Victoria that aims to provide students with the opportunity to work on real-world projects with industry partners. We are a student-run organization that is open to all students at UVic. We are a great way to get involved in the UVic community and to build your resume. We are always looking for new members, so if you are interested in joining, please reach out to us at []().

**If you are already part of a team, you can skip the content here.** Feel free to use this as a reference though!

## Joining a Project

**TBD**

## Starting a project

**TBD**

## Forming a Team

**TBD**

## Brainstorming

**TODO**: Fill out this section. Depends on how team formation works.

## Planning

Once you have a team and idea it's time to start planning. Planning is a very important part of any project. It's important to plan out what you want to do and how you want to do it. This will help you avoid a lot of headaches down the road. That being said, don't overplan. You don't want to spend too much time planning and not enough time actually building. It's important to have a plan, but it's also important to be flexible. Things will change, and you will need to adapt. That's okay. It's part of the process.

### Minimal Viable Product (MVP)

A minimal viable product (MVP) is the smallest possible product that you can build to test your idea. It's important to build an MVP because it allows you to test your idea and see if it's worth pursuing. It also allows you to get feedback from users and stakeholders. This feedback can be used to improve your product and make it better.

In the context of VikeLabs, building an MVP helps keep the project scope manageable. The last thing you want that is too big and the you end up losing steam. You can always add more features later, but it's hard to remove features once they are built.

That said, you are in no way required to build an MVP. If you have a good idea and you think you can build it in a reasonable amount of time, then go for it! If you are unsure, then it's probably a good idea to build an MVP. Also, if you just want to get your hands on some new technologies, then do that too!

#### Examples

> As a student, finding parking at the university is difficult. I wish there was an app that showed me where parking spots are available.

Consider what a MVP for this idea would look like. What features would it have? What would it look like? How would it work? What would it do? What would it not do?

- Is it important to have a map? What about a list of parking spots?
- Is it important to show the number of spots available or just if there are any spots available?
- Is it important to show the exact location of the parking spot or just the parking lot?

> As a student, I want to be able to see what courses are available in the upcoming semester so that I can plan my schedule.

This was a real idea from a real team [(CourseUp)](https://github.com/vikelabs/courseup). What would a MVP for this idea look like? What features would it have? What would it look like? How would it work? What would it do? What would it not do?

- Is it important to show the course description?
- Is it important to show the course prerequisites?
- Is it important to show the course schedule?
- Is showing scheduling conflicts important?
- Is having user accounts important?

Thing about these questions and check out [(CourseUp)](https://github.com/vikelabs/courseup) and see what they did.

### User Interface (UI) Design

A lot of time (but not always), your application will have a user interface. This is the part of your application that users will interact with. It's important to think about how you want your application to look and feel.

Doing this design process code can be a bit tricky. Therefore it's recommended that you do this design process before you start writing any code. This will help you avoid having to rewrite a lot of code later on. You can use tools like [Figma](https://www.figma.com/) to help you with this process or you can just use pen and paper. A whiteboard is also a good tool for this.

#### Examples

> As a student, driving to the university is expensive so I want to find a way to carpool with other students.

What would the UI for this idea look like? What would it do? What would it not do? What is the first thing a user would see when they open the application? What would they do next? What would they do after that?

### Project Management

When working on a team, it's important to have a way to manage your project. This is where project management tools come in. There are a lot of different project management tools out there. Some examples include:

- [Trello](https://trello.com/)
- [Asana](https://asana.com/)
- [Jira](https://www.atlassian.com/software/jira)
- [ZenHub](https://www.zenhub.com/)
- [Linear](https://linear.app/)
- [GitHub Issues/Projects](https://github.com)

We recommend using GitHub Issues/Projects because it's free and it's integrated with GitHub. This means that you can use GitHub Issues/Projects to manage your project and use GitHub to manage your code. This is a good way to keep everything in one place. Reach for other tools when you need them.

### Code Management

It's important to have a way to manage your code. This is where code management tools come in. At VikeLabs, we use GitHub to manage our code and therefore we use [Git](https://git-scm.com/) to manage our code. Git is a version control system that allows you to track changes to your code. It also allows you to collaborate with other people on your code.

Learn the basics of Git and GitHub by following the [GitHub Learning Lab](https://skills.github.com/).

> 🚨 **Remember to ask for help if you need it on our Discord!** 🚨

## Building

**Are you awake!?** Congradulations on making it this far! You are now ready to start building your project. This section will cover some of the basics of building a web application. If you are already familiar with these technologies, feel free to skip this section. If you're not building a web application, feel free to skip this section.

**If you're going to use another language, framework, or library ask in the Discord server for advice and consultation first with peers and admins.**

If you've been following along, you will notice we have not talked about what technologies you should use. That's because it's up to you! You can use whatever technologies you want. That being said, we do have some recommendations.

### Picking a Technology Stack

In software development, a technology stack is a collection of technologies that are used to build a product. For example, a technology stack for a web application might include:

- HTML
- CSS
- JavaScript
- Node.js
- Express
- MongoDB
- Blood
- Sweat
- Tears

Given the state of web development, you can pick any word and it'll probably be a JavaScript framework or library. The last 3 are jokes, by the way.

Choosing a technology stack **should be rooted in the project** you're building _unless_ you're using a technology stack that you're interested in learning.

- If you're building an application that requires a lot of computation then picking a language like Python or C++ might be a good idea.
- If you're building an application needs to be accessible from a lot of different devices then picking a language like JavaScript/TypeScript might be a good idea.

**✅ Consider your goals as a team and pick a technology stack that will help you achieve them.**

> 🚨 **If you're confused about what to pick, ask in our Discord!** 🚨

## Example: Web Application with Next.js and sqlite3

In our example, we're going to build a web application that allows users to create posts. We're going to use [Next.js](https://nextjs.org/) and [sqlite3](https://www.sqlite.org/index.html) to build this application.

### Setting up the Project

You're going to need to install [Node.js](https://nodejs.org/en/) and [npm](https://www.npmjs.com/) to get started. Once you have those installed, you can create a new project using the following command:

```bash
npx create-next-app --typescript
```

> 🚨 **If you're stuck setting up your development environment ask in our Discord!** 🚨

This will create a new project using [Next.js](https://nextjs.org/) and [TypeScript](https://www.typescriptlang.org/). You can learn more about Next.js [here](https://nextjs.org/learn/basics/create-nextjs-app).

### Setting up the Database

We're going to use [sqlite3](https://www.sqlite.org/index.html) to store our data. To get started, we need to install the [sqlite3](https://www.sqlite.org/index.html) package:

```bash
npm install sqlite3
```

This will install the [sqlite3](https://www.sqlite.org/index.html) package and add it to our `package.json` file. We can now use this package in our project.

We'll provide the basic SQL commands to get started. You learn about database in CSC 370.

## Deploying

**TODO**: Fill out this section

**Deploy your projects early! Deploy your projects often!**
