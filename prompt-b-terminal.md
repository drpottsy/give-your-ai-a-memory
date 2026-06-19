# Path B — The Terminal Prompt

For when you're ready for the real thing. This one runs in **Claude Code** (or **Cowork**), where Claude can read and write files itself. Make a new, empty folder for your business first, open Claude Code in it, and paste everything in the box as your first message. No more copy-pasting context: once this is done, Claude reads its memory on its own, every session.

(New to the terminal? Read *"The terminal isn't as scary as you think"* in the paper first. Install line is on Anthropic's own page.)

---

```
You are going to help me build a "business memory" for yourself: a small set of
plain files, saved right here in this folder, that hold what you need to know
about my business, so you start every future session already knowing it instead
of making me re-explain it. I am a business owner, not a developer. Keep
everything in plain English.

Before you write anything, these rules:

SAFETY.
- Work only inside this folder. Do not touch anything outside it.
- Do NOT overwrite or delete any file that already exists here. If a file you
  want to create already exists, stop and ask me before changing it.
- Show me the contents of every file before you save it. Save only after I say
  okay.

Then work in this order, and do not skip ahead.

1. Look around first. List what is already in this folder and tell me in a
   sentence or two what you think is here, so you build on it instead of talking
   over it.

2. Interview me. Ask ONE question at a time and wait for my answer before the
   next one. Cover, roughly in this order:
     - What my business is, and what I actually do day to day.
     - Who my customers are, and who my key suppliers or partners are.
     - The handful of names, terms, or facts you would otherwise get wrong.
     - A few decisions I have already made, and why (so you don't reopen
       settled questions later).
     - How I want you to work with me, and how I want you to write.
   Ask a follow-up when an answer is thin. Stop interviewing when you have
   enough to be genuinely useful, not when you have hit some quota.

3. Keep secrets OUT. No passwords, no account keys, no card or bank numbers.
   Prices and ordinary business facts are fine; anything that would unlock an
   account is not. If I start to hand you one, stop me.

4. Then create these files in this folder, showing me each one before you save:
     - CLAUDE.md: my constitution, the short rules file you will read on your
       own at the start of every session in this folder. Who I am, how to work
       with me, how to write, and the habit in point 5. Name it exactly
       CLAUDE.md at the top level of this folder. (In Claude Code this gets
       loaded automatically; in Cowork, just keep this folder connected.)
     - Business.md: my living memory. What my business is, my customers, my
       suppliers, my key terms, and a short "Decisions" list.

5. Put this habit into CLAUDE.md, in your own words: at the end of every working
   session, ask me whether anything from today should be saved into these files.
   Propose the exact lines. I approve or change them. Nothing is saved without
   my okay.

6. When the files are saved, prove it worked: tell me to start a brand-new
   session in this folder and ask you "what do you know about my business, and
   where did you learn it?" If you answer from these files and get it right, the
   memory is live. Tell me that is the test, and how to run it.

7. Last, tell me the truth about the limits: this is a strong starter, but you do
   not yet know which of my facts matter most, and these files will drift out of
   date unless I keep the habit in point 5. Deciding what is load-bearing, and
   keeping it alive, is the real work.

Begin by telling me in one sentence what we are about to do, then do step 1:
look around this folder.
```

---

**That's the whole thing.** From now on Claude walks into this folder already knowing your business, every single session, with nothing for you to paste. When you want it to grow into a system that doesn't just *remember* your business but *runs* one (a running log, an index, the rest of it), that's the next paper.
