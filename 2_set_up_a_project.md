# 2 — Set up a Project

So you don't start from zero every time. About 10 minutes. 5 steps.

**The idea:** a good prompt disappears when you open a new chat. A ChatGPT **Project** keeps
it: instructions and files stay in one place, every chat inside the Project starts with them,
and colleagues can use the same setup.

| Part of a good request | Where it goes in a Project |
|---|---|
| Format and limits — what never changes | **Instructions** |
| Context — facts and reference material | **Files** |
| Task — what you want today | **A new chat in the Project**, one line |

## Step 1 of 5 — Create the Project

**Why:** a Project is a folder for chats that share the same instructions and files.

In the ChatGPT sidebar, click **New project** and call it `Event invitations`.

**Notice:** the Project has its own space for instructions and files.

## Step 2 of 5 — Add the instructions

**Why:** these are the parts of your Exercise 1 prompt that never change — format and limits.

Open the Project's instructions and paste:

```
You help the events team write invitation emails for our members.
Format: a subject line plus max 110 words, warm but professional.
Put the registration deadline in the first sentence.
Use only facts from the Project files or from my message.
If a fact is missing, say so — do not guess.
Never mention speakers who are not confirmed.
```

**Notice:** no event facts here — those go into a file.

## Step 3 of 5 — Add the facts as a file

**Why:** facts live in a file, so you update one file instead of retyping them in every chat.

Open https://raw.githubusercontent.com/Amarows/ai-event-practice/HEAD/2_events_calendar.md , save it (Ctrl+S) and add it to the Project's files.

**Notice:** the file has a "last updated" date and an owner. Shared facts go stale — someone has
to keep them current.

## Step 4 of 5 — Use it

**Why:** now a one-line request is enough — the Project supplies the rest.

In a **new chat inside the Project**, type:

```
Invitation for the autumn member event.
```

Then another new chat in the Project:

```
Invitation for the winter networking evening.
```

**Notice:** same format, different facts, nothing retyped.

## Step 5 of 5 — Compare

**Why:** a Project makes results more consistent, not identical — it is still prediction.

Check both drafts against the calendar.

**Notice:** did it take the right facts for the right event? Did it follow the format rules?

**Next:** 3 — From an idea to a plan: use ChatGPT to question an idea and research it.

---

## Coach notes

- Winter evening facts: Thursday 3 December 2026, 18:30–21:00, Brasserie du Lac, Geneva, drinks
  and networking (no talk), members free, one guest each at CHF 25, register by Monday
  30 November, 12:00, example.com/winter.
- If they can't create Projects: paste the instructions and the calendar into a normal chat —
  it works once, but is gone next time. That is exactly the difference a Project makes.
- Sharing: a Project can be shared with colleagues — they get the same instructions and files.
  Share information and know-how; keep your own progress and priorities in your own chats.
- What they learned: prompt parts move into the Project — rules → instructions, facts → files,
  today's task → one line.
- Next: **3 — From an idea to a plan**: using ChatGPT to question an idea and research it.
