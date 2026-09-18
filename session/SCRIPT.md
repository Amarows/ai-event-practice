# AI Foundations — session notes

The ideas, slides and prompts from a three-hour hands-on session on working with ChatGPT.
Use them to look something up, to repeat a demo, or as context for your own questions.

**Participant edition.** Organisation-specific rules, names and internal details are not
included. For what you may put into which AI tool, your organisation's own rules apply.

The session in one line per block:

1. **Get one useful result** — AI predicts text; brief it well, keep the conversation going, check.
2. **From a prompt to a Project** — keep a good prompt, add your facts, share it; use AI to
   question and research an idea.
3. **Use it safely, make it a habit** — know what goes where; be the author; start with one task.

What to take away:

1. AI predicts text — a fluent answer is a proposal, not evidence.
2. A briefed request beats a one-liner: context, task, format, example, limits.
3. A Project makes a good prompt repeatable, data-backed and shareable.
4. AI is also a tutor, a challenger and a researcher — not only a writer.
5. Know what may go into which tool — and ask when in doubt.
6. One recurring task, started this week.

---

## Block 1 — Get one useful result

### What AI is
- When we say "AI" today, we almost always mean an LLM — a large language model. ChatGPT is one.
- An LLM predicts the next word. That's it. It learned from a giant pool of text, and for your
  request it produces the most likely next word, then the next, until the answer is complete.
- Think of linear regression: a cloud of data points, one best-fit line. Ask about a new point and
  you get the value on the line — typical and plausible, not necessarily right for your case.
- It does not think the way you do and it does not check facts. When ChatGPT shows "Thinking…",
  it is writing notes to itself — still predicting words.
- Other kinds of AI exist: systems that decide, see images, generate video. ChatGPT bundles some
  of them — it reads images, makes images, talks.

### Where AI is good for you
"Fast, broad, tireless" — Adam Brown, Google DeepMind, *Training Sand to Think* (2026).
- **Patient tutor** — explain it again, simpler, with an example. It never judges the question.
- **Search by meaning** — find things when you don't know the right keyword. Open the source.
- **Brainstorming partner** — ten options in seconds; you pick.
- **Sparring partner** — "what's weak in this?", "what would a sceptical member say?"
- **Reviewer of its own work** — "check this against my notes and list the mistakes". Helps, but
  is not proof.
- **Drafting and reshaping** — first drafts, shorter, different tone, translation, notes → table.

### What AI does not do well
- It doesn't know your context — your members, your events, your history — unless you tell it.
- It doesn't collect the facts of your case; it fills gaps with plausible guesses.
- It doesn't know your priorities. It can rank, but only by criteria you give it.
- It doesn't make output unique — it gravitates to the typical (the regression line).
- It sounds equally confident when right and when wrong.
- It doesn't know today's news unless it searches — its knowledge has a cutoff.
- It doesn't own the result. You send it; you are responsible.

**AI proposes, you decide.**

### The context window
- Everything in a chat — your messages, its answers, files, search results — is one long text.
  Before every reply the model re-reads all of it and predicts what comes next.
- You build it together: each message steers the next answer.
- Nothing outside the window exists for it: not your inbox, not last week's chat (unless memory
  is on).
- New topic → new chat. Old material keeps pulling answers off course.

Idea from Andrej Karpathy, *How I use LLMs* (2025): the context window is the model's working memory.

### Elements of a good prompt
- **Context** — who you are, who it's for, the facts (paste the notes).
- **Task** — what exactly you want.
- **Format** — length, structure, tone.
- **Example** — optional: something that looks like what you want.
- **Limits** — "use only these facts", "don't mention X".

### Demo 1 — From one line to a useful draft
Fictional notes:

> Autumn member event, Thu 22 Oct 2026, 18:00–20:00, Atelier Linden, Zürich.
> Topic: better decisions from information. Free for members, 60 places.
> Register by Tue 20 Oct, 17:00. Link: example.com/autumn.
> Guest speaker invited, NOT confirmed — don't mention.

1. **The lazy prompt** (new chat, no notes): `Write an invitation for our autumn member event.`
   → polished, generic, invented details. The window held one line.
2. **Briefed:** paste the notes, then: `Write an invitation email for our members. Subject line
   plus max 110 words, warm but professional. Use only the facts in my notes. Don't mention the
   guest speaker.`
3. **Keep improving in the same chat:** `Shorter, and put the registration deadline in the first
   sentence.` — you didn't start over; you added to the window and steered.
4. **Let it check itself:** `Check your last draft against my notes. List every fact that is
   missing, changed or not in my notes.` — give it something to check against. It narrows your
   check; it doesn't replace it.
5. **Your own check:** date, time, place, deadline, link, no speaker, nothing extra promised.

Try it yourself: exercise 1 in this repository.

---

## Block 2 — From a prompt to a Project

A good invitation took a careful prompt and three rounds of fixes. Next week there's another
event, and a colleague needs the same. Now what?

### What a prompt cannot do
1. **Not repeatable.** A new chat starts blank. Your prompt and your fixes are gone.
2. **No additional data.** Everything must be pasted, every time.
3. **Not shareable.** You can send the text — but not the notes, the fixes, the full context.
   Your colleague gets a different result.

### A Project is a prompt that stays

| Part of a good prompt | Where it goes in a Project |
|---|---|
| Format, limits, example — what never changes | **Instructions** |
| Context — facts and reference material | **Files** |
| Task — what you want today | **A new chat in the Project**, one line |

- Repeatable: every chat starts with the same instructions and files.
- Additional data: files are there for every chat.
- Shareable: invite colleagues; they get the same instructions and files.
- Remembers the work: chats can build on earlier chats in the same Project.
- More consistent, not identical — it is still prediction. Test it on a new case.

### Demo 2 — Build the "Event invitations" Project
Instructions: the fixed part of the Block 1 prompt. Files: the event notes and an events
calendar. Then `Invitation for the autumn member event.` and, in a new chat,
`Invitation for the winter networking evening.` — same format, new facts, nothing retyped.

Try it yourself: exercise 2.

### Demo 2b — From an idea to a researched plan
Two more roles: **sparring partner** (it grills your idea) and **search by meaning** (it
researches it). Questions first, research second.

1. **Get grilled with a borrowed skill.** A skill is a saved way of doing a task that someone
   wrote down and shared. "Grilling" by Matt Pocock (MIT licence) interviews you in rounds —
   numbered questions, each with a recommended answer — until nothing is left assumed:
   `Read https://raw.githubusercontent.com/mattpocock/skills/main/skills/productivity/grilling/SKILL.md
   and follow it to grill me about my idea: offer candidate members free entry to the autumn
   event to raise attendance.` Answer a round in one line: "agree with all, except Q2: …".
2. **Research it with Web search:** `Research whether free or discounted entry actually raises
   attendance at professional and membership events. Give sources, say where the evidence is
   weak, and suggest other ways to reach the same goal.` Sources are leads, not facts — open two.
3. **Five-line plan:** the idea, what the evidence says, the main risk, one alternative.

You bring the idea and the judgement; AI brings questions, breadth and sources.
Try it yourself: exercise 3.

### Demo 3 — Share it
A colleague opens the shared Project and gets a consistent result from the same one-line request.
Shared: instructions and files. Not shared: your own progress and priorities.

### Keep it working
- A shared Project needs an **owner** and **dated files**. Stale files = confident wrong answers.
- Share information and know-how. Keep progress, priorities and next steps personal.
- Hand over context with a short note: goal, facts, decisions and why, open questions.
- "About me" personalisation is the same idea applied to all your chats.

---

## Block 3 — Use it safely, make it a habit

### "Confidential data went to an AI provider. So what?"
Usually nothing you will ever see. The risk is not a hacker — it is four ordinary paths:
1. **Someone else sees it.** In 2025 about 4,500 shared ChatGPT chats turned up in Google search —
   CVs, names, work documents. OpenAI removed the option.
2. **It stays longer than you think.** In 2025 a US court ordered OpenAI to keep chats users had
   deleted, and later to hand 20 million de-identified chats to a newspaper's lawyers.
3. **The wrong people are in the room.** A workspace or Project shared too widely shows your
   material to people who shouldn't see it.
4. **The breach is the sending, not a leak.** Data protection law cares where personal data went,
   even if nothing ever leaks.

### The badge list (a fictional story)
Someone pastes a registration export — names, emails, dietary and accessibility needs — into an
AI tool to make name badges. It works. They share the chat link with a volunteer, who forwards it.
Months later a member asks, under data protection law, which of their data the organisation holds
and whom it gave it to. Honest answer: an AI provider abroad, a volunteer, a stranger — stored
where, for how long, seen by whom: unknown.
**The bill:** no hacker, no leak anyone can prove — and still days of work, a complaint, a member
lost, trust damaged. **What would have prevented it:** names only. The badges still work.

### What can go where — the general pattern
Your organisation's rules decide the details. The general pattern:

| Type of information | Work AI account (with a contract) | Public AI (free or personal accounts) |
|---|---|---|
| Already published — website, programmes, press releases | ✅ | ✅ |
| Internal work without personal data — drafts, plans, budgets | ✅ if your rules allow | ❌ not public yet |
| Personal data — names, roles | only as your rules allow | ❌ |
| Contact details, identifiers, lists with emails | usually ❌ | ❌ |
| Confidential — contracts and fees, HR, health, payments, legal, board papers | ❌ no AI at all | ❌ no AI at all |

- **Public AI test:** would it be fine in a public search result tomorrow? If not, it doesn't go in.
- A text that mixes rows takes the strictest row.
- Not sure? Ask before you paste.

### Turn a real case into a safe question
Instead of `Member Anna Keller (anna.keller@…) lost her job and asks if she can pause her fees`,
ask: `A member asks whether they can pause their fees after losing their job. Draft a kind reply
with placeholders for the details.` Ask about the type of case; fill in the specifics yourself.
Try it yourself: exercise 4.

### You are the author
- Read every line. Check names, dates and numbers against the source — not against another AI answer.
- If AI shaped *what* it says, say so: *"Drafted with AI assistance; reviewed by [name]."*
- Pasted something you shouldn't have? Tell the responsible person the same day.

### The day in three lines
**AI predicts, you decide** · **a Project remembers and shares** · **know what goes where.**

### Your one task this week
Pick one recurring task from your own work. Try it with ChatGPT this week. Decide what "good"
looks like, and count the time you spend checking.

---

## Appendix — beyond ChatGPT

### A1 — Codex: an agent on your computer
- Chat answers; an agent acts: it reads and writes files, runs commands and looks things up, in
  steps, towards a goal you give it.
- **Plan mode:** before it touches anything, the agent drafts a step-by-step plan and waits. You
  correct and approve it; only then does it act. In ChatGPT the same habit is one sentence:
  `Before you start, propose a plan and wait for my OK.`
- This practice repository was tested by an agent playing a participant; it found four problems
  that were fixed before the session.
- An agent acts with your permissions: sandbox, approvals, and the same data rules — stricter.

### A2 — GitHub and skills
- GitHub is a shared folder with a history. ChatGPT can read a public repository from a link —
  that is how this practice works.
- A skill is a saved way of doing a task, often in a file called `SKILL.md`. Adopt one: find it →
  read it yourself → adapt it → put it in a Project → test it on a new case → give it an owner.

### A3 — "Grill me"
github.com/mattpocock/skills → `skills/productivity/grilling` (MIT licence). Paste it into a
Project's instructions and every chat in that Project starts by grilling you.

### A4 — From script to slides
- AI is great at agenda and script; it is weak at design.
- This session was built that way: the ideas came from people; AI structured, challenged,
  checked facts and wrote the script; slides came last.
- ChatGPT can create a PowerPoint file from a script: expect a usable skeleton, then take over
  the design. Double-check every number, name, date and link.
- Try it yourself: exercise 5.
