
## Automated Prediction of Item Difficulty and Item Response Time for ACL Sig-edu shared task 2024

#### Problem Statement:
Motivation For standardized exams to be fair and valid, test items must meet certain criteria. One important criterion is that the questions should cover a wide range of difficulty levels to gather information about the abilities of test takers effectively. Additionally, it is essential to allocate an appropriate amount of time for each question: too little time can make the exam speeded, while too much time can make it inefficient. Typically, item difficulty and response time data are collected via a process called pretesting, where new items are embedded in live exams alongside scored items. While robust, this process of collecting item characteristics data is time-consuming and expensive. As noted by Settles et al. (2020), “This labor-intensive process often restricts the number of items that can feasibly be created, which in turn poses a threat to security: Items may be copied and leaked, or simply used too often”.

To address this challenge (also referred to as the “cold-start parameter estimation problem” (McCarthy et al., 2021)), there is growing interest in predicting item characteristics such as difficulty and response time based on the item text. Such estimates can be used to “jump-start” parameter estimation by exposing the item to a smaller sample of test-takers, or improve fairness by reducing the time variance for forms that include pretest items (Baldwin et al., 2020).

Due to difficulties with sharing exam data, efforts to advance the state-of-the-art in item parameter prediction have been fragmented and conducted in individual institutions, with no transparent evaluation on a publicly available dataset. In this Shared Task, we bridge this gap by sharing practice item content and characteristics from a high-stakes medical exam called the United States Medical Licensing Examination® (USMLE®) for the exploration of two topics: predicting item difficulty (Track 1) and item response time (Track 2) basured in seconds.

reference : https://sig-edu.org/sharedtask/2024
