---
title: "Introduction to Social Networks (SOC 321K)"
subtitle: "University of Texas at Austin, Department of Sociology"
date: 2025-04-21
type: page
layout: page
summary: "Overview of the CSS graduate course"
draft: false
share: false
url: "/teaching/social_networks/"
---

**Meeting Times:** Tue/Thu 09:30 AM – 11:00 AM  
**Meeting Location:** RLP 0.102  

**Course Instructor:**  
Casey Breen (Email: [casey.breen@austin.utexas.edu](mailto:casey.breen@austin.utexas.edu))  
🕒 Office Hours Sign-up (Tuesdays from 11:30am–2:00pm): [Book Link](https://outlook.office.com/bookwithme/user/1980bdc73dae4f878e7a706d170fbd71@eid.utexas.edu/meetingtype/t0EPQaqRKkeIfsN843-J9A2?bookingcode=05d60240-2c1f-4a72-9c31-00358ea6e815&anonymous&ismsaljsauthenabled&ep=mlink)

---

## Course Overview

This course introduces the science of social networks—how people are connected and how those connections shape social behavior, 
opportunities, and outcomes. We will use concepts and methods from the social, natural, and mathematical sciences to define networks,
analyze network data, and examine how networks are applied in both academic research and practice. The course draws on examples from 
public health (e.g., HIV prevention at CDC and UNAIDS), sociology (e.g., how friendship networks influence educational outcomes), 
and technology (e.g., the rise and diffusion of social media platforms in Silicon Valley). We will combine theory, empirical research, 
and hands-on data analysis to build a foundational understanding of social networks.

---

## Learning Outcomes

At the conclusion of this course, students will be able to:

- Understand the components and properties of social networks  
- Critically engage with classic and contemporary social network research  
- Evaluate how social networks structure the social world and shape life outcomes  

---

## Assignments and weight

- Exam 1 — 20%  
- Exam 2 — 20%  
- Homeworks — 15%  
- Labs — 15%  
- Final Podcast Project — 20%  
- Attendance — 10%  

---

## Class Schedule

| Date | Type | Topic | Due |
|------|------|-------|-----|
| Jan 13 | Lecture 1 | [Introduction to course + syllabus](#jan-13) | — |
| Jan 15 | Lecture 2 | [Basic graph theory / giant component / degree distributions](#jan-15) | — |
| Jan 20 | Lecture 3 | [Personal networks & social isolation](#jan-20) | — |
| Jan 22 | Lab 1 | [Intro to R and iGraph](#jan-22) | **Lab 1 due** |
| Jan 27 | Lecture 4 | [Personal networks (cont.) & triadic closure](#jan-27) | — |
| Jan 29 | Lecture 5 | [Strength of weak ties / social capital](#jan-29) | — |
| Feb 3 | Lecture 6 | [Structural balance](#feb-3) | — |
| Feb 10 | Lecture 8 | [Friendship paradox & centrality](#feb-10) | **Homework 1 due** |
| Feb 12 | Review | [Exam 1 review](#feb-12) | — |
| Feb 17 | Exam | [Exam 1](#feb-17) | **Exam 1** |
| Feb 19 | Lecture 9 | [Homophily](#feb-19) | — |
| Feb 24 | Lecture 10 | [Contagions I](#feb-24) | — |
| Feb 26 | Lecture 11 | [Contagions II](#feb-26) | — |
| Mar 3 | Lecture 12 | [Social influence, herding & cascades](#mar-3) | — |
| Mar 5 | Lab 2 | [Network visualization & homophily indices](#mar-5) | **Lab 2 due** |
| Mar 10 | Lecture 13 | [Community detection](#mar-10) | — |
| Mar 12 | Lecture 14 | [Respondent-driven sampling](#mar-12) | — |
| Mar 17 | — | [Spring break — no class](#mar-17) | — |
| Mar 19 | — | [Spring break — no class](#mar-19) | — |
| Mar 24 | Lecture 15 | [Network scale-up method](#mar-24) | **Homework 2 due** |
| Mar 26 | Review | [Exam 2 review](#mar-26) | — |
| Mar 31 | Exam | [Exam 2](#mar-31) | **Exam 2** |
| Apr 2 | Lecture 16 | [Final project overview & meet-up](#apr-2) | — |
| Apr 7 | Lecture 17 | [Networks in practice: suicide networks](#apr-7) | **Homework 3 due** |
| Apr 9 | Lecture 18 | [Networks in practice: experiments](#apr-9) | — |
| Apr 14 | Lab 3 | [Network scale-up method](#apr-14) | **Lab 3 due** |
| Apr 16 | Flex | [Final project preparation](#apr-16) | — |
| Apr 21 | Presentation | [Final presentations](#apr-21) | — |
| Apr 23 | Presentation | [Final presentations](#apr-23) | — |
---

## Daily Schedule

### January 13 — Lecture 1 {#jan-13}
**Welcome! Introduction to course + syllabus; examples of social network research**  

— Course syllabus

<div style="position:relative; padding-top:56.25%;">
  <iframe
    src="https://docs.google.com/presentation/d/e/2PACX-1vQj-X9r6WgSOq8ByGZI3i-xx-jQWL6ZCSrCn65yd0KGRb_2cijPFTKyec4ogpul6zP8QhKVF6QAf7_D/pubembed?start=false&loop=false&delayms=60000"
    frameborder="0"
    allowfullscreen
    style="position:absolute; top:0; left:0; width:100%; height:100%;"
  ></iframe>
  
 <!-- click-capture only on the lower-right "Google Slides" area -->
  <a href="https://drive.google.com/drive/folders/1-xt639Jn8B6Ak4wxSVg5JOFG5SerQSHo?usp=sharing"
     target="_blank" rel="noopener noreferrer"
     aria-label="Open course folder"
     style="
       position:absolute;
       right:8px;
       bottom:8px;
       width:170px;
       height:56px;
       z-index:10;
       background:transparent;
     ">
  </a>
</div>


---

### January 15 — Lecture 2 {#jan-15}
**Basic graph theory / giant component / degree distributions**  
— Easley and Kleinberg Ch 1, Ch 2  
— Borgatti, Stephen P., Ajay Mehra, Daniel J. Brass, and Giuseppe Labianca. 2009. “Network Analysis in the Social Sciences.” *Science*.


<div style="position:relative; padding-top:56.25%; border-radius:8px; overflow:hidden;">
  <iframe
    src="https://docs.google.com/presentation/d/e/2PACX-1vRUaPvvOV5VcbMblLTEDHP-lkO5zz8IqT6yp0_gfLYOF5H5b8t9nQBqcM41trulNvK7u2Vbk_ONqJn-/pubembed?start=false&loop=false&delayms=3000"
    frameborder="0"
    allowfullscreen
    style="position:absolute; top:0; left:0; width:100%; height:100%; border:0;"
  ></iframe>

  <!-- click-capture only on the lower-right "Google Slides" area -->
  <a href="https://drive.google.com/drive/folders/1-xt639Jn8B6Ak4wxSVg5JOFG5SerQSHo?usp=sharing"
     target="_blank" rel="noopener noreferrer"
     aria-label="Open course folder"
     style="
       position:absolute;
       right:8px;
       bottom:8px;
       width:170px;
       height:56px;
       z-index:10;
       background:transparent;
     ">
  </a>
</div>

---

### January 20 — Lecture 3 {#jan-20}
**Personal networks; social connectedness and social isolation in America**  
— McPherson, Miller, Lynn Smith-Lovin, and Matthew E. Brashears. 2006. “Social Isolation in America: Changes in Core Discussion Networks over Two Decades.” *American Sociological Review*.


<div style="position:relative; padding-top:56.25%;">
  <iframe
    src="https://docs.google.com/presentation/d/e/2PACX-1vRbx4IH2eUrV8Ai4OJErG7UDoKfosVq7j6aWaIBtoxAJkLxnsMaJiqTOMqubtWiyh7HVBOvTs5sGgjJ/pubembed?start=false&loop=false&delayms=3000"
    frameborder="0"
    allowfullscreen
    style="position:absolute; top:0; left:0; width:100%; height:100%;"
  ></iframe>
  
   <!-- click-capture only on the lower-right "Google Slides" area -->
  <a href="https://drive.google.com/drive/folders/1-xt639Jn8B6Ak4wxSVg5JOFG5SerQSHo?usp=sharing"
     target="_blank" rel="noopener noreferrer"
     aria-label="Open course folder"
     style="
       position:absolute;
       right:8px;
       bottom:8px;
       width:170px;
       height:56px;
       z-index:10;
       background:transparent;
     ">
  </a>
</div>
</div>

*Note: Please install R and RStudio in advance of next sesion, which is an R lab.*
---

### January 22 — Lab 1 {#jan-22}
**Intro to R and iGraph package**  
— Textbook: [R for Data Science](https://r4ds.hadley.nz/intro.html) [For reference; not required reading]  


**Lab 1 Due**

<div style="
  max-width: 1200px;
  margin: 2rem auto;
  padding: 0.75rem;
  border: 1px solid #ddd;
  border-radius: 10px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.08);
  background: #fff;
">
  <div style="width:100%; height:45vh;">
    <iframe
      src="/media/teaching_materials/session1_slides.html"
      style="width:100%; height:100%; border:0; border-radius:6px;"
      allowfullscreen>
    </iframe>
  </div>
</div>

---

### January 27 — Lecture 4 {#jan-27}
**Personal networks (cont); triadic closure**  
— Easley and Kleinberg, Ch. 3.1–3.3

---

### January 29 — Lecture 5 {#jan-29}
**Strength of weak ties / structural holes / social capital**  
— Easley and Kleinberg, Ch. 3.2  
— Granovetter, Mark S. 1973. “The Strength of Weak Ties.” *American Journal of Sociology*.

---

### February 3 — Lecture 6 {#feb-3}
**Structural Balance**  
— Easley and Kleinberg, Ch. 5.1–5.2

---

### February 10 — Lecture 8 {#feb-10}
**The friendship paradox and node centrality**  
— Feld, Scott L. 1991. “Why Your Friends Have More Friends Than You Do.” *American Journal of Sociology*.  

**Homework 1 Due**

---

### February 12 — Exam 1 Review {#feb-12}
**Exam Review**

---

### February 17 — Exam 1 {#feb-17}
**Exam 1**

---

### February 19 — Lecture 9 {#feb-19}
**Homophily**  
— Easley and Kleinberg, Ch. 4.1 and 4.2  
— Currarini, Sergio, Matthew O. Jackson, and Paolo Pin. 2010. “Identifying the Roles of Race-Based Choice and Chance in High School Friendship Network Formation.” *Proceedings of the National Academy of Sciences*.

---

### February 24 — Lecture 10 {#feb-24}
**Contagions Part I**  
— Easley and Kleinberg, Ch. 21.1–21.3  
— Watts Ch. 6

---

### February 26 — Lecture 11 {#feb-26}
**Contagions Part II**  
— Easley and Kleinberg, Ch. 19.1–19.6

---

### March 3 — Lecture 12 {#mar-3}
**Social influence, herding, and cascades**  
— Watts Ch. 8

---

### March 5 — Lab 2 {#mar-5}
**Visualizing network data and calculating homophily indices**  

**Lab 2 Due**

---

### March 10 — Lecture 13 {#mar-10}
**Community Detection**

---

### March 12 — Lecture 14 {#mar-12}
**Respondent-Driven Sampling**  
— Salganik, Matthew J., and Douglas D. Heckathorn. 2004. “Sampling and Estimation in Hidden Populations Using Respondent-Driven Sampling.” *Sociological Methodology*.

---

### March 17 — Spring Break {#mar-17}
**No Class**

### March 19 — Spring Break {#mar-19}
**No Class**

---

### March 24 — Lecture 15 {#mar-24}
**Network Scale-up Method**  
— Breen, Casey F., et al. 2025. “Estimating Death Rates in Complex Humanitarian Emergencies Using the Network Survival Method.” *American Journal of Epidemiology*.  
— Feehan, Dennis M., and Matthew J. Salganik. 2016. “Generalizing the Network Scale-up Method.” *Sociological Methodology*.  

**Homework 2 Due**

---

### March 26 — Exam 2 Review {#mar-26}
**Exam Review**

---

### March 31 — Exam 2 {#mar-31}
**Exam 2**

---

### April 2 — Lecture 16 {#apr-2}
**Final Project Overview + Class Project Meet-up Day**

---

### April 7 — Lecture 17 {#apr-7}
**Social Network Research in practice: Suicide Networks**  
— Pescosolido, Bernice A., and Sharon Georgianna. 1989. “Durkheim, Suicide, and Religion.” *American Sociological Review*.  
— Centola, Damon, and Michael Macy. 2007. “Complex Contagions and the Weakness of Long Ties.” *American Journal of Sociology*.  

**Homework 3 Due**

---

### April 9 — Lecture 18 {#apr-9}
**Social Network Research in practice: Network Experiments**  
— Centola, Damon. 2010. “The Spread of Behavior in an Online Social Network Experiment.” *Science*.  
— Rand, David G., Samuel Arbesman, and Nicholas A. Christakis. 2011. “Dynamic Social Networks Promote Cooperation in Experiments with Humans.” *PNAS*.

---

### April 14 — Lab 3 {#apr-14}
**Network scale-up method**  

**Lab 3 Due**

---

### April 16 — Presentation Prep {#apr-16}
**Final Project Prep (Flex Day)**

---

### April 21 — Presentations {#apr-21}
**Mini–conference — Final Presentation**

### April 23 — Presentations {#apr-23}
**Mini–conference — Final Presentation**

---


## Class Attendance

In this course, attendance at these meetings is mandatory and part of your grade.  
Every student is allowed four (4) free absences with no questions asked. In other words, you do  
not have to inform me (or your TA) that you are missing class. For every absence after the  
allotted four (4), you lose 2.5% of the possible 10% for attendance/participation. You will receive a  
0% for class attendance/participation after eight (8) absences.  

**Please do not email us if you are using a free absence from lecture “just to let us know.” You  
can just not show up!**

---

## Religious Holy Days

By UT Austin policy, you must notify me of your pending absence for a religious holy day as far in  
advance as possible of the date of observance. If you must miss a class, an examination, a work  
assignment, or a project in order to observe a religious holy day, you will be given an opportunity to  
complete the missed work within a reasonable time after the absence. For questions regarding  
religious accommodations, please contact the Office of the Dean of Students  

---

## Academic Integrity

Academic integrity is foundational to scholarly work. To learn more about academic integrity  
standards, tips for avoiding a potential academic misconduct violation and the overall conduct  
process, please visit the Student Conduct and Academic Integrity website. I have a 0-tolerance policy  
towards any type of academic misconduct.  

---

## Letter Grade Percentage

Final grades will be based on the standard UT grading scale. Grades will use +/-. Grades will not  
be curved.

A 93% & above; A- 90% – 92.9%; B+ 87% – 89.9%; B 83% – 86.9%; B- 80% – 82.9%;  
C+ 77% – 79.9%; C 73% – 76.9%; C- 70% – 72.9%; D+ 67% – 69.9%; D 63% – 66.9%;  
D- 60% – 62.9%; F 59.9% and below  

---

## Incompletes

Incompletes (I) are given only when a student is unable to complete a segment of the course  
because of circumstances beyond the student’s control. To be considered for an incomplete a  
student must have completed two-thirds of all course work with at least a satisfactory grade. An  
‘incomplete’ is never granted automatically and each request is carefully reviewed by both the  
Professor and the Teaching Assistant.

---

## Acknowledgements 

This course is largely based on a course originally developed by the wonderful Prof. Dennis Feehan at UC Berkeley.
I am grateful for his generosity in sharing materials and pedagogical approaches that informed the structure and 
content of this class.

