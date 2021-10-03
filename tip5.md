# Git/GitHub tip No. 5: Push when your changes are tested
The worst Git-related bug I’ve ever had the misfortune to know about happened when an outsourcing company switched from Subversion but didn’t train its developers on the difference between distributed source control and centralized source control. About a month later, the project developed weird bugs that nobody could seem to track down. At the daily stand-up meetings, the developers responsible for the area of the application that was misbehaving would protest, “I fixed that two weeks ago!” or accuse another developer of not bothering to pull the changes they had so carefully checked in.

Eventually, someone identified the problem and taught all the developers how and when to push their commits: In short, whenever the commits test successfully in a local build. Then the company did a two-day-long merge fest before being able to build and deploy the updated, integrated product.

