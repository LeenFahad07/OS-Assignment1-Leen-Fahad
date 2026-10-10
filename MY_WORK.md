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
| **Full Name** | [Leen Fahad ALmigirn] |
| **Student ID** | [446052579] |
| **University Email** | 446052579@std.psau.edu.sa |
| **GitHub Username** | [LeenFahad07] |
| **Repository Link** | [https://github.com/LeenFahad07/OS-Assignment1-Leen-Fahad.git] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/file/d/1TKtw8RLDHogdf-WDCI3B3K3d8x-qS6iE/view?usp=drivesdk]

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

### Entry 1 - [8 Occt 10pm]
**What I did**:
Reviewed the assignment requirements and examined the starter Java code
**Details**:
Identified the Process class, the Runnable interface, the ready queue, and the main scheduling loop
**Challenges**:
Initial confusion with GitHub fork vs clone
**Solution**:
Watched a short tutorial and understood the difference
**Time spent**:
2 hours
---

### Entry 2 - [9 Oct 9pm]
**What I did**:
Added priority values to the simulated processes
**Details**:
Used random priority values from 1 to 10 and included the priority in the process information displayed by the simulation
**Challenges**:
Integrating the new priority field without disrupting the existing process creation and queue logic
**Solution**:
Updated the process constructor and the code that creates and adds processes to the queue
**Time spent**:
2 hours
---

### Entry 3 - [10 Oct 1am]
**What I did**:
Added a counter to track process dispatches during the simulation
**Details**:
Updated the execution logic to increment the counter and displayed the total after scheduling finished
**Challenges**:
Deciding where the counter should be updated so that it represents the intended scheduling events
**Solution**:
Added the increment to the process execution method used by the scheduler
**Time spent**:
1 hour
---

### Entry 4 - [10 Oct 2:30am]
**What I did**:
Added waiting time tracking and a final process summary
**Details**:
Recorded when a process entered the ready queue and accumulated elapsed waiting time when it was scheduled. Displayed waiting time and calculated turnaround time for each process
**Challenges**:
Tracking queue waiting time while accounting for the fact that Java thread execution has runtime overhead
**Solution**:
Added fields and methods to record ready queue entry time and calculate the reported metrics
**Time spent**:
1:30 hour
---

### Entry 5 - [10 Oct 3:30am]
**What I did**:
 Ran the simulation and reviewed the scheduling output
**Details**:
Tested the program with a 2000 ms time quantum and 19 processes. The run I reviewed reported 39 context switch/dispatch counts and showed the final waiting time and turnaround-time summary
**Challenges**:
Understanding why random priorities and timing measurements could differ between runs
**Solution**:
Compared the outputs and identified random priority assignment and runtime timing variation as reasons for the differences
**Time spent**:
30 min
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

**Total time spent on assignment**: [3 Days]

**Most challenging part**:
Waiting time calculation and thread behavior
**Most interesting learning**:
Observing how a process that exceeds the time quantum returns to the ready queue and receives another turn
**What I would do differently next time**:
I would plan the testing earlier and keep a record of each change
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

This assignment taught me how to simulate multiple processes vying for CPU time using Java threads. I discovered that a thread can be started by calling start() and created by passing a Runnable object to the Thread constructor. I also discovered that the Round-Robin algorithm divides CPU time among processes using a fixed time quantum. A process may be put back in the ready queue for another turn if it doesn't finish within its time slice. I was able to comprehend the connection between thread execution, scheduling choices, and the ready queue thanks to the simulation. I also discovered that runtime overhead and thread scheduling can cause variations in measured waiting times.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

Understanding how to combine Java threads with the Round-Robin scheduling algorithm was the most difficult aspect of this assignment. I had to comprehend how a process's remaining burst time indicates whether it has finished or needs to go back to the ready queue. It was also necessary to pay close attention to when a process entered the queue and when it finished in order to track wait times and turnaround times. Differentiating the simulated processes from the real Java threads that run their Runnable code presented another difficulty. After making adjustments, I examined the scheduling flow and verified the program's output in order to resolve these problems. This made it easier for me to comprehend how the code and the simulation's output relate to one another.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

By going over the current code and comprehending the function of each crucial method, I was able to overcome the difficulties. From adding a process to the ready queue to executing it for the allotted time quantum, I followed the execution flow. After that, I ran a simulation test to see if processes with burst times longer than 2000 ms were added back to the queue. In order to see the number of context switches as well as the waiting and turnaround times, I also looked at the final summary. I was able to observe that timing measurements and priority values could change between runs by running the program multiple times. I gained a better understanding of the interaction between Java threads and the scheduler by comparing the outcomes.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Applications that need to manage several tasks without making the entire program wait for one task to finish can benefit from multithreading. A web server, for instance, can use threads to manage work for various client requests. A desktop program that completes a task in the background while maintaining a responsive user interface is another example. By allocating a finite time quantum to each task, the Round-Robin algorithm illustrates how CPU time can be distributed among them. A task can wait for another chance to be completed if it is not completed during its turn. Developers can create applications that are responsive and efficiently utilize system resources by having a thorough understanding of thread scheduling and waiting.

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

**Your Answer:A program that is running and has its own memory and system resources is called a process. Within a process, a thread is a smaller unit of execution that shares resources and memory. Threads can assist a program in carrying out several tasks at once and are typically less expensive to create and switch between than separate processes. The Process class in my assignment implements the Runnable interface and simulates a process. Each simulated process can run on its own Java thread while the scheduler maintains the ready queue thanks to the addProcessToQueue() method, which creates a Java thread using new Thread(process).** *(3-5 sentences)*

[Write your answer here.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

The scheduler puts a process at the end of the ready queue so that other processes can run if it does not complete within the 2000 ms time quantum. P1, for instance, has a burst time of 3725 ms. It is added back to the ready queue after running for 2000 ms during its first turn, with 1725 ms left. P1 is scheduled twice and re-queued once prior to completion since it executes once more for the final 1725 ms before finishing. Because lengthy processes cannot occupy the CPU continuously while other processes wait for their turns, this behavior promotes fairness.

Example from my output:
```
P1 - Burst Time: 3725ms
Executing for 2000ms
P1 remaining burst time: 1725ms
P1 added back to the ready queue

P1 - Burst Time: 1725ms
Executing for 1725ms
P1 completed
```

**Explanation of example:**
this output shows that P1 initially requires 3725 ms of CPU time, but the time quantum is only 2000 ms. After its first execution, P1 has 1725 ms remaining because 3725 − 2000 = 1725 ms. Since P1 has not finished, the scheduler adds it to the end of the ready queue, allowing other processes to execute first. P1 then receives another turn and executes for the remaining 1725 ms until it completes. Therefore, P1 executes twice and is re-queued once before completion, demonstrating how Round-Robin scheduling promotes fairness.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:The lifecycle of a process thread in my simulation can be explained using P1. First, the Java thread is in the New state when it is created with new Thread(process). When start() is called, the thread becomes eligible to run and enters the Runnable state; the operating system or JVM scheduler determines when it actually executes. While P1 is executing its time slice, it is in the Running state conceptually. When the thread calls Thread.sleep(), it enters the timed waiting state temporarily, and when the scheduler thread calls join(), the calling scheduler thread waits for the joined thread to finish. After the thread's run() method completes, the thread enters the Terminated state.** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [When is P1 in the New state?]

2. **Runnable**: [When does P1 become Runnable?]

3. **Running**: [When is P1 Running?]

4. **Waiting**: [When and why would a thread be Waiting?]

5. **Terminated**: [When is P1 Terminated?]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:An operating system that divides CPU time among several interactive processes is one practical use of round-robin scheduling. Every process is given a finite amount of time; if it doesn't finish, it goes back to the ready queue so that another process can start. A server that uses threads to manage several client tasks is a second example, though actual servers may also employ other scheduling techniques. Instead of letting one lengthy task take up all of the CPU time in such a system, the scheduler can give each task a chance to run. Each turn is limited by the time quantum, and the overhead of switching between tasks is represented by context switches.** *(3-5 sentences per example)*


## Summary

**Key concepts I understood through these questions:**
1.Concurrency and threads: Threads in the same process share memory and resources, and they enable several tasks to advance within a program.
2.Round-Robin scheduling assigns a fixed time quantum to each process. It is put at the end of the ready queue if it doesn't finish.
3.Thread lifecycle and synchronization: Java threads go through various states, and methods like join(), sleep(), and start() have an impact on waiting and thread execution.

**Concepts I need to study more:**
1.Thread synchronization: When multiple threads access shared data, I'd like to know more about how to avoid race situations.
2.Algorithms for scheduling: I want to contrast Round-Robin with algorithms like Shortest Job First and Priority Scheduling, taking into account how they affect waiting times and fairness.

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
