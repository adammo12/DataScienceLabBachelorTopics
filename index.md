![Logo](uibk-logo.2017.svg)
## Topics for Bachelor Theses   

### Topic 1: Developing Interactive Website for Text Readability Assessment (Supervisor: Univ.-Prof. [Adam Jatowt](mailto:adam.jatowt@uibk.ac.at))

Readability measurement estimates how easy is to read a given text. Highly readable texts are accessible to users of varying educational background, reading skills or ones with limited knowledge of a given foreign language. Readability measures have been developed since some time ago taking into consideration the length of sentences, number of syllabes, grammatical and lexical complexity of text and so on. Recent measures use neural networks to determine readability scores of paragraphs or sentences. The objective of this topic is to develop an interactive tool which will take an input text either in the form of pdf, doc, txt or as pasted text and will return a range of readability measures and lexical complexity estimates for the text, as well as, will highlight the text portions that are difficult to read according to selected readability metric. The working languages should be German and English.

Prerequisites: basic knowledge of text processing, interactive web site design

### Topic 2: Designing Approach for Image Age Estimation based on Age of Image Objects (Supervisor: Univ.-Prof. [Adam Jatowt](mailto:adam.jatowt@uibk.ac.at))

A significant number of old photographs including ones that are posted online do not contain the information of the date at which they were taken, or this information needs to be verified. Many of such pictures are either scanned analog photographs or photographs taken using a digital camera with incorrect settings. Automatically estimating the date of such pictures is useful for enhancing data quality and its consistency, improving information retrieval and for other related applications. The objective of this task is to propose an efficient approach for automatic estimation of the shooting dates of scanned born-analog photographs based on: (a) object detection and segmentation, (b) estimating age of detected objects and (c) ensembling date estimation for detected objects. The proposed method can borrow from the initial work conducted in this direction [1]. The object segmentation approach is available [here](https://github.com/ArunMichaelDsouza/tensorflow-image-detection). The task assumes also generating a new dataset of segmented objects based on the existing [dataset](https://www.radar-service.eu/radar/en/dataset/tJzxrsYUkvPklBOw) which contains close to 1mln photographs taken over about 70 years of 20th century.

[1] Shota Ashida, Adam Jatowt, Antoine Doucet, Masatoshi Yoshikawa: Determining Image Age with Rank-Consistent Ordinal Classification and Object-centered Ensemble, Proceedings of the 2nd ACM International Conference on Multimedia in Asia (ACM MM Asia 2020), Singapore, ACM DL (2021)[paper](https://adammo12.github.io/DataScienceLabBachelorTopics/ACMMM-paper.pdf)

Prerequisites: knowledge of image processing and machine learning, interest in history

### Topic 3: Generating History-related Interactive Quizzes (Supervisor: Univ.-Prof. [Adam Jatowt](mailto:adam.jatowt@uibk.ac.at))

The objective of this topic is designing history-focused quiz generator for educational and entertaining objectives. Given a database of historical events in the form of short event descriptions, the task is to first generate a question for each event which is a valid and answerable question, using question generation tool based on transformers ([link](https://github.com/patil-suraj/question_generation)). Next, the system must generate a series of hints based on the correct answer to the created question and based on the received user answers. If user answers are incorrect (which is expected) the goal is to automatically provide hints which do not contain the ready answer but which help the user come up with the correct answer. The hints should not be too obvious but should lead the user to find the answer in small number of steps (few generated hints) by progressively revealing more data related to the answer. Hints will be generated using Wikipedia as knowledge base, as well as the original question, the correct answer and the sequence of user answers for previous hints as an input.

Prerequisites: knowledge of text processing, and interest in history or education





For more details on research in the data science lab check: [Homepage of Adam Jatowt](https://adammo12.github.io/adamjatowt/).


