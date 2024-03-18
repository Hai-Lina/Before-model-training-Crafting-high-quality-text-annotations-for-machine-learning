# Before model training: Crafting high-quality text annotations for machine learning
This ICWSM'24 tutorial teaches gathering high-quality text annotations for machine learning including social scientific methods.

## Abstract
Contrary to common misconceptions, data cannot speak for itself. Researchers will select, construe, shape, and process data even before statistical modeling begins. However, this is where most supervised machine learning courses start: with a clean data set, thus overlooking the process of how this data came about. We will work hands-on through the steps necessary to gather high-quality text annotations with a special focus on classification widely prevalent in computational social science. We cover three topics: We discuss modeling goals that can inform data collection and annotation decisions. We employ qualitative methods (particularly grounded theory) to explore how valid annotation schemes can be created. We ask participants to annotate a sample of data along a given annotation scheme and highlight that disagreement can be informative through the lens of data perspectivism. For our exercises, we work with text data from a conversational corpus (CANDOR Corpus; Reece et al., 2023) to identify strategies for how people influence others emotions. The tutorial aims at building bridges between researchers from technical and social scientific backgrounds, a collaboration which benefits both communities in building state-of-the-art classification pipelines. Researchers from all fields are welcome; no specific background knowledge is required.

## Target audience
We encourage both researchers with a technical and a social scientific background to engage in our tutorial. While technical researchers will be introduced to qualitative text analysis methods, social scientists will benefit from the modeling perspectives provided in the tutorial. We will conduct group work, where members with diverse backgrounds can engage in mutual learning and form interdisciplinary connections.

## Prerequisites
Basic programming knowledge is beneficial for minor parts of the exercises (~10% of the entire tutorial time), but other than that no prior knowledge (social scientific or computational) is required.

## Preparation
- An installation of Python and Jupyter Notebooks on the participants’ own laptops is beneficial (e.g., using the Anaconda environment). Alternatively, participants can use Google Colab.
- A list of necessary packages to execute the provided notebook(s) will be provided in an environment file beforehand.

## Duration and tutorial schedule
The tutorial lasts 4 hours including breaks.

- [15 min, PRESENTATION] *Welcome, Introduction & Set Up*: This part will quickly introduce the lecturers, schedule and goals of the tutorial.
- [20 min, PRESENTATION] *How modeling choices can inform data collection and annotation*: We will elaborate on how anticipated machine learning modeling choices should influence the training data set creation.
- [20 min, PRESENTATION] *A short introduction to grounded theory*: This classical social science technique can guide the work with unstructured text data, where theories are constructed from the bottom-up through iterative reading.
- [70 min, PRACTICAL] *Creating an annotation scheme using deep reading and open coding*: Participants will be guided in creating an annotation scheme for interpersonal emotion regulation strategies based on selected transcripts of natural conversations.
- [15 min, BREAK]
- [60 min, PRACTICAL] *Annotating data along a given framework*: Provided with a fixed annotation scheme for interpersonal emotion regulation strategies, participants will annotate a small amount of short text samples including the discussion and measurement of disagreement.
- [20 min, PRESENTATION] *Trading agreement for disagreement - an introduction to perspectivism*: Data perspectivism states that different human interpretations of the same data sample can and should coexist and how multiple perspectives can be integrated in the modeling process.
- [20 min, DISCUSSION] *Final discussion & feedback*: We will reflect upon the aquired knowledge and clarfiy open questions.

## Presenters
- Alina Herderich (Graz University of Technology, Harvard University) [https://hai-lina.github.io](https://hai-lina.github.io)
- Sofie Labat (Ghent University) [https://lt3.ugent.be/people/sofie-labat/](https://lt3.ugent.be/people/sofie-labat/)
- Jana Lasser (University of Graz, Complexity Science Hub Vienna) [https://www.janalasser.at](https://www.janalasser.at)

## Literature
For participants who prefer to familiarize themselves with the tutorial content beforehand, we recommend the following literature. ! Preparation is not expected, nor necessary !

- Cabitza, F., Campagner, A., & Basile, V. (2023). Toward a Perspectivist Turn in Ground Truthing for Predictive Computing. _Proceedings of the AAAI Conference on Artificial Intelligence, 37_(6), 6860-6868.
- Glaser, B. G., & Strauss, A. L. (1967). _The discovery of grounded theory: Strategies for qualitative research_. Aldine.
- Lasser, J., Herderich, A., Garland, J, Aroyehun, S. T., Garcia, D., & Galesic, M. (2023). _Collective moderation of hate, toxicity, and extremity in online discussions_. arXiv. https://arxiv.org/abs/2303.00357
- Reece, A., Cooney, G., Bull, P., Chung, C., Dawson, B., Fitzpatrick, C., Glazer, T., Knox, D., Liebscher, A., & Marin, S. (2023). The CANDOR corpus: Insights from a large multimodal dataset of naturalistic conversation. _Science Advances, 9_, eadf3197. https://doi.org/10.1126/sciadv.adf3197

## Provided materials
Expect the following materials to be provided with closer proximity to the tutorial date:
- Selected transcripts of bidirectional, daily conversations (CANDOR Corpus; Reece et al., 2023)
- Worksheets for practice sessions on grounded theory and data annotation
- A Jupyter Notebook for the practice session on data annotation to compute inter-annotator agreement
- Slides for all presentations
