# VersionControl.md

## Version Control in Life
Version control doesn’t just exist in the computing realm, in fact it’s all around us. Many things we see in 
 life keep track of changes and processes. Consider the three examples given to us in lecture [1]:

#### Animal Kingdom
Animal and plant evolution can be considered version controlling, scientists and biologists keep track 
of how and when species evolved to fit certain needs.

#### Banks
Banks need version control to keep track of all the money and decide when it changes hands. Things like 
ledgers handled the transactions and were the records for the amount of gold and silver to be paid out 
to everyone.

#### Hospitals
Hospitals need version control to keep track of patient records, staffing schedules, and medication 
records. Malpractice is a big deal in the medical fields and record keeping is important to ensure it 
doesn’t happen.

[1] Paul, Logan. “Version Controlt”. Info-I 303. Bloomington, IN. 27-3-2019. Lecture.

Another real world example of version control that I found was in sports. More specifically, the 
Australian Sailing team used it to keep track of different statistics and analysis of their speeds 
and times [2].

[2] “Australian Sailing Team - Sharing Files Securely in Sports.” Dropbox, 
www.dropbox.com/business/customers/australian-sailing-team-case-study.

## Three Pieces
This is referring to version control. In lecture, we defined these 3 stages as [3]:
1. _What Changed?_
    Which pieces, lines, or structures changed?
2. _When did did it change?_
    At what point in the process did the item change?
3. _Who changed it?_
Who was responsible for the change? Not necessarily a method for blaming problems. 

[3] Paul, Logan. “Version Control”. Info-I 303. Bloomington, IN. 27-3-2019. Lecture.

For each change, what pieces are the most and least important? This will be different for each 
scenario. 

#### Risk

Making significant changes presents risk because it may affect people invested in the project 
(stakeholders), and these effects may be bad. However, not keeping track of change presents 
the risk of being unable to trace back what/when changes cause problems. 

## Version Control Protocol Importance

Version control is very prevalent and extremely important, as mentioned above. Everything 
contains some form of it: you have a common experience with it in the form of Canvas via its 
assignment submission system, when many different versions may be uploaded. However, these 
benefits only come with the protocol if it is properly implemented & appropriately used [4].

[4] “Version Control”. The University Of Leicester,
https://www2.le.ac.uk/services/research-data/organise-data/version-control. Accessed 12 Apr. 
2019.







## Pre-Software
Before there was version control on the machines we have nowadays, the old school methods of version control was to have carbon copies stored in filing cabinets. Phases such as rough drafts and final drafts existed and were kept as methods of versioning. Obviously since this was a manual form of versioning, going through the history of a product took a lot of time.

## Manual Versioning
As mentioned in the pre-software section, manual versioning took an excessive amount of time. As a result, "some organizations had Source Control Departments" [7a] to be in charge of a product's history and code. Essentially they "would put together all of the code to make" [7b] a program run once all of it was compiled.

[7] Paul, Logan. “Version Control”. Info-I 303. Bloomington, IN. 27-3-2019. Lecture.

##SCM Tools
As time progressed, people wanted to reduce the amount of time it took to go through a product's history which made Source Control Management (SCM) extremely important.

##SCCS! ('72) & RCS ('82)
Source Code Control System and Revision Control System essentially stored a recent version of a file and any recent changes which was significantly more efficient than storing an entire file over and over again.

##CVS
In about 1990, Concurrent Versions System was the start of real version control in that it could handle more than one version of a product at a time. The progression of servers allowed for branching and merging to also spurt growth. Four years later in 1994, the modifications to CVS allowed for its repos to be used from remote places. 

##SVN ('00)
Subversion allowed people to track an entire commit as we do nowadays using GitHub and ultimately marked the end of SCM.

##DCVS Tools (00's)
Distributed Concurrent Versions Systems is essentially multiple working repos on a local level (an advanced way to SCM).

##Bitkeeper ('00)
Bitkeeper is essentially scalable version control, however had a lot of drama with the owners. Essentially there was "no central repository" and "each developer could maintain one or more fully independent trees." [8]

[8] corbet. “The kernel and BitKeeper part waysl”. LWN.net.6 April, 2005. Web. Retrieved from https://lwn.net/Articles/130746/

## Github
Git is "the actual version control system that you interact with on the command line" while the Hub is the backend software where all of the information can hosted on repositories. Some of the GUIs that GitHub uses are command line, GitHub, XCode, and more.

## Best Practices
Although it is true that there are numerous ways to make the use of Version Control more effective, sometimes the opposite happens. Following are some of the best practices that one must follow.

1. Compartmentalization: separating commits in an organized fashion that is more effective.
2. Committing early and often is another good practice since it secures progress if anything goes wrong.
3. This also gives a timely and detailed history of the project
4. One should make good comments and description of copies since that would help someone else understand the project clearly and would reduce any chance of confusion.

## Single Developer Method
The following steps ensure a practice on how a single developer should work on a project. It basically means separating the project into four categories, starting with the Development stage where all the new versions start, then testing the progress in the second stage called Testing, followed by the third step called Staging where one readies to set up the project, and ending by Production stage where one produces and takes backup before pushing it.

[9] Paul, Logan. “Version Control”. Info-I 303. Bloomington, IN. 27-3-2019. Lecture.

