# Syllabus

**Fall 2026–2027**

**Course:** Programming for minor Computational Science (6 EC)

**Expected workload:** ~20 hours/week

## Teaching Team & Contact

**Teaching staff**

<style>
.team, .team thead, .team tbody, .team tr, .team th, .team td { background: transparent; }
</style>

<table class="team">
  <tr><td>Lara</td><td> ...
  </td></tr>
  <tr><td>Lisette</td><td> ...
  </td></tr>
  <tr><td><img src = "https://github.com/spcourse/website/raw/2026/team/simon.jpg" style="max-width:90px" width = "150"><br>Simon</td><td> Simon studied Computer Science and then the Master of Logic at the University of Amsterdam (UvA). He conducted research in computational linguistics and robotics at Sony, Aldebaran (now Softbank), the Universitat Autònoma de Barcelona, and the UvA. He now works as a lecturer at the UvA and teaches programming in various programs.</td></tr>
</table>

**Contact email**
[mcs@proglab.nl](mailto:mcs@proglab.nl)

**Schedule, locations, and deadlines**
[jump to schedule](#schedule)

**Grading**
[jump to grading](#grading)

## General info {#general-info}

Welcome to this course! Here, you’ll use the Python programming language while learning to solve scientific problems from several fields of science. This course is intended for students who have no experience in programming at all. You learn about the Python language by working on programming problems from several scientific areas.

The course runs for seven weeks, from **31 August** to **16 October 2026**, and ends with a programming exam on **19 October**.

### Schedule {#schedule}

Below is the week-by-week overview.

<p class="legend">Sessions with a solid dark border, <span class="lab req">like this</span>,
are compulsory. A dashed border, <span class="lab cond">like this</span>, means the session
is only compulsory for you if you failed that Monday's test.</p>

<style>
.weeks {
  width: 100%; font-size: 0.9em; margin-bottom: 1.5em;
  border-collapse: separate; border-spacing: 4px 6px;
}
.weeks, .weeks thead, .weeks tbody, .weeks tr { background: transparent; }
.weeks th, .weeks td {
  border: none; padding: 0.4em 0.5em; text-align: left;
  background: transparent; vertical-align: top;
}
.weeks thead th { font-size: 0.9em; color: #6b6455; font-weight: normal; }
.weeks tbody th { white-space: nowrap; font-weight: bold; text-align: left; }
.weeks tbody th span { display: block; font-weight: normal; font-size: 0.9em; color: #6b6455; }
.weeks .lec, .weeks .lab, .weeks .disc, .weeks .exam, .weeks .dl, .legend .lab {
  padding: 0.3em 0.5em; border-radius: 4px; border: 2px solid transparent;
}
.weeks .lec, .weeks .lab, .weeks .disc, .weeks .exam, .weeks .dl {
  display: block; margin-bottom: 0.2em;
}
.legend .lab { display: inline-block; }
.weeks .lec  { background: #f0e2be; color: #5d4713; }
.weeks .lab, .legend .lab { background: #dbe3d1; color: #39492a; }
.weeks .disc { background: #d3e0dc; color: #2d4a43; }
.weeks .exam { background: #ecd3c5; color: #6d3a20; }
.weeks .dl   { background: #e8cfd2; color: #662e35; }
.weeks .req,  .legend .req  { border-color: currentColor; }
.weeks .cond, .legend .cond { border-color: currentColor; border-style: dashed; }
.weeks .test { font-weight: bold; }
</style>

<table class="weeks">
  <thead>
    <tr><th></th><th>Monday</th><th>Tuesday</th><th>Friday</th></tr>
  </thead>
  <tbody>
    <tr>
      <th>Week 1<span>31 Aug - 4 Sep</span></th>
      <td><span class="lec">9-11, lecture, D1.116</span><span class="lab req">11-13, lab, L0.11 (compulsory)</span></td>
      <td><span class="lab req">13-15, lab, L0.11 (compulsory)</span></td>
      <td><span class="lab req">13-15, lab, L0.11 (compulsory)</span></td>
    </tr>
    <tr>
      <th>Week 2<span>7 - 11 Sep</span></th>
      <td><span class="lec">9-11, lecture, D1.116</span><span class="lab req">11-13, lab, L0.11 (compulsory)</span></td>
      <td><span class="lab req">13-15, lab, L0.11 (compulsory)</span><span class="dl">23:59 deadline: module 1</span></td>
      <td><span class="lab req">13-15, lab, L0.11 (compulsory)</span></td>
    </tr>
    <tr>
      <th>Week 3<span>14 - 18 Sep</span></th>
      <td><span class="lec">9-11, lecture, D1.116</span><span class="lab req">11-13, lab, L0.11 (compulsory)<br><span class="test">test 1</span></span></td>
      <td><span class="lab cond">13-15, lab, L0.11 (compulsory if you failed test 1)</span><span class="dl">23:59 deadline: module 2</span></td>
      <td><span class="lab">13-15, lab, L0.11</span></td>
    </tr>
    <tr>
      <th>Week 4<span>21 - 25 Sep</span></th>
      <td><span class="lec">9-11, lecture, D1.116</span><span class="lab req">11-13, lab, L0.11 (compulsory)</span></td>
      <td><span class="lab">13-15, lab, L0.11</span><span class="dl">23:59 deadline: module 3</span></td>
      <td><span class="lab">13-15, lab, L0.11</span></td>
    </tr>
    <tr>
      <th>Week 5<span>28 Sep - 2 Oct</span></th>
      <td><span class="lec">9-11, lecture, D1.116</span><span class="lab req">11-13, lab, L0.11 (compulsory)<br><span class="test">test 2</span></span></td>
      <td><span class="lab cond">13-15, lab, L0.11 (compulsory if you failed test 2)</span><span class="dl">23:59 deadline: module 4</span></td>
      <td><span class="lab">13-15, lab, L0.11</span></td>
    </tr>
    <tr>
      <th>Week 6<span>5 - 9 Oct</span></th>
      <td><span class="lec">9-11, lecture, D1.116</span><span class="lab req">11-13, lab, L0.11 (compulsory)</span></td>
      <td><span class="lab">13-15, lab, L0.11</span><span class="dl">23:59 deadline: module 5</span></td>
      <td><span class="lab">13-15, lab, L0.11</span></td>
    </tr>
    <tr>
      <th>Week 7<span>12 - 16 Oct</span></th>
      <td><span class="lec">9-11, lecture, D1.116</span><span class="lab req">11-13, lab, L0.11 (compulsory)<br><span class="test">test 3</span></span></td>
      <td><span class="lab cond">13-15, lab, L0.11 (compulsory if you failed test 3)</span><span class="dl">23:59 deadline: module 6</span></td>
      <td><span class="disc">13-15, discuss module 6 + practice exam, L0.11</span></td>
    </tr>
    <tr>
      <th>Week 8<span>19 - 23 Oct</span></th>
      <td><span class="exam">13-15, exam, USC Universum Sporthal 1</span></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

The resit exam is on **Wednesday 6 January 2027**, 13:00 - 15:00, in IWO 4.04B (Geel).

The deadlines are shown in the table above. They are strict, but there is some leniency. You can submit up to three modules a *few days* after the deadline. If you need to submit more than three modules late, please **contact the teacher** before continuing the course.

If you notice that you're falling structurally behind, please contact the teacher to make a plan to catch up.

The official timetable is on [DataNose](https://datanose.nl/#course[147421]).

### Attendance {#attendance}

In the lectures we go through the theory and look at code samples together. In the labs you work on the assignments on campus, together with other students, and you can ask us questions while you work. The labs are also where you discuss your finished modules with us, and where the tests are taken.

- The **Monday lab** is compulsory, every week.
- The **Tuesday and Friday labs** are compulsory in the first two weeks. After that they are optional, with one exception: **if you failed Monday's test, the Tuesday lab of that week is compulsory for you**.
- Even when a lab is optional, we highly recommend you come. It's the main place where you talk with us and meet other students.

## Getting started {#getting-started}

To begin:

1. Read this syllabus carefully.
2. Install Python (instructions on the website).
3. Start with **Module 1** (*Numbers*).

## Programming modules {#programming-modules}
Here below is an overview of all modules.

<style>
.modules { width: 100%; border-collapse: collapse; margin-bottom: 1.5em; }
.modules th {
  text-align: left; padding: 0.5em 0.6em; font-size: 0.9em; white-space: nowrap;
  vertical-align: top; width: 1%; background: #f0ede6; border: 1px solid #d8d2c4;
}
.modules td { vertical-align: top; padding: 0.5em 0.6em; border: 1px solid #d8d2c4; line-height: 1.4; }
.modules td b { display: block; margin-bottom: 0.3em; }
</style>

<table class="modules">
  <tr>
    <th>Module 0</th>
    <td><b>INSTALL</b>Before you can start programming you set up your own machine: learn to use the command line, install Python together with uv and checkpy, and install the Zed editor. Work through these steps before Module 1.</td>
  </tr>
  <tr>
    <th>Module 1</th>
    <td><b>NUMBERS</b>How do you know if a number is a prime number? Number theory is the science about properties of numbers. In this mathematically oriented module you create a series of programs that compute this and other properties of numbers. No math knowledge required for this module. (You will learn some, though.)</td>
  </tr>
  <tr>
    <th>Module 2</th>
    <td><b>INTEGRATION</b>In many scientific fields you need to determine the surface area under a function. Integration is a mathematical tool for doing so. However this tool doesn't always work and in such cases we can use numerical integration techniques to let the computer do the work for us. You will learn two important techniques for numerical integration.</td>
  </tr>
  <tr>
    <th>Module 3</th>
    <td><b>BIG DATA</b>In this module you will learn to work with data. You will, for example, analyze weather from the Netherlands and answer questions like: When was the first heat-wave? What was the longest freezing period?</td>
  </tr>
  <tr>
    <th>Module 4</th>
    <td><b>MONOPOLY</b>When playing Monopoly, a starting player's advantage seems unfair. To verify, you could play many (millions) real games, but this would take way too much time. Instead, you'll write a computer simulation. This also allows you to experiment with game adjustments to make it fair. You're doing all this for a board game, but this simulation principle applies to various scientific fields (economy, chemistry, biology...).</td>
  </tr>
  <tr>
    <th>Module 5</th>
    <td><b>MONOPOLY 2</b>This is a continuation of MONOPOLY. You’re going to improve the design of your Monopoly simulation. You will learn about more advanced data structures that can help you improve the design of your code dramatically, making it easier to debug, maintain and extend. You will also learn about computational complexity, which gives you a way to reason about the efficiency of your algorithms and shows why picking the right data structure can mean the difference between a run time of a couple of minutes and one of weeks. Redesigning code that you already wrote using more advanced concepts might seem redundant, but it can be one of the most valuable learning experiences on the way to becoming a good programmer.</td>
  </tr>
  <tr>
    <th>Module 6</th>
    <td><b>POPULATIONS</b>Predator-prey simulations are models used in ecology and computer science to study the dynamics between populations of predators and their prey within an ecosystem. What's particularly interesting about these simulations is how they can reveal emergent patterns and complex behaviors that arise from relatively simple rules. To make it easier to program such a simulation you will learn a programming technique called object oriented programming (OOP). This whole module counts as a challenge: it is not required to pass the course, but it does count towards your grade.</td>
  </tr>
</table>
## Coursework (modules)

Each module is graded on a scale from 1 to 10. The grade is determined by how many
assignments you handed in correctly. 

Each module consists of theory sections, assignments and challenges. In the schedule
you will see these icons:

<ul class="types">
  <li><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-people-fill" viewBox="0 0 16 16"><path d="M7 14s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1zm4-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6m-5.784 6A2.24 2.24 0 0 1 5 13c0-1.355.68-2.75 1.936-3.72A6.3 6.3 0 0 0 5 9c-4 0-5 3-5 4s1 1 1 1zM4.5 8a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5"/></svg> <b>Collaborative assignments</b>: you are encouraged to work on these
      together with other students, and copying each other's code is no problem here.</li>
  <li><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person-fill" viewBox="0 0 16 16"><path d="M3 14s-1 0-1-1 1-4 6-4 6 3 6 4-1 1-1 1zm5-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6"/></svg> <b>Individual assignments</b>: you make these entirely on your own
      (with our help, of course). You may not copy code from anyone else.</li>
  <li><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person-fill-gear" viewBox="0 0 16 16"><path d="M11 5a3 3 0 1 1-6 0 3 3 0 0 1 6 0m-9 8c0 1 1 1 1 1h5.256A4.5 4.5 0 0 1 8 12.5a4.5 4.5 0 0 1 1.544-3.393Q8.844 9.002 8 9c-5 0-6 3-6 4m9.886-3.54c.18-.613 1.048-.613 1.229 0l.043.148a.64.64 0 0 0 .921.382l.136-.074c.561-.306 1.175.308.87.869l-.075.136a.64.64 0 0 0 .382.92l.149.045c.612.18.612 1.048 0 1.229l-.15.043a.64.64 0 0 0-.38.921l.074.136c.305.561-.309 1.175-.87.87l-.136-.075a.64.64 0 0 0-.92.382l-.045.149c-.18.612-1.048.612-1.229 0l-.043-.15a.64.64 0 0 0-.921-.38l-.136.074c-.561.305-1.175-.309-.87-.87l.075-.136a.64.64 0 0 0-.382-.92l-.148-.045c-.613-.18-.613-1.048 0-1.229l.148-.043a.64.64 0 0 0 .382-.921l-.074-.136c-.306-.561.308-1.175.869-.87l.136.075a.64.64 0 0 0 .92-.382zM14 12.5a1.5 1.5 0 1 0-3 0 1.5 1.5 0 0 0 3 0"/></svg> <b>Challenges</b>: optional, considerably harder assignments,
      for when you want to get the most out of this course.</li>
</ul>

## Grading {#grading}

Programming for minor Computational Science is a graded course.

### Final grade

Your final grade is built from three components:

| Component | Weight |
|-----------------------|-----|
| Coursework (modules)   | 30% |
| Tests                 | 10% |
| Final exam            | 60% |

To pass the course you need:

- a rounded final grade of **6.0** or higher;
- at least a **5.5** for the final exam;
- all modules *submitted* and *discussed* in person (Module 6 excepted, see below).

There is no minimum grade per module — a weak module can be compensated by the rest.

- The **individual** assignments and the **collaborative** assignments together are the 
  base assignments. If you complete them all you get a 7.
- The **challenges** are not compulsory, but they allow you to get a grade above a 7. We
  also highly recommend completing at least one per module to be fully prepared for the exam
  and/or future courses.

Some additional remarks:

- Module 6 (Populations) is semi-optional: You can still pass the course without it, 
  but it will cost you points on your coursework grade.
- For a challenge to count you have to be able to explain your code to a teacher.
- After you have submitted all parts of a module, **you need to come to a lab and discuss
  your code in person**. Only then do you get the grade for that module.

### Tests

- There are three short programming tests, taken during the Monday lab:
  **14 September**, **28 September** and **12 October**.
- Their average counts for 10% of your final grade.
- If you fail a test, the **Tuesday lab** of that week is compulsory for you. We will discuss the test and do a resit for it at the end of the session.

### Final exam

- The final exam is an (on campus) programming exam in a controlled setting, on an exam
  laptop. This will take about 2 hours. It contains a couple of small programming
  assignments, and is graded on a scale from 1 to 10.
- The exam is on **Monday 19 October, 13:00-15:00**, in USC Universum Sporthal 1.
- The resit is on **Wednesday 6 January 2027, 13:00-15:00**, in IWO 4.04B (Geel).

## Prerequisites {#prerequisites}

* No prior programming experience required.
* Some modules assume **high-school level mathematics**.

## Learning goals {#learning-goals}

After this course, you:

- can transform the description of a simple algorithm into working code by combining basic program elements;
- can apply several scientific programming techniques from different areas of study;
- can use a couple of libraries in your program and know how to find and read documentation on other libraries;
- can make your programs simpler and easier to read by employing a few standard tactics;
- can trace and fix several common programming errors;
- can use native python data structures (like sets, dictionaries, and tuples);
- can analyze the complexity of an algorithm;
- can use object oriented programming to structure a simulation.

## Course materials {#materials}

All the reading and video material is available on this website. You do not need to purchase any books or software. Every module consists of short explanations (written and in the form of videos) and assignments. _You do need to bring your own laptop._

## Doing your own work {#plagiarism}

This course's philosophy on academic honesty is best stated as "be reasonable." The course recognizes that interactions with classmates and others can facilitate mastery of the course's material. However, there remains a line between enlisting the help of another and submitting the work of another. This policy characterizes both sides of that line.

The essence of all work that you submit to this course must be your own (unless explicitly stated otherwise). Collaboration on problem sets is not permitted except to the extent that you may ask classmates and others for help so long as that help does not reduce to another doing your work for you. Generally speaking, when asking for help, you may show your code to others, but you may not view theirs, so long as you and they respect this policy's other constraints. Collaboration on the course's test and quiz is not permitted at all.

Below are rules of thumb that (inexhaustively) characterize acts that the course considers reasonable and not reasonable. If in doubt as to whether some act is reasonable, do not commit it until you solicit and receive approval in writing from the course's heads. Acts considered not reasonable by the course are handled harshly.

### Reasonable

- Communicating with classmates about problem sets' problems in English (or some other spoken language).
- Discussing the course's material with others in order to understand it better.
- Helping a classmate identify a bug in his or her code at office hours, elsewhere, or even online, as by viewing, compiling, or running his or her code, even on your own computer.
- Incorporating a few lines of code that you find online or elsewhere into your own code, provided that those lines are not themselves solutions to assigned problems and that you cite the lines' origins.
- Reviewing past semesters' quizzes and solutions thereto.
- Sending or showing code that you've written to someone, possibly a classmate, so that he or she might help you identify and fix a bug.
- Sharing a few lines of your own code online so that others might help you identify and fix a bug.
- Turning to the course's heads for help or receiving help from the course's heads during the quiz or test.
- Turning to the web or elsewhere for instruction beyond the course's own, for references, and for solutions to technical difficulties, but not for outright solutions to problem set's problems or your own final project.
- Whiteboarding solutions to problem sets with others using diagrams or pseudocode but not actual code.
- Working with (and even paying) a tutor to help you with the course, provided the tutor does not do your work for you.

### Not Reasonable

- Accessing a solution to some problem prior to (re-)submitting your own.
- Asking a classmate to see his or her solution to a problem set's problem before (re-)submitting your own.
- Decompiling, de-obfuscating, or disassembling the staff's solutions to problem sets.
- Failing to cite (as with comments) the origins of code or techniques that you discover outside of the course's own lessons and integrate into your own work, even while respecting this policy's other constraints.
- Giving or showing to a classmate a solution to a problem set's problem when it is he or she, and not you, who is struggling to solve it.
- Looking at another individual's work during the test or quiz.
- Paying or offering to pay an individual for work that you may submit as (part of) your own.
- Providing or making available solutions to problem sets to individuals who might take this course in the future.
- Searching for or soliciting outright solutions to problem sets online or elsewhere. So, **avoid** sources like: **Stackoverflow, Google, chatGPT, GitHub, Copilot**, etc.
- Splitting a problem set's workload with another individual and combining your work.
- Submitting (after possibly modifying) the work of another individual beyond the few lines allowed herein.
- Submitting the same or similar work to this course that you have submitted or will submit to another.
- Submitting work to this course that you intend to use outside of the course (e.g., for a job) without prior approval from the course's heads.
- Turning to humans (besides the course's heads) for help or receiving help from humans (besides the course's heads) during the quiz or test.
- Viewing another's solution to a problem set's problem and basing your own solution on it.

In all cases we follow the directives regarding fraud and plagiarism of the
University of Amsterdam and of the Computer Science
BSc programme. Find them here in [English] and [Dutch].

[Dutch]: http://uva.nl/plagiaat
[English]: https://student.uva.nl/en/content/az/plagiarism-and-fraud/plagiarism-and-fraud.html


## Acknowledgements {#acknowledgements}

This course has been designed by Simon Pauw, Martijn Stegeman, Wouter Vrielink, Tim Doolan and Ivo van Vulpen.

It is partially based on many great programming resources that have been published as Open Courseware under a Creative Commons license. The resulting work itself is also published under the Creative Commons License Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. Feel free to re-use! If you would like to use the work commercially, please send an e-mail for arranging a license.

We have had lots of help from students as well as teaching assistants who tried the course or added ideas of their own. We especially thank:

- Jelle van Assema (assignments and checkpy)
- Puck te Rietmolen (revisions)
- Roan van Blanken (checkpy tests)
- Amir Sahrani (assignments)
- Natasja Wezel (videos, revisions)
- Iris Luden (video)
- Marianne de Heer Kloots (revisions and testing)
- Maarten Inja (DNA assignment)
- Quinten Post (translations)
- Marleen Rijksen (revisions)
- Huub Rutjes (films)
- Vera Schild (checkpy tests)
- Luca Verhees (artwork “semester of code”)

We have used many programming recourses for inspiration:

- 6.189 A Gentle Introduction to Programming Using Python by Sarina Canelake at MIT http://ocw.mit.edu
- 6.00 Introduction to Computer Science and Programming, Fall 2008 by Eric Grimson and John Guttag at MIT http://ocw.mit.edu
- CS50 Introduction to Computer Science I by David Malan at Harvard http://cs50.tv/
- 6.0001 Introduction to Computer Science and Programming in Python by Ana Bell, Eric Grimson and John Guttag at MIT http://ocw.mit.edu
- Think Python by Allen B. Downey http://greenteapress.com/wp/think-python/
