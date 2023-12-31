# Bug Repositories

With the support of NSFC, we have established a collection of bug repositories aimed at facilitating research related to software bugs. These repositories serve various purposes such as software testing, fault localization, and program repair. Notably, certain unique types of bugs, such as resource leakage defects and concurrency defects, present distinct challenges in terms of their detection, analysis, and reproduction. To address this, we have developed a comprehensive bug repository named "GrowingBugs," which encompasses common bugs, as well as several specialized bug repositories dedicated to specific types of bugs, such as resource leakage defects.

## GrowingBugs

GrowingBugs is essentially an expanded version of the widely used Defects4J: It not only includes all defects in Defects4J, but also reuses its APIs to faciliate users to switch seamlessly from Defects4J to GrowingBugs. The key difference is that growingBugs levearages an automated approach to exclude bug-irrelevarange changes from bug-fixing commmits automatically whereas Defects4J requests human experts to accomplish the same task. Consequently, growingBugs can keep growing automatically even without human intervention. That is the reason why it is called "growingBugs". 

Notably, each bug in growingBugs is composed of a buggy version, a fixed version, a concise patch (bug-fixing changes only), and one or more triggering test cases. To date, growingBugs contains 1911 real-world bugs from open-source Java projects. 

GrowingBugs is publically available at https://github.com/liuhuigmail/GrowingBugRepository

## JLeaks

JLeaks contains 1,094 resource leaks from 321 open-source projects on GitHub. It was built after multiple rounds of filtering and validation from more than 3,185 commits. Each case is well-labeled in detail, including the defect code, patches, and location, providing convenience for defect code analysis, automatic testing, and tool evaluation. To the best of our knowledge, JLeaks is the largest and most informative resource leak repository so far.


JLeaks is publically available at https://github.com/BIT-SYS/BIT-DBench/tree/main/Java/JLeaks-2023

