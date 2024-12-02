java c
MIS3010S: Analytics Modelling
Problem Assignment
Due date: Saturday, 23rd March, 2024.
Assessment weight: 40%.
Teams of two or three students: do problems 1, 2 and 3.
Teams of four students: do problems 1, 2, 3 and 4.
1. Introduction
1.1. Overall form. of assignment. This is a team assignment, worth 40% of the course mark.
Teams of two or three students must attempt questions 1–3. Teams of four must attempt all four questions. The mark for each question or part of a question is given in brackets [ ] in the right-hand margin. Teams of two or three are marked out of 100. Teams of four are marked out of 133.
This is an open book assessment. You may use a calculator throughout, and software packages where stated; but otherwise you must show all of the details of your work, including when using algorithms.
1.2. Randomisation of problem data. In the problems, you will notice that I have used digits from student numbers. This is in order to make the problems differ from one student to another, and so enhance integrity of the assessment. Your student number is largely random and so allows for some randomisation of problem data.
Teams of two: choose one team member to be Student 1 and the other team member to be Student 2. Follow the instructions below, using the digits of Student 1’s student number for Question 1, and the digits of Student 2’s student number for both of Questions 2 and 3.
Teams of three: choose one team member to be Student 1, a different team member to be Student 2, and the third different team member to be Student 3. Follow the instructions below, using the digits of Student 1’s student number for Question 1, the digits of Stu-dent 2’s student number for Question 2 and the digits of Student 3’s student number for Question 3.
Teams of four: choose one team member to be Student 1, a different team member to be Student 2, a third different team member to be Student 3 and the fourth different team member to be Student 4. Follow the instructions below, using the digits of Student 1’s student number for Question 1, the digits of Student 2’s student number for Question 2, the digits of Student 3’s student number for Question 3 and the digits of Student 4’s student number for Question 4.
To find the digits to use, work as follows, using the relevant student number for the relevant problem:
• Let s1, s2, . . . , s8 be the first, second, . . . , eighth digits, respectively, of your student num-ber, with the extra condition that if a digit is 0, you should change it to 5. For example, if your student number is 18473025, then s1 = 1, s2 = 8, s3 = 4, s4 = 7, s5 = 3, s6 = 5 (not 0), s7 = 2 and s8 = 5. This si notation refers exclusively to student number digits, and will not be used for any other purpose in this assignment.
• If two digits occur consecutively in a question, treat them as the 10s digit and units digit of a two digit number. For example, if your student number is 18473025 as above, then s3s8 = 45 as a decimal number. Similarly for three or more digits, or digits after a decimal point: for this example student number, s1s6s8 = 155, and if p = 0.s4s7, then you would get p = 0.72.
• Similarly if a student number digit comes after another digit, it does not mean multipli-cation, e. g., for student number 18473025, 3s3 = 34.
• −si means the negative of si, e. g., for student number 18473025, −s3 = −4.
• In certain questions, you may need to make other adjustments to some digits.
1.3. Deliverable. Provide as your deliverable a single document, with word limit 3000 words, in the form.
(i) A standard signed cover page (see Appendix 3 of Study Guide), containing
• title and handup date of assignment,
• full name and student number of each student, identifying which student’s student number was used in which question,
• a statement that this assignment is all your own work;
(ii) an individual statement by each student saying what that student contributed to the assignment: what they did for each question and the approximate percentage they did of the total work for the assignment. This may be used if differential grading is required. Each student may also give a personal reflection on the assignment;
(iii) your answers to the set problems:
• text must be typed, no smaller than 10 point font;
• diagrams e. g., of graphs/trees should be produced with a graphics tool if possible but may be hand-drawn if you cannot achieve this.
The cover page, individual statements, diagrams (and bibliography/references, if any) do not count towards the word limit. This deliverable may be in Word, Openoffice.org or pdf format.
Name the document deliverable according to the convention
AM_Surname_List_problems.pdf (or .docx, .odt, etc.)
where Surname List means one of
• Surname1 Surname2,
• Surname1 Surname2 Surname3 or
• Surname1 Surname2 Surname3 Surname4
as appropriate to the team size. Each model file developed (e. g., in Mosel) must also be named with a similar convention: use file extension .mos and replace problems by Q4 etc., as appropriate, e. g., you would submit AM Surname List Q4.mos as the Mosel file for Problem 4.
Submit your deliverables through Brightspace. This must be done by Saturday, 23rd March, 2024; after this time, it will lose marks for being late according to the UCD Late Submission of Coursework policy.
2. Problems
1. In the decision problem described below, you will notice that “the chance that the antidumping tax will be imposed is p, where p is derived from the third and eighth digits of your student number”. To find the p to use in your submission, work as follows:                                                                                                          [30]
• Let s3 and s8 be the third and eighth digits, respectively, of your student number. For example, if your student number is 18473925, then s3 = 4 and s8 = 5.
• If s3 ≤ 3, then set s3 := s3 + 3. For example, if s3 = 1, then set s3 to 4.
• If s3 ≥ 8, then set s3 := s3 − 2. For example, if s3 = 9, then set s3 to 7.
• Let p = 0.s3s8 as a decimal number. For example, if s3 = 5 and s8 = 9, then you would get p = 0.59.
AAA Electronics has contracted to supply half a million TabletPC systems to CostCo Stores in 90 days at a fixed price. Each TabletPC system requires a High Speed Northbridge chip (“HSN chip”) in order to function. In the past, AAA has bought these chips from a Korean chip manufacturer, Recce Chips. However, AAA has been approached by a Chinese manufacturer, CAC Electronics, which is offering a lower price on the chips. This offer is open for only 10 days, and AAA must decide by then whether to buy some or all of the HSN chips from CAC.
Any chips that AAA does not buy from CAC will be bought from Recce. Recce will sell HSN chips to AAA for S$3.00 per chip in any quantity. CAC will accept orders only in multiples of 250,000 HSN chips, and is offering to sell the chips for S$2.00 per chip for 250,000 chips, and for S$1.50 per chip in quantities of 500,000 or more chips.
However, the situation is complicated by a dumping charge that has been filed by Recce against CAC. If this charge is upheld by the Singapore courts, then the CAC chips will be subject to an antidumping tax. The judgement in this case will be de代 写MIS3010S: Analytics ModellingC/C++
代做程序编程语言livered exactly two weeks from now and, if the charge is upheld, the antidumping tax will go into effect immediately. If AAA buys the CAC chips, these will not be shipped until 30 days from now, meaning the chips would be subject to the tax if the charge is upheld. Under the terms proposed by CAC, AAA would have to pay any antidumping tax that is imposed.
AAA believes that the chance that the antidumping tax will be imposed is p, where p is derived from the third and eighth digits of your student number as described above. If it is imposed, then it is equally likely that the tax will be 50%, 100%, or 200% of the sale price for each HSN chip.
(i) Draw a decision tree for this decision.
(ii) Using expected value as the decision criterion, determine AAA’s preferred ordering alter-native for the HSN chips.
2. You have S$50,000 to invest. You have identified five investment opportunities. Each is an “all-or-nothing” investment: you must invest the full amount or not invest at all.                             [35]
• Investment 1 requires that you invest S$16,000 and has a present (time-discounted) value of S$23,000;
• Investment 2 requires S$14,000 and has a present value of S$s1s2,000;
• Investment 3 requires S$22,000 and has a present value of S$3s3,000;
• Investment 4 requires S$12,000 and has a present value of S$14,000; and
• Investment 5 requires S$38,000 and has a present value of S$4s8,000.
Into which investments should you place your money so as to maximise your total present value?
Solve this problem using Branch and Bound, showing the full tree you develop, and clearly explaining why certain subproblems are fathomed. For each intermediate subproblem, solve the LP associated to that problem using Xpress. Include in your submission the Xpress model formulation and Xpress output for each subproblem investigated. Name the model files AM_Surname_List_Q3a.mos, AM_Surname_List_Q3b.mos, etc.
3. In the following, s1, . . . , s8 are the digits of the relevant student number for this question. They are used for some edge weights in Figure 1 below. If any si = 0, then set that si:= 5. For example, if s3 = 0, then set s3 to 5, meaning that the edge 4-5 in Figure 1 will have length 5.                      [35]
Figure 1 represents the road system in the town Marawatna, with streets being edges and street junctions being vertices. The number on each street is the length of the street in hundreds of metres. Traffic can travel in either direction along any street. The Hospital is located at the junction marked 1.

Figure 1. Street plan of Marawatna.
(a) To improve ambulance service quality, you are asked to find a shortest path from the Hospital to vertex 11, and its length. Solve this problem, using an appropriate algorithm. Show all of your work, including the resulting shortest path spanning tree rooted at the Hospital.
From your work, what — if anything — can you say about the shortest path from vertex 3 to vertex 11; or the shortest path from vertex 3 to vertex 7? Explain your thinking.
(b) The Marawatna Town Council wish to install a new traffic light system, which will replace the existing traffic light at each junction in the town. This will involve connecting all of the junctions together by a system of electrical cables. Cables must be laid along existing streets to allow access for maintenance. The costs involved in installing the new traffic lights (including material and labour costs) are:
• S$35000 per traffic light;
• S$2500 per metre of cable.
The Town Council have approached you to help them minimise the total cost of installing the new traffic light system. Decide which network model and algorithm would be appro-priate for this problem. Solve the problem, explaining the steps of your work.
4. A large engineering firm, Heavy Automation Logistics (HAL), is changing its focus to become a services firm, and seeks an efficient way to do this. HAL has identified three categories of customer-facing staff: Engineers, IT Consultants and Business Consultants. It is embarked on a workforce repositioning effort, wherein it wishes to decrease the number of engineers and increase the numbers of business consultants and IT consultants. Its approach to achieving this will be a combination of hiring, firing and training (new skills development). Coupled with this workforce repositioning, the current economic climate is expected to mean a short term reduction in the total number of staff required. Table 1 gives the expected number of staff of each category required over each of the next three years.                      [33]

Table 1. Current and expected required staff levels by category, up to 2027
HAL wishes to identify a policy to achieve these numbers, in terms of (a) hiring, (b) firing and (c) training.
A complicating factor is that there is a normal turnover of staff (that is, staff leaving HAL). HAL’s experience is that staff are more likely to leave during their first year. HAL have forecast the staff turnover percentage rates as in Table 2. Currently, all staff have been

Table 2. Expected staff turnover rates, by category
working for HAL for more than one year.
The information to hand regarding possibilities of hiring, firing and training is as follows.
Hiring: It is possible to recruit from outside a limited number of people with the appro-priate skill sets for HAL. It is expected that in each of the years from now to 2025, the availabilities of the three categories will be as in Table 3:

Table 3. Expected staff availability for hiring, by category
Firing: The costs of making staff redundant are as in Table 4:

Table 4. Cost in thousands of S$ of making staff redundant, by category
Training: Certain categories of staff may be retrained to other categories, as given below.
However, it is considered too expensive to retrain Engineers to be Business Consultants, or vice versa, since their skillsets are so different.
• Up to 400 Engineers may be retrained to be IT Consultants each year, at a cost of S$5000 each, by sending them on external courses.
• IT Consultants may be retrained to be Business Consultants, at a cost of S$7000 each; however, some of this training is done on the job by existing HAL Business Consultants, which means that the number trained in this way each year is limited to at most one third of that year’s Business Consultant population.
• Up to 300 Business Consultants may be retrained to be IT Consultants each year, at a cost of S$6000 each, again by sending them on external courses.
• Up to 200 IT Consultants may be retrained to be Engineers each year, at a cost of S$4000 each, also by sending them on external courses.
For simplicity, it is assumed that all of the events, namely, hiring, firing, training and staff turnover, occur once each year, on the first day of the year.
HAL’s objective is to meet these staffing requirements while minimising the amount of staff redundancy (firing) required. Formulate this as a mathematical programme and solve.
If their objective were changed to minimising costs, how much extra money could they save?       Modify your mathematical programme to answer this revised question.









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
