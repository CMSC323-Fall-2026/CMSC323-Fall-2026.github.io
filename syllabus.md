---
layout: article
title: Syllabus

# layout: article
layout: default
aside:
  toc: true
---

# Syllabus

## Meeting Times and Staff

### Instructor

* **Instructor:** Dr. Doug Szajda
* **Email:** [dszajda@richmond.edu](mailto:dszajda@richmond.edu)
* **Office Hours:** (Jepson 219)
  * TBD -- I will discuss this in lecture so we can agree on times that work for you.
  * Non-scheduled times by appointment (email me or catch me before or after class to schedule)
  * You should also feel free to drop by my office.
* **Prerequisites:** CMSC 301 with a minimum grade of C-. CMSC 315 is recommended, but not required. (See [computer science curriculum](https://cs.richmond.edu/Academics/courses/index.html))

### Meeting Times

## Class/Lab Info
* Lecture (Weinstein 210)
  * Tue 12:00PM - 1:15PM
  * Thr 12:00PM - 1:15PM
* Lab (Weinstein 210)
  * Fri 12:00PM - 12:50PM

### Course Staff
- Dr. Doug Szajda - Instructor


## Course Details 

### Welcome to the Design and Implementation of Programming Languages!

Your dedication and hard work have led you to this moment; you belong here. Congratulations on your achievements, and welcome to the course. I am thrilled to have you here and am looking forward to a semester filled with growth, learning, and success. Together, we will explore, create, and innovate. Let's make this an outstanding semester for everyone!

### Course Description

This is a one unit course on the design and implementation of programming languages. These are not independent.  What we'll be discussing in this course are the features of programming languages, along with how such features effect the implementation of these languages.  As an analogy, consider an architect.  An architect can design anything they can imagine.  But they don't work in a vacuum.  Their perhaps very creative designs have to be constructed.  An architect who does not consider how their designs can be built, and at what cost, will likely end up designing a lot of structures that are never built. So an architect needs to understand how, and whether, the features they design can actually be practically implemented.  Our journey in this course will be doing the same with programming languages. 

We will consider this relation between design and implementation of programming languages  by building features of a specific language. The features we will implement include an interpreter, a parser, a program generator, and a type-checker. You will be briefly exposed to compilers and learn about garbage collectors. The programming language you design and build in this course will follow the *Standard Model Of Programming Languages* (SMOL), which many popular programming languages (e.g., Java, C#, JavaScript, Python) follow. We will implement our programming language using the *Standard Implementation Plan* (SImPl), where expressions in a language are represented as trees. You will also be exposed to functional languages, particularly Dr Racket’s PLAIT, which are elegant and concise ways of expressing problems. PLAIT is built on the functional language Scheme, and is used in this course for its simplicity, expressive elegance, and size.

### Course Topics 

I could provide a long list of the topics we'll cover, but I expect that at this point most
of them would not make sense to you.  So my intention is to add them as we cover them. We
start with an introduction to PLAIT, which is a *functional* programming language.  (And if you're asking what that is, then you understand why I did not provide a list of topics.) Know that during the course, we will be implementing an interpreter for a functional language, using a functional language.  

<ul>
<li> PLAIT and an introduction to functional languages</li>
</ul>
## Prerequisite

The pre-requisite for this course is CMSC 301, completed with a grade of C- or better, or permission of the instructor.  As mentioned, CMSC 315 is recommended, though not required.  These courses are recommended for reasons of CS maturity, not because we'll be using circuits, gates, etc. This being said, CMSC 315 is really all about computational problem solving. We'll have a good bit of this to do, though we'll do it in code, not through proofs (which I'm sure makes all of you a bit sad). 

## Textbook

There is a textbook for this course.  It is free and can be found [here](https://www.plai.org/ ).  I realize that some of you prefer to absorb material through other types of media.  Feel free to do so.  But at least you know that you have a text reference should you need one.  

## Course Structure

Tuesdays and Thursdays: Lectures, discussion, and exercises. Exercises are typically unannounced and open-book.  They are not graded, but are instead an opportunity for you
to reinforce what has been discussed in lecture, and to practice the concepts you will need to complete the programming projects. 

Fridays (Labs): Typically, work on the programming projects.  These projects are also typically released during our labs. 

## Coursework and Grading

Traditional grading schemes have been shown to be counterproductive for 
a number of reasons.  One of these is that such systems often incentivize the 
wrong thing -- getting the highest grade -- as opposed to incentivizing 
learning the material.  While I will not be using a specifications-based grading 
system, I want to make learning goals clear, and provide students with an opportunity to 
earn back *some* of the points that are missed on midterm exams.  Note that
I cannot allow students to earn back points lost on the final exam.


### Course Work

- The majority of the points (70%) that determine your course grade will come from the programming projects.  There will be 7 or 8 of these.  They will be released on lab days and are due two weeks from the date assigned.  Projects are released via GitHub repositories.  Some of you have had classes with me, so know the drill.  For those
that don't, please drop by and I will be happy to explain.

- There will be two midterm exams, and one final.  With the exception of the 
final, you will have the opportunity to earn back a portion of the points you 
lose on an exam.  All exams will be in-class.  I have not yet determined whether they will be open-book, open note. They will definitely *not* be open Internet.  Because
the exams are in-class, there is no need for a followup oral exam component.  

I typically do not watch students when they take exams, but in this class, I reserve the right to do so.  I want to assert that should I do so, I am not attempting to detect cheating.  Rather, by watching you write PLAIT code, I am able to judge something of your facility with the language, and with the concepts we have learned. 


### Grade Determination

| Grade Component | Proportion |
| :---:| :--- : |
| Programming projects | 70 % |
| First midterm | 10 %|
| Second midterm | 10 %|
| Final Exam | 10 % |

One note on the grade distribution mentioned above.  Failure to turn in two of the programming projects will result in a failing grade for the course.  Moreover, any assignment or exam submitted that indicates that a lack of a sincere effort will be treated as if it was not submitted.  

Regarding the final course grade, my goal is that your final course grade reflects the following ideal as much as possible. (Note that this means that curving grades is not necessary, nor are you competing against your classmates.)
- An ``A'' means that your knowledge of this material is exceptional. Should you ever have to build on the material that you learned in this class, you will be able to do so easily.
- A ``B'' means that you have a good understanding of most of the material, but may have some gaps in your understanding, or are not as comfortable with some aspects of it as you might be. You will generally be able to apply the material in this class, but you may have difficulty doing so with some of it.
- A ``C'' means that your knowledge of this material is average/mediocre. You will likely struggle to apply this material, as you have struggled learning the material in this class.
- A ``D'' means that you are not sufficiently prepared to builds on the material from this class.
- An ``F'' means that in addition to the conditions for a ``D'' grade, you also didn't try and/or failed to hand in work.
- A ``V'' means that you missed too many classes to pass the class, regardless of your performance on the work.

### On Coding Help and Debugging

Programming Help:  The programming requirements for this course can be challenging, but that is primarily because it is a language style that most of you have not seen before (and because PLAIT's static typing can be, well, something you have not experienced before). I am happy to discuss programming and debugging techniques, as well as the semantics of particular aspects of PLAIT. Bottom line, I am in general happy to help you in whatever way is necessary. I will not, however, debug your code for you! If you describe your programming issue with me, I will suggest potentially useful debugging strategies. But debugging is an important part (and in fact the majority part) of many programming-related projects. As such, you need to be comfortable with doing it on your own!  That does not mean I intend for you to be stuck on a particular error for hours.  

You may discuss projects with your classmates, faculty, other students, etc, subject to the
*empty hands policy* presented below. 

When you receive coding help, you should mention that help (and who helped) in your project submission. Regardless of how much help you received and from who, once you submit a project, it is expected that you will be able to provide me with answers to any questions I may have about what you have submitted. 

Finally, any help you receive from someone other than me is subject to the 
``Empty Hands'' policy --- you may freely discuss ideas and approaches with your anyone 
subject to the restriction that you must leave the discussion without any written or otherwise recorded material. Failure to comply with this policy or the guideline discussed here will be treated as an Honor Code violation. 

### Late Work Policy

Non-exam assignments may be submitted late with a **10%** deduction **per day** late, up to a maximum of four days late. 

In cases of personal illnesses, emergencies, or documented accommodations, assignments may be submitted late for full credit if you notify me of your situation prior to the time
the project is due!


### Attendance Policy
Regular attendance for the entire class time is expected. You should not miss more than 4 total sessions (including lecture and lab).  If you miss enough classes that I notice, then you are missing too much (I do record attendance). 
   

## Class Communication

I will use two primary forms of communication in this class: email announcements and Slack. You are responsible for remaining up to date on any information sent by email or posted to Slack. This may include clarifications to assignments, updates on grading rubrics, and changes in office hours.  I will set up the Slack channel shortly. 

For all general course information, questions, and clarifications, please use Slack. I hope that the Slack workspace can be an extension of our classroom community where we can share questions and answers for the entire class to view and learn from.

If you have personal, individual issues you'd like addressed, you should send those by email to me. However, all course related topics should be directed to Slack.

## Course Policies

### Illness policy

If you are ill and it will cause you to miss class, lab, or an assignment, you should let me know in advance, if possible. It is your responsibility to catch up with any missed material if you are able to do so.  If not, then immediately on return, work out a time-frame with me on when work will be submitted. 

### Generative AI

You will almost certainly be using generative AI in some way for the rest of your career. You may use generative AI tools for the projects in the following manner.

You must: 

- Understand any code that you use. I reserve the right to review your submitted code with you, and ask you to explain how it works. 

You may:
- Ask a GenAI tool a generic question for informational purposes. For example, "Please explain the PLAIT syntax for defining a function, and give an example."  If you use this code, please cite the source in a comment.

You may not:
- Ask a GenAI tool to solve any part of the assignment.  For example, you should not paste the entire problem description and ask the GenAI to solve it for you.

- No GenAI tools can be used for any of the exams.

This policy is subject to change as we all learn more about how GenAI works and doesn’t work as part of learning college level course content.

### Disability Services 

Any student who may need an accommodation based on the potential impact of a disability should contact [Disability Services](https://disability.richmond.edu/) (or call 804-662-5001) to establish eligibility and to coordinate reasonable accommodations. 

If you are approved for classroom and/or testing accommodation(s) please make sure to submit a Disability Accommodation Notice to me at this [link](https://disabilityportal.richmond.edu/ClockWork/user/selfregC/courses.aspx).


## Wellness

If any issue arises that may limit your ability to participate in class, for example, personal illness, family emergency, etc., please be sure to discuss these matters with me as soon as possible and accommodations will be made available to you as appropriate.

Feelings of being overwhelmed are unfortunately quite common in the university environment. You are not alone, and there are a number of resources available to provide support in those moments. Learning to ask for help is an important part of the university experience, and if you or anyone you know experiences any academic stress, difficult life events, or feelings of anxiety or depression, we strongly encourage you to seek support. UR offers counseling services, and also consider reaching out to a friend, family or faculty member you trust for help.

If you or someone you know is feeling suicidal or in danger of self-harm, call someone immediately, day or night:
* UR Counseling and Psychological Services: 804-289-8119
* University of Richmond Police: 804-289-8911 
* National Suicide Prevention Lifeline: 1-800-273-8255



## Weinstein Learning Center

[Academic Skills Center](asc.richmond.edu): Academic coaches assist students in assessing and developing their academic and life-skills (e.g., critical reading and thinking, information conceptualization, concentration, test preparation, time management, stress management, etc.). Peer tutors offer assistance in specific subject areas (e.g., calculus, chemistry, accounting, etc.) and will be available for appointments in-person and virtually. Peer tutors are listed on the ASC website. Email Roger Mancastroppa ([rmancast@richmond.edu](mailto:rmancast@richmond.edu)) and Hope Walton ([hwalton@richmond.edu](mailto:hwalton@richmond.edu)) for coaching appointments in academic and life skills.

[English Language Learning](https://llc.richmond.edu/faculty/lbohon): assists multi-lingual and international students in honing their language, academic, and/or intercultural skills. Among other available services for students are one-on-one tutoring, group workshops, and semester-long classes on writing and U.S. culture. Please contact Dr. Bohon, Director of English Language Learning, at [Leslie.Bohon@Richmond.edu](mailto:Leslie.Bohon@Richmond.edu) for more information and appointments.

[Quantitative Resource Center](https://qrc.richmond.edu): Provides services related to quantitative and computational learning across the curriculum through tutoring, consultation and training.

[Speech Center](https://speech.richmond.edu): Assists with preparation and practice in the pursuit of excellence in public expression. Recording, playback, coaching and critique sessions are offered by teams of trained student consultants. During scheduled appointments, consultants assist in developing ideas, arranging key points for more effective organization, improving style and delivery, and handling multimedia aids for individual and group presentations. We look forward to meeting your public speaking needs.

[Technology Learning Center](https://tlc.richmond.edu) The TLC is a staffed public lab dedicated to supporting digital media projects. Services include camera checkout, video/audio recording assistance, virtual reality, poster printing, 3D printing and modeling. The TLC is located on the second floor of Boatwright Library.

[Writing Center](https://writing.richmond.edu): Assists writers at all levels of experience, across all majors. Students can attend walk-in hours at Boatwright Library (room 171A) with trained writing consultants who offer friendly critiques of written work.


## Other Campus Services

[Boatwright Library Research Librarians](https://library.richmond.edu/help/ask/) (289-8876): Research librarians help students with all steps of their research, from identifying or narrowing a topic, to locating, accessing, evaluating, and citing information resources. Librarians support students in their classes across the curriculum and provide individual appointments, class library instruction, tutorials, and research guides (libguides.richmond.edu). Students can contact an individual [librarian](https://library.richmond.edu/help/liaison-librarians.html) or ASK a librarian for help via [email](mailto:library@richmond.edu), text (804-277-9ASK), or [chat](https://library.richmond.edu/chat.html).

[Career Services](https://careerservices.richmond.edu) (289-8547): Can assist you in exploring your interests and abilities, choosing a major or course of study, connecting with internships and jobs, and investigating graduate and professional school options. We encourage you to update your profile in Handshake and schedule an appointment with a career advisor early in your time at UR. 

[Counseling and Psychological Services](https://caps.richmond.edu) (289-8119): Assists currently enrolled, full-time, degree-seeking students in improving their mental health and well-being, and in handling challenges that may impede their growth and development. Services include brief consultations, short-term counseling, skills-building classes, therapy groups, crisis intervention, psychiatric consultation, and related services.

## Acknowledgments

Some of the material for this course (especially the homework assignments) comes from previous iterations taught by Prof. Prateek Bhakta. 



[def]: https://www.plai.org/