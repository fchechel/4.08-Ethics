# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Explainable Models

> Unit X, Lesson Y

<!--- This template is an instructor-facing description of lesson contents. Students who fork these repos may also be able to view. --->

---

## Materials We Provide
<!--- This section is a table of contents for the lesson. The table structure breaks down typical lesson resources into types, distinguishing between lesson notebooks and other supporting materials. Note that the table below demonstrates the total possible range of materials; most lessons won't require all of the categories below. Also note that every item in the repo should get its own line and link, like the example shown for data. --->

| Topic | Description | Link |
| --- | --- | --- |
| Lesson | Interactive jupyter notebook with structured lesson content | [Link](./explainable-models.ipynb)|
| Data | Titanic dataset | [Link](./datasets/titanic.csv)|
| Relevant Video | The Era of Blind Faith in Big Data Must End  | [Link](https://www.ted.com/talks/cathy_o_neil_the_era_of_blind_faith_in_big_data_must_end) |

> Dataset description: The usual Titanic data; chosen because everybody knows what the answer should look like
>
> Note that this topic is unusual. You will find it easy to generate class discussions -- they will probably happen
> spontaneously! -- but there is very little hands-on coding.
>
> It is also possible that some students may have emotionally traumatising stories to tell of their experiences.
> If this happens, remind your class of their responsibilities to make the world a better place; and support
> your students in whatever way possible.

---

## Learning Objectives
<!--- This section lists the learning objectives of the lesson. For information on how to write clear learning objectives, see: http://ii.library.jhu.edu/2016/07/20/writing-effective-learning-objectives/ --->

- **Define** some of the political, ethical and economic ramifications of using black-box models in data science.
- **Describe** the features of explainable vs non-explainable (black-box) models
- **Define and discuss** the global implications of the EU GDPR
- Use LIME to **explain** a black-box model

---

## Student Requirements
<!--- This section explains the relevant prerequisites; in other words, what do students need to know to be able to benefit and perform the tasks required in this lesson? This includes lists of skills or prior learning objectives --->

**Before this lesson(s), students should already be able to**:
- Define what a classifier is
- Perform a train-test split on a dataset
- Slice columns from pandas dataframes and numpy arrays
- Create a K-Nearest-Neighbor classifier using scikit-learn
- Understand what a linear model is, and a linear classifier boundary

---

## Lesson Outline

<!--- This section outlines the lesson plan with relevant sections and subsections, providing both the total time required as well as suggestions for timing in each subsection --->

> Total Time: 82 min. 

- **Introduction** (10m)
  - Observations of national approaches to racism (5 min)
  - Ethical responsibilities of data scientists (5 min)
- **Blackbox models**  (20m)
	- Comparisons of black-box vs explainable (5 min)
	- Class discussion (15 min)
- **EU GDPR** (25 min)
	- Articles (7 min)
	- Recitals (8 min)
	- Class discussions (10 min)
- **Resolutions** (27 min)
        - Available options (2 min)
        - LIME (25 min)

---

## Additional Resources
<!--- This section lists useful reference materials that can inform, extend, or deepen a student's understanding of the material. While this may seem like a "nice to have" feature, we normally see a range of advanced and remedial students in our classes. Curating these resources allows us to provide targeted materials and suggestions that instructors can use to support different student needs. --->

For more information on this topic, check out the following resources:

- [Is there are a right to explanation for Machine Learning in the GDPR?](https://iapp.org/news/a/is-there-a-right-to-explanation-for-machine-learning-in-the-gdpr)
- [Why a Right to Explanation of Automated Decision-Making Does Not Exist in the General Data Protection Regulation](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2903469)
- [Towards Interpretable Reliable Models](https://blog.kjamistan.com/towards-interpretable-reliable-models/)
- [GDPR and you](https://blog.kjamistan.com/gdpr-you-my-talk-at-cloudera-sessions-munchen/)
- [Hold Your Machine Learning and AI Models Accountable](https://medium.com/pachyderm-data/hold-your-machine-learning-and-ai-models-accountable-de887177174c)
- [How GDPR Affects Data Science](https://kdnuggets.com/2017/07/gdpr-affects-data-science.html)
- [Scaleable Bayesian rule lists](https://arxiv.org/pdf/1602.08610v2.pdf)
- [Why Should I Trust You? Explaining the Predictions of Any Classfier ](https://www.youtube.com/watch?v=hUnRCxnydCc)
- [Explaining Complex Machine Learning Models with LIME](https://datascienceplus.com/explaining-complex-machine-learning-models-with-lime/)"
