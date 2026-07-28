<h1 align="center">Memori</h1>

<p align="center">
  <b>A free flashcard app that helps you remember things for years, not days.</b><br>
  It comes with a music theory deck, but you can learn absolutely anything with it.
</p>

<p align="center">
  <a href="https://rohittabs.github.io/memori/"><b>Open Memori</b></a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-blue">
  <img alt="Price" src="https://img.shields.io/badge/price-free%20forever-brightgreen">
  <img alt="Files" src="https://img.shields.io/badge/whole%20app-1%20file-ec1e97">
  <img alt="Account" src="https://img.shields.io/badge/account-not%20needed-lightgrey">
  <img alt="Tracking" src="https://img.shields.io/badge/tracking-none-lightgrey">
</p>

---

## How to read this guide

This guide explains **every single button** in Memori. Every screen, every setting, every message.

You do not need to read it all. Here is the short version:

> Make a deck. Put cards in it. Open the deck, press **Review**, and answer honestly. Come back tomorrow. That is the whole app.

Everything below is detail for when you want it.

---

## Contents

**Part 1: Understanding the idea**
1. [What is a flashcard?](#1-what-is-a-flashcard)
2. [Why your brain forgets](#2-why-your-brain-forgets)
3. [What spaced repetition is](#3-what-spaced-repetition-is)
4. [Who actually uses this](#4-who-actually-uses-this)
5. [The four rules that decide whether this works for you](#5-the-four-rules-that-decide-whether-this-works-for-you)

**Part 2: Getting started**

6. [Opening Memori](#6-opening-memori)
7. [Putting it on your phone](#7-putting-it-on-your-phone)
8. [Your first five minutes](#8-your-first-five-minutes)

**Part 3: Every screen, every button**

9. [Getting around](#9-getting-around)
10. [The Home screen](#10-the-home-screen)
11. [The Deck screen](#11-the-deck-screen)
12. [The Deck editor](#12-the-deck-editor)
13. [The Card editor](#13-the-card-editor)
14. [Studying: the three modes](#14-studying-the-three-modes)
15. [Inside a study session](#15-inside-a-study-session)
16. [The finish screen](#16-the-finish-screen)
17. [The Revise screen](#17-the-revise-screen)
18. [The Stats screen, every number explained](#18-the-stats-screen-every-number-explained)
19. [The Settings screen](#19-the-settings-screen)

**Part 4: Reference**

20. [Every message the app can show you](#20-every-message-the-app-can-show-you)
21. [Keyboard shortcuts](#21-keyboard-shortcuts)
22. [Your data, backups, and moving devices](#22-your-data-backups-and-moving-devices)
23. [Questions people ask](#23-questions-people-ask)
24. [When something goes wrong](#24-when-something-goes-wrong)
25. [For developers](#25-for-developers)
26. [Licence and credits](#26-licence-and-credits)

---
---

# Part 1: Understanding the idea

## 1. What is a flashcard?

A flashcard is a card with a **question on the front** and the **answer on the back**.

```
   FRONT                    BACK
┌──────────────┐        ┌──────────────┐
│              │        │              │
│  What is     │  flip  │              │
│  the capital │ ─────► │    Paris     │
│  of France?  │        │              │
│              │        │              │
└──────────────┘        └──────────────┘
```

You look at the front. You **try to remember** the answer before you flip it. Then you flip and see if you were right.

That last part is the important bit. Reading the answer straight away teaches you almost nothing. The effort of digging the answer out of your own head is what builds the memory. Scientists call this **active recall**, and it is far stronger than re-reading: active retrieval combined with spacing produced 150% better long-term retention compared to restudying.

Think of it like a path through a forest. Reading your notes is like *looking* at the path. Recalling the answer is like *walking* it. Walk it enough times and it becomes a road.

Paper flashcards have existed for over a century. Memori does the same thing, with one huge addition, explained in section 3.

---

## 2. Why your brain forgets

In 1885, a German psychologist called **Hermann Ebbinghaus** did an experiment on himself. He memorised lists of nonsense syllables, then tested how much he still knew as days passed.

What he found is now called the **forgetting curve**, and it is brutal. Ebbinghaus (1885) demonstrated that 67% of learned material is forgotten within 24 hours without review.

Roughly, without review:

| Time since you learned it | How much you still remember |
| --- | --- |
| Right now | 100% |
| 20 minutes | about 60% |
| 1 hour | about 50% |
| 1 day | about 33% |
| 1 week | about 25% |
| 1 month | about 10% |

This is not a personal failing. This is how every human brain works. Your brain is not a hard drive, it is a filter, and it throws away anything that does not look important.

**Here is the trick.** Ebbinghaus also found that *each time* you review something, the forgetting slows down. The curve gets flatter. Reinforce it enough times and it stops dropping in any meaningful way.

The forgetting curve is exponential: memory loss is biggest in the first days, and later you still forget but the rate is much, much slower.

So the question becomes: **when exactly should you review?**

---

## 3. What spaced repetition is

Imagine your memory of a fact is a **bucket with a small hole in the bottom**.

- When you first learn something, the bucket is full.
- It slowly leaks.
- If you top it up **just before it runs empty**, two things happen:
  1. The bucket refills.
  2. **The hole gets smaller.** So next time it takes much longer to drain.

That is spaced repetition. Review at growing gaps, timed so each review lands just before you would have forgotten.

### Why the timing matters so much

Review **too early** and you are wasting time on something you already know solidly.

Review **too late** and you have forgotten it, so you are relearning from scratch.

Review at **just the right moment**, when it is slightly hard to recall, and the memory gets dramatically stronger. Giving the brain more time to almost forget a fact before reviewing it actually improves the quality of the memory.

That awkward "ugh, wait, I know this..." feeling is not failure. **That feeling is the entire mechanism working.**

### What the research says

This is one of the most tested findings in all of psychology.

- Cepeda et al.'s (2006) meta-analysis of 254 studies confirmed that distributed practice produces 10-30% better retention than massed practice.
- Ebbinghaus (1885) found that practicing in intervals was more effective than rehearsing in one long stretch, meaning cramming for an exam almost never works.
- Adaptive spacing algorithms, like the one in this app, outperform fixed spacing schedules by adjusting review intervals based on individual performance.

### What it looks like in real numbers

Take one brand new card. Every time you see it, you press **Good**, meaning you remembered it. Here is exactly what Memori schedules:

| Which review | You see it again in |
| --- | --- |
| 1st | 1 day |
| 2nd | 3 days |
| 3rd | 8 days |
| 4th | 20 days |
| 5th | 50 days |
| 6th | 125 days |

Look at what happened. **Six short reviews spread over about six months**, and now that fact only needs checking about three times a year. It is, for practical purposes, yours.

Now compare cramming. Read the same fact 6 times in one evening and you will know it tonight and have lost it by Friday. Same six repetitions. Completely different outcome. The only difference is **when** they happened.

---

## 4. Who actually uses this

This is not a study hack from the internet. It is standard equipment in some of the hardest fields there are.

### Doctors and medical students

This is the biggest user group in the world, by a distance. Medical students have to memorise an amount of detail that is genuinely absurd: every muscle, every drug, every dose, every interaction, every rare disease and its symptoms.

In one survey, most students identified as Anki users (94%), with 87.8% believing it significantly contributes to their success in modules. Anki is the best known spaced repetition app, and Memori works on the same principle.

The results show up in exams. In one cohort study, the percentage of "mature" cards a student had was the only statistically significant predictor of course exam performance, explaining over a third of score variability.

That word **mature** matters, and Memori shows you the same number on your Stats screen. Section 18 explains it.

Interestingly, 56.6% reported multitasking with Anki during activities like exercising or eating, which tells you something about how these apps get used in practice: small pockets of time, every day.

### Language learners

The classic use. One card per word, per phrase, per character.

This is where Memori's **audio** feature earns its place. You can record yourself saying a word and compare it to a native speaker, which is worth more than reading it fifty times. Section 13 covers recording.

### Musicians

Note names, key signatures, intervals, chord formulas, how a mode sounds. The starter deck that ships with Memori is exactly this.

The **image** feature matters here. A card can show a bar of sheet music and ask what chord it is.

### Everyone else

- **Law students**: case names, statutes, definitions
- **Pilots**: checklists, regulations, airport codes
- **Nurses**: drug names and dosages
- **Programmers**: syntax, shortcuts, commands
- **Anyone with a new job**: names and faces of colleagues, using photos
- **Anyone taking any exam at all**

The app does not know or care what your cards contain.

---

## 5. The four rules that decide whether this works for you

Read these four things and you will avoid every mistake beginners make.

### Rule 1: Be honest with the buttons

Memori cannot see you. It only knows which button you pressed.

If you press **Good** on a card you barely dragged out of your memory, you have just told the app "make the gap two and a half times longer." You will then see that card in 50 days when you needed it in 5, you will fail it, and you will conclude the app does not work.

Be honest and it works. Be generous with yourself and it collapses. It really is that simple.

Experienced users have a trick: **say the answer out loud before you flip.** It stops you from reading the answer and thinking "yeah, I knew that," when you did not.

### Rule 2: One card, one fact

The single most common beginner mistake is making cards that are too big.

**Bad card:**

> Front: Explain the circle of fifths
> Back: (nine sentences)

That is not a flashcard, it is a lecture wearing a costume. You will never be able to grade it honestly, because you will always get *part* of it right.

**Good cards:**

> Front: How many sharps are in the key of D major? → Back: Two
> Front: Which note comes after G in the circle of fifths? → Back: D
> Front: What does the circle of fifths help you find? → Back: Key signatures and closely related keys

Small cards are answered faster, remembered better, and are far less painful to review. If a card takes you more than about 15 seconds, split it up.

### Rule 3: A little, every day

Ten minutes every day beats two hours every Sunday. The whole system is built around daily gaps. Skipping days creates a pile-up, and a pile-up makes you quit.

This is why Memori has a **streak** counter and a **daily goal**.

### Rule 4: Do not add too many new cards at once

Every new card you add today is a small permanent obligation. Roughly, **each new card generates about 8 to 10 reviews over the following year**.

So 20 new cards a day means roughly 200 daily reviews once things settle. That is why Memori defaults to 20 new per day and enforces it. The limit is not there to slow you down, it is there to stop future-you from drowning.

---
---

# Part 2: Getting started

## 6. Opening Memori

Go to **[rohittabs.github.io/memori](https://rohittabs.github.io/memori/)**.

That is it. No download, no sign up, no account, no payment.

The first time it opens, Memori creates a starter deck called **General Knowledge** with 23 music theory cards, so you have something to press buttons on. Delete it whenever you like.

**Where your stuff is kept:** on your own device, inside your browser's storage. Not on a server. Nobody, including me, can see your cards. This also means it does not sync between devices by itself, see section 22.

---

## 7. Putting it on your phone

Memori can live on your home screen with its own icon, and open with no browser bar around it, exactly like an app from the app store.

**On iPhone or iPad**

1. Open the link **in Safari**. This does not work in Chrome on iPhone.
2. Tap the **Share** button, the square with an arrow pointing up.
3. Scroll down and tap **Add to Home Screen**.
4. Tap **Add**.

**On Android**

1. Open the link in Chrome.
2. Tap the **three dots** menu.
3. Tap **Install app**, or **Add to Home screen**.

**On a computer**

1. Open the link in Chrome or Edge.
2. Look at the right hand end of the address bar for a small **install icon**.
3. Click it, then click **Install**.

Once installed it launches instantly and works whether you are online or not, because your cards live on the device.

---

## 8. Your first five minutes

| Step | What to do | What you should see |
| --- | --- | --- |
| 1 | Tap the deck **General Knowledge** | The deck screen, with 23 cards listed |
| 2 | Tap **Flip** | A question, with "Tap to reveal answer" underneath |
| 3 | Read the question. **Try to answer it in your head.** | Nothing yet, this bit is you |
| 4 | Tap the card, or tap **Show answer** | The answer appears |
| 5 | Tap **Still learning** or **I know it**, honestly | The next card |
| 6 | Keep going to the end | The finish screen with your accuracy |
| 7 | Tap **Done**, then go to **Stats** | Your numbers, now with something in them |

Now do the real thing:

| Step | What to do |
| --- | --- |
| 8 | Go back to the deck and tap **Review** instead of Flip |
| 9 | Notice you now get **four** buttons instead of two, each with a number of days on it |
| 10 | Those numbers are real. This mode is the one that schedules your cards |

The difference between Flip and Review is the single most important thing to understand about this app. Section 14 covers it properly.

---
---

# Part 3: Every screen, every button

## 9. Getting around

Memori has **five main places**. How you reach them depends on your screen size, but they are the same five.

### On a computer (wide screen)

A **sidebar** runs down the left:

| Item | Icon | What it does |
| --- | --- | --- |
| **Decks** | Two stacked cards | Home screen, your deck list |
| **Study** | Play triangle | Starts reviewing whatever is due, right now |
| **Revise** | Circular arrow | Practice screen, nothing is recorded |
| **Stats** | Line chart | All your numbers |
| **Settings** | Gear | Preferences and your data |

Below the sidebar there is a **Study now** button in a pink to purple gradient, with a number next to it. That number is how many cards are due. It does exactly the same thing as the sidebar **Study** item, it is just placed where your hand already is.

### On a phone (narrow screen)

A **tab bar** across the bottom, with the same five: **Home, Study, Revise, Stats, Settings**.

Five is the maximum any interface should put in a bottom bar, because tap targets get too small beyond that. Memori sits exactly at that limit.

There is also a round **+** button floating above the tab bar on the right. It creates a new deck.

### One thing worth knowing about Study

**Study is not a place, it is an action.** Tapping it does not open a screen called Study. It looks at every deck, finds the one with the most cards due, and starts a review session there immediately.

If **nothing** is due anywhere, it takes you to the **Revise** screen instead and tells you nothing is due. It will not silently start a random session.

### Getting back

Any screen you drill into has a **back arrow** in the top left. During a study session the same corner has an **X**, which leaves the session.

---

## 10. The Home screen

This is where you land. From top to bottom:

### The header

| Element | What it is |
| --- | --- |
| **Memori** logo and name | Top left |
| **"Remember on purpose"** | The tagline, sits under the name |
| **Greeting** | "Good morning", "Good afternoon" or "Good evening", based on your device clock |
| **Gear icon** | Top right, jumps straight to Settings |

### The hero card (the big coloured one)

The most eye-catching thing on the screen, a pink to purple gradient block.

| Element | What it shows |
| --- | --- |
| **Kicker text** | The greeting again, in small capitals |
| **Big number** | How many cards are due today |
| **Label** | "cards due today", or "card due today" if it is exactly 1 |
| **Button** | Says **Review now** if anything is due, or **Study a deck** if nothing is |

**How the big number is worked out.** This is not simply "everything that is overdue." Memori also respects your daily limits:

```
new allowance    = your new-per-day limit  minus  new cards already done today
review allowance = your reviews-per-day limit minus reviews already done today

Due today = min(new allowance, new cards actually waiting)
          + min(review allowance, review cards actually waiting)
```

**Example.** Your limit is 20 new per day. You have three decks with 30 brand new cards each, so 90 are technically waiting.

```
new allowance = 20 - 0 done = 20
new waiting   = 90
smaller one   = 20

Due today = 20
```

It says **20**, not 90, because 20 is genuinely all you are allowed today. Study 12 of them and it recalculates to 8.

### The two small cards

| Card | What it shows |
| --- | --- |
| **Day streak** | A flame icon, a number, and a ring that fills as the streak grows |
| **Min today** | Minutes you have studied today |

**How the streak is counted.** Memori starts at today. If you have studied today, it counts today. If you have not studied today *yet*, it starts from yesterday instead, so your streak is not destroyed at one minute past midnight. Then it walks backwards a day at a time and stops at the first day with nothing.

So if you studied Monday, Tuesday and Wednesday, your streak on Wednesday is **3**. Skip Thursday entirely and on Thursday evening it still says 3, because it falls back to Wednesday. Skip Friday as well and it drops to 0.

### Your collection

A white card containing a **donut chart** and a legend.

- The number in the middle of the donut is your **total card count**
- The word **CARDS** sits under it
- Four coloured slices, one per card state

| Colour | State | Meaning |
| --- | --- | --- |
| Teal | **Mature** | Interval of 21 days or more, you properly know it |
| Blue | **Young** | Interval of 7 to 20 days, it is sticking |
| Amber | **Learning** | Interval of 1 to 6 days, still bedding in |
| Grey | **New** | Never answered |

Each legend row shows the state name and a count.

**How a slice is sized:** that state's count divided by your total, as a percentage. 100 cards with 40 New means the grey slice takes 40% of the ring. A slice with almost nothing in it is not drawn at all, so a single card does not become an ugly sliver.

**What to look for:** at the start your donut is nearly all grey. That is normal. Over months you want the **teal** slice growing. That slice is the entire point of the app.

**All stats ›** in the corner jumps to the full Stats screen.

### Decks

A heading with a **+ New** button beside it, then one tile per deck.

Each deck tile shows:

| Element | What it shows |
| --- | --- |
| **Coloured stripe** | Down the left edge, in the deck's own colour |
| **Deck name** | Bold |
| **Description** | Small grey text, if you wrote one |
| **Card count** | For example "23 cards" |
| **Due badge** | For example "8 due", only when something is due |
| **Percentage ring** | A circle on the right showing how much of that deck is Mature |

The ring percentage is: **mature cards in that deck ÷ total cards in that deck × 100**. A deck of 50 cards with 12 mature shows `12 ÷ 50 = 0.24`, so **24%**.

Tap anywhere on a tile to open that deck.

### If you have no decks

You get an empty state instead:

> **No decks yet**
> Create your first deck to start learning. Add text, images, and audio to any card.
> **[ Create a deck ]**

---

## 11. The Deck screen

Tap any deck to get here.

### The coloured header

A block in the deck's own colour, containing:

| Element | What it is |
| --- | --- |
| **Back arrow** | Top left, returns to Home |
| **Pencil icon** | Top right, opens the Deck editor |
| **Bin icon** | Top right, deletes the deck |
| **Deck name** | Large |
| **Description** | Underneath, if you wrote one |
| **Three numbers** | Cards, % mature, due now |

**The bin icon asks first.** You get a confirmation naming the deck, and deleting removes every card in it plus every image and sound those cards held. There is no undo.

### The three mode buttons

Side by side: **Flip**, **Review**, **Quiz**. Review is highlighted because it is the important one.

Underneath them is a line of small text:

> Review is the scheduled mode, it updates your cards and counts towards statistics. Flip and Quiz are revision, they change nothing.

Section 14 explains all three properly.

### The four state boxes

A 2x2 grid: **New**, **Learning**, **Young**, **Mature**. Each box shows a coloured dot, the state name, a count, and what percentage of the deck that is.

### The card list

A heading such as "23 CARDS" with **+ Add card** beside it.

Then a **search box** reading "Search this deck", and next to it a **star button**.

- **Search** matches the question text, the answer text, **and** the tags. Typing `scales` finds every card tagged "scales" plus any card with that word in it.
- **Star button** toggles "show only starred cards". Tap again to show all.

Then one row per card:

| Element | What it shows |
| --- | --- |
| **Coloured stripe** | Left edge, the deck colour |
| **Front text** | Bold, the question |
| **Back text** | Grey, the answer |
| **State chip** | NEW, LEARNING, YOUNG or MATURE |
| **Interval chip** | When it is next due: "New", "due", "in 1d", "in 2w", "in 3mo" |
| **Tag chips** | Any tags you added |
| **Image icon** | If the card has pictures |
| **Audio icon** | If the card has sound |
| **Bin icon** | On the right, deletes that one card |

Tap a row to open the Card editor. The bin asks "Delete this card?" first.

### If the deck is empty or nothing matches

> **This deck is empty** / Add your first card to begin.

or, when a search finds nothing:

> **No cards match your search.**

---

## 12. The Deck editor

Opens when you tap **+ New**, the **+** floating button, or the **pencil** on a deck.

The title reads **New deck** or **Edit deck**.

| Field | What it does |
| --- | --- |
| **Deck name** | The name. Placeholder shows "e.g. French Verbs". Required. |
| **Description** | Optional note to yourself. Placeholder shows "Optional". |
| **Color** | Eight swatches |

The eight colours are **Magenta, Grape, Indigo, Ocean, Forest, Gold, Sunset and Slate**. The selected one gets an outline. Colour is purely visual, it helps you tell decks apart at a glance and it is what colours the deck's chips in the Coming up forecast.

At the bottom: **Cancel**, and **Create deck** (or **Save** when editing).

The save button is faded out until you type a name.

---

## 13. The Card editor

Opens when you tap **+ Add card** or tap any existing card row.

The title reads **New card** or **Edit card**.

### The two sides

The editor has a **Front (question)** section and a **Back (answer)** section. They are identical in what they can hold.

For each side:

| Control | What it does |
| --- | --- |
| **Text box** | The words. Front placeholder: "Type the question". Back placeholder: "Type the answer". Any length. |
| **Image button** | Attach pictures. You can add as many as you like. |
| **Audio button** | Attach sound files. As many as you like. |
| **Record button** | Records straight from your microphone. Tap it and it becomes **Stop**. |

Attached items appear as thumbnails or players with a small **x** on each to remove it.

**About recording.** Your browser will ask permission for the microphone the first time. If you decline, you get the message "Microphone permission needed". Some browsers do not support it at all, in which case you get "Recording not supported here".

Recording is genuinely one of the most useful features here. For a language, recording yourself saying a word and comparing it to a native speaker teaches your mouth as well as your memory.

### The extras

| Field | What it does |
| --- | --- |
| **Hint (optional)** | A small nudge. Placeholder: "A little nudge". During study a **Show hint** button appears, and tapping it reveals this without showing the answer. Good for "starts with B" or "think about the left hand". |
| **Tags, comma separated** | Placeholder: "e.g. music, theory". Type a list. These become searchable chips. |
| **Star icon** | Marks the card as one that keeps catching you out. Starred cards can be filtered on the deck screen. |

### On an existing card only

A small line of statistics:

> Reviews 4, lapses 1, interval 20d

- **Reviews** is how many times you have answered it
- **Lapses** is how many times you pressed Again on it
- **Interval** is the current gap in days

Next to it, **Reset progress**. This asks:

> Reset this card to new? It becomes due now. Past reviews stay in your stats.

So the card's schedule goes back to zero, but your history is not rewritten. Useful when you realise you never really learned something.

### At the bottom

**Cancel**, and **Add card** (or **Save card** when editing).

If you try to save without both a front and a back, you get: **"Add a front and a back"**.

---

## 14. Studying: the three modes

This section is the most important one in the guide.

### The short version

| Mode | Cards it shows | Grades | Does it change your schedule? | Does it count in Stats? |
| --- | --- | --- | --- | --- |
| **Flip** | Every card in the deck, shuffled | 2 buttons | **No** | **No** |
| **Review** | Only cards actually due, oldest first | 4 buttons | **Yes** | **Yes** |
| **Quiz** | Multiple choice from the deck | Automatic | **No** | **No** |

**Review is the real one.** Flip and Quiz are practice. They change nothing at all.

### Flip

Every card in the deck in random order. You see the question, tap, see the answer, then choose:

- **Still learning**
- **I know it**

Use it when you want to run casually through a deck, or when you are meeting a deck for the first time and just want to see what is in it.

Because it is untracked, you can do it as many times as you like without any consequence.

### Review

**This is the mode that does the real work.**

It shows only cards that are actually due, oldest first, and respects your daily limits. You get four buttons, each labelled with the exact gap it will schedule.

If nothing is due it will not start, and you get the message **"Nothing due. Great work!"** That is not a bug. It means you are finished for today, and studying early would make the cards stick *less* well.

### Quiz

Multiple choice. Memori shows the question and four possible answers: the right one, plus three borrowed from other cards' answers in the same deck.

You need **at least 2 cards with answer text** for Quiz to work, otherwise you get **"Need at least 2 cards with answers"**, because it has nowhere to steal wrong options from.

Be aware Quiz is **easier** than the other modes. Recognising the right answer in a list is much easier than pulling it out of your head cold. Treat it as a light session, not your main method.

### Why Flip and Quiz do not count

Earlier versions of Memori let Flip and Quiz change your schedule, which caused a real problem: a casual flip through a deck would silently reschedule 20 cards, and then the app would tell you nothing was due for two days.

Now they are honest practice. During a Flip or Quiz session the header says so:

> General Knowledge · Revising, Flip, nothing is saved

and the two buttons show **no** day numbers, because no days are being scheduled.

---

## 15. Inside a study session

The session takes over the whole screen. Top to bottom:

### The top bar

| Element | What it does |
| --- | --- |
| **X button** | Leaves the session. Progress on cards you already answered is kept. |
| **Progress bar** | Fills as you work through the queue |
| **Counter** | For example "1 / 23" |

Underneath, a line naming the deck and the mode:

- `General Knowledge · Spaced review` in Review mode
- `General Knowledge · Revising, Flip, nothing is saved` in Flip
- `General Knowledge · Revising, Quiz, nothing is saved` in Quiz

### The card

A large white card with a small label at the top reading **QUESTION**, then the text.

If the card has images they appear here. If it has audio, a player appears.

At the bottom of the card: **Tap to reveal answer**.

If the card has a hint, a **Show hint** button appears. Tapping it reveals the hint only.

### Revealing

Tap the card itself, or press the **Show answer** button underneath.

The label changes to **ANSWER** and the back of the card shows, including its own images and audio.

**Audio autoplay.** If the setting is on (it is by default), the first audio clip on the back plays automatically when you reveal.

### Grading in Flip mode

Two buttons:

| Button | Colour | Meaning |
| --- | --- | --- |
| **Still learning** | Red | I did not know it |
| **I know it** | Teal | I knew it |

No day numbers, because nothing is being scheduled.

### Grading in Review mode

Four buttons, each with the real gap printed underneath:

| Button | Press it when |
| --- | --- |
| **Again** | You did not know it. Wrong, or no idea. |
| **Hard** | You got it right, but it was a struggle. |
| **Good** | You got it right with normal effort. **This is the one you will press most.** |
| **Easy** | You knew it instantly. Felt too obvious. |

**The maths behind those four buttons.**

Every card carries two hidden numbers:

1. **Interval**, how many days until you see it again. New cards start at 0.
2. **Ease**, how generous the app is with this particular card. Starts at **2.50**, never drops below **1.30**.

| Button | Ease changes by | New interval becomes |
| --- | --- | --- |
| **Again** | minus 0.20 | 0, comes back today, and a lapse is recorded |
| **Hard** | minus 0.15 | old interval × 1.2 |
| **Good** | no change | old interval × ease |
| **Easy** | plus 0.15 | old interval × ease × 1.3 |

With two special cases at the very start, before multiplying makes sense:

- **First** time you answer a card: Good and Hard both give **1 day**, Easy gives **2 days**
- **Second** time: Good gives **3 days**
- **Third** time onwards, the multiplying above applies

**A full worked example.** A card sitting at **20 days** with ease **2.50**:

```
Press Again:
   ease:     2.50 - 0.20 = 2.30
   interval: back to 0
   result:   returns today, lapses +1

Press Hard:
   ease:     2.50 - 0.15 = 2.35
   interval: 20 × 1.2     = 24
   result:   24 days

Press Good:
   ease:     unchanged     = 2.50
   interval: 20 × 2.50     = 50
   result:   50 days

Press Easy:
   ease:     2.50 + 0.15   = 2.65
   interval: 20 × 2.65 × 1.3 = 68.9, rounds to 69
   result:   69 days
```

Note Easy uses the **new** ease of 2.65, not the old 2.50. That is why Easy pulls away so quickly.

You never need to remember any of this. Each button prints its own answer.

**How ease drifts over time.**

A card you keep finding hard:

```
Start:                     ease 2.50
Press Hard:  2.50 - 0.15 = 2.35
Press Hard:  2.35 - 0.15 = 2.20
Press Again: 2.20 - 0.20 = 2.00
```

A card you keep finding easy:

```
Start:                     ease 2.50
Press Easy:  2.50 + 0.15 = 2.65
Press Easy:  2.65 + 0.15 = 2.80
```

The floor is 1.30. No matter how many times you fail a card, it can never get harsher than that.

### Grading in Quiz mode

Tap one of the four options. Memori tells you immediately whether it was right, then a **Next** button appears, which reads **See results** on the final question.

---

## 16. The finish screen

When the queue empties you get a summary.

| Element | What it shows |
| --- | --- |
| **Big ring** | Your accuracy for this session, as a percentage |
| **Praise line** | Depends on how you did, see below |
| **Correct** | How many you got right |
| **Time** | How long the session took, such as "4m 12s" |
| **Mastered** | How many cards crossed into Mature during this sitting |

**The praise line:**

| When | It says |
| --- | --- |
| Review, 80% or above | Brilliant work |
| Review, 50% to 79% | Nicely done |
| Review, under 50% | Keep practicing |
| **Flip or Quiz, any score** | **Revision finished, nothing was saved** |

Two buttons at the bottom:

- **Study again** starts another session in the same deck
- **Done** returns you to where you were

---

## 17. The Revise screen

Reached from **Revise** in the sidebar or bottom bar, and automatically when you press Study with nothing due.

**What this screen is for:** practising freely without touching anything. Nothing you do here is recorded, scheduled, or counted.

### What is on it

**An intro line**, which changes depending on your situation:

- If cards are due: *"You have 8 cards waiting in Study. Revising here is extra practice on top of that."*
- If nothing is due: *"Nothing is due right now. Revising will not disturb your schedule."*

**A review button**, shown only when cards are actually due, reading for example **Review 8 cards**. This starts a proper tracked session, so you do the real work first if you want to.

**Revise a deck**, a list of every deck you own. Each row has:

- A coloured stripe in the deck's own colour
- The deck name
- The card count
- A **Flip** button
- A **Quiz** button

**A closing note:**

> Revising never changes a card's schedule, its state or your statistics. Every card comes back exactly as it was.

### Why this exists

Two reasons.

First, sometimes you want to run through a deck before an exam without disturbing months of carefully built scheduling. This is the safe place to do that.

Second, before this screen existed, pressing **Study** with nothing due would silently start a Flip session on some random deck, which was baffling. Now it brings you here and explains itself.

---

## 18. The Stats screen, every number explained

This is the part people find confusing, so here is every number, what it means, the exact sum behind it, and a worked example.

### The example used throughout

Imagine you have studied on three days. This is everything Memori knows about you:

| Day | Cards studied | Got right | Time |
| --- | --- | --- | --- |
| Monday | 10 | 8 | 5 minutes |
| Tuesday | 12 | 11 | 6 minutes |
| **Wednesday (today)** | **8** | **7** | **4 minutes** |
| **Totals** | **30** | **26** | **15 minutes** |

Every number below comes from that table.

---

### 18.1 The six boxes at the top

#### Current streak

Days in a row you have studied, counting back from today, with the midnight grace period described in section 10.

Underneath it shows your **best streak**, the longest run you have ever managed. Memori lists every day you studied, sorts them, and finds the longest unbroken chain.

**Example.** You studied on:

```
Jan 1, Jan 2, Jan 3,  [gap],  Jan 8, Jan 9,  [gap],  Jan 15

Chain 1: Jan 1 to Jan 3 = 3 days
Chain 2: Jan 8 to Jan 9 = 2 days
Chain 3: Jan 15         = 1 day

Best streak = 3 days
```

In our three-day table, current streak = **3**.

#### Reviews today

How many cards you answered today. From the table, Wednesday = **8**.

Important: this counts **answers**, not cards. Press Again and the card returns later in the same session, and answering it again adds 1 more. So 8 answers might be 6 different cards, two seen twice.

Underneath, your goal progress:

```
Goal % = reviews today ÷ your goal × 100, capped at 100
```

With the default goal of 40 and 8 done today:

```
8 ÷ 40 = 0.2
0.2 × 100 = 20%
```

It reads **goal 40, 20% there**. It never goes above 100%, so a huge day does not read 300%.

#### Retention

**This is the one people misread most. Read this bit twice.**

Out of every answer you have ever given, the share that were right. Your all-time accuracy.

```
Retention = total correct ÷ total studied × 100
```

From our table:

```
26 ÷ 30 = 0.8666...
0.8666... × 100 = 86.66...
rounds to 87%
```

**What counts as correct:**

| Mode | Correct | Not correct |
| --- | --- | --- |
| Review | Hard, Good or Easy | Again |
| Flip | I know it | Still learning |
| Quiz | Right option | Wrong option |

Hard counts as a success. You did remember it, it was just slow.

**Now the important part: what is a good number?**

Your instinct says higher is better and 100% would be perfect. **That is wrong.**

If you score 100%, every card you were shown was one you already knew solidly. You did not need to see any of them. You spent that time confirming rather than learning.

If you score 50%, you are being shown cards long after you forgot them, and you are relearning from scratch every time. Slow and demoralising.

**The sweet spot is around 85 to 90 percent.** At that level you are being pushed just hard enough that recall takes effort, and effort is what builds memory. A bit of forgetting is the engine, not the failure.

So 87% is healthy. If yours sits at 97% for weeks, raise your target retention so cards space out further and get harder.

**One warning.** This number covers your entire history forever. After a thousand reviews, one bad day barely moves it. Good long-run health check, useless as a daily one. For "how am I doing right now", use the Accuracy trend.

#### Mature cards

How many cards have an interval of 21 days or more.

Shown as, for example, **15**, with "of 100, interval past 21 days" underneath.

This is arguably the truest measure of progress in the whole app. Not how much you have studied, but how much has actually stuck. It is also the number that predicted exam performance in the medical school research quoted in section 4.

#### Time studied

Every session length added together. From our table, 5 + 6 + 4 = **15m**. Once it passes an hour it shows as hours, such as "3h 25m".

Underneath, **seconds per card**:

```
Seconds per card = total seconds ÷ total answers
```

15 minutes is 900 seconds over 30 answers:

```
900 ÷ 30 = 30.0
```

Shows **30.0s per card**.

**What to do with it.** Most people settle between 5 and 15 seconds. Much higher and your cards are too big, see Rule 2 in section 5.

#### Avg stability

The average interval across every card you have actually studied. New cards are ignored, because they have no interval yet.

```
Avg stability = sum of intervals of studied cards ÷ number of studied cards
```

**Example.** Five studied cards with intervals of 3, 8, 20, 21 and 50 days, plus 40 new cards:

```
3 + 8 + 20 + 21 + 50 = 102
102 ÷ 5 = 20.4
rounds to 20 days
```

Shows **20d**. The 40 new cards are not in the sum at all.

The subtitle says *"days until recall drops to 90%"*. That is not poetic, it is literally what an interval means here. A 20 day interval is Memori's estimate that after 20 days you have about a 90% chance of still remembering.

**What to look for:** this should climb slowly over months. If it stalls, you are adding new cards faster than you are maturing old ones.

---

### 18.2 Study activity (the heatmap)

A grid of small squares. Each square is one day, covering the last **15 weeks**. Columns are weeks, rows are days. A **Less** to **More** legend sits underneath.

**How the shading works.** This surprises people: the colours are **relative to your own busiest day**, not to any fixed number.

Memori finds the day you studied most in the window and calls that the maximum. Then:

| Cards that day | Shade |
| --- | --- |
| 0 | Empty |
| More than 0, under 25% of your best | Lightest |
| 25% to 49% | Light |
| 50% to 74% | Dark |
| 75% or more | Darkest |

**Example.** Your busiest day was **40 cards**:

```
25% of 40 = 10
50% of 40 = 20
75% of 40 = 30
```

| That day you did | Shade |
| --- | --- |
| 0 | empty |
| 3 | lightest |
| 9 | lightest |
| 10 | light |
| 19 | light |
| 20 | dark |
| 29 | dark |
| 30 | darkest |
| 40 | darkest |

**A consequence worth knowing.** One monster day of 200 cards drags the scale so far up that all your normal 20-card days look nearly empty. The heatmap is about **consistency**, not volume. Chase an unbroken grid, not dark squares.

---

### 18.3 Reviews, last 14 days

One bar per day for the last fortnight, each split into two colours with a legend reading **recalled** and **forgotten**.

**Bar height** is relative to the busiest of those 14 days:

```
Bar height = cards that day ÷ busiest day × 100%
```

with a minimum of 7% so a tiny day is still visible, and a 3% stub for days you did nothing.

**The split:**

```
Recalled part  = correct ÷ studied × 100%
Forgotten part = (studied - correct) ÷ studied × 100%
```

**Example.** Tuesday: 12 studied, 11 correct.

```
forgotten = 12 - 11 = 1
recalled  = 11 ÷ 12 = 0.9166... = 92%
forgotten =  1 ÷ 12 = 0.0833... =  8%
```

So Tuesday's bar is 92% teal and 8% red.

**What to look for.** A red section that keeps growing means either your cards are too hard, or you are pressing Good on things you did not really know, or your target retention is too low.

---

### 18.4 Coming up

Shows what is already booked in for the next three weeks.

**The bar chart.** 21 bars, one per day, today in a different colour. Labels read **Today** on the left and **3 weeks** on the right.

These bars count **only cards with a real scheduled date**. Brand new cards are deliberately excluded, because a new card has no due date, and piling them all onto today made a fresh deck look like an enormous spike.

**The new card note.** If you have cards that have never been reviewed, a small box says so:

> 3 new cards are ready, no date yet

**The day-by-day breakdown.** Under the chart, one row per day that actually has cards. Empty days are skipped.

Each row shows:

| Part | What it is |
| --- | --- |
| **Left** | The day: "Today", "Tomorrow", or a short date like "Sat 2 Aug" |
| **Middle** | One chip per deck, each with a coloured square in that deck's own colour, the deck name, and the count |
| **Right** | The total for that day |

**Example row:**

```
Tomorrow    [■ Music 2]  [■ Spanish 1]              3 cards
```

At most six rows are shown. If there are more days beyond that, a small line says "and 4 more days".

**What to look for.** You want something reasonably flat. A single enormous spike three weeks out means you added a big batch of cards on the same day and they are all coming back together. Smooth it by doing a few early, or by adding new cards in smaller batches.

---

### 18.5 Accuracy trend

A line showing your accuracy on each recent study day.

```
That day's accuracy = correct that day ÷ studied that day
```

**Example.** Our three days:

```
Monday:    8 ÷ 10 = 0.80 = 80%
Tuesday:  11 ÷ 12 = 0.9166 = 92%
Wednesday: 7 ÷  8 = 0.875 = 88%
```

The line joins 80%, 92%, 88%. Axis labels read 0% and 100%.

**Two things to know.**

1. Days you did not study are **skipped**, not drawn as zero. A rest day does not punch a hole in your line.
2. It needs **at least 2 study days** to appear. Until then you see: *"Study a few more days to see your accuracy trend."*

**Retention versus this line.** Retention is your whole life. This is recent. If Retention says 87% but this line has sat at 70% all week, something changed lately and the lifetime number is hiding it.

---

### 18.6 Your forgetting curve

The most useful chart here once you understand it. It shows how memory of a typical card of yours fades, and marks the moment Memori will bring it back.

**The curve.** Memori takes your **average stability** and calls it `S`. For any number of days `t`:

```
recall = 0.9 ^ (t ÷ S)
```

**Worked example** with average stability of 20 days:

| Days since you saw it | The sum | Chance you still remember |
| --- | --- | --- |
| 0 | 0.9 ^ (0 ÷ 20) = 0.9 ^ 0 | 100% |
| 5 | 0.9 ^ (5 ÷ 20) = 0.9 ^ 0.25 | 97.4% |
| 10 | 0.9 ^ (10 ÷ 20) = 0.9 ^ 0.5 | 94.9% |
| **20** | 0.9 ^ (20 ÷ 20) = 0.9 ^ 1 | **90.0%** |
| 40 | 0.9 ^ (40 ÷ 20) = 0.9 ^ 2 | 81.0% |
| 60 | 0.9 ^ (60 ÷ 20) = 0.9 ^ 3 | 72.9% |

Look at the 20 day row. At exactly your average stability you are at exactly 90%. That is what stability means, and why it is defined that way.

The chart marks **90%** and **50%** lines, and the horizontal axis runs from **0d** to your domain.

**The dotted marker.** A vertical line where your **target retention** crosses the curve. That is the day the card comes back.

```
Day it comes back = S × ln(target ÷ 100) ÷ ln(0.9)
```

With S of 20 days:

| Your target | Marker lands at |
| --- | --- |
| 80% | 42.4 days |
| **90%** | **20.0 days** |
| 95% | 9.7 days |

That is the entire retention setting in one picture. Raise the target and the line slides left, giving shorter gaps and more reviews. Lower it and it slides right.

The caption underneath says so:

> Modelled for a card with your average stability. The scheduler picks the moment the curve crosses your target retention.

Needs at least one studied card to appear.

---

### 18.7 Overall breakdown and Per deck progress

**Overall breakdown** is the same donut as the Home screen, with your total in the middle and the four states in the legend.

**Per deck progress** lists every deck with a bar and a percentage:

```
Mastered % = mature cards in that deck ÷ total cards in that deck × 100
```

A deck with 50 cards of which 12 are Mature:

```
12 ÷ 50 = 0.24 → 24%
```

Tap a bar to jump into that deck.

---

### 18.8 Cheat sheet

| Number | One line version | Healthy sign |
| --- | --- | --- |
| Reviews today | Answers given today | Near your goal |
| Goal % | Today ÷ goal | Hitting 100% most days |
| Current streak | Days in a row | Any unbroken number |
| Best streak | Longest ever run | Being beaten occasionally |
| Retention | Lifetime accuracy | **85 to 90%**, not higher |
| Mature cards | Cards past 21 days | Rising every month |
| Time studied | Total minutes ever | Whatever you can spare |
| Seconds per card | Average speed | 5 to 15 seconds |
| Avg stability | Average gap in days | Slowly climbing |
| Heatmap | Consistency | Few gaps, not dark squares |
| 14 day bars | Recent volume and errors | Small red portion |
| Coming up | Workload ahead | Fairly flat, no huge spike |
| Accuracy trend | Recent accuracy | Flat, 85 to 90% |
| Forgetting curve | Your memory model | Marker where you expect |

---

## 19. The Settings screen

Three sections: Studying, Appearance, Your data. Plus an About block.

### Studying

#### Target retention

A slider, showing the current value in the heading, for example **Target retention: 90%**.

**Range: 70% to 97%.**

The caption reads: *"Higher means shorter intervals and more reviews. Around 90% is the usual sweet spot."*

This is the most powerful setting in the app and the easiest to set badly. It is the chance you want of remembering a card at the moment it comes back. Memori turns the percentage into a multiplier:

```
multiplier = ln(your target ÷ 100) ÷ ln(0.9)
```

You do not need to follow that. Here is the table:

| Target | Multiplier | A 20 day card becomes | Meaning |
| --- | --- | --- | --- |
| 70% | 3.39 | 68 days | Very few reviews, lots of forgetting |
| 80% | 2.12 | 42 days | Relaxed |
| 85% | 1.54 | 31 days | Slightly relaxed |
| **90%** | **1.00** | **20 days** | **The default. Leave it here.** |
| 95% | 0.49 | 10 days | Demanding, roughly double the work |
| 97% | 0.29 | 6 days | Exam panic mode |

The multiplier is applied **once**, when the due date is set. It does not pile up over time, so switching between settings never corrupts your schedule.

**Practical advice.** Leave it at 90 unless you have a reason. Raise to 95 in the fortnight before an exam and put it back after. Drop to 85 if you are drowning.

#### New / day

**Default: 20.** The most brand new cards Memori will introduce in one day, across everything.

This is the throttle on your future workload, and people set it far too high. See Rule 4 in section 5.

This is a genuine daily limit. Do 20 today and you get no more until tomorrow, even if you close and reopen the app.

#### Reviews / day

**Default: 200.** The most already-seen cards you will be handed in a day.

A safety valve. Take a fortnight off and come back to a mountain, and rather than 900 cards in one sitting you get 200 a day until you are level.

#### Daily goal

**Default: 40.** Purely the target for the progress percentage on the Stats screen. Nothing is blocked or unlocked by it.

#### Longest interval, days

**Default: 3650**, which is 10 years. No card will ever be scheduled further out. Set it to 365 to force everything to be checked at least once a year.

#### Shuffle the queue

**Default: on.** Caption: *"Mix due and new cards instead of a fixed order."*

Worth keeping on, because a fixed order lets you accidentally memorise the sequence rather than the content.

#### Play the first audio clip on reveal

**Default: on.** Caption: *"Useful for pronunciation decks."*

When you reveal an answer, the first sound on the back plays by itself. Turn it off if you study in public.

### Appearance

Three buttons:

| Option | Icon | What it does |
| --- | --- | --- |
| **System** | 🖥️ | Follows your device, and switches live when your device does |
| **Light** | ☀️ | Always light |
| **Dark** | 🌙 | Always dark |

### Your data

A line showing **how many decks and cards** you have, and *"Stored privately on this device."*

Then three actions:

| Button | What it does |
| --- | --- |
| **Back up all data** | *"Download a .json file of everything."* |
| **Restore from backup** | *"Import a .json backup file."* |
| **Erase all data** | *"Delete your decks and stats, restore the starter deck."* |

Covered properly in section 22.

### About

> Memori schedules reviews with spaced repetition. Each answer updates the card's interval and ease, and the next date is when your recall is predicted to drop to your target retention.

Then a live count: **Cards: 23, decks: 1, reviews logged: 47**.

And:

> Free and open. Runs entirely in your browser: no account, no servers, no tracking.

---
---

# Part 4: Reference

## 20. Every message the app can show you

### Small pop-up messages (toasts)

These appear briefly at the bottom and disappear on their own.

| Message | What just happened |
| --- | --- |
| **Deck deleted** | You deleted a deck |
| **Progress reset** | You reset a card's schedule |
| **Add a front and a back** | You tried to save a card missing one side |
| **Could not add file** | An image or sound failed to attach |
| **Recording not supported here** | Your browser has no microphone recording |
| **Microphone permission needed** | You declined the mic prompt |
| **Add some cards first** | You tried to study an empty deck |
| **Nothing due. Great work!** | You pressed Review with nothing due |
| **Need at least 2 cards with answers** | Quiz has nowhere to get wrong options |
| **Backup downloaded** | Your .json file was saved |
| **Backup failed** | Something went wrong saving it |
| **Data restored** | A backup was loaded successfully |
| **Invalid backup file** | The file was not a Memori backup |
| **Reset to starter deck** | You erased everything |

### Questions the app asks before doing something

These need a yes or no, because they cannot be undone.

| When | What it asks |
| --- | --- |
| Deleting a deck | Confirms by name, and warns the cards go too |
| Resetting a card | *"Reset this card to new? It becomes due now. Past reviews stay in your stats."* |
| Deleting a card | *"Delete this card?"* |
| Restoring a backup | *"Restore will replace everything currently in Memori. Continue?"* |
| Erasing everything | *"Erase all your decks, cards, and stats and restore the General Knowledge starter deck? This cannot be undone."* |

---

## 21. Keyboard shortcuts

Only on a computer, but they make studying much faster.

| Key | What it does |
| --- | --- |
| `Space` or `Enter` | Reveal the answer. Press again to grade it Good. |
| `1` | Again (Review) / Still learning (Flip) |
| `2` | Hard (Review) / I know it (Flip) |
| `3` | Good (Review) |
| `4` | Easy (Review) |
| `1` to `4` | Pick that option (Quiz) |
| `Enter` | Next question (Quiz) |
| `Esc` | Leave the session |

Shortcuts are ignored while you are typing in a box, so they will not fire while writing a card.

---

## 22. Your data, backups, and moving devices

### Where it lives

On your device, in your browser's own storage, in a database called `memori-db`.

- Decks, cards and study history in one part
- Images and sounds as separate blobs, so big files never slow the rest down

Nothing is uploaded anywhere. No account, no server, no analytics. The app makes zero outbound requests.

### The one real risk

Browsers are allowed to clear website storage when a device runs low on space. And if you ever click "clear browsing data" and include site data, Memori goes with it.

**So back up.** Settings, **Back up all data**. You get one `.json` file containing everything: decks, cards, study history, and every image and sound encoded inside it. Keep it somewhere real, like a cloud drive.

### Moving to a new device

1. Old device: Settings, **Back up all data**, save the file
2. Get the file onto the new device
3. New device: Settings, **Restore from backup**, choose the file

Everything comes across, including your streak and history.

**Restoring replaces everything.** It is not a merge. The app warns you first.

### Erase all data

Wipes everything and puts the starter deck back. No undo. Back up first.

---

## 23. Questions people ask

**Is it really free?**
Yes. No account, no subscription, no ads, no paid tier. The code is here to read.

**Do I need the internet?**
Only to load the page. Once open, everything works with no connection, because your cards are on your device.

**Does it sync between my phone and my laptop?**
No. Each device keeps its own copy. Use Back up and Restore to move between them.

**Why does it say "Nothing due"?**
Because nothing is due. Every card is scheduled for a later day. Studying early would make them stick less well. Use **Revise** if you want to run through a deck anyway.

**I did 20 new cards and it will not give me more. Why?**
The daily new card limit, protecting your future self. Raise it in Settings if you really mean it, but read section 5 Rule 4 first.

**Should I press Hard or Again?**
Did you get it right? If yes, Hard. If no, Again. Hard is not "wrong but only just".

**My retention is 97%. Is that great?**
No. It means you are reviewing too often and wasting time on cards you already know. Aim for 85 to 90%. See section 18.1.

**What is the difference between Flip and Review?**
Review is real and changes your schedule. Flip is practice and changes nothing. Section 14.

**Can I study just my starred cards?**
Yes, on the deck screen tap the star button next to the search box to filter, then start a session.

**How many cards should a deck have?**
No limit that matters. What matters is that each card is small. One card, one fact.

**Can I use this for languages, medicine, law, anything?**
Yes. The app has no idea what your cards are about. Delete the music theory starter deck and build whatever you want.

**Can I share a deck with a friend?**
Send them your backup file. Note that restoring replaces their collection, so it is best for a fresh install.

**What happens if I answer a card wrong in Review?**
It comes back later in the same session, and its interval resets to 0 so it returns today. A lapse is recorded on the card.

---

## 24. When something goes wrong

| Problem | Likely cause and fix |
| --- | --- |
| **The app is empty after it was working** | Browser cleared site storage. Restore from your backup. This is why backups matter. |
| **Recording does nothing** | Microphone permission was declined, or the browser does not support it. Check your browser's site permissions. |
| **Quiz will not start** | You need at least 2 cards with answer text in that deck. |
| **Review will not start** | Nothing is due. Use Revise, or add new cards. |
| **My streak reset unfairly** | The streak allows today to be empty, but breaks if a full day passes with nothing. |
| **Coming up shows a huge spike** | You added a large batch of cards on the same day. Spread new cards over several days. |
| **The install option does not appear** | You must be on `https`, and on iPhone you must use Safari, not Chrome. |
| **Audio does not autoplay** | Some browsers block autoplay until you interact with the page. Tap the player once. |

---

## 25. For developers

### What it is built from

Plain JavaScript on React, with the Plus Jakarta Sans typeface, IndexedDB for storage and the MediaRecorder API for microphone capture. No build step, no bundler, no dependencies to install.

### The repository

```
memori/
├── index.html              the entire app
├── manifest.webmanifest    makes it installable
├── assets/
│   ├── icon-192.png
│   ├── icon-512.png
│   ├── icon-maskable-512.png
│   └── favicon.png
├── README.md
└── LICENSE
```

`index.html` is a self extracting bundle. The React runtime, the fonts and the app are all inside it.

### Running it locally

Download `index.html` and open it. That is the whole setup.

For a proper origin, which you need to test installability:

```bash
python3 -m http.server 8080
```

then open <http://localhost:8080>.

### Deploying your own copy

1. Fork or copy the repository
2. Settings, Pages
3. Source: **Deploy from a branch**, branch `main`, folder `/ (root)`
4. Make sure **Enforce HTTPS** is ticked, it is required for installability

### The scheduling algorithm

An SM-2 style scheduler. Section 15 documents the exact arithmetic. Every card carries an ease factor starting at 2.50 with a floor of 1.30, and an interval in days. The target retention setting is applied once when the due date is set, never compounded into the stored interval.

### Card states

Bucketed purely on the stored interval:

| State | Rule |
| --- | --- |
| New | never answered |
| Learning | interval 1 to 6 days |
| Young | interval 7 to 20 days |
| Mature | interval 21 days or more |

### Offline support

The app runs offline once loaded, but a cold launch with no connection would need a service worker, which by browser rules must be a separate file at the site root. It is not included, because it is no longer required for installability: Chrome dropped the service worker requirement in version 108 on mobile and 112 on desktop.

### Ideas that would help

- Bulk import from CSV or Anki
- Cloze deletion cards
- Reverse cards generated from a single entry
- A service worker for true offline launch
- Sync through a file in a folder you already sync

Issues and pull requests welcome.

---

## 26. Licence and credits

**MIT.** Do whatever you like with it, including commercially, as long as the copyright notice stays. See [LICENSE](LICENSE).

The science this app is built on is not mine. The forgetting curve and the spacing effect come from Hermann Ebbinghaus's 1885 work *Memory: A Contribution to Experimental Psychology*, and have been confirmed by researchers repeatedly ever since. The SM-2 family of scheduling algorithms comes from the SuperMemo project.

Built by [rohittabs](https://github.com/rohittabs).
