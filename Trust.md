# Trust.md
---

## SDLC

Stands for **Software Development Life Cycle**, and in plain english this means 
"*how software/systems come to exist in the world ... and how they're maintained*" [1]

It has the following stages in a loop:

<pre>
Requirement Analysis >>>>> Design >>>> Development
^                                           V
^                                           V
^                                           V
^                                           V
^                                           V
^                                           V
Release  <<<<<<<<<<<<<<<<<<<<<<<<< Quality Assurance
</pre>

[1]Paul, Logan. “Information Systems SDLC”. Info-I 300. Bloomington, IN. 4-3-2019.
Lecture.


### Requirement Analysis
This sounds more complicated than it actually is: all this means is that the 
designer gathers what the system absolutely needs to do, how they should be
done, and within what scopes. 

#### Functional Requirements
These are what the system *should* do, but only looking at discrete tasks 
(inputting/outputting/processing information). Basically, things that are 
absolutely necessary for the system to *function*.

A good Functional Requirement
includes a function (ex. logging in), detail (ex. logging in on a secure webpage),
and a rational (ex. logging in so that the user can post a comment on an article).

#### Non-Functional Requirements

These are things that *should* be performed, but aren't really crucial to the system's
function(s). Ex. Requiring secure passwords, designing the system to operate quickly, 
how many decimal places numbers in a database should contain. 

Sometimes these are also referred to as *technical requirements* or *operational
requirements*. 

#### Transitional Requirements
Transitional Requirements define what an organization needs to begin using a new Information System. Transitional Requirements can include things like asking how long the transition will take, asking if data cleanup will be necessary, and asking about how much training will be necessary[1].

#### Requirements Analysis
In lecture, we talk about 3 big steps to analyzing requirements[1]:
Eliciting Requirements
Analyzing Requirements
Recording Requirements

Requirements Analysis can result in saved time, stress, and personal reputation if done correctly.

#### Gathering Requirements
Gathering requirements can be conducted in a number of ways, including discussing and observing those involved with the system. Gathering can also include surveys and “just knowing” the requirements[1].

### Design
Design is assessing requirements and deciding how a system should work. Design can begin at any stage of production.

### Who Has The Data
People are more inclined to share their data because data breaches are rare for most companies, as security has evolved. With that being said, around 69% of consumers believe that all companies are susceptible to some sort of security related attack[2]. The same study found that 25% of consumers believe that their data is actually secure[2]. This result is shocking because these findings show distrust between consumers and corporations. The liability therefore lies in the corporation to create levels of trust between the consumer and the corporation. 

[2] PricewaterhouseCoopers. “Consumer Intelligence Series: Protect.me.” PwCs/cybersecurity-protect-me.html., www.pwc.com/us/en/services/consulting/library/consumer-intelligence-serie

### What we understand/What are we Trusting
When one thinks about trust, it’s easier to trust a person or corporation if they have a personal connection to the person or place. So why are people so eager to give corporations and websites their personal information? This is due to the fact of the internet being a more secure place than before. Millenials have also grown accustomed to practices on the internet that didn’t exist in earlier times such as online banking. Therefore, trust was inherited with increased use. This makes sense because the more you get to know someone you begin to trust them more[1]. With this trust comes expectations in the corporations to ensure the data is stored securely and ethically. 

### Loss of Trust
It remains in a companies power to maintain trust. Articles explaining when a company has compromised data in some sort of essence are prime examples of the loss of trust. More examples of losing trust include lack of communication, unresponsive customer support, and unethical operation circumstances.

## Building Trust
Building trust is essential. Some applications such as Duo when logging into IU services has trust as "a byproduct of mandates from the top," which occurs in more of the classical organizations [1]. On the other hand, modern information systems require a whole different level of trust. When discussing these systems such as Facebook and Twitter, a lot of issues occur with trust because many of the times, it is not clear what these companies are doing with the data. Thus these companies utilize a different approach when trying to build trust. Most of these companies allow its users to adjust privacy settings which ultimately make people believe that most of their information is secure. Small things like this is what makes people trust certain applications, however in the scenario information leaks (such as Facebook's information incident), building trust with many users is very difficult. In short, trust is difficult to build, and by using some means such as allowing users to adjust privacy settings is one of many ways that companies can build trust with its users. However, once any issues occur, building trust with users becomes exponentially more difficult each time.

[1] Paul, Logan. "What is Trust?”. INFO-I 300. Bloomington, IN. 8 March 2019.
Lecture.

## Quality Assurance
Quality Assurance (QA) is a fancy phrase for comprehensive testing of a system. It basically means to ensure that a system working and functioning properly, and according to its functional requirements. This is done in two ways: Automated Testing, and Manual Testing
 
### Manual Testing
It is manual and direct human testing of the system, which requires the checking of all inputs and outputs of the system. Although it seems to be too much monotonous work, it has further side effects, for example, it may prove that the system contains some errors and may not be as functional as was presumed, which may in return in losing the trust of a client.
 
### Automated Testing
Automated testing of a system is basically re-loading or rebooting of the system to ensure that there are no bugs or errors in the system. It is exponentially faster than manual testing and maintains consistency in results, more often than not.
 
### Training
Training in an SDLC cycle usually occurs between the QA stage and the Release stage. It, arguably, comes under the umbrella of QA as it considered to be a good practice as it gives an opportunity to validate functionality with actual users of the system, on a first-hand basis.
 
 
## Release
In the SDLC process/cycle, the Release stage is the last stage but is still an important and crucial stage as moving software to production can be a massive task, especially in environments where the software is critical to the business process. In other words, the release process is considered vital because it affects a business process significantly, thus being a risk if not done so carefully. The Release process also deals with what might be called the implementing of the system and may deal with the replacing of an older system.

[3]Paul, Logan. “Information Systems SDLC”. Info-I 300. Bloomington, IN. 4-3-2019.
Lecture.
