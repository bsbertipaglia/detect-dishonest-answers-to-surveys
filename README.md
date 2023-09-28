*prj*: project code  
*Report*: project paper  
*folders*: datasets  

# Detect Dishonest Answers to Surveys using Machine Learning

Lying can be defined as the act of hiding the truth using a false statement with the intention to make someone else believe it. The evaluation of a statement to detect dishonesty is known as ***lie detection***.  
The aim is to address the ***reliability problem*** and mitigate it by finding a reliable feature selection criterion, i.e. a model that always gives similar importance to features, which, at the same time, gives good performance in lie detection.

Not all feature selection techniques are good in terms of reliability, but among those that are, there is no benchmark method that outperforms all others in every dataset. There are, however, some good candidates who appear to be reliable across all datasets tested.  
More in detail, ***Model Agnostic techniques*** and ***Psychometric Inspired techniques*** are tested and their performances are compared over the available datasets. For each of the proposed methods two metrics are used for evaluation: firstly their *accuracy score* and secondly their *"robustness index"*. The attention will be more focused on the second point, i.e. the best choice is a compromise between the two measures, with a greater weight for the robustness of models.  
The conclusion reached is that, comparing the average results obtained on all datasets, the best performance in terms of accuracy is given by Model Agnostic techniques, but at the same time they show worst results in terms of robustness. Psychometric Inspired techniques, instead, show better values for the robustness index while they reach smaller accuracy scores.  
Following the goal of finding the best trade-off, the conclusion is that good results can be obtained, on average, using Psychometric Inspired techniques.
