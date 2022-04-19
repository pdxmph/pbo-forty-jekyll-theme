---
layout: post
title: So you want to write an RFC
description: RFCs help teams leverage DACIs and work more asynchronously with clearer outcomes. 
image: 
nav-menu: false
show_tile: false

---

A request for comment (RFC) is a way to propose an idea to a group of stakeholders that uses writing and dialog to help get your idea across, expose it to other ideas, and ensure that everybody is aligned and committed by the time the process is over. RFCs can also serve as "case law" for an organization, allowing people to review not only what you do, but why you do it. 

You can use RFCs for a number of things:
- proposing a change to existing tools or processes
- proposing a new tool, practice, or process
- getting buy-in on a change to a team's work

When you write an RFC, you are committing to:
- Seeing the RFC through from beginning to end. 
- Making sure you identify the right stakeholders
- Holding others accountable for contributing through comments or proposed changes. 
- Holding yourself accountable to hear out all your contributors and make sure their questions or concerns are answered, even if they won't necessarily agree. 
- Communicating the results of the process. 

Here's how, step-by-step, to write an RFC and see it through. 

# Grab an RFC template
Hashicorp [provides an excellent template](https://works.hashicorp.com/articles/rfc-template), or you can [use this simpler Markdown version](https://gist.github.com/pdxmph/cb47bd5acb68f7fb8080f56a83c497a2). 


# Figure out who your stakeholders are with a DACI
"DACI" is a framework for understanding peoples' roles and responsibilities in a given decision-making situation. It stands for "driver, approver, contributor/consulted, informed." In short:

- **Driver:** Who is responsible for making sure this happens or that a decision is made?
- **Approver:** Who authorized this and/or is responsible for approving it?
- **Contributor/Consulted:** Who is expected to weigh in or contribute?
- **Informed:** Who needs to know about this?

It's important to figure out your DACI, so it's worth spending some time thinking about it, and even taking time to talk things through with people to understand where they feel they should fit into it. A lot of the hard work of keeping people feeling like they're included and ultimately aligned involves making sure everyone's clear on their individual role in the RFC. 

[Here's a quick guide to DACI](./writing/using_the_daci_framework.html). Some highlights: 
- It's okay to name groups as approvers. Sometimes the next level up in a decision-making situation is a group. 
- It's okay to circulate just the DACI to the people on it for a quick check that it makes sense to them, and that you've been as inclusive as needed. Sometimes someone you thought just needed to be informed actually needs to be consulted. Sometimes people are happy just to know what the outcome is and don't care to consult. 
- It's a good idea, especially for something with cross-functional impact, to ask the approver for a review. They may have context about other departments or stakeholders that can help you craft a better, more inclusive DACI.


# Write your RFC
The two templates I linked to include explanatory text for each part of the RFC: 

- **Summary:** One or two sentences
- **DACI:** See above
- **Deadline/timeframe:** Make clear when feedback is expected by, and set a date for when all comments and questions will be resolved or closed. 
- **Background:**  A few paragraphs to a page that provides links and context to explain why this change or proposal is necessary. 
- **Proposal:** The meat of the RFC. What you want to do and how you want to do it. 

# Share and set contributor expectations
Once you've written your RFC, it's time to let your stakeholders know about it by sharing it with the approver and the people you're asking to contribute/consult. 

You can choose to share in a couple of ways:
- **Everyone all at once.** Generally this is the way to go. 
- **Bringing people in by function or where it will be most useful to them.** For instance, it may make sense to bring an initial set of contributors in who can help provide shaping and direction through their early feedback before bringing in people who are better at looking down from 10,000 feet and seeing how the whole thing hangs together once more details are resolved. Just be aware that if there are trust issues or unease about roles/responsibilties, this approach could provoke those tensions. 

Either way, each time you share, make sure communicate a few things:

- **What's the deadline for contributing?** Make clear when you'd like to see everyone "pencils down" with their initial contribution. This is meant to be an asynchronous document, so a minimum of a week is best to let people fit time for reflection and commentary into their already busy schedules. 
- **What's the deadline for closing out comments and questions?** Make clear how long you are going to take to answer questions, resolve comments/concerns, etc. You may need to adjust this. Some groups can pull this off in a day or two, others need more time. Sometimes you realize that something was more complex than you thought and needs more time to work through. 
- **How can people best contribute?** People have a lot of different styles, and Google Docs enables a few different approaches: 
	- **Comment only:** People can ask questions and propose changes as comments, but not change the document. 
	- **Suggest changes:** People can alter the text in "suggest mode," meaning that the editor or owner has to approve changes. The advantage is that the proposed changes can help shape dialog. The drawback is that a document with a lot of this kind of markup is hard to parse, especially if you're working in waves. 
	- **Just make changes:** This can quickly take you off course if your RFC is strongly opinionated, but if you're doing authoring in waves and your first contributors/consultees are key to setting direction before sharing more widely and getting more input, this can work. 
- **Will there be a meeting?** Sometimes you can't work through everything asynchronously and your contributors will need to show up and talk out things that would take too long or be too complex to fit into comments. If there's a chance that your RFC will require some face-to-face to truly resolve all questions and concerns, say so. 

# Gather feedback, monitor your document
Once your contributors are participating, you should spend a few times a day answering questions or concerns as best you can. If your contributors identify other stakeholders who were left out of the initial DACI, add them to the DACI if you think that's appropriate. If you think someone else is better equipped to respond to a comment or question, +name them in the comments to pull them in. 

You should remind your contributors of their deadlines mid-way through the process. 

# Close out comments and questions
Once everyone is pencils down, hopefully on the deadline you set, look for open questions and comments and resolve them. As the driver, this is a point where you may want to work with your approver to review the open items so you can get their support to make decisions on open items. 

Part of work life is the simple fact that we sometimes have to disagree and commit. The approver may be useful for sussing out when you can simply close out a line of questioning, reject a proposed change, or make a decision where one needs to be made. 

## Meeting or not? 

At some point during the close-out period, you'll probably have to decide whether or not to have a meeting. Some questions and concerns are too big to fit in a comment on a doc, or you need people to bring data to inform a decision, or you can just tell that you need to talk it through. 

If that's the case, schedule it as quickly as possible, be clear about what's in scope for the meeting, and push through. Calendars can be hard, but try to keep your momentum. If someone can't make a meeting for whatever reason, try to spend a few minutes getting their input or concerns and do your best to advocate for their position or share their information; or see if they can send someone in their stead. 

This is another case where pre-aligning with your approver will help you decide how important someone delivering feedback or commentary in person is. They can support your decision to exclude someone, bring in an alternate, etc. especially if, as sometimes happens, there's an attempt to derail the decision. 

# Finalize it 
It's a best practice to not consider an RFC "done" until all comments, questions, and suggestions are closed out. At the top of this document, we said RFCs can serve as "case law" for an organization, so it's important to make sure loose ends are cleaned up.

Some things you may want to include in an outcomes section:

- Where the work the RFC proposed now lives (e.g. JIRA tickets, a strategic intiiative workstream, an OKR)
- Issues you couldn't resolve, but that aren't so material you couldn't  decide to table for another RFC. 
- Circumstances under which the RFC shouldn't be applied. For instance, you may be addressing a one-time issue with a solution that won't work for similar situations. 
- Conversely, related circumstances under which the RFC should be applied. Sometimes RFCs result in general principles that apply to similar situations. 

The idea here is to do the work of collaborating and thinking through a common problem once, and making that thinking and collaboration available to others in a way that saves them doing that work all over again for this particular situation or things that are similar to it. 

# Post somewhere
If your organization or team has some a documentation space, post the RFC there, share it with the "informed" parties with a mail pointing to where they can find it, and consider sharing a link in your departmental or organizational Slack if the RFC is of broad interest. 
