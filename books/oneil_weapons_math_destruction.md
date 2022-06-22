## Weapons of Math Destuction: How big data increases inequality and threatens democracy

**Keywords**:  Big data; machine learning; inequality

**Authors**: Cathy O'Neil

**Date of Publication**: 2016

**Reference**: O’Neil, C. (2016). Weapons of Math Destruction: How Big Data Increases Inequality and Threatens Democracy (1 edition). New York: Crown.



#### Key Concepts
----

1. **Weapon of Math Destruction:** shortened to WMD, this is a particularly harmful kind of mathametical model. One characteristic of WMDs is that they are opaque, their inner workings invisible; outputs of these systems are uncontestable, even when wrong or harmful. However, these output are also often treated as authoritative. These models tend to create negative feedback loops that reinforce existing or past inequalities and injustives. More often than not, they will punish the poor and make the rich richer. Examples of WMDs include the financial systems that lead to the 2008 recession, predictive policing that target poor and black/latino neighborhoods, workplace hiring systems that punish protected groups, and personalized or targeted advertisting systems. 
2. **Feedback Loop:** A feedback loop, in the context of this book, occurs when a WMD begins to shape the world it is trying to model, further reinofrcing the patterns that it was trained to recognize. For example—predictive policing will place police in areas where crimes were previously reported; arrests will naturally occur where the police are; therefore, the future data feeding into the system will reinforce the existing racist data. 
3. **Proxy:** When something cannot directly be measured, a proxy is often used. For example, if someone cannot directly meausre trust in a scoring system for bank loanss, then they will try to measure something that they feel is related to trust, like credit score or some other e-scoring system. 

#### Questions
----

***What is the main argument of the text?***

O'Neil aruges that certain "Weapons of Math Destruction" (WMDs) pose a danger to democracy and society, mainly through their tendency to punish the poor (and everyone who isn't wealthy, really). They create negative feedback loops that reinforce inequality and social injustice, especially thsoe based around race, gneder, class, and geography. These models that constitute WMDs are unregulated and uncontestable. Moreover, they are invisible to those who are more wealthy and powerful–they can be safely ignored or money can be spent to avoid them (though, middle class individuals also must deal with these issues, though in different ways, see the chapter on college admissions). O'Neil argues that data scientists and mathameticians should be aware of WMDs, and have an ethical responsibility to avoid them. A "hippocratic oath" for data scientists is proposed (originally proposed by two financial engineerings in 2008), which summarizes the ethical view of this text:

- I will remember that I didn't make the world, and it doesn't satisfy my equations
- Though I will use models boldly to estimate value, I will not be overly impressed by mathematics
- I will never sacrifice reality for elegance without explaining why I do so
- Nor will I give the people who use my model false comfort about its accuracy. Instead, I will make explicit its assumptions and oversights. 


***Describe at least three ways that the main argument is supported.***

The author supports her argument primarily through case studies: she gives many examples of WMDs "in the wild", showing how they can cause harm and perpetuate inequality. 

1. One example that she gives is in e-score systems. Banks, employers, landlards, and many other groups are interested in the "trust" of an applicant. However, trust is difficult to quantify. Outside credit score (which the author argues is not actually a WMD), a myriad of e-scores have been created, which attempt to quantify the trust of an applicant. These e-scores use data like: the shopping patterns of individuals, their zip code, their search histories, and more, in an attempt to gauge trust. However, all to often these factors end up being proxies for race, gender, or class, leading to racist, sexist, and classist models. Such e-scores are often invisible, kept hidden from the individuals they claim to measure. They are often also uncontestable, yet have so much effect on people's lives. 

2. Another system mentioned by the author is that of teaching evlauatuon systems, which attempts to provide a "score" to quantify the effectiveness of a teacher. However, the author argues through her example that these scores are all too often meaningless, and based on statistical errors. However, because the system producing these scores is invisible, inscrutable, and bathed in a sense of mystique and authority, they all too often go unchallenged and impact employment decisions. 

3. A third example that the author often referred to was a model that attempted to predict the chance that a person arrested for a crime would return to prison, if released (a recidivism risk scoring system). This system was not only racist, but also produced feedback loops that fed off other WMDs. If an individual was given a higher risk of recidivism, they would be placed in prison for longer; they would thus have a higher chance of becoming more hardened criminals while in prison; they would return into the world and find that other WMDs will dey them loans, housing, and employement, and they will now be more likely to return to prison—the WMDs create a self-furfilling prophecy.


***Describe the main literatures that the text draws on and contributes to, and the particular contribution made by the text.***

O'Neil draws on relatively little literature to argue her point. Likely this is due to the "popsci" quality of the book, which intends to appeal to a wide audience. The author writes in a topic in the STS tradition, but given her background in mathematics and industry, does not seem herself to be a part of this tradition. 

***Describe the methodology (or methodologies) used in the text, and how it enables the author(s) to support the text’s main argument.***

This book draws on a mix of the author's personal experience, and examples (which I assume are drawn from the public domain, from papers, and new stories) to make her arguments. For the purpose of the book (warning of the current and potential dangers of WMDs) this serves her purposes well—these examples provide real-world demonsrations of WMDs to people that are all-to-often ignorant of them. 

***Describe at least three of the text’s themes or topics that are of interest to my quals or dissretation research.***

1. Dangers of algorithms. The main point of this text is that WMDs pose certain dangers to society. My work does not necessarily concern WMDs, but it does concern algorithms and data science more broadly. This book seems of particular interest to the "application" or "black box" section of my qualifying exam. One of the key dangers of WMDs stems from theri inscrutability, and this is a key issue with many data analysis moe broadly. 

2. Ethics of data science: O'Neil argues in favor of a "hippocratic oath" for data scientsits, one that centers the dangers of WMDs and similar systems. 

3. Data and equations are not reality: my work focuses on the epistemic implications of these methods. A common theme of the text is summarized in a tennant of the ethical oath in the conclusion: *"I will remember that I didn't make the world, and it doesn't satisfy my equations"*. Data scientsits have a duty to interrogate their data. Good data is good, but no matter the quality, data is not an accurate representation of reality, and this should be considered. The quality of data, and the quality of analysis are essential to ethical data science. 

***What three quotes capture the critical significance of the text?***

1. "As is so often the case with WMDs, the very same models that inflict damage could be used to humanity's benefit. Instead of targeitng people in order to manipulate them, it could line them up for help. IN a mayoral race, for example, a microtargeting campaign might tag certain voters for angry mesages about unnofordable rents. But if the candidate knows these voters are angry about rent, how about using the same technology to identify the ones who will most benefit from affordable housing and help them find it? with political messaging, as with most WMDs, ***the heart of the problem is almost always the objective***. Change the objective from leeching off people to helping them, and the WMD is disarmed—and can even become a force for good." (pg 197)

2. "But human decision making, while often flawed, has one cheif virtue. It can evolve. As human beings learn and adapt, we change, and so do our proesses. Automated systems, by contrast, stay stuck in time until engineers dive in to change them. If a Big Data college application model had established itself in the erly 1960s, we wouldn't have many women going to college, because it would have been trained largely on successful men...***Big Data processes codify the past***. they do not invent the future. Doing that requires moral imagination, and that's something only humans can provide. We have to epxlicitely embed better values into our algorithms, creating Big Data models that follow out ethical lead. Sometimes that will mean putting fairness ahead of profit." (pg 203)

3. "A person who scores as ‘high risk’ is likely to be unemployed and to come from a neighborhood where many of his friends and family have had run-ins with the law. Thanks in part to the resulting high score on the evaluation, he gets a longer sentence, locking him away for more years in a prison where he’s surrounded by fellow criminals—which raises the likelihood that he’ll return to prison. He is finally released into the same poor neighborhood, this time with a criminal record, which makes it that much harder to find a job. If he commits another crime, the recidivism model can claim another success. ***But in fact the model itself contributes to a toxic cycle and helps to sustain it.*** "

#### Other Notes
----
I like this book because, unlike some STS literature, it does not uniformly dismiss quantitative models. Instead, the author argues that these tools can, in fact, become forces for good, but that it will require a reorienting of our priorities and appraoches. Particularly, we should change the focus of these systems away from punishing people, and towars helping people—optimizing for good, rather than harm. 

