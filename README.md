# CollegeAdmissionPredicter
 Predict chances of a student's college admission based on 2 exam scores


===== DESCRIPTION ===== 
 
These are OCTAVE files (i.e., similar to MATLAB), largely based on matrix operations implementing logistic regression to predict if a given student will be admitted to a university based on the results of two prior exams.  The total size of the data (sample) set (X) is 100 x 2, with each row representing the results of two tests for each of 100 students.
 
 
===== HOW TO USE =====

Type (without quotes) "admissionPredict" in the Octave Command-Line Interface (CLI).  

You will first see a plot of students who were and were not admitted as a function of their prior exam scores in Figure 1, accompanied by both the computed and expected costs and gradients of the first 5 samples in the CLI; these were calculated with initial theta values of zero.  Next, you will see the computed and expected costs and gradients for the first 5 samples with different test theta values.  A final plot will be shown in Figure 2 that displays the resulting decision boundary.  Finally, an admission probability prediction will be made for a hypothetical student with exam scores of 45 and 85, and the training accuracy is displahyed (89% for this specific project).


===== CREDIT =====

This project was based on week 4 programming assignment of Coursera's Machine Learning course by Stanford University's Andrew Ng.  Enjoy! 

