# Cognitive Notes

## Rzhetsky, A., Foster, J. G., Foster, I. T., & Evans, J. A. (2015). Choosing experiments to accelerate collective discovery. Proceedings of the National Academy of Sciences, 112(47), 14569–14574. 

**Tags**: discovery; research strategy; individual
.
"A scientist’s choice of research problem affects his or her personal career trajectory. Scientists’ combined choices affect the direction and efficiency of scientific discovery as a whole"

- The authors model scientists search strategies through a "research space", identifying the most efficient strategy and relating it to strategies from the empirical data. 
- They model the research space for biomedical sciences as a network of chemicals, linked based on their co-occurrence in the same paper. The authors model "novelty" or "discvery" as linking together chemicals that are the distance from the network. They model efficiency as the speed by which this network of chemicals is explored. 
- The authors find, using empirical data, that biomedical sciences are more conservative and have become more conservative over time, focusing on only a subset of popular/well known chemicals. 
- The authors also argue that publishing negative results would allow researchers to more effectively navigate the research space, and make scientific discovery more efficient. 
- Their data comes from MEDLINE. Chemical names were matched to metadata appearing in these articles. 

## Ramage, D., Manning, C. D., & McFarland, D. A. (n.d.). Mapping three decades of intellectual change in academia. 15.

**Tags:** Visualization; Linguistics; Topic

In a somewhat awkward paper, the authors map "intellectual change in academia" based on the adoption of language across fields. Using dissretations from ProQuest they train a kind of discipline-aware topic model that identifies words and language more fitting of every discipline (based on an _a priori_ designation). They then analyze how language inherent to one field is adopted by those in other fields over time. 

There are no major findings, just nice figures and an interesting method. Their abstract summarizes as:

- "Results of the analysis include identifying methodological fields that export broadly, emerging topical fields that borrow heavily and expand, and old topical fields that grow insular and retract"
- "Particular findings show a growing split between molecular and ecological forms of biology and a sea change in the humanities and  social sciences driven by the rise of gender and ethnic studies."

Can be used as an example of mapping science based on language, or of highlighting a divide between fields. 


##  Domenico, M. D., Omodei, E., & Arenas, A. (2016). Quantifying the diaspora of knowledge in the last century. Applied Network Science, 1(1), 1–13. 

**Tags:** Visualization; Interdisciplinarity; Topic

This paper aims to visualize the "diaspora of knoweldge", by which they mean the flow of researchers between different research topics over time. Some disciplines are defined as "sinks" of knoweldge, meaning that they attract increased attention, whereas others are instead "sources", meaning that many researchers move from them to another field. Using data from MAG and SciMago, they build both size-dependent and size-independent indices of movement across fields, and build several pretty visualizations. 
- They relate changes in the flows of knowledge to historical events, such as intensive interest in nanotechnology after the 2004 Nobel Prize in Chemistry. 
- They also find that researchers are more interdsiciplinary, publishing in more topics, over time. 


## Hofstra, B., Kulkarni, V. V., Galvez, S. M.-N., He, B., Jurafsky, D., & McFarland, D. A. (2020). The Diversity–Innovation Paradox in Science. Proceedings of the National Academy of Sciences.

**Tags:** Diversity; Innovation; Impact; Novelty; Embedding

The authors conduct a systems-level analysis of the "diversity-innovation paradox" in science, stated as "Diversity breeds innovation, yet underrepresented groups that diversify organizations have less successful careers within them". 

Key findings are:

- underrepresented groups produce higher rates of scientific novelty. - However, their novel contributions are devalued and discounted: 
  - Novel contributions by gender and racial minorities are taken up by other scholars at lower rates than novel contributions by gender and racial majorities,
  - Equally impactful contributions of gender and racial minorities are less likely to result in successful scientific careers than for majority groups. 
- These results suggest there may be unwarranted reproduction of stratification in academic careers that discounts diversity’s role in innovation and partly explains the underrepresentation of some groups in academia.

For each Phd dissretations indexed in ProQuest and published between 1977 and 2015, the authors calculate a score of novelty and subsequent update. 
- "Concepts" are extracted from each dissretation based presence in a lexicon constructed from the important words learned from a set of several hundred topics trained on the corpus. 
- Novelty is defined as the number of new concept linkages in the dissretation, modified somewhat by the likelihood of making the links randomly
- "Impactful novelty" or "uptake" is the number of times those new linkages were used in future dissretations.
- Also, a "distal" score is assigned to each combination based on their simialrity within an embedded space of topics


## Iacopini, I., Milojević, S., & Latora, V. (2018). Network dynamics of innovation processes. Physical Review Letters, 120(4), 048301.

**Tags:** Networks; Innovation; Model

The authors construct a dynamic network model of innovation processes that reproduces real-world data on the exploration of new scientific ideas.

The model assumes that ideas are arranged as nodes in a network, and that idead are explored via a random walker moving between ideas with probability proportional to the relative weight of neighboring nodes. At the beginning stages, all edges have the same weight. However,  walker *reinforces* edges that it traverses, meaning that previously-traveled paths are more likely to be taken. This means that the network co-evolves with the random-walk process, and that the walker is non-Markovian, its history matters. The exact strength of this reinforcement is the only tunable parameter of the model. 

This model captures the idea of the "adjacent possible", in that after a move, the walker has the potential to take another "step" away from the origin node. However the model also incorperates the "tradition" inherent to innovation processes, whereby known ideas are more likely to be explored than new ones. 

The authors find that this model can reproduce characteristics of real-life innovation processes using keywords from scientific journals in AStronomy, Economics, Ecology, and Math. 



## Wang, J., Veugelers, R., & Stephan, P. (2016). Bias against Novelty in Science: A Cautionary Tale for Users of Bibliometric Indicators (Working Paper No. 22180; Working Paper Series). National Bureau of Economic Research.

**Tags:** Novelty; Bias; Impact; Indicators

The authors argues that bibliometric indicators are biased against novel research. Here, they define novel research similar to Uzzi's *atypicality*, except instead of looking at typical/atypical combinations of referenced journals, they aim to capture completely novel combinations. Their findings confirm a "high risk/high gain" pattern for novel research
- Novel papers have a higher variance in citation performance than do non-novel papers, confirming their risky profile. 
- At the same time, novel papers are associated with big hits. They have a much higher chance of being top 1% highly cited, and are more likely to lead to follow-up high impact research. 
- Novel papers also have a broader impact across scientific fields, and are more likely to be highly cited in foreign fields compared with non-novel papers but not more likely to be highly cited in their home fields. 
- Novel papers require a sufficient period of time before their important contribution is recognized.

Because novel research is typically published in lower-than-expected impact journals, and because they suffer from delayed recognition, the authors argue that bibliometric indicators are biased against novel research. This is especially concerning given the increasing importance of such indicators to evaluation. 


## Guevara, M. R., Hartmann, D., Aristarán, M., Mendoza, M., & Hidalgo, C. A. (2016). The research space: Using career paths to predict the evolution of the research output of individuals, institutions, and nations. Scientometrics, 109(3), 1695–1709.

**Tags:**: Visualization; Trajectories; Mapping


The authors construct a map of science based on teh probability that a researcher publisheing in one field will also publish in another. Using proximity derived from this space, they predict the future activity of individuals, instititons, and countires in fields and find that their research space outperforms the alternative citation-based USCD Map of Science. Their map offers an alternative for visualization and deriving distances between fields. 

- They use the map to predict future activity in an area. Activity is quantieid as the RCA, and the prediction is made based on the probability of activity increases conditioned on the proximity of active fields (connected fields that have high RCA). 
- Predictive power is best for individuals and institions, not quite as good for countries
- A good quote for future project motivations: "Understanding the structure of research production is important for scientists, universities, and countries, because it can help them comprehend where they are and where they can go."




## Shibayama, S., & Wang, J. (2020). Measuring originality in science. Scientometrics, 122(1), 409–427.

**Tags:** Originality; Novelty; Indicators; Impact

A new publication-level bibliometric indicator of originality is introduced, one that is theoretically similar yet more computationally efficient than betweeness centrality. The key idea is that in a directed network formed around a tarket paper, including papers referenecd by the target and papers citing the target, the betweeness of the target can be conceived as its originality. Basically, an original paper will act as an intermediary between future papers and the literature the original paper draws on (references). 

The authors conduct an assessment and analysis with this indicator, finding that:
- It correlates with researcher's self-reported theoretical originality of their papers
- Is predictive of future validity
- Can be computed with only a subset of future citations, making it more computationally efficient than other measures


## Zhang, L., Rousseau, R., & Glänzel, W. (2016). Diversity of references as an indicator of the interdisciplinarity of journals: Taking similarity between subject fields into account. Journal of the Association for Information Science and Technology, 67(5), 1257–1265. https://doi.org/10.1002/asi.23487


**Tags:** Interdisciplinarity; Impact; Proximity; Diveristy; Theory

The authors conduct a theoretical investigation of diveristy measures, identifying key properties that they should satisfy.
- A diveristy measure should allow analysis in terms of ratios and percentages; some previous measures have not
- Should incorperate notions of variety (number of types), balance (evenness og type groups), and disaprity (similarity of types)

These considerations are similar to those in Yergos-Yergos et al., (2015). However, that study used three separate indices, whereas here they authors construct a single index. They go on to conduct a case study to assess diveristy in 7 major journals across multipiple fields. 
- They find that diveristy is positively associated with impact, up to a point, but that some fields (bioinformatics) have a negative relationship. 
- Disparity is calculated using both maojr-field and sub-field categories, with strong correlation between the two. 


## Yegros-Yegros, A., Rafols, I., & D’Este, P. (2015). Does Interdisciplinary Research Lead to Higher Citation Impact? The Different Effect of Proximal and Distal Interdisciplinarity. PLOS ONE, 10(8)

**Tags:** Interdisciplinarity; Impact; Proximity


Key concepts:
- Distal Interdiscilinarity: would refer to bold interdisciplinary papers that draw a significant proportion of references from disparate disciplines.
- Proximal Interdiscilinarity: reflects more cautious research practices that go beyond the immediate sub-discipline, but still mainly draw on related knowledge.

The relationship between a paper's interdisciplinarity and its citation impact is compelx. The authors define a papers's interdisciplinarity based on their references and along three axes: 
- Variety: Number of disciplines represented
- Balance: The evenness of the number of references in each discipline
- Disparity: The degree of "proximity" between disciplines represented, calculated based on disciplinary citation flow matrix

Via a multivariate analysis, the authors find that variety, the number of disciplines represented, is positively correlated with citation impact, wheras both balance and disparity are *negatively* correlated with impact. This suggest that simple policy claims like "interdisciplinary research is more impactful" can be misleading—interdisciplinarity has multiple dimensions that their respective effects differ. 

Useful quotes:
- "A first insight from these results is that publications that accrue the most citations are moderately interdisciplinary (neither too much, nor too little), in accordance with suggestions from previous studies. The key new insight of this study is that highly cited papers tend to cite various disciplinary categories (higher variety), but cite little outside their disciplinary vicinity (lower disparity) and in small proportions (lower balance)."
- "Our study, in everyday terms, suggests that practicing ‘meek’ or ‘shy’ (proximal) interdisciplinarity pays off in citations, but that brazen, audacious (distal) interdisciplinary efforts are not rewarded with citation success"



## Mukherjee, S., Romero, D. M., Jones, B., & Uzzi, B. (2017). The nearly universal link between the age of past knowledge and tomorrow’s breakthroughs in science and technology: The hotspot. Science Advances, 3(4)

**Tags:** Hotspot; References; Impact; Age

The authors identify a "hotspot" pattern in the age of paper's references such that drawing on a mix of both old and recent references increases the chance of a hit paper. This relationships holds true over time, across fields, occurs in both scientific papers and patents, and is robust to contorl variables such as novelty and interdisciplinarity. Moreover, collaboration incraeses the likelihood of producing a paper in the hostpot. 
- For each paper, a distirbution of the ages of its references is calculated. The mean and vairance of this distirbution are used as indicators of the hotspot. 
- Papers in the hotspot are those that a low mean age (drawing mostly from recent papers), but a high variance (injecting older knoweldge)
- There is an intricate relationship between this mean and vairance measurement. Papers with high mean (only drawing on older papers) are no more likely to be a hit paper, regardless of variance. Papers with high variance are only more likely to be a hit when passing a certain threshold of the mean. 
- Analysis of collaboration focuses on Math field medalists only, based on teh assumption that they will be the *least* likely to see a bump in impact from collaboration alone. 

Other useful quotes:
- "Drawing narrowly on recent ideas does not lead to exceptional impact. Similarly, drawing on vintage knowledge or widely sampledwork is associated with an impact no greater than expected by chance."
- "The hotspot’s generality indicates that there is an age distribution of prior knowledge that is particularly linked to tomorrow’s breakthroughs"
- We found that one determinant of being in the hotspot is related to collaboration: Authors are more likely to produce work that is in the hotspot when coauthoring than when working alone."



## Youn, H., Strumsky, D., Bettencourt, L. M. A., & Lobo, J. (2015). Invention as a combinatorial process: Evidence from US patents. Journal of The Royal Society Interface, 12(106)

**Tags:** Patents; Innovation; Invention

Key Concelts
- Exploitation: refinemenets of existing combinations of technologies
- Exploration: The development of new technological combinations


Youn et al., take a theoretical approach to understanding the process of invention via examinzation of codes used to demarcate the technological contribution of patents in the USPTO over tha past two centuries. The key ideas here are that invention is assumed as combinatorial, and that there are invariant patterns of combinations over time. Patents are each assigned a set of codes which define the scope and novelty of their contribution, and new codes are only created as necessary. Through their analysis, the authors find support for the following:
- "...the combinatorial inventive process exhibits an invariant rate of ‘exploitation’ (refinements of existing combinations of technologies) and ‘exploration’ (the development of new technological combinations)."
- "‘refinements’, which here means the reuse of existing technology codes or of existing combination of codes to identify the novelty of a patented invention, are very important in pushing invention forward...We also find that a few technologies and their combinations are used much more intensely in the construction of inventions and that the level of utilization is not correlated with how long the technologies have been available in the system"
- "notwithstanding thevery reducedrate atwhichnewtechnologies are introduced, the generation of novel technological combinations engenders a practically infinite space of technological configurations"

Other key points:
- The paper provides a good explanation of the US patenting system
- The authors pose a simlarity between combinatorial technological invention and biological structures
- Even old and seemingly obsolete patent codes still find occasional use

## Uzzi, B., Mukherjee, S., Stringer, M., & Jones, B. (2013). Atypical Combinations and Scientific Impact. Science, 342(6157), 468–472. 

**Tags:** Innovation; Impact; Teams; Novelty

Key concepts:

- Tail Novelty: The novelty of something's most novel parts. Something can be conventional overall, yet still have high tail novelty if it contains exceptionally novel elements. 
- Burden of knowledge: The ever-increasing knoweldge  demands of science require more education and complexity to make progress. 


In this landmark paper, Uzzi et. al investigate the incidence of paper-level measures of co-reference novelty, and relate these measures to citation impact and team size. They find that the most impactfu appers exist in a sweet spot, largely drawing on conventional combiantions of past work, while also incoerpating novel combinations. The authors fins that these papers are rare, but are more often produced by large teams. 
- Co-reference novelty: For every paper, the authors calculate the likelihood of every pairwise combination of references occuring by change, based on their incidence and co-occurence across the scientific literature. Connections are aggregated to the level of journals. Each paper thus becomes a distirbution of z-scores comparing the likelihood of pariwise combinations against a null model. 
- Tail novelty: The 10th percentile novelty scores in a paper's distribution. Otherwise though of as "how novel are the most novel parts"
- Most papers were conventional, having high median conventionality and low tail novelty
- The highest-impact papers had high tail novelty and also high conventionality, hitting the "sweet spot"
- Co-authored papers, especially with teams (3+ co-authors) were more likely to produce high tail-novelty papers, but just as likely to produce high-median conventionality papers


Useful Quotes:
- "Thus, novelty and conventionality are not opposing factors in the production of science; rather, papers with an injection of novelty into an otherwise exceptionally familiar mass of prior work are unusually likely to have high impact"
- "First, high tail novelty papers had higher impact than low tail novelty papers, an impact advantage that occurred at any level of conventionality and regardless of authorship structure. Second, peak impact occurred in the 85th to 95th percentile of median conventionality, an exceptionally high level"
- "The finding that teams preserve high conventionality yet introduce tail novelty suggests that teams help meet the challenge of the burden of knowledge by balancing domain-level depth with a capacity for atypical combinations"



## Gates, A. J., Ke, Q., Varol, O., & Barabási, A.-L. (2019). Nature ’s reach: Narrow work has broad impact. Nature, 575(7781), 32–34.

**Tags:** Interdisciplinarity; Impact; Temporal; Nature

This short paper investigates the changing interdisciplinarity of references and citations of articles published in nature compared to other scientific articles as a whole. The authors also use visualizations to walk through the impact of several "episodes" or key papers that have been published in the journal. 

- For most journals, the bredth of inspiration (what they reference) and impact (who cites them) is highly correlated. However, general journals like *Nature* and *Science* have more bredth than 99.7% of journals
- The diversity of disciplines in nature article's reference sections is increasing. This is also true for science as a whole
- Nature tends to draw on fewer disciplines than other journals, but is cited by a broader swathe of disciplines, hence the title "narrow work has broad impact"


## Larivière, V., & Gingras, Y. (2010). On the relationship between interdisciplinarity and scientific impact. Journal of the American Society for Information Science and Technology, 61(1), 126–131.

**Tags:** Interdisciplinarity; Impact; Citation

The authors examine the link between interdisciplinarity and scientific impact at a macro scale across many disciplines by examining the references of publications in the Web of Science. Their findings are,

- In some disciplines, a higher level of interdisciplinarity is related with more impact
- The most traditional and most interdisciplinarity research, across all disciplines, has the lowest impact—there is some "optimum" amount of interdisciplinarity
- "The relationship between interdisciplinarity and scientific impact is highly determined by the citation characteristics of the disciplines involved: Articles citing citation-intensive disciplines are more likely to be cited by those disciplines and, hence, obtain higher citation scores than would articles citing non-citation-intensive disciplines."
- "In biomedical research and to a lesser extent in physics, earth and space sciences, and professional fields, a higher degree of interdisciplinarity is correlated with lower citation rates.Onthe other hand, in biology, clinical medicine, humanities, psychology, and health (social sciences), a moderate interdisciplinarity is associated with higher citation rates."


## Evans, J. A. (2008). Electronic Publication and the Narrowing of Science and Scholarship. Science, 321(5887), 395–399.

**Tags:** Digital Libraries; Specialization; Citations; 

The author examines the consequences of online (rather than print) publications on scholarly work by examining how citation patterns changed before and after. "Citation data were drawn from Thompson Scientific’s Science, Social Science, and Arts and Humanities Citation Indexes" for publications between 1945 and 2005. Among the findings are:

- As more journals came online, the articles cited tended to be more recent
- Fewer journals and articles were cited
- More of those citations were to a smaller set of journals and articles

Together, this suggests that the shift online has been coupled with a shift away from browsing and perusing literature in *less efficient* print archives, leading to an avoidance of older or less relevant literature. Indexing shapes science, and so the turn to electronic has also had an impact.  



## Jones, B. F. (2009). The Burden of Knowledge and the “Death of the Renaissance Man”: Is Innovation Getting Harder? The Review of Economic Studies, 76(1), 283–317. JSTOR.

**Tags:** Innovation; Education; Economics; Patents; Specialization

The author argues that, since technology progresses with similar progression in knowledge, that future innovation will rely on more education and more specialization. 

> "Innovators can compensate in their education by seeking narrower expertise, but narrowing expertise will reduce their individual capacities, with implications for the organization of innovative activity - a greater reliance on teamwork - and negative implications for growth."

The author constructs a (pretty complex) economic model to examine the dynamics of knoweldge production following this idea. The model is fit to patent data from the USPTO between 1963 and 1999. Key findings from the model and data are summarized as,

> "We find that the age at first innovation is increasing over time while it shows no variation across widely different fields... Meanwhile, team size and specialization are increasing over time and varying across fields, with greater teamwork and specialization the larger a measure for the amount of underlying knowledge...The upward trends in age, teamwork, and specialization are robust across widely different technological areas and research environments. The upward trends in teamwork and specialization are also especially steep.."

The author concludes by claiming that his model holds true, and that there are bounds to innovation based on the ever-expanding frontier of knoweldge and the limits of human capital. He posits several escapes from this pessimistic future: 
- The value of new knowledge will become greater, meaning that even small gains will be sufficient
- Future revolutions will collapse or simplify the knowledge space, making it easier to learn
- Better education/methods to transfer and grow one's knowledge

## Bromham, L., Dinnage, R., & Hua, X. (2016). Interdisciplinary research has consistently lower funding success. Nature, 534(7609), 684–687. 

**Tags:** Interdisciplinary, collaboration, funding

As the title says, interdisciplinary research has lower funding success in regards to grant proposals than does strictly-disciplinary research. The authors analyzed proposals submitted to the *Australian Research Council Discovery Program*, which included both funded and non-funded proposals. Here, authors self-report at least 1 disciplinary code, along with percentages detailing how closely the dsiciplinary code fits with the project. They arrange discipline as a hierarchically-clustered dendrogram, and use a method called "phylogenetic species evenness" to measure both the eveness of representation of the disciplines as well as their distance in the discipline dendeogram. 

Among their other key findings:
- Interdisciplinarity is consistently negatively correlated with funding success, even when controlling for other factors such as institution
- The overall funding success rates variaed between institutions, with more prestigious institions having higher success rates
- Proposals with more chief investigators had slightly higher funding success
