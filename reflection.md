# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").

**Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input | Expected Behavior | Actual Behavior | Console Output / Error |
|-------|-------------------|-----------------|------------------------|
|Attempts|Attempts should be 8|Attempts were 7|Console Output: none/|
|Attempts|Higher & Lower should be correct|Higher and lower were swapped|Console Output: none/|
|Attempts|TypeError Higher & Lower should be correct|TypeError Higher & Lower were also swapped|Console Output: none/|

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
None, as the TA used Claude, however I did not
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
When the TA had used Claude it had determined that the higher and lower were swappped
- Give one example of an AI suggestion you did not accept as written (including what the AI suggested, why you rejected or changed it, and how you verified your version). It does not have to be a suggestion that was wrong: over-engineered, out of scope, harder to read, or a poor fit for this codebase all count.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
I had to go through and play the game to determine if it was fixed.
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
I went through checking to see if I had fixed the higher and lower, and found out that it had to be fixed twice.
- Did AI help you design or understand any tests? How?
It showed what was wrong when the TA had gone through it.
---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
It's an open end python that allows you to use cluade or other devices, much like how google collab allows the use of copilot.

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
Using github as a way of storing everything
- What is one thing you would do differently next time you work with AI on a coding task?
PRobably use it myself in order to do the assignment instead of relying on the TA to do such.
- In one or two sentences, describe how this project changed the way you think about AI generated code.
I believe that the AI generated code will fix what errors there are with the current existing code. However even if it does fail I will be able to give it back to get a working one that will be fixed to the error that is displayed.
