# Getting into open source: a field guide for technical writers

It's easy to assume that the only way to contribute to open source software (OSS) is to be a developer. The reality is that OSS has the same documentation needs as any other product.

At the [CNCF](https://cncf.io), our annual [members survey](https://www.cncf.io/wp-content/uploads/2020/03/CNCF_Survey_Report.pdf) shows that 71% of our community learns about cloud native technology through documentation. 
Making sure documentation is complete and accurate is one of our most important metrics for project success. 

## Why contribute?

Open source offers challenges, communities, and opportunities that are often in short supply for technical writers in paid professional opportunities. 
At a glance, open source gives you the following:

**Portfolio work:** Open source projects and documentation are all publicly available, making them great portfolio pieces.

**Leadership opportunities:** Opportunities to lead others in big projects are limitless, making it a great place to develop your leadership skills.
You can also lead OSS projects other than docs and develop yourself laterally.

**Learning opportunities:** Many cutting edge organizations take a docs-as-code approach to documentation. 
Contributing is a great way to expose yourself to a docs-as-code workflow in production, though most projects expect you to learn the tech yourself.

**Feedback:** Many professional writers find themselves writing in isolation.
Open source projects offer an opportunity to get feedback from technical and non-technical reviewers and improve.

**Community and friendship:** Open source projects are a fantastic way to network with talented, hardworking and passionate individuals across the industry working on interesting projects.

## Working in open source software for technical writers 

In most companies, technical writers are embedded in a larger product or support organization. 
There, they work with subject matter experts to create and update content. 

In open source, the opportunity for the kind of deep, paired collaboration that most technical writers are used to doesn't exist.
Open source development occurs asynchronously. 
In some cases, design documents and enhancement proposals exist, as does a regular release schedule. In other projects this isn't the case. 

This leaves writers with two options. The first: get technical, dive in, and do some documentation from scratch. The second: let others do the first draft, and improve documentation by editing.

Both approaches are valuable! 
Open source needs both kinds of contributors. 
In many projects, core contributors – maintainers and leads – write most of the documentation. 
Maintainers are busy, and often don't have the time to fully finish documentation.
A trained technical writer who knows the software and can write from scratch is a huge asset. 
Similarly, because open source contributors are global, deep edits for grammar, spelling and style are also valuable.

Open source rewards taking initiative: you're more likely to get feedback and adoption by doing something than by looking for guidance _about_ doing something. 
It's up to you to decide how you want to contribute. 

## Getting in and around an OSS project

There's no one way to get involved in open source: each project runs itself differently. In general, you'll need to figure out the following:

**Figure out how the project communicates**  
Most open source projects use multiple forms of communication. 
Your first job is to figure out where the planning and discussion happen. 
If there's a contributor guide, you can usually find the maintainer's preferred methods of communication here. 
In smaller projects, you may only find a `README.md` or `CONTRIBUTING.md` file!

**Where does the project keeps its documentation?**  
Some projects keep their documentation in the same repository; others keep it elsewhere. The next step is to find the project's documentation and understand it: do docs build to a website? Do docs exist only as code comments, like many Java-based libraries do? 
Once you find the docs, work on getting them to build locally before you make any changes.

**Who can and can't contribute?**  
Some open source projects have restrictions around who can and can't contribute changes. 
If you can't find any information, submit changes anyway, but be prepared: you may be asked to follow an undocumented process.


## Challenges to overcome

Open source communities are often developer-centric, and interacting with them from non-developer roles is challenging. Here are some common ones, and ways to move forward:

**Docs-related issues are often light on details or too general to be useful.**  
The best way to deal with this is to ask the original reporter for more details. 
If the original reporter doesn't flesh out the issue, move on to something else – there's always more work to do.

**Projects don't understand how to interact with writers.**   
Projects know they need help with documentation, but don't know how to interact with writers in a useful way. 
You need to analyze the existing documentation for gaps and obvious wins, then work closely with the project team to improve incrementally, usually by creating an issue backlog for them. 

**You need a base level of technical skill.**  
Most open-source projects use Git for source control and documentation, and expect incoming contributors to be self-sufficient using it. 
As a writer, you'll need to learn the tools thoroughly before your first commit. 

**Open communication is key.**  
Communication that exists in GitHub or a project tracking site is what's official, regardless of other communication channels. 
These are permanently attached to the changes made and therefore easy to track down in the future. 
They also allow for easier asynchronous comments from people in different time zones. 

**Propose fully scoped work.**  
Project maintainers are often inundated with requests to review proposals and approve courses of action. 
The work that gets done is work that's scoped in full, which allows a team of diverse people with different skill sets to have an intelligent discussion on things that aren't their speciality. 
Open source isn't the best place to present work in progress or half-formed ideas.

**Feedback quantity and quality is different.**  
Get used to proposing major structural feedback on someone else's final drafts, particularly when reviewing another person's changes. 
This can be uncomfortable for writers, but open source prioritizes finished work. You may not get an opportunity to look at the structure of a document prior to a final PR, so you may be forced to leave larger reviews closer to the end of the process.

## How we do it at the CNCF

Every open source project works differently, even at the CNCF. Of the CNCF's projects, Kubernetes boasts the largest contributor community, and is easiest to interface with. Here's how to get involved as a technical writer with Kubernetes:

**Start with Contribex:**  
Kubernetes SIG Contribex, short for contributor experience, is the starting point for new contributors. 
The `kubernetes/community` repository lists the different SIGs (Special interest groups) in the project. 
For technical writers, SIG Docs is the place to go!

**Join us on Slack and by mailing list:**  
Most Kubernetes SIGs communicate in two places: mailing lists and Slack channels. Join both! 
For docs, this is the #sig-docs Slack channel and the sig-docs mailing list.

**Attend the weekly status meetings:**  
When you join the mailing list, you should receive invitiations a SIG's the weekly syncs.
Attending a SIG Docs meeting is the best way to start to understand what work is happening in documentation, meet people, and ask for help. 

**Get verified:**  
Contributing to Kubernetes requires that you sign the Contributor Lisence Agrement. 
Any and all PRs you open will fail to merge if you don't do this step.

**Dip your toes in and review pull requests:**  
One of the easiest ways to get involved for new technical writers is to start reviewing. 
The `kubernetes/website` repository sees 150+ open PRs per day, many of which need basic language review!

## Other ways to get involved 

[Google Season of Docs](https://developers.google.com/season-of-docs) is a great way to get exposure to open source projects as a writer in a structured, time-boxed way. 
