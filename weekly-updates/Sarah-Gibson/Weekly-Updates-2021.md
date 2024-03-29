# Sarah's Fortnightly Mentoring Meetings

- [2021-10-14](#date-2021-10-14)
- [2021-09-16](#date-2021-09-16)
- [2021-08-18](#date-2021-08-18)
- [2021-08-05](#date-2021-08-05)
- [2021-07-22](#date-2021-07-22)
- [2021-07-08](#date-2021-07-08)
- [2021-06-04](#date-2021-06-24)
- [2021-05-14](#date-2021-05-14)
- [2021-05-05](#date-2021-05-06)
- [2021-04-16](#date-2021-04-16)
- [2021-04-07](#date-2021-04-07)
- [2021-03-24](#date-2021-03-24)
- [2021-03-10](#date-2021-03-10)
- [Template](#template)

---

## Date: 2021-10-14

### Who did you help this week?

- Cheered on Georgiana who was nervous about facilitating her first meeting

### Who helped you this week?

- Erik talking me through network policies for Kubernetes

### What did you achieve?

- Merged a lot of stuff so that 2i2c JupyterHubs can authenticate with GitHub Teams!
- I started a blog about some work I did in mybinder.org for testing PRs

### What did you struggle with?

- Network policies on our JupyterHubs: where is traffic allowed to come from/go to, and what should the users be able to access/not access
- Migrating the Pangeo user directories.
  I'm having difficulty ssh'ing from one machine to another with the correct user and I'm praying that it has nothing to do with Columbia's IT policies!

### What would you like to work on next week?

- I need to continue cracking on with network policy and user migration work for Pangeo
- Continue with blog writing, get a rough draft to Chris so he can cut out everywhere I've waffled
- I also need to record a short video (2mins) on our JupyterHub Community Strategy Lead project for the CZI EOSS launch call

## Date: 2021-09-16

### Who did you help this week?

- Helped Ryan Abernathey get access to a new Pangeo hub for his course

### Who helped you this week?

- Yuvi and Damián with various debugging
- The Lab with finding motivation/inspiration to get my TPS Coffee talk done

### What did you achieve?

- Prepped my talk for TPS Coffee on my journey as an SSI Fellow
- Deployed a production version of a Pangeo hub for Ryan to use in his classes

### What did you struggle with?

- Lots of technical stuff!
  Google's node auto-provisioning is not working as we expected and it's a feature we'd like to use.

### What would you like to work on next week?

- Some authentication work to diversify the range of options 2i2c-managed hubs can offer
- Polishing off my SSI Fellow talk for the Launch Webinar

## Date: 2021-08-18

### Who did you help this week?

- I feel like I'm either receiving a lot of help, or working in isolation recently - so I'm struggling to answer this!

### Who helped you this week?

- Erik helped me with deploying an NFS server directly into a kubernetes cluster

### What did you achieve?

- Erik and I found a solution to NFS server issues that have been plaguing me and we put a proposal together for a new way to deploy them
- I made some upgrades to one of my bots to perform more sensible checks against open PRs and to assign reviewers
- I finished a big piece of infrastructure work for mybinder.org that will allow us to deploy PRs from forks to our staging infrastructure

### What did you struggle with?

- I struggled a lot being technically blocked on the NFS server stuff.
  The team are having discussions around "how do we signal that we are blocked, how we are blocked, and what help we require".
  But that was mostly why I dove back into my bots and the mybinder work - I needed some tech wins!

### What would you like to work on next week?

- Still working towards deploying a staging hub for Pangeo
- I will also be going on holiday next week so I would like to work towards relaxing!

### Any other topics

- I have cancelled the meeting due on Sept. 2nd as I will be returning from holiday that day.

## Date: 2021-08-05

### Who did you help this week?

- Fede by running a mybinder tutorial as part of his Digital Humanities summer school
  - AM: Great stuff!

### Who helped you this week?

- 2i2c engineering team by thinking through team practices
- Yuvi for reviewing my PRs

### What did you achieve?

- Reconfigured our terraform backend to dynamically select storage buckets.
  Helps solve the "double login" problem.
- Success fully deployed a private cluster to Pangeo/Columbia's Google Cloud project that conforms to all their controls
- Gave a successful mybinder tutorial at Fede's Digital Humanities summer school
  - AM: Sounds like you had a very productive August so far - well done! 🎉

### What did you struggle with?

- "Double login" for Pangeo/Columbia continues to be an issue.
  I now have to figure out secret encryption, the keys for which we store centrally in the same manner as the terraform state.
  So frustrating that accommodating Columbia IT's needs has caused process changes at literally every level.
- I was asked to give my Binder tutorial at the AGU Fall Meeting as part of a "Open Science in Action" session led by Fernando Perez (among others).
  Not only do AGU require you to be a _paid_ member before you can submit an abstract, but there is also an abstract submission fee.
  On top of that, the payment system isn't even working, so I'm completely blocked on submitting this abstract!
  What I need to do is write up a Speaker Rider explicitly stating that I will likely not participate in PayToSpeak conferences (among other conditions) since they are massively exclusionary to folk who don't have the liquid cash to pay upfront - even if the tech works!

### What would you like to work on next week?

- Secret encryption for Pangeo deployment
- Actually deploying a Pangeo hub!
  - AM: I would love to chat next time about how this has panned out. Good luck! ✨

## Date: 2021-07-22

### Who did you help this week?

- Former Turing colleagues transferring ownership of Zotero account
- A Turing researcher automatically deploy their Jupyter Book to GitHub Pages
    - AM: That sounds very nice of you - thank you! 🙏

### Who helped you this week?

- Yuvi with many, _many_ questions about Google/Terraform/Kubernetes/etc...
    - AM: One day I will know something about Terraform 😂

### What did you achieve?

- Deployed a JupyterHub for a geospatial workshop in Ghana next week! :tada:
   -  AM: Well done!!! 🎉
- Reviewed some submissions for the Hidden REF Practices panel
   - AM: great stuff!

### What did you struggle with?

- A meeting with a university IT department was full of condescension and disrespect
    - 🤦‍♀️ And also well done on standing up to that behaviour!

### What would you like to work on next week?

- Hopefully the Ghana workshop will go well and I won't be needed much there
- I would like to work more on unblocking the cluster deployment for Pangeo (it's not going to be as simple as we first hoped)
- I am presenting Zero to Binder for Digital Humanities with former Turing folk next week
    - ✨ all sound fab!!

## Date: 2021-07-08

### Who did you help this week?

- Someone in 2i2c community who had trouble building a Jupyter Book on GitHub Pages
  - We didn't solve it, but in the process I got them setup on GitHub Actions

### Who helped you this week?

- Min with providing an initial review of my first GitHub Action

### What did you achieve?

- Got a (roughly) working prototype of my first GitHub Action to circumvent the problem of secrets not being available to Pull Requests originating from forks

### What did you struggle with?

- Git authentication within my GitHub Action
- Identity conflict in gcloud when trying to use 2i2c infrastructure to deploy to a Pangeo/Columbia-owned project

### What would you like to work on next week?

- Continue plodding on with the Action and cluster deployment

## Date: 2021-06-24

### Who did you help this week?

- SB fix her git commits to register on GitHub from her preferred account
- CM begin to spin up a small cluster at Turing to add to the mybinder staging federation

### Who helped you this week?

- Yuvi understand more about 2i2c / Pangeo helm charts and the challenges we face working with them
- Min figure out a Kubernetes issue when upgrading Turing's mybinder deployment

### What did you achieve?

- I had a great kick off meeting with Pangeo / 2i2c and opened an issue to track the migration of the first Pangeo hub
- I've made lots of little PRs to various 2i2c repos to suggest docs fixes, and performed code review too
- I moved the Whitaker Lab website onto Netlify

### What did you struggle with?

- Still a bit timid to try out deployments in 2i2c as it's not clear how I can separate myself from the infrastructure in production and, therefore, have a safe space to make mistakes. Raised an issue with the team though, and they agree it's a good idea.
- While there are two people in the team who are in similar time zones to me, they're a bit quieter on Slack. Therefore, most of the action happens in my evening and I can feel a bit at a loose end during the day. I'm sure this will change as the amount of work I have to focus on increases though.

### What would you like to work on next week?

- Waiting for Pangeo to provide access to their current cluster so I can check it out and make a migration plan
- Continue deploying the staging cluster with CM

## Date: 2021-05-14

### Who did you help this week?

- Lab members learn about blogging with Hugo and GitHub Pages
- Reviewed my OLS mentees' graduation slides
- CH writing CZI EOSS proposal

### Who helped you this week?

- MD reviewed my OLS graduation slides

### What did you achieve?

- Gave a _really fast_ demo of setting up a blog using Hugo and GitHub Pages to the Lab
- Synced up KW, MS and CM on Binder/Turing Way/TPS
- Emptied and sorted my Turing locker
- Copied OLS work under my account (not Turing's) for some future work

### What did you struggle with?

- Had a few headaches this week that made focusing difficult

### What would you like to work on next week?

- Handing over LwM
- Prepare to graduate OLS
- Wrap up CZI EOSS application with CH

### Any other topics

To discuss with AM:

- [ ] Meeting in two weeks is my last at the Turing and will be taking two weeks break
- [ ] When to restart meetings?
- [ ] Platform? Stick with Zoom or change to Google Meet?

## Date: 2021-05-06

### Who did you help this week?

- CM onboard as new Turing cluster admin

### Who helped you this week?

- I've been mostly head down getting through my to-do list!

### What did you achieve?

- Updated progress on some LwM tickets
- Setup lots of intro meetings between KW/MS/CM and JupyterHub/Binder/CM
- Did some self-analysis into time/productivity management using various Jupyter tools.
  Whitaker Lab meeting on this TBC!
- Began my Lab presentation on building blog sites with Hugo and GitHub Pages for next week

### What did you struggle with?

- Fully disconnecting from work (particularly Slack) last week while on leave.
  This was probably due to the fact I was working on some non-work but still techy side-projects.

### What would you like to work on next week?

- Finish and deliver presentation on blogs with Hugo and GitHub Pages for Lab meeting next week

## Date: 2021-04-16

### Who did you help this week?

- Helped LC set the order of her online CV
  - AM: 🎉
- Helping the authors of a paper I'm reviewing
  - AM: Sounds SUPER interesting! Would love to read this!! ✨

### Who helped you this week?

- MS, YY and the OLS community answering questions I had distinguishing some open science concepts
  - AM: The roadmap discussion is really interesting to contextualise. No one method is perfect!!
- AB for running a co-working session that was relly productive
  - AM: SUPER well done on writing a whole section! 🎉
- CH with getting panels working on the Turing Way Jupyter Book
  - AM: ✨
- IKG with the ethics approval process for the Open Source Service Area user research

### What did you achieve?

- Got panels working in the Jupyter Book and started transferring the Zero-to-Binder tutorial across.
  This means I only have to maintain 1 file with 3 languages, instead of 3 files containing a language each.
  - AM: :tada:
- Caught up with OLS assignments
- Read and made notes on a paper ready to write a peer review report
- Chaired the JupyterHub/Binder team meeting, disseminated the notes and scheduled the next meeting
- Wrote a blog post for the Whitaker Lab on the CollabW21 reflections meeting, and adapted the text for my own blog!
  - This is AMAZING! Especially since very few folks actually did it.
- Attended a mentorship training session ran by the Turing
- Rounded off the "job ad" for the Turing Beinder Federation Cluster Admin role
  - ✨

### What did you struggle with?

- Not much!
  The productivity management system I'm implementing seems to be really effective at nudging me to realise what I'm supposed to be working on, schedule the time, and plough through it.
  - AM: 🎉🎉🎉🎉🎉🎉🎉🎉🎉🎉 SUPER WELL DONE!!

### What would you like to work on next week?

- Need to do some work for LwM around a long-running task and trying to speed it up
  - Good luck!
- Get the Turing Binder cluster back online
- Pitching the Turing Binder Federation cluster admin role to a couple of internal people I have in mind
- Continue migrating the Zero-to-Binder workshop into the Turing Way book and write a chapter discussing why mybinder.org is a better communication tool than collaboration tool
 - AM: Sounds like that productivity management system is working wonders!! Well done Sarah! ✨✨✨✨

### Where do you need help from Kirstie?

- All good!

## Date: 2021-04-07

### Who did you help this week?

- SD at CollabW21 by sharing my (albeit small) knowledge on crowdsourcing
- KW and AB by providing a continuous deployment workflow to convert Markdown files to PDFs
- GT onboarding to LwM crowdsourcing tools

### Who helped you this week?

- AB prepare a user research interview script
- MD and lab members for providing feedback on the interview script

### What did you achieve?

- I had a wonderful and creative time at CollabW21 last week.
  I achieved 3rd place in the hack day with my team!
- I implemented calendar blocking to dedicate time to my TODOs.
  It seems to be working well so far!

### What did you struggle with?

- Onboarding can be frustrating when RSEs are viewed as support

### What would you like to work on next week?

- Moving the Zero-to-Binder tutorial into the Turing Way book
- Finish up role responsibilities for Turing BinderHub cluster admin
- Plan the implementation of open practices survey for Open Source SA/OLS-3

### Where do you need help from Kirstie?

- If Kirstie could provide her preference for being updated on the Turing BinderHub Federation cluster, that would be a huge unblocker!
  https://github.com/alan-turing-institute/the-turing-way/pull/1785#discussion_r598594375

## Date: 2021-03-24

### Who did you help this week?

- MS and KW run a Turing Way/Binder workshop for Engage@Turing students
- Other members of my Carpentries instructor training cohort with questions and suggestions

### Who helped you this week?

- MS for setting up the workshop so well that I could just turn up and do my thing
- AN and SC for running such a wonderful training

### What did you achieve?

- Completed the Carpentries Instructor Training course.
  Only the checkout procedure to go!
- Delivered Zero-to-Binder and received a lot of positive feedback

### What did you struggle with?

- I probably overcommitted myself.
  Spent a lot of time in meetings/trainings this week rather than working.
  It'll pay off in the long run, but also probably burned myself out a touch.
- I wish some internal training could be as engaging as the external training I received

### What would you like to work on next week?

- Finishing my slides for my talk at Lund and giving a great talk/tutorial
- Scoping a person to look after the Turing Binder Federation cluster with me
- Should probably focus on some LwM stuff too

### Where do you need help from Kirstie?

- All good I think!

## Date: 2021-03-10

### Who did you help this week?

- MS think through agenda for HDRUK Binder workshop next week
- CM question on Kubernetes.
  I gave some "this is how I would try and narrow the problem down" advice.
- My OLS-3 mentees.
  I think they will benefit from GA's advice on communicating with dev teams so coordinated a meeting.
- A whole bunch of people (30?) at the SSI Research Software Camp Binder workshop who wanted to know about reproducibility and building binders!

### Who helped you this week?

- KW by being at the other of end of Slack and just knowing how hard it can be
- AM with some fun discussions on what start-ups are like
- My OLS-3 mentor with advice and sympathy on culture in institutions
- EM, SB and MV with running the SSI Binder workshop

### What did you achieve?

- Successful Binder workshop at the SSI Research Software Camp
- Gave a talk on Binder at a Remote ReproHack
- Moved Hub23 onto the same cluster as the Turing Binder Federation deployement, halving financial and maintenance costs
- Explicitly wrote down the minimum tasks I do to support the Turing Binder Federation cluster for transparency and sustainability

### What did you struggle with?

- Deeply embedded institutional biases
- Finding the motivation to work on a task that will likely not be appreciated even though you can see the benefit

### What would you like to work on next week?

- Software Carpentry Instructor training
- Help out with the HDRUK Binder workshop
- Prepare for another Turing Way/Binder demo for Lund University
- Scoping out who could fit the Turing Cluster Admin role if not me

### Where do you need help from Kirstie?

- Continued acknowledgement and recognition that the hard things are hard

### Any other topics

My meeting with Aida today was mostly expectation setting regarding what my role might look like in the future, some therapy around institution culture and contrasting this with start-up culture.

## Template

```
## Date: [INSERT DATE OF MEETING]

### Who did you help this week?

Replace this text with a one/two sentence description of who you helped this week and how.

### Who helped you this week?

Replace this text with a one/two sentence description of who helped you this week and how.

### What did you achieve?

- Replace this text with a bullet point list of what you achieved this week.
- It's ok if your list is only one bullet point long!

### What did you struggle with?

- Replace this text with a bullet point list of where you struggled this week.
- It's ok if your list is only one bullet point long!

### What would you like to work on next week?

- Replace this text with a bullet point list of what you would like to work on next week.
- It's ok if your list is only one bullet point long!
- Try to estimate how long each task will take.

### Where do you need help from Kirstie?

- Replace this text with a bullet point list of what you need help from Kirstie on.
- It's ok if your list is only one bullet point long!
- Try to estimate how long each task will take.

### Any other topics

This space is yours to add to as needed.
```
