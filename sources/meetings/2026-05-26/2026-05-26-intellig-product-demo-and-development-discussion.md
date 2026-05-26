# IntelliG Product Demo and Development Discussion

| Field | Value |
|---|---|
| **Date** | 2026-05-26 |
| **Type** | MEETING_TRANSCRIPT |
| **Source** | [Link](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks) |

## Executive Summary

## Meeting Purpose

[Demo IntelliG and kick off a new project using an AI-driven workflow.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=6.0)

## Key Takeaways

  - [**IntelliG Demo:** Levi demoed IntelliG, an execution intelligence platform that connects code, meetings, and finance to track progress on business initiatives, replacing manual Jira updates.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=6.0)
  - [**New Project Kickoff:** Abhishek will build a laundry service marketplace for Nepal using an AI-first workflow with Cursor (Codex), IntelliG, and Fathom.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=2202.0)
  - [**AI-Driven Architecture:** The project will use a Next.js/React monorepo with Supabase and Vercel, following advanced patterns like CQRS, DDD, and Vertical Slice to ensure clean, scalable code.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=3000.0)
  - [**Partnership:** Levi offered to connect Abhishek to CTOs for jobs in exchange for Abhishek providing intros to Nepali product companies for IntelliG trials.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=1454.0)

## Topics

### The Problem: Inefficient Engineering & Layoffs

  - [Current tools like Jira fail to track progress on business initiatives, focusing instead on manual ticket updates.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=60.0)
  - [This lack of objective data leads to inefficient layoffs, where high-value contributors (like Abhishek at Fluid.app) are cut while less productive, higher-paid staff are retained.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=725.0)
  - [**Levi's Thesis:** If an engineer isn't pushing code daily, their contribution is unclear.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=432.0)

### The Solution: IntelliG Platform

  - [IntelliG provides "execution intelligence" by connecting GitHub, meeting notes (via Fathom), and finance data.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=370.0)
  - [**Key Features:**](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=23.0)
      - [**Cogniz:** An AI reasoning engine to query all connected data (e.g., "What was discussed in stand-up?").](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=182.0)
      - [**Initiative Discovery:** Automatically identifies potential initiatives from meetings and code.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=552.0)
      - [**ROI Analysis:** Objectively measures engineer value by linking code output to salary.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=381.0)
      - [**Automated Stand-ups:** An agent generates daily summaries of commits and PRs.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=456.0)
  - [**Status:** Production-ready with paying customers (3 AI startups, 2 enterprises).](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=1617.0)

### The Workflow: AI-First Development

  - [Levi's framework uses AI to build products rapidly; he built Tree Inventory AI in two weeks while on vacation.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=1231.0)
  - [**Core Principle:** The codebase is the single source of truth.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=1159.0)
  - [**Process:**](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=1114.0)
    1.  [**Define Specs:** Create detailed markdown files (`vision.md`, `architecture.md`) in the repo for each feature.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=1114.0)
    2.  [**Orchestrate AI:** Use an AI assistant (Cursor/Codex) to generate code based on these specs.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=1114.0)
    3.  [**Provide Context:** Feed the AI the full context from IntelliG, including meeting transcripts and engineering standards, to ensure high-quality, architecturally sound code.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=3326.0)

### Project Kickoff: Laundry Service Marketplace

  - [**Idea:** A marketplace app for laundry services in Nepal.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=2233.0)
  - [**Tech Stack:**](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=3000.0)
      - [**Frontend:** React](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=3000.0)
      - [**Backend:** Next.js (monorepo)](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=3000.0)
      - [**Database & Auth:** Supabase](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=3000.0)
      - [**Hosting:** Vercel](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=3000.0)
  - [**Architecture:**](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=3342.0)
      - [**CQRS (Command Query Responsibility Segregation):** Separates write (commands) and read (queries) operations.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=3534.0)
      - [**DDD (Domain-Driven Design):** Models the business domain with rich objects (aggregates).](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=3780.0)
      - [**Vertical Slice:** Organizes code by feature, making each slice a self-contained microservice.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=3434.0)
      - [**MVVM (Model-View-ViewModel):** Segregates DTOs from business layer models.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=3677.0)
  - [**Goal:** Use this project to demonstrate the AI-first workflow and build a production-ready app.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=1231.0)

## Next Steps

  - [**Levi:**](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=4321.0)
      - [Send Abhishek the engineering standards zip file.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=4321.0)
      - [Send the meeting transcript file.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=4321.0)
      - [Send a new meeting link.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=4321.0)
  - [**Abhishek:**](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=4321.0)
      - [Download the standards and transcript files.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=4321.0)
      - [Start a new Cursor (Codex) session.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=4321.0)
      - [Load the standards and transcript into the AI's context.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=4321.0)
      - [Join the next call to begin building the project with Levi.](https://fathom.video/share/vo5-qYqA49s2fg6izhwvyprcx8ygRwks?tab=summary&timestamp=4321.0)


## Decisions

- **Abhishek will sign up for a free trial of IntelliG and onboard with Levi's guidance.** — _Levi Garner_
- **A new application for a cleaning service marketplace in Nepal will be developed using IntelliG.** — _Levi Garner_
- **The new cleaning service app will be built using React frontend, Next.js backend, Vercel, and Supabase for database and authentication.** — _Levi Garner_
- **The development of the cleaning service app will follow specific engineering standards including CQRS, DDD, Vertical Slice, MVVM, and a clean repo structure.** — _Levi Garner_
- **Fathom AI Notetaker will be integrated to sync meeting transcripts into the project's repository.** — _Levi Garner_

## Action Items

| Action | Assignee | Due | Status |
|---|---|---|---|
| Sign up for IntelliG using the provided coupon code and complete the onboarding process. | Abhishek Bhatta | — | PENDING |
| Set up a new repository for the cleaning service marketplace app. | Abhishek Bhatta | — | PENDING |
| Integrate Fathom AI Notetaker to sync meeting transcripts into the repository. | Abhishek Bhatta | — | PENDING |
| Send Levi engineering standards for the new app development. | Levi Garner | — | PENDING |
| Coordinate introductions to potential product-based companies in Nepal for IntelliG trials. | Abhishek Bhatta | — | PENDING |

**Duration**: 73 minutes

## Transcript

Levi Garner: You can see my screen, all right?
Levi Garner: Yeah.
Levi Garner: All right, so this is the product, okay?
Levi Garner: So, and I'll touch on, this would be a bit educational to you.
Levi Garner: I'll share a few different points that I've learned along the way of building these agentic systems, okay?
Levi Garner: So, essentially what IntelliG is, okay, as I mentioned, it's essentially execution intelligence.
Levi Garner: So, as you can see, the left side menu here essentially explains everything.
Levi Garner: Cogniz, okay, is basically the reasoning layer on top of it.
Levi Garner: So, you can imagine for an engineering work, you're a CTL.
Levi Garner: You would buy this product to understand how your team's actually executing across strategy.
Levi Garner: Strategy is very important.
Levi Garner: I don't want to act like it's not.
Levi Garner: Using ClickUp, Jira, those tools are the problem because what the business has always cared about, man, is how are we progressing on our initiatives, right?
Levi Garner: You know, initiatives.
Levi Garner: So, like, we'll have an initiative like SOC 2 Compliance, right?
Levi Garner: Or, you know, LaunchX Portal, right?
Levi Garner: So on and so forth.
Levi Garner: Those are initiatives, right?
Levi Garner: And initiatives will make up epics, stories, so on and so forth.
Levi Garner: So essentially what I've done in this platform is I connected my thesis, which is business doesn't care about Jira, tickets, et cetera.
Levi Garner: What they care about is where are we at on the initiative, how much time has went into the initiative, et cetera.
Levi Garner: So what I've done is I've essentially built an execution graph where I've connected code to those initiatives.
Levi Garner: Because if you think about it from an engineering perspective.
Levi Garner: perspective.
Levi Garner: Everything comes down to commits, right?
Levi Garner: Pull requests, right?
Levi Garner: Meetings, et cetera.
Levi Garner: That's actual work, not the JIRA ticket that the product manager creates that you manually input time on, right?
Levi Garner: So you connect basically your GitHub, okay?
Levi Garner: So you would connect, for example, you can see I'm connected to GitHub here.
Levi Garner: And then I sync everything.
Levi Garner: I sync your commits, your PRs, your releases, your delivery, you know, deploying to production.
Levi Garner: You can see I've connected.
Levi Garner: This is, I'm actually using IntelliJ for IntelliJ, okay?
Levi Garner: Connect your repos.
Levi Garner: This is kind of standard, just so you know, engineering intelligence, right?
Levi Garner: Like commits, PRs opened, engagement, thorough put, how many PRs have been created, how many have been merged, what's our merge rate, that's all analytics.
Levi Garner: Analytics are dead, right?
Levi Garner: But why are they dead?
Levi Garner: Because they don't give intelligence, right?
Levi Garner: And that's essentially what Cogniz does, okay?
Levi Garner: I can literally come in here, man, and ask anything about the engineering work.
Levi Garner: Summarize my meetings from yesterday, right?
Levi Garner: What was talked about?
Levi Garner: Imagine I'm a CEO, right?
Levi Garner: Intelligence is connected to all your meetings.
Levi Garner: It's connected to your daily stand-ups, your architecture assessments, et cetera.
Levi Garner: You just ask the question, and you can see I had three meetings yesterday.
Levi Garner: I had a sales call, sprint planning, and then another kind of sales call.
Levi Garner: Oh, okay, so I had three action items.
Levi Garner: What were the action items?
Levi Garner: But what's really cool with this, man, is what Cogniz does is it connects not just code, but also meetings.
Levi Garner: So I could ask questions like, okay, what was talked about in the stand-up today?
Levi Garner: Okay, that was decided.
Levi Garner: Okay, well, were there any commits pushed related to it today?
Levi Garner: Did we progress on it?
Levi Garner: I'll give you a perfect example of that.
Levi Garner: I actually have one.
Levi Garner: So you come in here, you can ask any question.
Levi Garner: can ask any question about strategy, code, meetings.
Levi Garner: I call them knowledge meetings because it's not just meetings.
Levi Garner: I mean, you could upload, you could connect, you know, your chats, whatever, whatever it is.
Levi Garner: So I'll say, what is the progress of our initiatives this quarter?
Levi Garner: Cogniz will lay that out for us.
Levi Garner: I'm doing a bunch.
Levi Garner: I'm doing, I'm building a harness.
Levi Garner: I'm revamped, I revamped Cogniz, this is Cogniz's, this is Cogniz that I'm showing you right now, the reasoning engine.
Levi Garner: I'm completely revamping its harness.
Levi Garner: That's one of my main initiatives.
Levi Garner: Sock 2, readiness, healthcare,  , you know, security-wise.
Levi Garner: Building it, I had to build a Teams integration for them.
Levi Garner: I'm built, I'll talk about agents here in a moment.
Levi Garner: I built a ton of agents because when you build these systems, man, data is extremely critical, right?
Levi Garner: Like data is everything.
Levi Garner: Data has got to be clean.
Levi Garner: So I built like 20-some agents to just constantly analyze the data, clean the data up, attach this, commit to this initiative, not just based off of an event like listening to a webhook.
Levi Garner: Autonomous intelligence.
Levi Garner: That's my end goal.
Levi Garner: Autonomous intelligence.
Levi Garner: Talk about that later.
Levi Garner: then initiative discovery engine.
Levi Garner: So then I can come in here and be like, okay, well, what meetings were covering these initiatives yesterday?
Levi Garner: And a lot of this is already just, the CTO doesn't even necessarily have to come in here and ask these questions.
Levi Garner: I've got agents that send them all this daily.
Levi Garner: I'm just kind of summer.
Levi Garner: I'm just giving you an example.
Levi Garner: So it's going to summarize those meetings.
Levi Garner: And then I.
Levi Garner: could cross-connect those meetings to the actual commits of what took place.
Levi Garner: Does that give you some context, man?
Levi Garner: But it's not just that.
Levi Garner: mean, it connects strategy, code, your meeting sources.
Levi Garner: So I suck in all of the meeting sources into the platform.
Levi Garner: And then also finance.
Levi Garner: Finance is one that I think is – and this is one of my main – one of the main value props.
Levi Garner: For these companies is to get an ROI on their engineers.
Levi Garner: So you can see here – and this example, kind of like I was mentioning before, you know, this guy's an outsourced engineer, Ravi.
Levi Garner: He's making $38,000 a year.
Levi Garner: He's actually the best return on investment for this organization from both a commit standpoint, quality, leveraging AI, et cetera.
Levi Garner: And then, you know, they're paying this dude $240,000, he's senior, et cetera.
Levi Garner: Of course, he's giving other things that are not just output, right?
Levi Garner: Not just output.
Levi Garner: But again, man, I think in the agentic era, that's my thesis as a whole, dude.
Levi Garner: I think if you're an engineer and you're not committing, if you're not pushing code daily, if you're not pushing code, then what the hell did you do today?
Levi Garner: That's always been my thesis.
Levi Garner: As a CTO, if you're not pushing code, what the hell are you doing?
Levi Garner: And that's why I built this, for example, stand-ups.
Levi Garner: know, stand-ups, the product manager will pull up the JIRA board.
Levi Garner: What did you work on?
Levi Garner: What did you work on?
Levi Garner: It's all  unless you've committed code.
Levi Garner: And that's why I built, for example, the stand-up feature.
Levi Garner: This is an agent that runs daily.
Levi Garner: CTO opens up the board or the project manager, whoever, VP.
Levi Garner: ability...
Levi Garner: So, So, um
Levi Garner: And it basically just gives a summary of what the engineer did that day.
Levi Garner: can see this is IntelliJ for IntelliJ.
Levi Garner: Yesterday, I pushed 33 commits, opened 7 PRs, 2 were merged.
Levi Garner: You can see all of the commits I worked on, 69, and then my pull request, right?
Levi Garner: And then it gives us a narrative of what I worked on yesterday.
Levi Garner: But does it make sense to you, dude?
Levi Garner: It's fun showing this to engineers like yourself because you get it, because you've worked in, you know, companies where you're using JIRA.
Levi Garner: And this type of system is what's going to replace all of that.
Levi Garner: I mean, every single AI-first org is going to be on this in the next.
Levi Garner: It's going to go.
Levi Garner: It's going viral, Every AI-first org.
Levi Garner: You can imagine all the YC companies, et cetera.
Levi Garner: They want something like this because, and I didn't even get into all the features.
Levi Garner: They want something like this, man, because we're moving too far.
Levi Garner: Fast, dude.
Levi Garner: Like, I don't, no one has time to update tickets, right?
Levi Garner: Like, I'm myself working so fast and creating new initiatives every day as I build.
Levi Garner: And I didn't show you this feature, but there's an initiative discovery feature.
Levi Garner: Let me show you that real quick.
Levi Garner: There's an initiative discovery feature that basically analyzes your meetings, okay?
Levi Garner: It analyzes your meetings and it analyzes your code base.
Levi Garner: And it actually discovers what initiatives you should be creating.
Levi Garner: Like, this is a perfect one, man.
Levi Garner: Cogniz tool expansion.
Levi Garner: I should definitely promote that to an initiative.
Levi Garner: I've kicked that off.
Levi Garner: Basically, what I'm doing is I'm creating a tool suite.
Levi Garner: Well, I won't even get into harness engineering.
Levi Garner: It's a longer discussion.
Levi Garner: If you're interested, we can talk about it sometime.
Levi Garner: Basically, what harness engineering is.
Levi Garner: It's an important concept, dude.
Levi Garner: Like, because I'm telling you that building these, this is called a React, not React front end,
Levi Garner: This is a reasoning loop, okay?
Levi Garner: So it reasons, and then it takes action based off what it has available to it.
Levi Garner: And that tool suite is what I was talking about.
Levi Garner: So the tool suite is basically what are all the commands I can execute, what are all the queries I have available to me to execute, right?
Levi Garner: Can I search the web?
Levi Garner: I just added that feature in here, actually.
Levi Garner: Can I search the web for information?
Levi Garner: Those are all your different tools that you have available, just like with Claude Code, right?
Levi Garner: Claude Code is nothing more than a harness, okay, with the large language models.
Levi Garner: So it can execute bash commands.
Levi Garner: It can search the web.
Levi Garner: Those are all its available tool sets, right?
Levi Garner: And they call that essentially the harness.
Levi Garner: I've got a good, actually, image to represent that for you.
Levi Garner: But this is the future, man.
Levi Garner: At least a
Levi Garner: Building everything agentic.
Levi Garner: Think of the large language model basically being the brain.
Levi Garner: The user is going to give some input.
Levi Garner: And then from there, you have to build everything around it.
Levi Garner: And that's essentially the harness, like managing memory, what tools it has available to it, what orchestration engine, how it basically, the thread essentially is what you can.
Levi Garner: You can, you can think of.
Levi Garner: So that's the app, man.
Levi Garner: That's the app.
Levi Garner: Definitely not HR.
Levi Garner: It's got HR, some HR functionality in it, like return on investment.
Levi Garner: But it's actually, I'm like, I'm very objective.
Levi Garner: You know, I'm very objective.
Levi Garner: And that's where this system roots out those that are weak contributors, high cost, non-producing.
Levi Garner: It's not based off feelings.
Levi Garner: You know what I mean?
Levi Garner: If that makes sense.
Levi Garner: Dude, and I'm telling you, the company I was a CTO of, okay?
Levi Garner: I was a CTO of multiple companies within a private equity firm.
Levi Garner: They did mass layoffs.
Levi Garner: A lot of these layoffs, dude, just so you know, a lot of these U.S.
Levi Garner: companies were in, and I'm not saying in your context.
Levi Garner: I'm talking about most other companies.
Levi Garner: You were probably one of the ones they definitely should have kept.
Levi Garner: A lot of these U.S.
Levi Garner: companies were extremely inefficient before AI, right?
Levi Garner: They were inefficient before AI.
Levi Garner: And all AI is to them is an excuse to the board to say, hey, we've gotten more efficient.
Levi Garner: So they're laying people off so that the board thinks that the management and leaders are AI-enabled.
Levi Garner: You know, it's just a talking point.
Levi Garner: A perfect example, the private equity company I was working for, they literally laid off all of the best.
Levi Garner: Contributors, okay, and kept, like, the senior ones that weren't doing .
Levi Garner: It was, like, comical.
Levi Garner: You know what I mean?
Levi Garner: Because they weren't using a tool like IntelliJ to say, no, Abhishek is the dude you gotta keep, right?
Levi Garner: He's the high-value contributor.
Levi Garner: He knows the code base, right?
Levi Garner: So that's why I built IntelliJ, man, to ultimately replace myself or assist myself if I take over a new engineering org.
Levi Garner: I could be sitting on a beach drinking a martini,  a martini, maybe a whiskey sour, chilling, and log into my laptop and see what my team's worked on today and not have to go through JIRA, not have to log in to Fathom and look at the transcript.
Levi Garner: It's all just right there.
Levi Garner: What did my team execute on?
Levi Garner: So, I know I went on, I gave you my sales pitch there, but...
Levi Garner: it.
Levi Garner: So,
Levi Garner: What's your thoughts on the app, man?
Abhishek Bhatta: This is actually an awesome product that you're working.
Levi Garner: Thanks.
Abhishek Bhatta: like during my layoff also, like our company was more, initially it was more Nepal-based and fewer team members were there in the U.S., but later it seemed like even, like they were not contributing, but they were with the team in their local time zone, right?
Abhishek Bhatta: So that's why that gave them the confidence, but really, like the developers here in Nepal were working their  off, and I felt like they were more talented and they know the code more better because they had been working for a long time, but yeah, they had to get laid off.
Abhishek Bhatta: What company was it, by the way?
Levi Garner: I'll check it out real quick.
Levi Garner: What was the name of the product?
Abhishek Bhatta: It was Fluid, Fluid.Ink, if you check it, sir.
Abhishek Bhatta: It's an e-commerce platform for the affiliate marketing.
Abhishek Bhatta: So it's FluidCommerce.co.uk?
Levi Garner: Yeah.
Abhishek Bhatta: hold on.
Abhishek Bhatta: No, not that one.
Abhishek Bhatta: Fluid.app, yeah.
Abhishek Bhatta: The third one, Fluid.app.
Levi Garner: This one here, Erika.
Levi Garner: Yeah.
Abhishek Bhatta: It's an amazing product, actually.
Abhishek Bhatta: Like, a lot of businesses are...
Abhishek Bhatta: It's a SaaS product.
Abhishek Bhatta: Lots of businesses are being served by this.
Abhishek Bhatta: How many devs did you guys have on this product?
Levi Garner: Yeah.
Abhishek Bhatta: In Nepal, we had around 20 to 25 devs.
Abhishek Bhatta: And in U.S., like...
Abhishek Bhatta: It was around, yeah, it was similar, 20-25 decks.
Levi Garner: So a pretty big team, right?
Levi Garner: Pretty big.
Abhishek Bhatta: They cut up with most of the Nepal's team, and even from the US, like, they cut up a few of the seniors that they were paying the most, and just minimized their team.
Levi Garner: Interesting.
Levi Garner: What was this app built on?
Levi Garner: Ruby on Rails, you said?
Levi Garner: Yeah, yeah.
Levi Garner: And then the front end was, what was the front end built on?
Abhishek Bhatta: Um, front end was, um, so initially it was monolith, but later we transformed it into React.
Levi Garner: All right, nice, nice, that's cool.
Levi Garner: It's pretty clean.
Levi Garner: Yeah, it is clean.
Abhishek Bhatta: So the project that you're working, so you're working alone or do you have already the team set up for it?
Levi Garner: Oh, it is.
Levi Garner: It's pretty all solo, man.
Levi Garner: I know.
Levi Garner: I'll say this.
Levi Garner: I built 90, more than 95% of it.
Levi Garner: The thing is, man, like over the years, like the engineers I've worked with, like they became like the company I started in India, right?
Levi Garner: The people I worked with, they just became like family.
Levi Garner: You know what I mean?
Levi Garner: Like, you know how like turnover in India is high?
Levi Garner: None of my developers left.
Levi Garner: Like every single one stayed with me, all 20.
Levi Garner: Some of them, some of them did leave.
Levi Garner: Some of them did leave.
Levi Garner: Some of them came back, but like the core group was with me.
Levi Garner: Right?
Levi Garner: Till the end.
Levi Garner: Until I left that private equity firm.
Levi Garner: So, kind of like you.
Levi Garner: You know what I mean?
Levi Garner: Like, I bring in some of them, right?
Levi Garner: Because they're just so curious what I'm working on.
Levi Garner: I'll be like, this is what I'm working on.
Levi Garner: I'll show them.
Levi Garner: I'll bring them into the code base and they'll just be like, Levi, is there any way I can work on this a little bit with you?
Levi Garner: You know what I mean?
Levi Garner: And I'll let them come in and work on stuff.
Levi Garner: So, I've built 95% of the app or more.
Levi Garner: You know what I mean?
Levi Garner: I've built pretty much all of it myself, just with Claude and Codex.
Levi Garner: And then I've got a really good agentic framework I use, man.
Levi Garner: Like, I build basically, I've got a repo set up specifically, you can imagine, called like IntelliG slash product.
Levi Garner: And then I have this features folder under it.
Levi Garner: For every single one of my features, I have, like, a work item folder, an architecture folder.
Levi Garner: And I basically just build out these specs.
Levi Garner: They're these markdowns.
Levi Garner: Files of like vision.md for each product or for each work item that I have, architecture.md, these clean specs, and then I just execute them myself.
Levi Garner: You know what I mean?
Levi Garner: That's kind of my agentic workflow.
Levi Garner: It works really, really well for teams.
Levi Garner: Like product managers are going to have to move to the code base because the code base is the source of truth, right?
Levi Garner: Like how can you create a project requirements document, a PRD, if you're not in the code base, right?
Levi Garner: Because you don't really know what the feature does.
Levi Garner: Like a product manager will try to create documentation or work with, you know, a content person on the application, and it doesn't do the thing that they think that it does.
Levi Garner: The code tells the source of truth.
Levi Garner: That's what I'm saying.
Levi Garner: Like everyone, including PMs, is going to have to move to the code base, or I think PMs will just be eliminated.
Levi Garner: Project manager.
Levi Garner: product managers, engineering managers, all of them gone.
Levi Garner: You know what I mean?
Levi Garner: They're all gone.
Levi Garner: All we're going to have is basically, I think the new title is engineering or agentic orchestrator.
Levi Garner: I consider myself an agentic, I consider myself an architectural agentic orchestrator.
Levi Garner: I'm just architecting the applications with agents and then orchestrating them to build it out.
Levi Garner: You know what I mean?
Levi Garner: I mean, dude, actually, I'll show you another product.
Levi Garner: I launched this product, dude.
Levi Garner: You can download this one just for fun, okay?
Levi Garner: I created this product.
Levi Garner: It's called Tree Inventory AI.
Levi Garner: In two weeks, I was like, I want to launch a brand new product, get it into the mobile, or get it into the app in Google Play Store, and get 20 users in less than a month, okay?
Levi Garner: I did this while I was on a vacation, dude.
Levi Garner: A vacation, okay?
Levi Garner: I did this in two weeks.
Levi Garner: And this is the app.
Levi Garner: It's a cool app.
Levi Garner: So basically, like, you basically take pictures of your, let me show you this one.
Levi Garner: In the U.S., we have this industry called field service.
Levi Garner: I don't know if you've ever heard of it, but like service-based companies are very, very popular in the U.S., right?
Levi Garner: You may have heard of this, like cleaning companies, right?
Levi Garner: They come to your house, they clean.
Levi Garner: Tree companies come to your house and, like, take care of your landscape.
Levi Garner: That's kind of what this app is for.
Levi Garner: So you basically, like, take pictures of the tree, automatically detects it, gives recommendations for it, and .
Levi Garner: So anyways, man, that's just an example.
Levi Garner: I launched that app in two weeks.
Levi Garner: Download it, dude.
Levi Garner: If you're outside and , seriously, download this app.
Levi Garner: It's completely free.
Levi Garner: Get it on Google Play.
Levi Garner: I'll send you the link.
Levi Garner: And just go outside your house, add your address, and then start taking pictures.
Levi Garner: It'll tell you what the truth
Levi Garner: What's wrong with it?
Levi Garner: This is an example.
Levi Garner: To be honest, this is my baby, though.
Levi Garner: I'm trying to take this thing to YC.
Levi Garner: You know what I mean?
Levi Garner: I'm trying to go big.
Levi Garner: This thing's got massive potential.
Levi Garner: I'm putting most of my effort in this, but I wanted to try out my framework, okay?
Levi Garner: Because like I said, it's a framework, how I build these apps very, very fast by myself.
Levi Garner: I wanted to prove it.
Levi Garner: And I website everything.
Levi Garner: I do everything with Quad.
Levi Garner: and, uh, and, uh, and, Kodak.
Abhishek Bhatta: So, uh, can I get that app in the app store as well?
Abhishek Bhatta: Oh, there's, there it is.
Levi Garner: Yeah, dude.
Levi Garner: Yeah, man, you can download it in.
Levi Garner: I need to do some touch-ups on it.
Levi Garner: The reasoning loop, the reasoning engine in that application is called Arborist, so you can ask it any question.
Levi Garner: I've got a release.
Levi Garner: I'm pushing for it to really, really improve the, uh, and maybe
Levi Garner: And I'd love to take you through sometime how you build these React loops.
Levi Garner: But anyways, I need to improve that one.
Levi Garner: It's called Arborist.
Levi Garner: It's not bad.
Levi Garner: You can ask your questions about the trees and , but I'm going to improve it in the future.
Levi Garner: But I'm just super hyper-focused on IntelliJ right now because it's the market potential.
Levi Garner: You know what I mean?
Levi Garner: For it is the tan, total addressable market is high.
Levi Garner: Out of curiosity, any product-based companies that you could have envisioned using IntelliJ, completely free, dude.
Levi Garner: You know how these product companies work, man.
Levi Garner: It's not necessarily – I'm not – I've got paying customers and , but it's not necessarily about that.
Levi Garner: Like, I can give someone a free 30-day, 60-day, 90-day, and even walk them through onboarding if they're interested in the product, which they need to be.
Levi Garner: You know, they need to be.
Levi Garner: But do you know of any Nepali companies?
Levi Garner: No.
Levi Garner: That are product-based?
Abhishek Bhatta: Yeah, there are plenty of them.
Abhishek Bhatta: So I can talk to some of the people just for trial, right?
Abhishek Bhatta: Yeah, for trial, dude.
Levi Garner: Maybe even if you know some good ones, man, hit me.
Levi Garner: Like, what would be good is if you give me an intro to them.
Levi Garner: You know what I'm saying?
Levi Garner: That always works better.
Levi Garner: Like, you kind of coordinate it to where we all get on a call or something, and I kind of give them a demo.
Levi Garner: You help me land some customers, dude.
Levi Garner: I'll land you jobs.
Levi Garner: Seriously, man.
Levi Garner: I've got connections.
Levi Garner: I'm doing – like I said, man, I talk to these CTOs all the time.
Levi Garner: So you help me out, man.
Levi Garner: I'll help you out.
Levi Garner: You know what I mean?
Levi Garner: For sure.
Abhishek Bhatta: For sure.
Abhishek Bhatta: Okay, I got it.
Abhishek Bhatta: So, like, is there any reason you're trying to sell it in the Nepal first, or are you also looking for I just
Levi Garner: just want users.
Levi Garner: That's it, man.
Levi Garner: You know what I mean?
Levi Garner: I want any tech company that's building product, that's using a project manager.
Levi Garner: And like I said, dude, see, this isn't going to necessarily work per se for Leapfrog.
Levi Garner: Now, it could work for Leapfrog, the companies that Leapfrog is selling, is building product for.
Levi Garner: And maybe that's an interesting point, right?
Levi Garner: It's like, Leapfrog, if you can get this into the hands of your product-based companies, they'll be able to see the return on investment they're getting from you.
Levi Garner: You see what I'm saying?
Levi Garner: Does that make sense?
Levi Garner: Dude, just like you, man, if your company would have been using this product, they would have been able to see, Abhishek is our main dude.
Levi Garner: Let's not get rid of him.
Levi Garner: He's committing the most.
Levi Garner: He's driving the most value, right?
Levi Garner: The thing about it, most of these layoffs are all being...
Levi Garner: Because they don't know who's contributing and who is not, you know what I mean?
Levi Garner: And that's what my tool solves, right?
Levi Garner: That's one of the value props, at least.
Levi Garner: Actually, one of the main ones, to honest.
Levi Garner: Yeah, man.
Abhishek Bhatta: And, like I said, You would say, like, your product is already production-ready, already usable?
Abhishek Bhatta: Yeah, dude.
Levi Garner: 100%.
Levi Garner: If you have GitHub right now, you could sign up for it.
Levi Garner: I don't know if you have any repos.
Levi Garner: Are pushing to?
Levi Garner: Are you pushing to any repos right now?
Levi Garner: Yeah.
Levi Garner: Like, locally, are you building some apps?
Abhishek Bhatta: Yeah, I was experimenting with some of the apps, some of the CLI scripts.
Abhishek Bhatta: Cool.
Levi Garner: Yeah, you could literally sign up for it today, and I could give you a token for free.
Levi Garner: It's 100% production-ready.
Levi Garner: I've got customers on it.
Levi Garner: So, I've got...
Levi Garner: I've got a handful, a handful, and then I'm closing in on, so I've got three AI startups on it.
Levi Garner: I've got one established, two established enterprise companies, and then one that's kind of a mix.
Levi Garner: And then I'm trying to close the deal on multiple venture capital companies right now as we speak.
Levi Garner: But, yeah, man, so it's, it's proofed.
Levi Garner: It's ready to be, ready to be used, man.
Abhishek Bhatta: You have one question in my mind.
Abhishek Bhatta: So we are connecting GitHub, right?
Abhishek Bhatta: The repo?
Levi Garner: Yes.
Abhishek Bhatta: And what are we doing with the meeting notes?
Abhishek Bhatta: We are, are we connecting that also with the Google?
Abhishek Bhatta: Let's just do this, dude.
Levi Garner: Let me sign you up real quick.
Levi Garner: Let me give, do you want to share, like, if you have your laptop open, let's just do it real quick.
Levi Garner: I'll let you onboard.
Levi Garner: I'll give you a free, I'll watch you, and I'll give you a free, a coupon code, so you don't have to pay.
Levi Garner: One second, let me do that.
Abhishek Bhatta: And how is it sync?
Abhishek Bhatta: How are the reports generated?
Abhishek Bhatta: Is it like a daily?
Abhishek Bhatta: Yeah, so we'll do an initial sync.
Levi Garner: You'll choose what history you want to sync, and then we'll sync it, like, you know, 30 days.
Levi Garner: just depends on how many commits.
Levi Garner: So, like, I'll sync around 10,000 commits.
Levi Garner: It's kind of the max.
Levi Garner: So it depends on how large the org is.
Levi Garner: Like, for IntelliJ, I could pretty much sync all the commits from the beginning of time, right, because it's 10,000.
Levi Garner: It's less than 10,000 commits.
Levi Garner: So I'll sync 10,000.
Levi Garner: Listen, commits, and then, you know, whatever it is, and then from there, it's webhooks.
Levi Garner: So we're listening to various events.
Levi Garner: Just one second.
Levi Garner: Yep.
Levi Garner: You can see me.
Levi Garner: You can hear me, man?
Levi Garner: Yeah, yeah.
Levi Garner: All right, cool.
Levi Garner: All right, I'm going to give you your coupon code.
Levi Garner: Just one second.
Levi Garner: So you can share your screen, man.
Levi Garner: Go to IntelliG.ai.
Abhishek Bhatta: Okay, hold on.
Levi Garner: I actually know a dude you should team up with.
Levi Garner: But that's Nepali, man, that I'm helping build a product for.
Levi Garner: You guys should build it together and take it big in Nepal.
Levi Garner: It's a  smart idea.
Levi Garner: He's using IntelliJ, actually.
Levi Garner: I'll tell you the concept here in a minute.
Levi Garner: But you guys should build it together.
Levi Garner: He's a developer that used to work for me, actually.
Abhishek Bhatta: Is he Nepal-based?
Abhishek Bhatta: Yeah, yeah, yeah, dude.
Abhishek Bhatta: His name's Appeal Guru.
Levi Garner: And I met him in Nepal, and I actually got him hired in the private equity firm that I used to work for.
Levi Garner: And when I left, the private equity company let him go, which, again, was stupid.
Abhishek Bhatta: Okay, can you, like, say the name again?
Abhishek Bhatta: His name is Appeal.
Levi Garner: Yeah, type it in.
Levi Garner: Appeal Guru.
Levi Garner: Yeah, Guru.
Abhishek Bhatta: Do you recognize him?
Levi Garner: Yeah, the top one.
Levi Garner: That's him.
Levi Garner: Oh, him.
Abhishek Bhatta: Okay.
Abhishek Bhatta: Oh, is he also working with you in the same, Intel is, like, the same product?
Levi Garner: So, he worked, um, no, no, he doesn't work there, Matt.
Levi Garner: He doesn't work there.
Levi Garner: He, uh, he, one second, I'll setting this code up for you, man.
Levi Garner: Thank you.
Levi Garner: Metadata, okay, planetize, digitize, you got it.
Levi Garner: All right, I'm hooking you up, one second.
Levi Garner: Got you.
Levi Garner: All right, cool, man.
Levi Garner: You go to IntelliJ.ai now.
Levi Garner: So, basically, kind of what I did with him is I actually set him up to use IntelliJ to help build his product.
Levi Garner: Okay, and I'll show you kind of how you can do that because we kind of organized it.
Levi Garner: And then I kind of gave him my framework to build the product he's going to be building and selling in India and Nepal.
Levi Garner: I'll explain it to you once you go through it.
Levi Garner: right, so go to IntelliJ.ai real quick.
Levi Garner: right, do sign up with GitHub, and then you'll authorize there.
Levi Garner: Perfect.
Levi Garner: Now, click, unlock, and activate enterprise.
Levi Garner: And then this is your coupon code.
Levi Garner: I'll just put it in the chat here.
Levi Garner: Just copy that.
Levi Garner: Well, jump back because you don't have to pay for it, dude.
Levi Garner: Jump back.
Levi Garner: Hit, uh, have an activation code at the bottom.
Levi Garner: See that for have an activation code?
Levi Garner: Yeah.
Levi Garner: Paste in what I sent you.
Levi Garner: It's, it's, yeah, I sent it to you in chat.
Levi Garner: It's capital A-B-H-I-S-H-E-K.
Levi Garner: I think I spelled your name right, right?
Levi Garner: A-B-I-S-H Yeah.
Levi Garner: Done.
Levi Garner: So then click activate enterprise.
Levi Garner: And then install GitHub app, right there.
Levi Garner: So yeah, connect GitHub.
Levi Garner: And you're logged into GitHub here.
Levi Garner: It'll come up if you are.
Abhishek Bhatta: No.
Levi Garner: Oh, is it asking you to, uh, to enter?
Abhishek Bhatta: my mobile phone, I have this MFA.
Levi Garner: All right.
Levi Garner: Is that your repo?
Levi Garner: Yeah.
Abhishek Bhatta: So it was a repo that I was experimenting with recently.
Abhishek Bhatta: Cool.
Levi Garner: So now what it's doing is basically just analyzing your commit volume.
Levi Garner: Just give it a second, and then it'll allow us to continue.
Levi Garner: Actually, just, yeah, perfect.
Levi Garner: So I don't think you have much, right?
Levi Garner: Just seven commits.
Levi Garner: Yeah, perfect.
Levi Garner: So then just hit continue on there.
Levi Garner: So then now it's going to sync all of your data, right?
Levi Garner: And you're inside IntelliJ.
Abhishek Bhatta: Okay.
Abhishek Bhatta: Yeah, well.
Abhishek Bhatta: This is the main dashboard, right?
Abhishek Bhatta: Yeah, this is the main dashboard, exactly.
Levi Garner: So what you could basically do from here, like if you had real data, Cogniz, you could start asking questions.
Levi Garner: If you go to strategy, real quick, man, this is where I helped my buddy, okay?
Levi Garner: And he had a vision, like he wanted, he's basically going to be creating, and don't steal this idea, okay, if I tell you.
Levi Garner: But he's creating a market, all right, he's creating a marketplace for plants in Nepal, okay?
Levi Garner: So I helped him create his initiatives, his vision, what it's going to take for him to get there.
Levi Garner: Now, what's really cool with this, dude, like let's, what product idea do you have?
Levi Garner: Let's just  build it, dude.
Levi Garner: It's easy to build.
Levi Garner: Let's just build an app.
Levi Garner: We'll just build one.
Levi Garner: I'll help you take it to market.
Levi Garner: What do you want to build?
Levi Garner: Like what could make you money?
Levi Garner: What, what is the need in.
Levi Garner: Nepal, right now, do you feel?
Levi Garner: What's missing?
Levi Garner: Or India?
Abhishek Bhatta: Okay, for example?
Levi Garner: Dude, I've got one for you to build.
Levi Garner: driver, like cleaning.
Levi Garner: Like, dude, what about an app to get our clothes washed?
Levi Garner: So, you know how, like, there's tons of laundry services around, right?
Levi Garner: You just log into this app.
Levi Garner: It shows all the different vendors that could wash your clothes, right?
Levi Garner: You know what I'm saying?
Levi Garner: You can contact them.
Levi Garner: I don't know, some  like that.
Levi Garner: Tell me an idea you have.
Levi Garner: What do you have?
Abhishek Bhatta: Yeah, let's go with that idea.
Abhishek Bhatta: like that idea.
Abhishek Bhatta: Just for the trial, right?
Levi Garner: Just for .
Levi Garner: Okay, so what's really cool with this is you would never create any of this manually.
Levi Garner: Okay, so what I would actually do is if you go down to Agent, see Agent down there?
Levi Garner: Yeah.
Levi Garner: You would go to API keys.
Levi Garner: There.
Levi Garner: So you'll generate an API key here, create your first API key, select all on those, and then let's just call it Claude, yeah, and then create it, call it like Claude or something, whatever you want to call the name of it.
Levi Garner: Planar?
Levi Garner: Asian, maybe?
Abhishek Bhatta: Right?
Abhishek Bhatta: No, just call it Claude.
Levi Garner: Either way, it doesn't matter.
Levi Garner: Copy that key, okay?
Abhishek Bhatta: Yeah.
Levi Garner: Just hit the key right there.
Levi Garner: Hit the actions icon.
Levi Garner: In the far right.
Levi Garner: Hit rotate.
Levi Garner: Yeah, hit rotate key.
Levi Garner: Hit copy there.
Levi Garner: Perfect, man.
Levi Garner: Now open up whatever IDE you have.
Levi Garner: Do you have like Claude or, yeah, like you were using anti-gravity, right?
Abhishek Bhatta: Yes.
Abhishek Bhatta: Yeah, I do have cursor as well.
Levi Garner: And what we're going to do?
Abhishek Bhatta: Okay, maybe I can set up a new project for cleaner service.
Abhishek Bhatta: Exactly.
Levi Garner: Now, do it all with Quad.
Levi Garner: Create a new repo with Quad.
Levi Garner: Like, let's make it a mono repo.
Levi Garner: Make it a Next.js.
Levi Garner: Let's do this.
Levi Garner: And do it.
Abhishek Bhatta: Can you show me your screen real quick?
Levi Garner: Oh, sorry.
Levi Garner: No, no, you're good.
Levi Garner: I can see the, I can only see IntelliJ, basically.
Abhishek Bhatta: Hold on, let me share you my old screen.
Abhishek Bhatta: I was working in the terminal, sorry.
Abhishek Bhatta: Okay.
Abhishek Bhatta: Do you see it?
Abhishek Bhatta: Okay, so let's you claw dangerously skip permissions.
Levi Garner: That's my favorite, man.
Levi Garner: That's my favorite command.
Levi Garner: Do this one.
Levi Garner: right.
Levi Garner: Yeah, perfect.
Levi Garner: I'll send it to you.
Levi Garner: Or Codex.
Levi Garner: Codex is perfect.
Levi Garner: Either one.
Levi Garner: Codex YOLO.
Abhishek Bhatta: Yeah.
Abhishek Bhatta: Yeah.
Abhishek Bhatta: All right.
Levi Garner: Perfect.
Levi Garner: Yes.
Levi Garner: Continue there.
Levi Garner: Perfect.
Levi Garner: All right.
Levi Garner: Do you have FreeFlow by chance?
Levi Garner: Or like OpenWhisper or anything like that?
Levi Garner: You can just talk to it.
Levi Garner: I love those, man.
Levi Garner: Makes it so easy.
Levi Garner: FreeFlow?
Levi Garner: I haven't tried that.
Abhishek Bhatta: FreeFlow or what?
Abhishek Bhatta: What was that other name?
Levi Garner: Yeah.
Levi Garner: Go to GitHub real quick.
Levi Garner: Yeah, it's that one.
Levi Garner: It's just really nice because you can just push FN.
Levi Garner: you.
Levi Garner: If you're a Mac, yeah, you can just talk to it.
Levi Garner: You know what I mean?
Levi Garner: Just talk to it.
Levi Garner: It's nice.
Levi Garner: It's kind of like Open Whisper.
Levi Garner: Have you heard of Open Whisper?
Levi Garner: I never type anything anymore.
Levi Garner: I just talk to it.
Levi Garner: You know what I mean?
Levi Garner: And it automatically translates it.
Levi Garner: You can set it up later.
Levi Garner: It's nice, man.
Levi Garner: So let's just prompt Claude to basically, let's come up with a better name here.
Levi Garner: All let's just talk about this real quick.
Levi Garner: Actually, let me just do this real quick.
Levi Garner: Go back.
Levi Garner: I'm going to end this call.
Levi Garner: And then actually what we're going to do, man, this is perfect, actually.
Levi Garner: Go to Fathom real quick.
Levi Garner: Let's set you up a Fathom integration for free because then this will automatically sync into your repo.
Levi Garner: Yeah, type in Fathom AI Notetaker.
Levi Garner: Yeah, so click on that.
Levi Garner: Yeah, click that one real quick.
Abhishek Bhatta: I should sign up for free, right?
Abhishek Bhatta: Yep.
Levi Garner: Continue with Google.
Abhishek Bhatta: For note-taking, I used to use this granular before I haven't tried this one.
Levi Garner: Connect to perfect calendar.
Levi Garner: Do you want to connect to calendar?
Levi Garner: I don't know.
Levi Garner: It doesn't matter.
Levi Garner: Whatever's cool.
Levi Garner: Just click through on that.
Levi Garner: It doesn't matter.
Levi Garner: Does it allow you to open it now?
Abhishek Bhatta: Yeah, I think I need to connect it first.
Abhishek Bhatta: Okay.
Levi Garner: And two, we'll do, so basically what we're going to do is, I don't know if we'll call it clean or whatever, what we're going to do.
Levi Garner: I'm going to send you these standards.
Levi Garner: We're going to have it pull these into your repo to build it out.
Levi Garner: And then what we'll do is we'll feed it the transcript of what we've talked about.
Levi Garner: So very important codex.
Levi Garner: What we're basically going to be doing is help us come up with a really cool name for this product that he's going to build using IntelliJ.
Levi Garner: Right.
Levi Garner: So we're going to call it something with cleaning, but it's basically going to be like a cleaning marketplace for Nepal.
Levi Garner: So all these small, you know, you know, DDs that do washing service, et cetera, they can come to this app and, you know, post their service.
Levi Garner: Or if you're a foreigner coming here, you can basically, you know, go to this app to request to get your clothes clean, pick up, drop off, all that kind of.
Levi Garner: Okay.
Levi Garner: Help us come up with the name of it.
Levi Garner: Okay.
Levi Garner: Then you're going to help us create.
Levi Garner: He's already got the repo, but we'll rename the repo.
Levi Garner: And then additionally, I'm sending him my engineering standards that we're going to use to build the app out.
Levi Garner: CQRS, clean, multi-tenancy, rule-level security, RLS.
Levi Garner: We could probably use, I would say, a monorepo next with React.
Levi Garner: Also, you need to set up in the repo a, whatever the name of this is, that we want a product section.
Levi Garner: Okay.
Levi Garner: And what we're going to do is within the product section, every single feature that you essentially build out, we're going to have a folder within that.
Levi Garner: And then those subfolders that you create, you're going to follow like a PRD, ARC, MD, spec, and so on and so forth.
Levi Garner: You can check out IntelliG signals for that.
Levi Garner: Web search for, actually, no, it's not public.
Levi Garner: Anyways, I'll send a screenshot for him to give you that.
Levi Garner: And then I'm going to give all the engineering standards.
Levi Garner: You can have an engineering standards folder in there.
Levi Garner: And then also set up an AgentsMD or something.
Levi Garner: So every single time Abhishek creates a new session with you, it automatically pulls those standards in and you build this thing super, super clean.
Levi Garner: Okay.
Levi Garner: Perfect, man.
Levi Garner: I just had to say all that  because then all, literally, that's the whole purpose of IntelliJ.
Levi Garner: After you, if you would have Fathom set up with here, it would automatically pull that in, push that into your repo.
Levi Garner: And then you could just link, you could say, go check this transcript.
Levi Garner: Help me come up with my Agents and execute on all this .
Levi Garner: You see what I mean?
Levi Garner: That's the whole purpose of it.
Levi Garner: All right.
Levi Garner: Continue on that, man.
Levi Garner: They've made this setup.
Levi Garner: On this, so , now, don't know, it's like, you can just, yeah, whatever, other, whatever, yeah.
Abhishek Bhatta: Right, well, check wires, connection with the Zoom.
Abhishek Bhatta: Eh, what's wrong?
Abhishek Bhatta: Oh, okay, wait a minute.
Abhishek Bhatta: I'll be right back, man.
Abhishek Bhatta: Let's go.
Abhishek Bhatta: Okay, okay.
Abhishek Bhatta: I think it's all set.
Abhishek Bhatta: So, we need only transcript now until we set it for video and audio.
Abhishek Bhatta: Yeah, give it, I would give it all, video and audio is cool.
Levi Garner: Yeah, video and audio is good, yeah.
Levi Garner: And what I'm doing too, man, I think you should build this app.
Levi Garner: Use, I'm getting, I'm building the standards out to send you right now.
Levi Garner: I think we're going to make it, I think you should do React, front-end, Next, again, the reason I like Next, and I didn't build, IntelliJ, just so you know, it's Java on the back end, Java Spring Boot.
Levi Garner: I don't recommend that for this app.
Levi Garner: You're going to get maximum cost savings, dude.
Levi Garner: It's going to be basically free if you use, this is your stat, on the back end, Versal with, um, Versal with Soupbase for your database.
Levi Garner: And Soupbase is going to handle all your authentication.
Levi Garner: It makes it extremely easy, dude.
Levi Garner: It's, it's basically free to build, okay?
Levi Garner: So Versal that, and then Next, JS on the back end with React on the front end.
Levi Garner: Makes it super, super easy.
Levi Garner: I'm going to send you my standards.
Levi Garner: basically what we'll do is, and then two, what we're going to do next.
Levi Garner: Okay.
Levi Garner: So Codex, this is very important for you.
Levi Garner: Okay.
Levi Garner: You're going to help him build out his intelligies, initiatives, his vision, and we're going to hand you the playbook for this.
Levi Garner: So we're going to build out his vision, his initiatives.
Levi Garner: What do we have to do to bring this product to market?
Levi Garner: Okay.
Levi Garner: To bring this product to market.
Levi Garner: What are the big themes, you know, to hold these initiatives, right?
Levi Garner: What are the major initiatives to get it to market?
Levi Garner: Like I'm, I'm probably thinking something like, you know, yeah, we'll, we'll iterate with you on those initiatives to build this out.
Levi Garner: Um, so anyways, man, so we'll end this call.
Levi Garner: I'm going to give you, cause now the next time we'll rejoin the call again.
Levi Garner: And you'll have, you'll bring your recorder in, okay?
Levi Garner: Because actually, go to your GitHub right now.
Levi Garner: Check this out.
Levi Garner: Check us out.
Levi Garner: Go to your GitHub real quick.
Levi Garner: I'll show you this.
Levi Garner: So, yeah, go to your repos.
Levi Garner: Well, yeah, go to your repos.
Levi Garner: If you click, I think your name.
Abhishek Bhatta: Yeah.
Abhishek Bhatta: one?
Abhishek Bhatta: Yeah, just all of your repos.
Levi Garner: Click, obviously, because I've already, I cloned your repo into here whenever you signed up for, yeah, IntelliJ.
Levi Garner: you should have one of, you should have the, and the, and the, the of the of and the If you jump back to IntelliJ real quick.
Levi Garner: Yeah, IntelliJ, the one right there.
Levi Garner: Perfect.
Levi Garner: So if you go to strategy, we'll have to connect your Fathom.
Levi Garner: Sorry, go to knowledge.
Levi Garner: Go to signal.
Levi Garner: Yeah, we'll connect that.
Levi Garner: The signal here.
Levi Garner: So it's going to automatically sync all of your meetings into that repo for you.
Levi Garner: So we'll have Codex clone your IntelliJ signals into that.
Levi Garner: Basically, it won't be necessarily a monorepo codex.
Levi Garner: His core product will be the monorepo, but open up a workspace with IntelliJ signals into it so he can easily bring in those meetings that he has with me or any other stakeholders into the repo, right?
Levi Garner: Okay.
Levi Garner: So perfect.
Levi Garner: So go to integrations there real quick.
Abhishek Bhatta: So is it only about the mating nodes, or maybe the other sources, like Ziraq, hiccups, so everything is dumped into the repo?
Abhishek Bhatta: So what was your question again, Ren, sorry?
Abhishek Bhatta: Yeah, so you mean like all the nodes coming from the Fathom, it's dumped into that repo, right?
Abhishek Bhatta: Inside that?
Levi Garner: Yes, yes, exactly.
Abhishek Bhatta: So signals is basically our knowledge base, right?
Abhishek Bhatta: So where every source of information is dumped into?
Abhishek Bhatta: Not just the nodes?
Levi Garner: essentially.
Levi Garner: So yeah, and there's other signals I push as well, like all of your initiatives, etc.
Levi Garner: We can push those down into the repo so that the agent has context.
Levi Garner: We can also set it up with a hook that we'll do with codex, so it just...
Levi Garner: immediately calls the API that pulls in your initiatives.
Levi Garner: I'll set all that up.
Levi Garner: It'll all be easily set up.
Levi Garner: But that's what we'll build out with Codex is we'll build this repo structure so it's very, very clean to pull in these engineering standards, pull in your context.
Levi Garner: I mean, if you think about it, dude, there's been three eras of agentic engineering.
Levi Garner: The first was prompt engineering, right?
Levi Garner: The second one was context engineering, which is basically kind of what we're doing right now with Codex.
Levi Garner: Like, if you just open up Codex and you start coding with it, it's not going to know that you should build this with CQRS, DDD, et cetera, right?
Levi Garner: And now, what do I mean by CQRS and DDD?
Levi Garner: Let me just share my screen real quick.
Levi Garner: Okay, I just want to show you this, dude, because this is how we're going to build your backend out, all right?
Levi Garner: So this is my application.
Levi Garner: Well, I've got a bunch of work trees in here.
Levi Garner: It's a little bit messy right now.
Levi Garner: But...
Levi Garner: Just follow me on these.
Levi Garner: I have – now, for Tree Inventory AI, I didn't do it this way, okay?
Levi Garner: I created a true mono repo.
Levi Garner: But I think for bigger organizations, I don't mind – I've worked with one technical lead architect.
Levi Garner: He's, like, a very close friend of mine.
Levi Garner: We always have these kind of discussions.
Levi Garner: But I actually like having separate repos for front-end, back-end, maybe splitting up different microservices, so on and so forth.
Levi Garner: That's essentially the approach I kind of took for IntelliJ.
Levi Garner: Even the IntelliJ back-end, I could technically split that up into multiple microservices.
Levi Garner: But anyways, man, the concept of mono repo is becoming very, very popular.
Levi Garner: And I think for a net new project, especially with Claude, it makes it easier to manage context, okay?
Levi Garner: It makes it easier to manage context.
Levi Garner: Anyways, I've done the exact same thing with this strategy.
Levi Garner: With separate repositories, it's not that big a deal.
Levi Garner: But let me just take you through what I'm talking about.
Levi Garner: I'm going to give you these engineering standards.
Levi Garner: It doesn't matter if you've ever built Java or not.
Levi Garner: This is all the same context.
Levi Garner: Another important piece.
Levi Garner: Not only will we do CQRS in this app, we will also follow Vertical Slice.
Levi Garner: Vertical Slice is basically microservices.
Levi Garner: I could split out any one of these as a microservice.
Levi Garner: That's all a Vertical Slice is.
Levi Garner: So I follow technically Vertical Slice, DDD, with CQRS and event sourcing.
Levi Garner: Just hear me out on this.
Levi Garner: I'm just going to take you through an example.
Levi Garner: I'm not going to take you through Cognos because that's a whole separate piece.
Levi Garner: But I'm just going to show you a very simple example of CQRS with, let's just say contributor, dude.
Levi Garner: So if you come into Code Intelligence, here are all the contributors to the code base, right?
Levi Garner: And we can do different things to these contributors.
Levi Garner: We can update, we could add.
Levi Garner: Get the contributor, so on and so forth.
Levi Garner: God, I'd never even go into these screens.
Levi Garner: Actually, let's do this one.
Levi Garner: Let's go to, I need to log in, next one.
Levi Garner: Okay, let's go to, back to contributors.
Levi Garner: All right, we can do different things with a contributor, okay?
Levi Garner: We can update its display name.
Levi Garner: We can set a role of the contributor, like are they a junior developer, all the way up to CTO, right?
Levi Garner: We can change their role.
Levi Garner: We could merge contributors.
Levi Garner: That actually becomes kind of critical whenever you do the initial sync with GitHub if it's a large org, because sometimes developers will change their username and , so we can clean up and we can do merges, right?
Levi Garner: Okay, what CQRS basically follows, and I follow structural CQRS.
Levi Garner: You can take...
Levi Garner: CQRS all the way to where you actually build a separate repo for your commands and a separate repo for your queries, completely segregated.
Levi Garner: I like to follow structural CQRS.
Levi Garner: So this is my vertical slice architecture.
Levi Garner: So let's go into contributor.
Levi Garner: This is the back end for this, okay?
Levi Garner: If I open this up and we look at contributor, you can see how this is a vertical slice for contributor, meaning all of the context for the contributor is in one vertical slice, okay?
Levi Garner: If you want to understand the context of this or even an agent understand the context, you just have to go here.
Levi Garner: So I have API.
Levi Garner: So, you know, my controllers, my controllers.
Levi Garner: I have my data transform objects for commands and queries.
Levi Garner: So let's say we want to do an update contributor, right?
Levi Garner: Visibility command.
Levi Garner: Update contributor profile.
Levi Garner: Let's just follow the easy one.
Levi Garner: Updating the profile.
Levi Garner: We'll just take that one all the way down.
Levi Garner: Okay, here's the profile.
Levi Garner: You can update the profile, right?
Levi Garner: So this is the update contributor DTO.
Levi Garner: This is my command, or I call it management controller.
Levi Garner: So this is the contributor management controller.
Levi Garner: Typically, man, what I would do is actually follow, have an update.
Levi Garner: I would actually have a contributor command controller sometimes.
Levi Garner: It depends on the bounded kind of context.
Levi Garner: So you can see if we come in here, and again, it's not like you're going to be looking at a lot of, you should review the code that gets generated.
Levi Garner: But most importantly, what I'm setting you up for here is the codex is going to make your code extremely clean following these patterns, right?
Levi Garner: So here's my update.
Levi Garner: Let's see, update contributor.
Levi Garner: All right, here's my update contributor, and this is just the endpoint that gets called.
Levi Garner: So you can see the request comes in, right?
Levi Garner: I then map that.
Levi Garner: So another pattern you should follow, Codex, in this project is MVVM, okay?
Levi Garner: It sounds like, well, why do you need to follow MVVM?
Levi Garner: Model, view, view, models.
Levi Garner: So a principle that I like to follow, man, is I don't like to allow DTO objects to slip into the business layer.
Levi Garner: It's important whenever you follow DDD.
Levi Garner: So see how, dude, screw this.
Levi Garner: Let me open up.
Levi Garner: I don't know why I'm in.
Levi Garner: I'm just going to open up.
Levi Garner: IntelliJ, so much better.
Levi Garner: I don't know why I'm in VS Code.
Levi Garner: All right.
Levi Garner: So, all right, we were following that.
Levi Garner: So basically what we'll have is each, basically what CQRS says from a structural standpoint, Abhishek, is every single command needs its own handler.
Levi Garner: Every single query needs its own handler.
Levi Garner: And if you think about it, that's how you actually abide to single responsibility.
Levi Garner: You know, everyone talks about dry, right, so on and so forth.
Levi Garner: But single responsibility is absolutely critical, right?
Levi Garner: And how can you follow single responsibility if all of your code's in a controller, for example?
Levi Garner: And that's what we want to avoid.
Levi Garner: We want our controllers to be very, very clean.
Levi Garner: Very, very clean, okay?
Levi Garner: And we want our business logic to be segregated from our controller logic.
Levi Garner: And all the handlers actually are, dude, are basically just thin orchestrators.
Levi Garner: That's all they are.
Levi Garner: See how clean they
Levi Garner: This command handler is, and it's clean because I follow DDD.
Levi Garner: So all the logic is actually in this contributor aggregate.
Levi Garner: That's the domain objects.
Levi Garner: So basically what domain-driven design does, and it pairs very nicely with command query responsibility segregation, is it says, let's build a model around our code, right?
Levi Garner: Let's model our code.
Levi Garner: Let's create good object-oriented programming.
Levi Garner: So that's essentially what DDD does.
Levi Garner: So you can see we have API.
Levi Garner: You'll have an application folder, okay, that will contain all your commands and queries, right?
Levi Garner: Mappers maybe.
Levi Garner: I'm not such a fan of services.
Levi Garner: Then you'll have your domain layer, right, with your aggregate, your events, et cetera.
Levi Garner: And then your infrastructure contains like your entities and your repositories, essentially.
Levi Garner: So Codex is going to take care of that part for you.
Levi Garner: But have
Levi Garner: you followed any kind of backend patterns similar to this, like vertical slice with, what I've shown you is I've shown you vertical slice with command query responsibility segregation.
Levi Garner: This design pattern here is called MVVM, model, view, view, model, where we separate and we segregate our DTOs from our command models, or sorry, our business layer models.
Levi Garner: So that's MVVM.
Levi Garner: And then, yeah, man, that's kind of, it's kind of an extension of, but anyways, let me digress.
Levi Garner: Have you, have you built any backend systems similar to that?
Abhishek Bhatta: Yes, actually.
Abhishek Bhatta: So the way your handlers are, you know, segregated from the controller actions.
Abhishek Bhatta: So we used to have that, we used to call it as a controller action.
Abhishek Bhatta: Where, like, each API endpoint would be inside a controller, but all the business logic will be segregated in separate files, and that provides them the single responsibility.
Abhishek Bhatta: Yeah, so the basic concept is we need to make controllers as thin as possible, and the models, like, we don't want to get models also thick, so we break them into the concerns.
Abhishek Bhatta: And, you know, basically drawing out the models, making controllers thin, so those practices, so I don't actually, like, remember what the name we call it.
Abhishek Bhatta: So sometimes we call it, like, sometimes we also use decorator patterns.
Abhishek Bhatta: Yes.
Abhishek Bhatta: Yeah, all the things that need to be displayed in the view will be decorated around model.
Abhishek Bhatta: forgot.
Abhishek Bhatta: I'll to Thank
Abhishek Bhatta: Yes, dude, 100%.
Levi Garner: Let's talk about design patterns for a minute.
Levi Garner: I want to refresh on.
Levi Garner: I've used Decorator, too.
Levi Garner: So what I just showed you, we'll go to Decorator in just a minute.
Levi Garner: But if you think about it, dude, there's basically, there's different categories of design patterns.
Levi Garner: So if you look over here, I love this.
Levi Garner: I've been going to this for years now, man.
Levi Garner: Creational, structural behavior.
Levi Garner: So I'm obsessed with, similar to you, with the Decorator pattern.
Levi Garner: I really, really love structural patterns.
Levi Garner: I mean, if you think about it in a way, facade is a great way, man.
Levi Garner: I've used facade pattern multiple times.
Levi Garner: That's kind of what the handler kind of does.
Levi Garner: It acts as a clean layer on top of, like, the domain.
Levi Garner: Because if you think about it, what is this handler doing here?
Levi Garner: So if I come into...
Levi Garner: To create custom role command handler, open a random one up.
Levi Garner: What's it doing?
Levi Garner: It's really a facade, right?
Levi Garner: In a way.
Levi Garner: It's an orchestrator.
Levi Garner: It takes the command in, right?
Levi Garner: It accesses the repository to find it, right?
Levi Garner: It gets the aggregate.
Levi Garner: It persists it, right?
Levi Garner: And it saves it, right?
Levi Garner: But it's not doing anything directly.
Levi Garner: You know what I mean?
Levi Garner: It's just calling other classes.
Levi Garner: That's kind of...
Levi Garner: I've used the facade pattern a lot when I have, like, a super messy stored procedures and , and it's a mess.
Levi Garner: I'll just create a real clean facade and just execute a bunch of...
Levi Garner: But decorator...
Levi Garner: Let's see if I've used decorator before.
Levi Garner: Yeah.
Levi Garner: Yeah.
Levi Garner: Yeah.
Levi Garner: Yeah.
Levi Garner: I mean, I've actually...
Levi Garner: I have that in my application, right?
Levi Garner: Right now, technically, to send multiple notifications in abstract.
Levi Garner: Yeah.
Levi Garner: So creational, dude, Builder's amazing.
Levi Garner: I love Builder Pattern because that's most of objects or most of building software is taking one object, mapping it to another object, passing it down to the next layer.
Levi Garner: Builder's absolutely excellent for that.
Levi Garner: And if you've ever used, I mean, this is Builder Pattern right here.
Levi Garner: That's a Builder Pattern.
Levi Garner: What's so nice, dude, about Java Spring Boot is it's got so many good abstractions built into it.
Levi Garner: You can just say, at Builder, add that bean, and it automatically gives the Builder functionality for you.
Levi Garner: It builds the Builder Pattern into it.
Levi Garner: Behavioral, I use a lot of Behavioral, actually.
Levi Garner: So, like, what I showed you was Command Query, Responsibility.
Levi Garner: Yeah.
Levi Garner: Template method, huge, dude.
Levi Garner: Think about, for example, IntelliJ, how many integrations I would have to add.
Levi Garner: Check this out.
Levi Garner: See, I'm going to have to start to build out other knowledge integrations.
Levi Garner: I had to add this Microsoft Teams because I onboarded a healthcare company that uses Microsoft.
Levi Garner: Microsoft.
Levi Garner: So how could I design my system in such a way I don't have to completely rebuild all of that logic?
Levi Garner: I use integration, segregation, adapter.
Levi Garner: So like when the object comes in, like the webhook comes in from Teams, I adapt it to another model and then reuse all the same code, right?
Levi Garner: That's what, design patterns are everything, dude.
Levi Garner: And that, if I could just give one, like if you're facing a difficult problem statement, like constantly, or maybe codex, anytime you're faced with a difficult problem, put inside his agents.md, go reference refactoring.guru, and decide what.
Levi Garner: What kind design pattern you should best use for it?
Levi Garner: Because we want clean- code.
Levi Garner: We don't want you producing  code.
Levi Garner: I'm telling you, man, telling this agent this, it's going to build you out of clean- agents MD file.
Levi Garner: Like, your back end is going to be clean as hell, even the front ends, after I send you these standards.
Levi Garner: All right, so let's do this now.
Levi Garner: Open up, if you share your screen real quick, can you connect to Fathom real quick, man?
Levi Garner: So, do you see my screen now?
Levi Garner: I think, yep, I can see it, yeah.
Levi Garner: Hit connect to Fathom there.
Levi Garner: And then plug in, so, open Fathom API settings, if you click that.
Levi Garner: Bam, we'll just create, yeah, close that, God.
Levi Garner: They are just obnoxious, dude.
Levi Garner: Like, that's why, did you notice when you logged into IntelliJ, I didn't ask you a bunch of dumb- questions?
Levi Garner: And make you do a bunch
Levi Garner: Such a dumbass .
Levi Garner: Like, I hate apps that do that.
Levi Garner: I purposely, like, it was tough for me even to, like, make a payment form.
Levi Garner: You know, it's like, connect GitHub, log in.
Levi Garner: You know what I mean?
Levi Garner: All right.
Levi Garner: So click Add there on API access.
Levi Garner: You click Add on that one.
Levi Garner: Click Generate an API key.
Levi Garner: And it's called IntelliJ.
Levi Garner: Yeah, the single L there.
Levi Garner: Yeah, perfect.
Levi Garner: Create API client and just copy that key.
Levi Garner: Not the secret.
Levi Garner: You don't need, no.
Levi Garner: Jump back there.
Levi Garner: The API key right above it.
Levi Garner: Yeah, you're good, man.
Levi Garner: Jump in.
Levi Garner: I'll paste that API key in and just hit Connect Fathom.
Levi Garner: And then, uh, start in, start import.
Levi Garner: I actually need to give a, don't start clean on that.
Levi Garner: You don't have any meetings.
Levi Garner: So now, the next meeting we join will automatically add to this.
Levi Garner: And I wouldn't have to give you the transcript to copy into.
Levi Garner: at two.
Levi Garner: And then And then So
Levi Garner: All right.
Levi Garner: So, all right.
Levi Garner: I'm going to do this, man.
Levi Garner: I'm going to end this call.
Levi Garner: Okay.
Levi Garner: I'm going to send you the standards.
Levi Garner: Okay.
Levi Garner: I'm going to zip these up, send you the standards.
Levi Garner: You're going to download the standards.
Levi Garner: And then I'm going to send you the transcript as well.
Levi Garner: You're going to paste in your codex session.
Levi Garner: You're going to paste in the standards and then you're going to paste in the transcript.
Levi Garner: Okay.
Levi Garner: Better yet, add the transcript in a file.
Levi Garner: That's fine.
Levi Garner: I'll add the transcript in a file and send it to you.
Levi Garner: Okay.
Levi Garner: And then we'll prompt Codex.
Levi Garner: We'll jump right back on call and Codex is going to get this  built out.
Levi Garner: Start building this out.
Levi Garner: One second.
Levi Garner: Let me end this and I'll send you that on email real quick and I'll send you another link to join.
Levi Garner: Cool, man.
Levi Garner: Just one second.

## Description

Fathom meeting recording with 2 participants (en)

---
*Synced by InteliG Signal*
