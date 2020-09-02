# Fear and Loathing in Romanian: An experimental study on the sematic properties of psych-verbs


## Description
This project was conducted during my Master's degree in Linguistics at Humboldt-Universität zu Berlin, inspired by the reasearch of [Prof. Elisabeth Verhoeven](https://www2.hu-berlin.de/experiencer/alternation/en/index.html) and [Hartshorne et al.](https://www.researchgate.net/publication/308761372_Psych_verbs_the_linking_problem_and_the_acquisition_of_language) on psych-verbs. 

**Psych-verbs** (also psychological verbs or experiencer verbs/predicates) express the mental state or emotion of an experiencer. The experiencer role refers to a participant that undergoes an event affecting consciousness. The experiencer can appear in one of two positions: as subject (**subject experiencer - SE**) or as object (**object experiencer - OE**). For example, in the sentences:

- *Jack scares Wendy.* - Wendy is the OE of an action (emotion) inflicted by Jack upon her.
- *Wendy fears Jack.* - Wendy is the SE of an emotion that arises within her in response to Jack. 

Even though the two verbs express the same emotion of fear, they have different syntactic structures, depending on the experiencer form. This structure appears to be unsystematic across languages, so there are no clear rules for which verbs are either OE, SE, or both. For this reason, psych-verbs pose a linguistic challenge in explaining the link between syntax and semantics. At the point of writing (early 2019), theoretical and experimental research has limited to popular languages (e.g., English, German, Japanese) and there are no experimental studies on Romanian psych-verbs. This is unfortunate, because native speakers' intuition can provide insights into a language. Therefore, my aim was to fill this research gap by conducting an experiment that reveals the semantic properties of psych-verbs in my native language, Romanian.

## Experiment
### Design
For this purpose, I composed a list of 54 Romanian verbs from six emotion categories: anger, disgust, fear, happiness, sadness, and surprise. Some of these verbs are used as examples in the literature explaining the structure of psych-verbs. Each verb is to be rated from 1 (least) to 5 (most) on four criteria: 
- valence (whether the verb expresses a negative or a positive emotion),
- arousal (how intense is the emotion expressed by the verb), 
- duration (how long is the emotion expressed by the verb likely to last), 
- cause (whether the emotion expressed by the verb is perceived to be caused by external or internal factors). 
### Participants
The verbs were rated by 30 participants:
- all native speakers of Romanian,
- 17 females, 6 males (self-identified),
- average age 32 years old.
### Method
The participants were selected through word of mouth. They were handed in the verb list in paper-form or sent via email and they completed it in one sitting. The verb list was randomized for each participant, so that the order of the verbs could not influence the ratings. 

## Data analysis
I analyzed and visualized the collected data with Python, in three main parts:
- descriptive analysis (by experiencer, emotion category, and verb)
- clustering
- classification.
For this, I employed different libraries: pandas, seaborn, scikit-learn, 
 
The complete data analysis can be found in the [psych-verbs Jupyther Notebook](https://github.com/lorenanda/psych-verbs/blob/master/psych-verbs.ipynb).

## Discussion
### Limitations
Though this experiment revealed new findings, this subject can be explored further. The main limitation of this study is the small sample size of participants. Moreover, it would be interesting to explore how verb ratings differ by gender or age of the speakers.
### Applications
Initially, my main interest was to explore the linguistic structure of psych-verbs, but while working on the data analysis and reading research on emotions, I realized the findings of my study could be used for natural language processing (NLP) tasks, such as sentiment analysis and emotion recognition. For example, detecting signs of depression or anxiety in texts (e.g., forums, clinical notes).
