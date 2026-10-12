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
| **Full Name** | Abdullah Abdulwahab Alawad |
| **Student ID** | 446050626 |
| **University Email** | 446050626@std.psau.edu.sa |
| **GitHub Username** | Abdullah-Alawad-77 |
| **Repository Link** | (https://github.com/Abdullah-Alawad-77/OS-Assignment1-Abdullah-Alawad) |
 
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

### Entry 1 - [October 6, 2026, 4:00 PM]
**What I did**:Set up the project repository and configured my Student ID.

**Details**:
Forked the repo for the baseline OS scheduler and set up git credentials.
- Changed line 184 in SchedulerSimulation.java with my student id 446050626 .
- Tested generation of pseudo random process burst times seeded by my id.
- Committed and pushed changes to Github.
**Challenges**:
    Struggled with git authorization setup in VS Code terminal.
**Solution**:
Signed in via the OAuth flow in the browser to enable push permissions.
**Time spent**: 45 min

---

### Entry 2 - [October 7, 2026, 6:15 PM]
**What I did**:Implemented Feature 1 (Process Priority display).

**Details**:The priority field (range 1–10) was added to the model of the Process class.
The addProcessToQueue() method has been updated to show the process priority when it is queued.
To confirm priority printing in the terminal console, local tests were carried out.

**Challenges**:Makeing sure the priority value was printed clearly alongside process burst time.

**Solution**:emphasize priority levels in the terminal, prepared ANSI color strings were added

**Time spent**:40 minutes.

---

### Entry 3 - [October 9, 2026, 5:30 PM]
**What I did**:Added Feature 2 (Context Switch Counter)

**Details**:Added a static int contextSet SwitchCount variable to SchedulerSimulation.
The counter in the main dispatching loop was incremented every time a thread was executed.
 Added a final output line printing total context switches performed (20 switches).

**Challenges**:Deciding if the initial thread starts should be counted as context switches or just the preemptions.

**Solution**:Counted every CPU dispatch event as a context switch to match theoretical Round-Robin behavior.

**Time spent**:35 mins.

---

### Entry 4 - [October 9, 2026 8:00 PM]
**What I did**:Implemented Feature 3 (Execution Summary Table & Waiting time tracking)

**Details**:Tracking the process start time, burst time and completion timestamp.
Calculated exact waiting times and turnaround time for each process between P1 and P10.
Created a well-structured table of execution metrics summary at the end of the simulation.

**Challenges**:Formatting tabular output with ANSI colors while keeping column alignment intact.

**Solution**:Standard String.format() specifiers with fixed column widths.

**Time spent**:50 minutes.

---

### Entry 5 - [October 10, 2026, 3:00 PM]
**What I did**:Completed Documentation and Created Demonstration Video

**Details**:Reflection and technical questions completed in `MY_WORK.md`
 Produced a demo video of the screen (3 mins) showing the GitHub repo, code features and execution.
 Uploaded video to Google Drive, public access link and documentation updated.

**Challenges**: To fit everything into the tight 2-3 minute time frame and still cover all the necessary points.

**Solution**: Short timed script covering student intro, GitHub commits, run of execution, threading

**Time spent**:1 hr.

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

**Total time spent on assignment**: 3.8 hr

**Most challenging part**:Java thread state transitions while maintaining the underlying process execution state across preemptions.

**Most interesting learning**:Multi-threaded operation scheduled in Round-Robin manner keeps fairness of multi-threaded operation through time quanta.

**What I would do differently next time**:I'd develop granular modular tests of scheduling metrics calculations before plugging into the main UI loop.

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

**Your Answer:** ## Question 1: What did you learn about multithreading?
**Your Answer:**
Through this assignment, I gained hands-on experience with Java's multithreading model by observing how concurrent execution threads are instantiated and managed. I learned how `Thread.start()` moves a thread into the `RUNNABLE` state and how `Thread.sleep()` simulates active CPU execution during a time quantum. Additionally, using `Thread.join()` allowed me to synchronize execution by ensuring the main scheduler thread waits for active process threads to finish their assigned quantum. Understanding how Java threads cannot be restarted once `TERMINATED` was a key insight that forced me to manage thread creation dynamically. Overall, this project demystified how operating systems control concurrent thread execution at a low level.

## Question 2: What was the most challenging part of this assignment?
**Your Answer:**
The most challenging part of the assignment was handling process preemption while working within the strict constraints of Java's thread lifecycle. In Java, once a thread finishes executing its `run()` method or completes a time slice, it enters the `TERMINATED` state and cannot be resumed or re-run. Since Round-Robin requires preempted processes to re-enter the ready queue and run again later, I could not simply pause and resume the same `Thread` object. To overcome this, I had to separate the simulated `Process` data model from the executing `Thread` wrapper, allowing me to instantiate a new `Thread` for each quantum while retaining process metrics like remaining burst time and priority.

## Question 3: How did you overcome the challenges you faced?
**Your Answer:**
I overcame these challenges through systematic debugging and analyzing the execution log output step-by-step. Whenever a thread behavior issue occurred, I added print statements to trace thread IDs and process states across queue insertions. I also carefully reviewed Java documentation regarding thread states and `Thread.sleep()` behavior during interrupts. Furthermore, I tested each feature incrementally—verifying priority displays first before adding the context switch counter and summary calculations. This modular approach made it much easier to isolate logical errors without breaking previously working code.

## Question 4: How can you apply multithreading concepts in real-world applications?
**Your Answer:**
Multithreading concepts are essential in building high-performance, responsive software applications today. For instance, in desktop applications and video games, background threads handle asset loading and network operations while the main UI thread renders graphics smoothly without freezing. In web servers like Apache or Tomcat, incoming user requests are assigned to worker threads managed by a thread pool to process concurrent requests efficiently. Similarly, database management systems use concurrent background threads for logging, indexing, and executing queries simultaneously. Understanding time-slicing and concurrency allows developers to prevent thread deadlock and maximize multi-core CPU usage.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*
The most difficult part of the assignment was managing process preemption under the rigid rules of Java threads' life cycle. In Java, after execution of `run()` method and end of a time slice, the `Thread` goes into the `TERMINATED` state and can never be restarted. Therefore, since Round-Robin scheduler needs processes to be put back in the ready queue to be executed again, I could not use the same `Thread` and just suspend and then resume it again. Thus, in order to solve this problem, I decided to decouple the `Process` data structure and the `Thread` which executes it at each time quantum.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

These problems were solved by debugging the system and analyzing the results of the execution log output in detail. In case there was any problem related to threads, I used print statements to print out thread IDs and process states during insertion into the queue. In addition, I referred to Java documentation for issues with thread states and `Thread.sleep()` behavior upon interrupt. Moreover, I checked every feature in isolation by checking the display of priorities first, followed by the context switch counter.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

The concepts of multithreading are integral in developing efficient software applications that respond quickly to users. For example, desktop applications and video games use background threads to manage the load of assets and network communication while the main thread is used to render the graphics without stopping. Web server applications such as Apache and Tomcat allocate user requests to worker threads through a pool of threads in order to execute multiple requests concurrently. Database management systems also use background threads concurrently to perform activities such as logging, indexing, and query processing.

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

A process is a program execution environment that has its own memory space allocated from the operating system, while a thread is an independent and light weight unit of execution running inside a process sharing memory space of its parent process. In `SchedulerSimulation.java`, we use Java threads to simulate processes instead of OS processes since threads share heap memory and thus, are faster to switch context than processes. In our code, on line 261, we create a real execution thread (`new Thread(currentThread)`) using our simulated process object.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

## Question 2: Ready Queue Behavior
**Your Answer:**
When a process does not complete within its allocated time quantum (2000ms), it is preempted by the scheduler, yields the CPU, and is placed back at the tail of the ready queue to await its next turn. For example, in my simulation run with student ID `446050626`, process `P2` started with a burst time of 3671ms. It executed for 2000ms, yielded the CPU with 1671ms remaining, and was re-queued **1 time** behind `P10` before finally executing its remaining 1671ms and finishing. Re-queueing is vital for fairness because it guarantees that long CPU-bound tasks cannot hog the processor indefinitely, giving shorter interactive processes equal opportunities to execute.

Example from my output:
P2 executing quantum [2000ms] 
  P2 completed quantum 2000ms │ Overall progress: 54%
     Remaining time: 1671ms
  P2 yields CPU for context switch
  P2 added to ready queue │ Burst time: 3671ms
     Priority: 10
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P4 -> P5 -> P6 -> P7 -> P8 -> P9 -> P10 -> P2]
└───────────────────────────────────────────────────────────────────────────────

**Explanation of example:**
Here, P2 exhausted its maximum quantum, which was 2000ms. Because it still had 1671ms left, the process was taken off from the CPU by the scheduling algorithm and placed at the rear of the Ready Queue after P10.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [When is P1 in the New state?] P1 transitions to the NEW state by being instantiated as a Runnable object in the method addProcessToQueue(), using Process p = new Process(...).

2. **Runnable**: [When does P1 become Runnable?] P1 enters the RUNNABLE state when the scheduler invokes currentThread.start() inside the main simulation loop.

3. **Running**: [When is P1 Running?] P1 moves into the RUNNING state whenever the OS thread scheduler decides to give it CPU time, leading to execution of its run() method.

4. **Waiting**: [When and why would a thread be Waiting?] When Thread.sleep() method is invoked, causing quantum simulation time, then P1 moves into the TIMED_WAITING state.

5. **Terminated**: [When is P1 Terminated?] After run() method has executed fully in 1516 ms, P1 moves into the TERMINATED state.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): OS CPU Time-Sharing Scheduler

**Description**:
Time slicing based on Round-Robin scheduling is used by operating systems like Linux and Windows to allocate their CPU cores between multiple active background applications and user processes at once.

**Why Round-Robin works well here**:
Round-Robin scheduling fits this scenario because it provides good responsiveness and fairness; nothing can freeze the computer because each program gets its slice of CPU time.

### Example 2: HTTP Request Handling on Web Servers

**Description**:
A busy web server receives a large number of HTTP requests and processes them by assigning to worker threads using a time-sliced scheduler.

**Why Round-Robin works well here**:
 fits this scenario: Round-Robin ensures predictable response times and avoids a situation where lengthy file downloads starve shorter API requests for processor time. fits this scenario: Round-Robin ensures predictable response times and avoids a situation where lengthy file downloads starve shorter API requests for processor time.
## Summary

**Key concepts I understood through these questions:**
1. The differences in operation in process memory isolation versus thread resource sharing in Java.
2. How Round-Robin ready queue imposes strict FIFO scheduling for ensuring scheduling fairness.
3. The transition of thread life cycles from NEW to RUNNABLE to TIMED_WAITING to TERMINATED.

**Concepts I need to study more:**
1.Semaphore and mutex locks for resolving race conditions.
2.MLFQ scheduling algorithms in operating system kernels.

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
