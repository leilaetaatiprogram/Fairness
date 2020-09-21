# Responsible machine learning principles
## Understand machine learning models
* Interpret and explain model behavior
* Assess and mitigate model unfairness
## Protect people and their data
* Prevent data exposure with differential privacy
* Work with encrypted data using homomorphic encryption
## Control the end-to-end machine learning process
* Document the machine learning lifecycle with datasheets

![Alt Text](https://docs.microsoft.com/en-us/azure/machine-learning/media/concept-responsible-ml/responsible-ml-pillars.png  )



# Fairness in Machine Learning 
As AI systems become more involved in the everyday decision-making of society, it's of extreme importance that these systems work well in providing fair outcomes for everyone.

## Unfairness in AI systems can result in the following unintended consequences:

* Withholding opportunities, resources or information from individuals.
* Reinforcing biases and stereotypes.
 Many aspects of fairness cannot be captured or represented by metrics. There are tools and practices that can improve fairness in the design and development of AI systems.
 
 ### Two common types of AI-caused harms are:

* Harm of allocation: An AI system extends or withholds opportunities, resources, or information for certain groups. Examples include hiring, school admissions, and lending where a model might be much better at picking good candidates among a specific group of people than among other groups.

* Harm of quality-of-service: An AI system does not work as well for one group of people as it does for another. As an example, a voice recognition system might fail to work as well for women as it does for men.

To reduce unfair behavior in AI systems, you have to assess and mitigate these harms.
# Fairness in Machine Learning: ![Alt Text](https://i1.wp.com/sitn.hms.harvard.edu/wp-content/uploads/2020/01/image003.png?resize=1024%2C779)


# Fairness assessment and mitigation with Fairlearn
Fairlearn is an open-source Python package that allows machine learning systems developers to assess their systems' fairness and mitigate the observed fairness issues.

_group fairness_
* Which groups of individuals are at risk for experiencing harms? `<sensitive_features>`
During assessment phase, fairness is quantified through _disparity metrics_.
 Disparity metrics can evaluate and compare model's behavior across different groups either as ratios or as differences.
