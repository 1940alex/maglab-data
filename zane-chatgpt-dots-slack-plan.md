# Zane — How I Think We Should Use ChatGPT Dots + Slack

## The simple idea

I think we can make **Slack the shared project workspace** for the real-estate project, while each of us uses ChatGPT as our AI interface.

There are really two layers:

1. **Normal ChatGPT conversations** — for things we initiate: thinking something through, drafting something, researching, reading email, working with GitHub/Drive, or asking ChatGPT to perform an available action in a connected app.
2. **Our Dots** — the ongoing/agentic layer. A Dot can own continuing responsibilities, keep working between conversations, watch specified sources, run scheduled or event-driven work, and bring us updates or decisions that need attention.

So normal ChatGPT is great for **"do this now."** A Dot is for **"own this responsibility and keep it moving."**

## What I want our setup to look like

### Slack = the shared project hub

We create a clean Slack workspace/channels for the real-estate project.

That becomes the place where we:
- discuss the project;
- post decisions and updates;
- share links to important documents;
- coordinate tasks;
- bring other people into the appropriate channels when needed.

We should keep a private channel for things that are just between us, and use separate channels when contractors, partners, attorneys, brokers, etc. need access.

### Shared documents stay in the right systems

We don't need Slack itself to become the document database.

Google Drive/Docs/Sheets can remain the home for shared working documents, and GitHub can remain the home for anything that belongs there. Slack becomes the communication/coordination layer linking everything together.

### ChatGPT = our ad-hoc AI interface

Once the appropriate apps are connected, I want to be able to have a normal conversation with ChatGPT and say things like:

- "Find the email about the property inspection and summarize it."
- "Look at the latest project document and help me revise this section."
- "Check the GitHub repo and update this Markdown file."
- "Search the relevant Slack discussion and tell me what we decided."
- "Draft/update something using the connected tools that are available."

We already tested the GitHub part: ChatGPT successfully wrote a Markdown file into one of my public repos and then read it back.

Slack capabilities depend on the Slack connection, workspace permissions, and the particular actions OpenAI exposes, so we'll verify the exact write actions after we connect it rather than assume every Slack operation is available.

## Where Dots change the game

A Dot is not merely another chat window. OpenAI describes it as an **always-on agent** with its own cloud computer that can keep working between conversations.

The important distinction for us is:

**Regular ChatGPT**
> Alex or Zane starts the interaction: "Check this, update that, summarize this thread."

**Dot**
> We give it an ongoing responsibility: "Keep track of this project, watch these sources, maintain this status, and tell me when something important changes."

A Dot can use connected apps, perform scheduled work, proactively review connected information, and continue work after a conversation ends.

## Slack + the Dot

This is especially interesting.

OpenAI says the same Dot can be reached through ChatGPT and Slack. In Slack, its owner can DM it or add it to a channel and mention it. We can tell it which channels/events to watch and where to send different kinds of updates.

Important nuance: **adding a Dot to a Slack channel does not automatically mean it monitors everything forever.** We explicitly tell it what to watch and when/how to notify us.

Also, by default a Dot responds to its owner. OpenAI says its owner can instruct it to engage with other people, but ownership and permissions still matter.

## I think we should each have our own Dot

Rather than trying to make one AI identity jointly owned, I think the clean model is:

**Alex → Alex's Dot**

**Zane → Zane's Dot**

Both can operate around the same shared project information and Slack channels, subject to the permissions we give them.

That means each of us has a personal agent that understands our own conversations, responsibilities and preferences, while Slack remains the common human-visible project layer.

Example:

Zane posts an update in the project channel.

My Dot has an explicit responsibility to watch that channel for meaningful project changes. It can surface the update to me, summarize what changed, identify something that needs my decision, or perform whatever follow-up I've authorized.

Likewise, Zane's Dot can handle the things Zane wants it to own.

## A practical first version

I would keep version 1 extremely simple:

1. Set up/clean up the Slack project channels.
2. Connect my Slack to ChatGPT and test reading/searching plus whatever Slack actions are enabled.
3. Connect the relevant Gmail and Google Drive access.
4. Create my Dot on desktop and connect the tools it actually needs.
5. Add my Dot to the appropriate Slack channel(s).
6. Give it one narrow responsibility first, something like:

> "Follow the real-estate project channel. Keep track of decisions, open questions, commitments and action items. Tell me when something important changes or when I need to make a decision. Don't bother me about routine chatter."

7. Zane can set up his Dot similarly if he wants independent control.
8. After a week or two, expand what the Dots own based on what is actually useful.

The goal isn't to automate everything on day one. It's to establish a **shared project nervous system**: Slack for the team, our existing files as sources of truth, normal ChatGPT for immediate work, and Dots for ongoing responsibility.

## Useful links

### Official OpenAI material

- Introducing Dots: https://openai.com/index/introducing-dots/
- Dots overview: https://chatgpt.com/features/dots/
- Getting started with your Dot: https://help.openai.com/en/articles/20001530-getting-started-with-your-dot
- ChatGPT Learn — Dots: https://learn.chatgpt.com/docs/dots
- Messaging your Dot through Slack/Teams: https://learn.chatgpt.com/docs/dots/channels
- Using Slack in ChatGPT: https://help.openai.com/en/articles/12525822-using-slack-in-chatgpt

### YouTube

Dots are brand-new, so creator coverage is changing quickly. Rather than hard-code an unverified Riley Brown video URL, here are searches that should surface the newest material:

- Riley Brown + OpenAI Dots: https://www.youtube.com/results?search_query=Riley+Brown+OpenAI+Dots
- OpenAI Dots demos/tutorials: https://www.youtube.com/results?search_query=OpenAI+Dots+ChatGPT+tutorial

I'd start with Riley Brown's newest Dots walkthrough if it's there, then compare it with OpenAI's official material above.

---

**Bottom line:** Slack is where we collaborate with each other and the rest of the team. Normal ChatGPT is where we can ask for immediate AI work across connected tools. Our Dots become the persistent agents that keep watching the project, moving assigned work forward, and bringing us the things that actually need our attention.
