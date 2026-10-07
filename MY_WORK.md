# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Rama saeed alshehri] |
| **Student ID** | [446051375] |
| **University Email** | [446051375]@std.psau.edu.sa |
| **GitHub Username** | [rama-alshehri] |
| **Repository Link** | [https://github.com/rama-alshehri/OS-Assignment1-Rama-Alshehri.git] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [21-10-2026]
**What I did**: I forked the repository then rename it and set up my ID 

**Details**:
 - Forked the starter repository and renamed it to my required repository name.
 - Set my student ID in SchedulerSimulation.java.
 - Checked the repository and remote connection using Git Bash

**Challenges**:
  use git bash to edit the code

**Solution**:
  I learned how to use basic Git Bash commands from youtupe



**Time spent**: about 2 hour

---

### Entry 2 - [21-10-2026]
**What I did**: worked on the git bash and prepared the project for compilation.

**Details**:
 - Found that java and javac were not recognized in git bash
 - checked the java is installed in netbeans

**Challenges**: git bash could not find javac

**Solution**: Located the JDK inside the Apache NetBeans installation and configured the PATH in git bash

**Time spent**: about 1 hour

---

### Entry 3 - [21-10-2026]
**What I did**: implemented feature 1 process priority

**Details**:
- added priority to process class
- generated a priority between 1 and 10
- added a getter method 
- test the code using javac and java.
- add commit 1

**Challenges**:
- first received a compiler error because the prioity was not declared
**Solution**:
- added int priority =1 + random.nextInt(10); before creating the process.

**Time spent**: about 1 hour

---

### Entry 4 - [22-10-2026]
**What I did**: implemented feature  2: Context Switch Counter.

**Details**: 
- add static contextSwitchCount variable.
- incremented it before currentThread.start().
- add the total context switch count to the final output.
- test the code using javac and java.

**Challenges**: i faced a proplem where the counter should incremented

**Solution**: I placed the increment  before currentThread.start()

**Time spent**: about 45 m

---

### Entry 5 - [23-10-2026]
**What I did**:implemented feature 3: Waiting Time Tracking.

**Details**:
- add waiting-time variables to the Process class
- used System.currentTimeMillis() to measure waiting time
- Calculated turnaround time using waiting time plus burst time
- Added the final process as table

**Challenges**: 
- understand when the waiting-time measurement should start and stop 

**Solution**:
- started timing when a process entered the ready queue and stopped timing when it was removed

**Time spent**: about 45 m

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [7 hours]

**Most challenging part**: part 2

**Most interesting learning**: I learned how a simulated process can be represented by a java

**What I would do differently next time**: I would use VS instead of git bash

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[I learned that multithreading enabels the program manage diffrent process,In this assignment, the Process class implements Runnable. In the assignment, we used Java Thread to execute each process. We used Thread.start() to begin the execution of a thread. The main thread uses Thread.join() to wait for child threads to complete. I used Thread.sleep() to simulate the amount of time that a process uses the CPU.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The challenging part was setting up the Java environment to work within Git Bash; when I attempted to compile the program for the first time after implementing the initial feature, Git Bash reported that Java was unrecognized. I had to locate the JDK within the Apache NetBeans installation folder and correctly configure the PATH variable. After testing the first feature and encountering an error, I realized the importance of compiling the code after every minor modification; this practice facilitated early error detection and debugging, as I learned how to interpret compiler error messages and pinpoint the exact line causing the issue..]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcome the challenges by testing the code after evry change i did insted of testing whole the code at onse,when java was not defined at git bash i checked netbeans and then configured the JDK path in git bash,When the priority feature produced a compiler error, I read the error message and saw that the priority variable had not been declared. then i added the variable before the Process object then i tested agin.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading is useful in many applications because a program can handle different tasks for ex. the university website can use threads to handle different studints interactions and background tasks, threads also enable music abbs play audio while the user browses the application.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[ Process class implements Runnable so each process can be executed by a Java Thread. program creates a thread using new Thread(process) and starts it using currentThread.start(). Calling start()  Java execute run() method through the thread, calling run() directly would not create a new thread. In this assignment, threads are used to simulate the execution of CPU processes.

Example from my code:
Thread thread = new Thread(process);
thread.start();]


## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, if a process does not end within its time quantum, it is added to the end of the ready queue This allows the processes in the queue to receive CPU time before the same process runs again and help to minmized waiting time.]

Example from my output:
```

[  P1 executing quantum [5000ms] 
   Quantum progress: [???????????????] 100%
   P1 completed quantum 5000ms ? Overall progress: [????????????????????] 99%
     Remaining time: 11ms
   P1 yields CPU for context switch

  P1 added to ready queue ? Burst time: 5011ms ? priority: 6

  P1 executing quantum [11ms] 
   Quantum progress: [???????????????] 100%
   P1 completed quantum 11ms ? Overall progress: [????????????????????] 100%
     Remaining time: 0ms
   P1 finished execution!
]
```

**Explanation of example:**
[P1 could not finish during 5000 ms of time quantum because it still had 11 ms remaining. the scheduler added P1 to the end of the ready queue, allowing P2, P3, P4, and P5 to run first. P1 was re-queued once and then completed when it received its next turn.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [When is P1 in the New state?when the program creates its Thread object using new Thread(process) in addProcessToQueue()]

2. **Runnable**: [When does P1 become Runnable?when currentThread.start() is called]

3. **Running**: [When is P1 Running?when the JVM actually executes its run() method]

4. **Waiting**: [When and why would a thread be Waiting?when Thread.sleep() is executed inside run(), while the main scheduler thread waits for P1 using currentThread.join()]

5. **Terminated**: [When is P1 Terminated?after its run() method finishes and the thread completes its execution.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Operating System CPU Scheduling]

**Description**:
[operating system use Round-Robin scheduling to share CPU time among multiple processes that are ready to run. Each have a fixed time quantum. When the quantum expires, the process can be moved to the end of the ready queue and another process gets CPU time.]

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?
provides fairness because every ready process gets an opportunity to use the CPU. It also improves responsiveness because a process does not have to wait for another process to finish completely before getting CPU time. Context switches allow the operating system to move between processes]

### Example 2: [Name of application/scenario]

**Description**:
[A server handling multiple client requests use threads so that different requests can receive processing time. Each request can be as a task, while the time quantum represents the maximum amount of CPU time given totask before another task gets a turn.]

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?
Round-Robin can provide fair CPU access. It can improve responsiveness because one long-running task takes many CPU time while other tasks are waiting. Context switching allows the system to move between different tasks.]

## Summary

**Key concepts I understood through these questions:**
1. Round-Robin gives process a fixed time quantum for each one and re-queues unfinished processes
2. A Java thread moves through different cycle states while the simulation is running.
3. Fair scheduling improves responsiveness by giving multiple processes opportunities to use the CPU.

**Concepts I need to study more:**
1. the difference between join() and sleep().
2. context switching and CPU scheduling in a real operating systems.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
