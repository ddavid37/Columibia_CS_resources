Course Syllabus
Course Summary
This course examines the foundations of digital computing, connecting the dots from software to the physical devices that execute software. Beginning with 1s and 0s and simple Boolean logic gates, the course will progress through key topics in digital logic design and optimization. At midsemester it will jump up to study assembly language, the rudimentary programming language in which all software is expressed to a processor. The final part of the semester will connect the two ends, applying the principles of digital logic design to implement a circuit that can execute assembly language. Specific topics covered include:

binary information representation
boolean algebra, canonical forms, and minimization 
combinational circuit design
sequential circuit design and finite state machines
memory and addressing
assembly language programming
single cycle and pipelined processors
cache organization
Prerequisites
Students should be familiar with the basics of imperative, sequential programming. This is typically provided by an introductory programming course such as COMS 1004 or 1007 or another similar course.

Instructors
Martha Barker (mbarker@cs.columbia.edu)
Martha Kim (martha@cs.columbia.edu)
Emma Li (eql2002@columbia.edu), Head TA
Madeline Skeel (mgs2189@columbia.edu), Head TA
The full TA staff will be announced during the first week of the semester.

Lectures
Lectures are scheduled for Tuesdays and Thursdays, 11:40am - 12:55pm (Sec 001) and 1:10pm - 2:25pm (Sec 002). All times are NYC time. We will meet in person in 301 Pupin Laboratories. The sections are identical and students are welcome to attend either lecture, except on test days (see below).

Grading and Requirements
Midterm Test (25% of final grade). The midterm is on Tuesday October 22nd, in person in 301 Pupin Laboratories during lecture time. This test will cover the first half of the semester.  Students must take the test with their registered section at the designated time.  

Take Home Programming Test (25% of final grade). There will be a take home programming assignment, which will be the assessment covering the third quarter of the semester. This assignment will be due Tuesday November 19.

Second Test (25% of final grade).  There will be a second test during the last class on Thursday December 5th.  It is also during lecture time in 301 Pupin Laboratories, and as with the other in-class test, students must take this test with their registered section.   This test is not cumulative and will cover the final quarter of the semester.  There is no final exam for this course, regardless of what is posted on the registrar’s exam schedule.

Reflections (12.5% of grade). Due on Monday evenings, these nine short assignments are opportunities to reflect on the prior week’s new material. Students are asked to submit a couple sentences summarizing the key points and insights and posing lingering questions that remain unclear. See this page or below for reflection instructions, scoring rubric, and examples.

Problem sets (12.5% of grade). There will be six problem sets provided over the course of the semester, to practice the material covered in class. See this page or below for the problem set scoring rubric.

Final grades are calculated based on these scores with no extra credit offered.

Course Resources
Course Calendar. A google calendar showing all course meetings, deadlines and office hours is available at http://bit.ly/FundiesCalendarLinks to an external site..

Textbook. There is no required textbook for this class. However, for those students that would like supplementary reading material, Digital Design and Computer Architecture 2nd EditionLinks to an external site. by David Harris and Sarah L. Harris is a good reference. It is available at campus libraries, and there are used copies available online and at the university bookstore. A complete digital copy is available through the library.  

ED Stem. We will be using EdLinks to an external site. for class discussion. Rather than emailing questions to the teaching staff, please post your questions on Ed. Whenever possible, we encourage you to post publicly so that your classmates may respond and/or see staff responses.   

Office Hours. The time and location of all office hours is posted on the course calendarLinks to an external site..

Canvas. We will be using Canvas for all course materials including all lecture slides. Everyone registered for the class should have been added to the Canvas site, but please contact the instructors if you have not been.

Gradescope. We will be using GradescopeLinks to an external site. for all assignment submissions and feedback. A link to the Gradescope class is available in the Canvas navigation pane.

Collaboration Policies and Academic Conduct
Students may discuss course material, reflections, and problem sets freely, with the exception of the two tests and programming take home, which are to be individual work, with no collaboration permitted.  All students are expected to adhere to the Computer Science Department’s Policies and Procedures Regarding Academic Honesty.  Contact the instructors with any questions as to what constitutes authorized collaboration and conduct.

If there is evidence of unauthorized collaboration or other misconduct, it will be reported to the Office of Student Conduct for investigation.  Students found responsible for misconduct, can expect a significant academic penalty, and potentially a failing grade in the course.  

Late Work Policy
Late work will be accepted for three days after the original submission deadline and incur a penalty of 5% per day. Each day is an atomic 24 hour unit that cannot be subdivided, so an assignment that is ten minutes late will count as one day late. Late work will not be accepted for the take home programming test; that is a hard deadline.

Regrade Policy
If you believe we have made an error in scoring your work, you may submit a regrade request through Gradescope no later than one week after the assignment was returned. Your regrade request must include a detailed description of the scoring error. A regrade request on a specific problem may entail a review of the entire assignment.  Scores will only be adjusted via this regrade process.

Emergencies
In the event of an emergency, please have your CSA advising dean write to the instructors.

Reflection Instructions and Scoring
Reflections are short weekly assignments, where students review and reflect on the new material from the previous week. Students are to submit a brief summary of the key points and insights from the prior week and pose lingering questions that remain unclear. A successful reflection will be clear, succinct, and pose questions on points of confusion and/or areas of curiosity. All reflections should be submitted on gradescope. 

Scoring Rubric.  Reflections are scored out of two points.

(2 pts) Well thought-out and put together response that is more than just a bulleted list of topics, providing key insights into topics learned. 
(1 pt) OK, but lacking in some critical respect (e.g., bulleted list of topics lacking insights, missing most important topics, no questions or point of confusion noted).
(0 pts) No submission, or irrelevant information provided.
Successful Example #1. I learned that canonical forms are unique representations of boolean expres- sions that allow you to compare expressions and determine logical equivalence. The canonical forms were truth tables, sum of minterms which involves focusing on the rows where the outputs are 1s to express f, and the product of maxterms which involves focusing on the rows where the outputs are 0s. I also learned that Karnaugh maps can be used to simplify boolean expressions.  

I didn’t completely grasp why k-map groupings must be a power of 2.

Successful Example #2. I learned that we decide whether to branch in the decode rather than execute stage in order to reduce the number of incorrectly executed instructions that will need to be flushed if the branch is taken, and to account for hazards we use branchstall (add a bubble to the execute stage) to allow memory to decode forwarding to kick in. Moreover, we distinguish between a data hazard, where the values are read before they are written to the register file by a previous instruction, and a control hazard, where we begin to do an instruction, before knowing whether it really should be the next instruction or a branch needs to be taken. We also talked about how pipeline CPIs tend to be greater than 1, as bubbles are needed to work with forwarding to eliminate hazards when a lw is followed directly by its consumer and when branches are taken, and we went over how speedup is used to measure how much one’s program performance improved.

I’m slightly confused on why when we calculate the processor’s critical path, the Writeback and Decode times are doubled. I know it had to do with having the time to write to and read from the register file within the same cycle, but am still uncertain about the multiplication factor of 2 and why it was said to be overly conservative.

Successful Example #3. This past week we dove into programming and processing in MIPS ISA. We learned that MIPS follows a load/store architecture, where registers give and take data to and from memory with a reduced, simple set of commands. We then talked about the memory structure and address format, as well as several specific commands in MIPS, such as jump, branch, and loading commands. Professor Kim then coded a strlen algorithm on video in emacs using MIPS commands; it was really interesting to see this and compare this implementation with how one would implement such an algorithm in C or another higher level language.

I had a hard time understanding the memory structure and address format in MIPS. After some thought, I realize that the address simply specifies the register being accessed, with a number in front of it to specify how much memory offset to access from, in a memory row. I’m still a little confused as to how much data can be stored in each address, as well as what the maximum offset value can be. I think I’ll understand these more after I complete the MIPS assignment for this week.

Successful Example #4. This past week, we finished up our discussion on pipelined control. We recalled that some hazards can be solved via forwarding, but Professor Kim showed that other hazards instead demand that completion of instructions are stalled; we were then shown how to do this in hardware. Professor Kim then went into the specifics of hazards that arise when branching in pipelined processors; she described a way to go around this by resolving branching earlier, while decoding instead of executing in the hardware. We then discussed a summary of forward- ing and stalling logic and observed the fully bypassed pipelined processor. We finished by calculating just how much these optimizations improve performance speed when executing instructions.

I am still rather confused about how branching in the Decode section instead of the Execute section of the hardware resolves the branching hazard. Specifically, I get how this helps in the high-level abstraction of these instructions’ executions, but I am unsure how the specific changes in the hardware level translate to the desired hazard protections. Hopefully doing problems on the remaining practice sheets and mulling over it some more should clarify things for me.

Successful Example #5. RS Latch, D Latch, and D Flip Flop are state-holding elements which means that they can store one bit and control, set the bit. RS Latch can set, reset, and hold state but has a drawback which is the invalid state, D Latch avoids this invalid case and has two inputs (CLK, D) that control when and what the output changes to. However, a drawback of D Latch is that there is no control over the rate of change of state: unlike D Latch, D Flip-Flop controls the rate at which the oscillating occurs, thus they are very important.

What are some trade-offs when using state-holding elements? What can be some drawbacks of D Flip-Flops? What happens when multiple D Flip-Flops are connected to each other? 

Problem Set Instructions and Scoring
The objective of the problem sets are to help students practice the new concepts and material introduced during the lecture. Each problem set will include some less challenging problems and some that are more challenging. In solving these problems, students will not only practice the material, but discover where they are struggling, so that they can take appropriate action (e.g., reviewing material, seeking help). 

Scoring Rubric.  This rubric is intended to incentivize students to attempt the problems and engage with the course material. This rubric is not designed to split hairs over degrees of correctness, and all reasonable attempts will receive “full credit.” Bear in mind that submitting a friend’s solution, or a non-genuine attempt will only deprive yourself of genuine feedback and practice, which may put you in a less prepared place when the assessments roll around.

On the problem sets, each problem will be scored out of a single point:

1pt

Problem attempted, solution incorrect
Problem attempted, solution almost correct, but not quite
Solution correct, but not quite optimal
Solution correct and optimal
0 pts

Problem not attempted
Unrelated answer given
