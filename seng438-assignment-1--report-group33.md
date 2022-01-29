>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group G33:      ||
|-----------------|-|
| Student Names:  |        |
|Lucas Ion        ||
|Alden Lien       |   |
|Hao Nguyen       |   |
|Nguyen Gia Hy Huynh|   |

**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

After discussing with everyone in our group. This was the first time we were formally introduced to the world of Exploratory and Scripted testing. Although each of us had worked with testing suites before. This was the first time we worked with Exploratory and Scripted Testing with a strict definition. Therefore going into the lab although not defined in our minds, we had brief knowledge of how to conduct testing without the explicit connection that the testing we had conducted in the past, was Exploratory and Manual Scripted Testing.

Moreover because we covered both Exploratory and Manual Scripted testing in the lectures. We were able to know what to expect in terms of what Exploratory and Manual Scripted Testing was, even though this would be the first time we covered it in a lab. Being that, Exploratory testing did not consist of a predefined sturucture and was reliant on the exploration of the tester. Whereas in Manual Scripted testing, the test scripts were pre-defined before the testing began, and the tests were conducted based on what scripts were intially layed out.

# High-level description of the exploratory testing plan

**Lucas & Hy:**

Our approach for exploratory testing stemmed from the description by Cem Kaner in his book, "Testing Computer Software." Modelled after the priciples of the Context-Driven School methodolgists. 

Firstly we decided to create a program flow. Where we sketched out how each intended operation would work when actually done on the program. For example, we sketched out what Withdrawing money from the ATM would look like. We ensured that we began from the moment the program is started to following the desired event. Which in this case was the money being drawn. This approach, where we designed a flow for each notable interaction with the system allowed us to be active in the testing process. With a roadmap of what we expected to come, this allowed us to pay higher attention to detail without being thrown off if something occured.

The second strategy we implemented was a scaling of complexity in our tests. As per the Article titled: "Exploratory Testing Explained" by James Bach, he described the need to begin with simple tests to familiarize yourself with the system, and then elevate your tests once you have become aquainted with the fundmental workings of the system. We made sure to implement this approach in our premliminary testing plan. By allowing us to scale the complexity of our tests we felt confident that failed tests weren't the result of a more simple failure, that masks itself as complex, this is because simple tests were addressed first.

The third aspect of our exploratory testing plan was to implement high heurisitc integration into our approach. This was manifested via two avenues. The first was through a comprehensive checklist of what needed to be accomplished in our tests. This was, rather than just noting tests in our mind as we went along and then recorded them all at the end. We could gradually record what we were accomplishing in live time so that no test went unrecorded. Alongside this, the second heurisitc that we implemented was general guidelines in the testing process. This was manifested through rough goals for each section that we wanted to test for, while ensuring that these goals were equivocated to each of our partners.

Overall these were the three key components of our testing plan.


**Hao & Alden:**

Our initial approach to the exploratory testing phase was to first familiarize ourselves with the Automated Teller Machine (ATM) program. Our expectations of this phase were to find and report any major defects in the program, and also ensure that all of the requirements listed were met.

In order to familiarize ourselves with the program, we navigated through the steps as outlined in the assignment document. We were able to identify and familiarize ourselves with the main functions of the program, and there was no reporting done on any bugs found at this time. This first run-through of testing was done with the mindset of an average consumer with no prior knowledge to how the system is supposed to function.

The next step in our plan was to run through the program with the high-level requirements outlined in Appendix B.1 in mind. In order to ensure that the requirements of the system were being met, we tested all basic functionality along with the specific transactions listed in the assignment document, noting any major defects found.

After testing the basic requirements of the system, we began to thoroughly run through the program in order to test all other functionalities and transactions, along with any possible edge cases. This testing was done by testing most functions of the program, with some being tested more extensively than others, and it was in this step where major or minor defects found in the program were noted and reported using the given bug tracking tool.

# Comparison of exploratory and manual functional testing

***Exploratory Testing:***

**Benefits**

  The first major benefit of exploratory testing is that is truly fosters a holistic approach to the testing of the code. This means that the dilegence of the tester is unintruded. Therefore with an exploratory testing approach very nuanced issues might be discovered that have nothing to do with the core functionality whereas as these could be overlooked in Manual Scripted Testing. The secondary benefit of exploratory testing was that it allowed for us to analyze issues with custom test criteria that did not exist in manual scripted testing. This meant that we could continue down specific rabbit holes of testing, as we were not constrained by a set of rules to follow.
  
**Tradeoffs**

  The primary trade off of exploratory testing is that is it fully strengthened or weakened by the skills and knowledge of the program tester. If the individual testing the code does not do his or her due dillegence in exploring the code completely this would lead to very insufficently tested software.
  Another tradeoff of exploratory testing is that it makes it difficult to identify the core functionality from the get go. Compared to Manual Scripted Testing which clearly lays out the flow of the program from the initial onset. It is up to the tester in Exploratory testing to determine the key flow of the program. Therefore, one tradeoff is that the tester could test for completely niche issues while overlooking key components of the code.

**Effectiveness**

  The effectiveness of exploratory testing is completely dependant on the quality of the tester. If the tester does their due dillegence and follows through testing all the issues in the code effectivley, then exploratory test can be very effective. However, if the tester, tests the code at a superficial level then Exploratory Testing is very ineffective.

**Efficency**

  Compared to Manual Functional Testing, Exploratory testing is much more inefficent. This is due to the fact that there is no predifined strucuture to the testing. Rather it is completely dependant on the exploration of the programmer. This can be a very time consuming and costly process.

***Manual Functional Testing:***


**Benefits**

  One of the main benefits of Manual Functional Testing is its clear predefined stucture. This means that a lot of ambiguity of what the testing stuctures needs to look like is removed. This results in a streamlined testing process. Another key benefit of Manual Functional Testing is that it ensures that the key components of the program and the main flow are predefined from the start. This means that during the testing process there is no ambiguity in what is to be accomplished.

**Tradeoffs**

  The largest trade off with Manual Functional Testing is that since the tests are predefined before the actual testing begins, this means that **you miss the same things every time!** This can lead to large holes in the application being overlooked simply because they were not established at the start

**Effectiveness**

  Similarly to Exploratory Testing, Manual Functional Testing's effectiveness is dependant on the quality of scripts that are established before the testing begins. Therefore a high quality testing script to be followed, will result in high quality test results. On the contray, low quality testing scripts will result in very ineffective testing. One other aspect regarding effectiveness, is that creating good testing scripts can result in higher effectiveness compared to Exploratory testing, as there is no ambiguity in the testing process itself. Resulting in a very streamlined testing process. 

**Efficency**

Compared to Exploratory Testing, Manual Functional Testing can be much more efficent. This is because once the tests and the flow to be followed are established -- recording and exploring the tests is as simple as following the established test scripts


# Notes and discussion of the peer reviews of defect reports

For each pair we ensured that we followed a rigourous peer review process. As per the Assignment 1 Handout, for the pair testing one of the team members did the testing, while the other partner reviewed the testing and ensured that the testing was performed correctly. This process of pair testing ensured that any errors or mistakes as the result of one of the partners was rooted out and corrected.

For the Manual Scripted Testing, we followed a similar process to the pair testing. We ensured that everytime a test was performed that it was double checked by each member in the group to maximize consistency.

# How the pair testing was managed and team work/effort was divided 

Pair testing was performed with an alternating structure. One test would be performed by one team member while the other checked over the test and ensured that it was performed properly. For the pair testing, this process repeated for all of the tests. For the pair testing we ensured that the work was divided equally with an equal amount of tests being balanced amongst all team members.

# Difficulties encountered, challenges overcome, and lessons learned

Although there were no substantial difficulties encountered. One small difficulty was recognizing and developing the best apporach possible for Exploratory testing. At the start of the lab all of us had only brief experience with exploratory testing so developing a clear and efficent plan took longer than we expected. However once we began to gain experience with our Exploratory testing approach, this difficulty dissapeared.

One of the challenges we overcame was how to effectively delegate and equivocate between group members. At the start it was challenging to clearly establish goals and requirements that needed to be fulfilled. However after meeting, and clearly laying out the goals for the lab we overcame the challange of feeling as though we did not understand our roles that were needed to be successful.

The key lesson learned was the importance of communication and transparency between group members in order to be successful in the lab.

# Comments/feedback on the lab and lab document itself

We found the lab quite enjoyable as it allowed us to familiarize ourselves with the core workings of Exploratory, Manual Scripted Testing, and Regression testing.

Although we found the lab document quite clear. We were slightly confused as to how the lab reports would be combined between the pair work and the group work. However after asking both clarifying questions in the Lab and in the Lecture this confusion was quickly dispelled.

Overall it was a very enjoyable lab that we very much enjoyed!
