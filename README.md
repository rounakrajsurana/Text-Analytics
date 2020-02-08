# Text-Analytics
A course evaluation is a paper or online survey that includes a response to a number of
questions written or chosen to determine the curriculum of a specified course. In academic
institutions, course evaluation at the end of each semester is normal, which includes quantitative scores such as rating scale and qualitative such as open-ended questions/text comments
which aim to study the sentiment of the students on course/instructor characteristics. The
quantitative scores give a brief about review on the course whereas qualitative content gives
a more accurate view about the course, helping instructors in improving the quality of the
course and learning experience of students. However, going through all the qualitative content manually and finding the sentiment of the students is a tedious task to achieve.

This research study addresses the problem by finding the sentiment of course evaluation in
the form of text comments given by students. The implemented method for solving the problem comprises data pre-processing, classification of the sentiment with the use of different
classification algorithms such as **Support Vector Machine (SVM), Multinomial Naive Bayes
(MNB), Decision tree (CART), XGBoost, Stochastic Gradient Boost**. The implemented solution also leverages the visualization of the
text comments.

Evaluation of the method and visualization is done on student’s feedback comments by the
courses taught in ICT department, Asian Institute of Technology helping the instructors in
understanding the sentiment of the students. Student feedback comments concentrate on
4 different aspects they are: course characteristics, instructor characteristics, course delivery/teaching methods/resource materials, and overall assessment. Applying the solution to
classify the sentiment of qualitative data on two courses with the highest number of comments, SVM works the best in finding the sentiment on course evaluation with an accuracy
of 78.2% and visualization of the text comments is done using word cloud helping the instructor in finding the opinion of students.
