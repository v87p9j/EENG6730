java c
SCHOOL OF ENGINEERING ASSIGNMENT COVER SHEET
Title:                           Formal testability
Module:                      EENG6730 Digital Systems Design
Assessment:              This assignment contributes 6.0% of the module.
Deadline:                   Submission deadline: 12:00 01/11/2024 Week 13
Marked work return date: 22/11/2024 Week 16
Collecting Point:       On line
Intended                    This assignment contributes to the assessment of the EENG6730
Learning                     learning outcomes:
Outcomes:                 8.1  design reliable digital systems using synchronous design techniques
8.2  design digital systems which are easily testable
Feedback                    Feedback will be via: Written comments on work. Further feedback
method:                     will be available on request.
You are reminded of the University rules on Academic Integrity as stated in the student handbook.  Examples of conduct regarded as a breach of these regulations include:
•    Plagiarism: reproducing in any work submitted for assessment or review (for
example, examination answers, essays, project reports, dissertations or theses) any material derived from work authored by another, without clearly acknowledging the source
•    Duplication of Material
•    Conspiring with others to reproduce the work of others without proper
acknowledgement, including knowingly permitting work to be copied by another student
•    Falsification of data/evidence.Please note that IET accreditation requires that when coursework contributes 30% or more   of a module then credit cannot be obtained if either your course代 写EENG6730 Formal Testability Assignment
代做程序编程语言work or examination scores are more than 10% below the module pass mark.  This is irrespective of your module overall mark.


EENG6730 Formal Testability Assignment
For the circuit shown in Figure 1, develop:
(a)        a binary test to detect the single-stuck condition X/0,                            (4 marks)
(b)        a test program for IC1 to detect the stuck condition
X/0 using serially scanned-in/out test data.                                             (10 marks)
(c)         discuss the test result data and possible faults if it fails this test.        (4 marks)
(d)        comment on what manufacturers could do to implement quality management systems, aiming to reduce failure rate and improve testability of electronic products. (2 marks)
The TAP Controller state diagram is supplied in Figure 2. The current state is unknown.

Figure 1 Circuit diagram
The instruction code set for IC1 is shown in the table below.
Instruction
OPCODE

MSB

LSB
SAMPLE
1
0
1
INTEST
0
1
0
BYPASS
1
1
1
EXTEST
0
1
1



Figure 2 State diagram of the TAP controller
Further informationIC1 is an IEEE1149.1 compatible 8-port boundary scan device, where ports A to D are inputs and ports E to H are the corresponding outputs.  A to H serially follow a path starting at TDI and finishing at TDO. The test procedure should show: the Clock Cycle, TDI, TMS, TDO, the Current State, the Next State and the current Instruction. Assume IC1 has an identity register but does not have external reset capability (e.g. no TRST).




         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
