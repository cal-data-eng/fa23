---
layout: page
title: Syllabus
nav_order: 2
description: >-
    Data Engineering
markdown: kramdown
---

# Syllabus
{:.no_toc}

**Note: This syllabus is subject to change! It has not been updated to reflect Fall 2023 policies.**

Jump to:
* TOC
{:toc}

<br>

<a name = 'about'></a>

## About Data 101

This course will cover the principles and practices of managing data at scale, with a focus on use cases in data analysis and machine learning. We will cover the entire life cycle of data management and science, ranging from data preparation to exploration, visualization and analysis, to machine learning and collaboration.

The class will balance foundational concerns with exposure to practical languages, tools, and real-world concerns. We will study the foundations of prevalent data models in use today, including relations, tensors, and dataframes, and mappings between them. We will study SQL as a means to query and manipulate data at scale, including analytical challenges like sampling, aggregation and windowing, and performance concerns like views and indexes, data models, query processing and optimization, and transactions, all from a user perspective. We will study the foundations and realities of data preparation, including hands-on work with real-world data using standard Python and SQL frameworks. We will explore data exploration modalities for non-programmers, including the fundamentals behind spreadsheet systems and interactive visual analytics packages. We will look at approaches for managing the lifecycle of data science, including the establishment, monitoring, and maintenance of data pipelines for both analytics and machine learning. Time permitting, we will look at the specifics of ML pipelines including data validation, training, prediction serving and feedback loops, as well as technologies for representing, moving, sharing, and caching data including event streaming systems, key-value/document stores, in-memory and on-disk representation formats, log analytics, and search engines.

**Textbook**: There is no official textbook for Data 100 this semester; we will provide course notes that will be released with the respective lectures.

## Prerequisites
COMPSCI C100/DATA C100/STAT C100 or COMPSCI 189 or INFO 251 or DATA 144/INFO 254 or equivalent upper-division course in data science. COMPSCI 61B or INFO 206B or equivalent courses in programming. This class will not assume deep experience with databases or big data solutions.

## Enrollment
The class is currently full with a long waitlist. Sadly due to teaching budget cuts we won't be able to expand the class or take concurrent enrollment students this semester, and we will let the waitlist play out on its own.

## Communications
Please make sure you are enrolled on Ed and Gradescope. Ed is our primary method of communication and making announcements, and you are responsible for checking it frequently. We plan on using bCourses only for lecture webcasts. Gradescope is where all assignments are submitted. 

The course staff email [{{site.course.email}}](mailto:{{site.course.email}}) is for private logistical student support and DSP accommodations and is monitored by both the instructor and a core set of staff to ensure fastest response. Please only contact the course instructor directly for matters that require strict privacy and their personal attention.

## Course Culture
Students taking Data C101 come from a wide range of backgrounds. We hope to foster an inclusive and safe learning environment based on curiosity rather than competition. All members of the course community — the instructors, students, and course staff — are expected to treat each other with courtesy and respect. Some of the responsibility for that lies with the staff, but a lot of it ultimately rests with you, the students.


### Be Aware of Your Actions
Sometimes, the little things add up to creating an unwelcoming culture to some students. For example, you and a friend may think you are sharing in a private joke about other races, majors, genders, abilities, cultures, etc. but this can have adverse effects on classmates who overhear it. There is a great deal of research on something called “stereotype threat”: research finds that simply reminding someone that they belong to a particular culture or share a particular identity (on whatever dimension) can interfere with their course performance.

Stereotype threat works both ways: you can assume that a student will struggle based on who they appear to be, or you can assume that a student is doing great based on who they appear to be. Both are potentially harmful.

Bear in mind that diversity has many facets, some of which are not visible. Your classmates may have medical conditions (physical or mental), personal situations (financial, family, etc.), or interests that aren’t common to most students in the course. Another aspect of professionalism is avoiding comments that (likely unintentionally) put down colleagues for situations they cannot control. Bragging in open space that an assignment is easy or “crazy,” for example, can send subtle cues that discourage classmates who are dealing with issues that you can’t see. Please take care, so we can create a class in which all students feel supported and respected.

### Be an Adult
Beyond the slips that many of us make unintentionally are a host of behaviors that the course staff, department, and university do not tolerate. These are generally classified under the term harassment; sexual harassment is a specific form that is governed by federal laws known as Title IX. UC Berkeley’s [Title IX website](https://ophd.berkeley.edu/){:target="_blank"} provides many resources for understanding the terms, procedures, and policies around harassment. Make sure you are aware enough of these issues to avoid crossing a line in your interactions with other students. For example, repeatedly asking another student out on a date after they have said no can cross this line.

Your reaction to this topic might be to laugh it off, or to make or think snide remarks about “political correctness” or jokes about consent or other things. You might think people just need to grow a thicker skin or learn to take a joke. This isn’t your decision to make. Research shows the consequences (emotional as well as physical) on people who experience harassment. When your behavior forces another student to focus on something other than their education, you have crossed a line. You have no right to take someone else’s education away from them.

### Issues with Course Staff

From the Data Science Department: [Data Science Undergraduate Studies](https://data.berkeley.edu/academics/undergraduate-programs){:target="_blank"} faculty and staff are committed to creating a community where every person feels [respected, included, and supported](https://data.berkeley.edu/equity-inclusion){:target="_blank"}. We recognize that incidents may happen, sometimes unintentionally, that run counter to this goal. There are many things we can do to try to improve the climate for students, but we need to understand where the challenges lie. **If you experience a remark, or disrespectful treatment, or if you feel you are being ignored, excluded or marginalized in a course or program-related activity**, please speak up. Consider talking to your instructor, but you are also welcome to contact Executive Director Christina Teller at [cpteller@berkeley.edu](mailto:cpteller@berkeley.edu) or report an incident anonymously through this [online form](https://docs.google.com/forms/d/e/1FAIpQLSfBwaUe7VMQz6VzkYFvf4KYwNSTve9iJlBSQyAmsXoSE0LnWw/viewform){:target="_blank"}.

As course staff, we are committed to creating a learning environment welcoming of all students that supports a diversity of thoughts, perspectives and experiences and respects your identities and backgrounds (including race, ethnicity, nationality, gender identity, socioeconomic class, sexual orientation, language, religion, ability, and more.) To help accomplish this:

- If your name and/or pronouns differ from those that appear in your official records, please let us know.
- If you feel like your performance in the class is being affected by your experiences outside of class (e.g., family matters, current events), please don’t hesitate to come and talk with us. We want to be resources for you.
- We (like many people) are still in the process of learning about diverse perspectives and identities. If something was said in class (by anyone) that made you feel uncomfortable, please talk to us about it.
- While the course staff understands that improving diversity, equity, and inclusion (DEI) are not enough to overcome systemic issues in academia such as racism, queerphobia, and other forms of discrimination and hatred, we also recognize the importance of DEI work.
    - The Data Science Department has some resources available at [https://data.berkeley.edu/about/diversity-equity-and-inclusion](https://data.berkeley.edu/about/diversity-equity-and-inclusion){:target="_blank"}.
    - There’s also a great set of resources available at [https://eecs.berkeley.edu/resources/students/grievances](https://eecs.berkeley.edu/resources/students/grievances){:target="_blank"}.
- If there are other resources you think we should list here, let us know!

**We will take all complaints about unprofessional or discriminatory behavior seriously.**

### Misuse of Course Resources
If individuals are disrespectful to students, course staff, or others via course resources, they will lose access to course resources. E.g., if someone is unkind in the course forum, their account will be removed from the course forum. If someone is unkind in the classroom, they will be asked to leave the classroom.

## Grading
60% of your grade will come from projects, and 25% of your grade will come from multivitamins. Each project and multivitamin will be weighted equally. The final exam will be worth 15% of your grade.

### Final Exam
Final exam will be held on Thursday, December 15th, from 11:30am - 2:30pm. **The final exam is offered in-person only (location TBD), and we will not offer alternate exams.** It is your responsibility to ensure that you are not enrolled in another class that conflicts with our exam time.

### Projects
Throughout the semester, we will release 5 programming assignments via Ed and the website. The 5th project is optional for undergraduate students enrolled in Data 101 and required for graduate students enrolled in Info 258. For Data 101 students, the first four projects are each worth 15% of your grade, and the fifth project can replace your lowest project score. For Info 258, each of the five projects is worth 12% of your grade.

### Multivitamins
Multivitamins are short written assignments designed to keep you on schedule and check your understanding of the basics from lecture. They will mostly consist of multiple choice questions covering material that is not covered in the projects. If you are struggling with any of the questions on the multivitamin, you are encouraged to come to office hours for help. We will have 5 multivitamins throughout the semester.

## Office Hours
Office hours are a great place to go for help with multivitamins, projects, or any other content-related questions. You can find a list of regular office hours under the Staff tab on this page. We may also host project parties throughout the semester ahead of project deadlines. The course calendar under the Calendar tab will always show the most up-to-date times and locations for office hours / project parties.

## Late Policy
You will get 4 slip days for projects and 4 slip days for multivitamins. Note that these are separate, so you will not receive extra project slip days if you do not use all of your multivitamin slip days. Likewise, using a slip day for a project will not use up one of your multivitamin slip days. Slip days are automatically used in the manner that will optimize your score the most. After using all of your slip time for a particular assignment category, you’ll be docked 15% of your score for the assignment each extra late day on your submission. This applies to both projects and multivitamins. Note that submission times are rounded up to the next day. That is, 2 minutes late = 1 day late.

## Collaboration Policy
We do not allow for collaboration on assignments since we expect you to complete all assignments individually; however, you are free (and encouraged!) to discuss concepts from lecture. We will follow the [EECS departmental policy](https://eecs.berkeley.edu/resources/students/academic-dishonesty) on academic honesty, so be sure you are familiar with it. And hey — don’t cheat. Not cool.

## Extensions
For administrative and logistics issues, deadline extension requests, alternate exam requests, DSP accommodations, or special accommodations (for emergencies or personal issues), please make a private post on Ed. If you need an extension, please include your reason for requesting an extension and any relevant documentation if applicable. If you are a DSP student and your accommodation letter allows for extensions on assignments, you will be given 2 extra days per assignment deadline on top of your slip day allocation. If you require any extensions beyond that, please make a private post on Ed. For issues that you do not feel comfortable with posting on Ed, feel free to email the TAs or the instructor. However, we would recommend posting on Ed if possible to ensure a quicker response.

## Academic and Wellness Resources

Our [Resources](../resources) page lists not only course-specific academic resources such as course notes, past exams, study guides, and prerequisite review links, but also campus wellness resources on COVID-19, academic support, technology support, mental well-being, DSP accommodations, dispute resolution, social services, campus community, and basic needs. Our staff will also refer to this page when supporting you through this course.


## We want you to succeed!

If you are feeling overwhelmed, visit our office hours and talk with us, or fill out the Extenuating Circumstances Form. We know college can be stressful and we want to help you succeed.

Finally, the main goal of this course is that you should learn, and have a fantastic experience doing so. Please keep that goal in mind throughout the semester. Welcome to Data 101!


## Acknowledgments

Academic Honesty policy and closing words adapted from [Data 8](https://data8.org/){:target="_blank"}. Course Culture inspired and adapted with permission from Dr. Sarah Chasins’ [Fall 2021 CS 164 Syllabus](https://inst.eecs.berkeley.edu/~cs164/fa21/syllabus.html){:target="_blank"} and Grace O’Connell, the Asssociate Dean for Inclusive Excellence.
