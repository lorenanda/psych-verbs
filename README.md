# Fear and Loathing in Romanian: An experimental study on the sematic properties of psych-verbs


## Description
This project was conducted during my Master's degree in Linguistics at Humboldt-Universität zu Berlin, inspired by the reasearch of [Prof. Elisabeth Verhoeven](https://www2.hu-berlin.de/experiencer/alternation/en/index.html) and the paper of [Hartshorne et al.](https://www.researchgate.net/publication/308761372_Psych_verbs_the_linking_problem_and_the_acquisition_of_language) on psych-verbs. 

**Psych-verbs** (also psychological verbs or experiencer verbs/predicates) express the mental state or emotion of an experiencer. The experiencer role refers to a participant that undergoes an event affecting consciousness. The experiencer can appear in one of two positions: as subject (**subject experiencer - SE**) or as object (**object experiencer - OE**). For example, in the sentences:

- *Jack scares Wendy.* - Wendy is the OE of an action (emotion) inflicted by Jack upon her.
- *Wendy fears Jack.* - Wendy is the SE of an emotion that arises within her in response to Jack. 

Even though the two verbs express the same emotion of fear, they have different syntactic structures, depending on the experiencer form. This structure appears to be unsystematic across languages, so there are no clear rules for which verbs are either OE, SE, or both. For this reason, psych-verbs pose a linguistic challenge in explaining the link between syntax and semantics. At the point of writing (early 2019), theoretical and experimental research has limited to popular languages (e.g., English, German, Japanese) and there are no experimental studies on Romanian psych-verbs. Therefore, my aim is to fill this research gap and bring a contribution to my native language, Romanian. 

## Experiment
### Design
For this purpose, I composed a list of 54 Romanian verbs from six emotion categories: anger, disgust, fear, happiness, sadness, and surprise. Some of these verbs are used as examples in the literature explaining the structure of psych-verbs. Each verb is to be rated on four criteria: 
- valence (whether the verb expresses a negative or a positive emotion),
- arousal (how intense is the emotion expressed by the verb), 
- duration (how long is the emotion expressed by the verb likely to last), 
- cause (whether the emotion expressed by the verb is likely to be caused by external or internal factors, in the sense of felt from within the experiencer). 
### Participants
The verbs were rated by 30 participants:
- 30 native speakers of Romanian,
- females, males (self-identified),
- average age 

### Method
The participants were selected through word of mouth and snowball effect. They were handed in the verb list in paper-form or sent via email and they completed it in one sitting. The order of the verbs was randomized for each participant, so that the verb order could not influence the ratings. 

## Data analysis
I analyzed and visualized the resulting data in Python, using different libraries: 
- for descriptive data analysis: pandas
- for data visualization: matplotlib, seaborn
- for clustering and classification: scikit-learn
 
The complete data analysis can be found in the [psych-verbs Jupyther Notebook](https://github.com/lorenanda/psych-verbs/blob/master/psych-verbs.ipynb).

## Findings

## Outlook / Discussion
Thogh this experiment revealed some interesting findings, this subject can be explored further. The main limitation of this study is the small sample size of participants. Moreover, it would be interesting to explore whether there are difference by gender or age.
