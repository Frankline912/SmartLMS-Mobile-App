# User Personas & Requirements

**Institution:** Dedan Kimathi University of Technology

## 1. User Personas

### Persona 1: The Busy Undergraduate

**Name:** Amina Yusuf
**Age:** 20
**Institution:** Dedan Kimathi University of Technology
**Role:** Second-year Information Technology student
**Tech comfort:** High — uses her phone for almost everything

**Background:**
Amina juggles five courses, a part-time job, and student club activities. She checks her phone constantly between classes and needs to know what's due, what's new, and what's urgent — fast.

**Goals:**
- Quickly see upcoming deadlines and new announcements
- Submit assignments without hassle, even close to a deadline
- Track her grades across all courses in one place

**Frustrations:**
- Course materials scattered across email, WhatsApp groups, and paper handouts
- Missing announcements because they're buried in email
- Slow or confusing submission processes that risk late penalties

**A typical quote:**
"If it takes more than three taps to find out what's due tomorrow, I'm not going to bother."

---

### Persona 2: The Detail-Oriented Instructor

**Name:** Dr. Peter Mwangi
**Age:** 42
**Institution:** Dedan Kimathi University of Technology
**Role:** Lecturer, teaches 2 courses per semester
**Tech comfort:** Moderate — comfortable with basic tools, impatient with clunky ones

**Background:**
Dr. Mwangi manages course materials, grades, and discussion forums for over 100 students across two courses. He wants a system that saves him time on repetitive tasks like posting announcements and grading.

**Goals:**
- Post announcements and materials to all students in one action
- Review and grade submissions efficiently
- Monitor discussion forum activity without much manual effort

**Frustrations:**
- Manually re-posting the same announcement across multiple channels
- Losing track of who has and hasn't submitted an assignment
- Discussion forums that are hard to moderate

**A typical quote:**
"I don't need more features — I need the ones I use every day to just work, quickly."

---

### Persona 3 (optional third persona): The First-Year Student

**Name:** Grace Wanjiru
**Age:** 18
**Institution:** Dedan Kimathi University of Technology
**Role:** First-year student, new to university life
**Tech comfort:** Moderate — comfortable with apps, unfamiliar with academic systems

**Background:**
Grace is still learning how university coursework, grading, and deadlines work. She relies heavily on clear instructions and a simple, uncluttered interface to avoid feeling overwhelmed.

**Goals:**
- Understand what's expected of her in each course
- Find course materials and grading criteria easily
- Feel confident she hasn't missed anything important

**Frustrations:**
- Complicated navigation with unclear labels
- Uncertainty about whether an assignment was successfully submitted

---

## 2. Functional Requirements

Functional requirements describe **what the system must do**.

| ID | Requirement |
|----|-------------|
| FR-1 | Users must be able to log in and view a personalized dashboard showing upcoming deadlines and recent announcements |
| FR-2 | Students must be able to view a list of enrolled courses and access each course's details page |
| FR-3 | Each course page must display course materials, organized and downloadable |
| FR-4 | Instructors must be able to post announcements visible to all students in a course |
| FR-5 | Students must be able to view and submit assignments before a deadline |
| FR-6 | The system must confirm successful assignment submission (e.g. confirmation message or status change) |
| FR-7 | Students and instructors must be able to participate in a course discussion forum (post, reply, view threads) |
| FR-8 | Students must be able to view their grades per assignment and overall per course |
| FR-9 | Instructors must be able to grade submissions and leave feedback |
| FR-10 | Users must be able to view and edit their profile information |
| FR-11 | The system must restrict access so students only see their own grades, and instructors only manage their own courses |

---

## 3. Usability Requirements

Usability requirements describe **how well** the system must perform for users.

| ID | Requirement |
|----|-------------|
| UR-1 | A new user should be able to find their upcoming deadlines within 10 seconds of logging in |
| UR-2 | Navigation labels must be clear enough that a first-time user (e.g. a new student) can find "Assignments" or "Grades" without guidance |
| UR-3 | The assignment submission process must take no more than 3 steps from the course page |
| UR-4 | The system must provide clear visual feedback (e.g. success/error messages) for key actions like submitting an assignment or posting to a forum |
| UR-5 | The interface must be consistent across all screens (same navigation structure, button styles, and terminology) |
| UR-6 | The system must be usable on both desktop and mobile screen sizes |
| UR-7 | Error messages must explain what went wrong and how to fix it, rather than showing generic errors |
| UR-8 | At least 80% of usability test participants should be able to complete a core task (e.g. submitting an assignment) without assistance |

---

## 4. User Journey

**Scenario: Amina submits an assignment before a deadline**

1. **Trigger:** Amina gets a reminder notification (or checks the app) that an assignment is due tomorrow.
2. **Login:** She opens the app and logs in, landing on her Dashboard.
3. **Discover:** The Dashboard highlights the upcoming deadline with the course name and due date.
4. **Navigate:** She taps the deadline, which takes her directly to the Course Details page for that course.
5. **Locate:** She finds the "Assignments" section and selects the relevant assignment.
6. **Review:** She reads the assignment instructions and checks the attached materials/rubric.
7. **Submit:** She uploads her file via the "Submit Assignment" screen.
8. **Confirm:** The system shows a confirmation message and updates the assignment status to "Submitted."
9. **Follow-up:** A few days later, she checks the "Grades" screen and sees her grade and instructor feedback for that assignment.

**Key touchpoints:** Dashboard → Course Details → Assignments → Submit Assignment → Grades

**Pain points this journey should avoid:**
- Getting lost trying to find which course the deadline belongs to
- Uncertainty about whether the submission actually went through
- Delayed or missing grade/feedback visibility after submission

---

*Prepared by: Teddy Kei — User Personas & Requirements*
*Folder: `docs/`*
