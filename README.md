# ML-Robustness-Model-Inversion-attack
The solution measures the robustness of an image classifier against model inversion attack while having black box access to the classifier

## Product Overview
As machine learning models gain prominence in various enterprise applications, privacy of data has become a growing concern. Model inversion attacks aim to infer sensitive information about data by exploiting the model's output. This is achieved by iteratively guessing the exact input data features based on the model's outputs. For example, if a model is trained to predict a person's income based on their education, experience, and other factors, an attacker can use the model's output (predicted income) to infer the person's education, experience, and other sensitive information. This solution takes an image classifier and gives the robustness of this classifier against model inversion attack.

## Product Highlight 

* The solution evaluates the model's vulnerability to inversion attack by simulating the attack and analyzing the model's output. To simulate the attack, user needs to input the target class label to be attacked. The solution generates images of target class and calculates the similarity of these images with actual image of that class. These similarities show the robustness of model against model inversion attack against the target class. The higher similiarity scores indicates the lesser robustness of model against inversion attack.
* The solution requires the keras model file of Image classifier and the original image of target class. The solution performs black box attack on the model i.e, only the model's ouput is accessible, and, not the internals of the model. The user can control the number of  iterations of gradient computations to be performed to generate image of  desired class. The similarity score of generated image to the acutal image of the target class measures the model vulnerability.  
* PACE - ML is Mphasis Framework and Methodology for end-to-end machine learning development and deployment. PACE-ML enables organizations to improve the quality & reliability of the machine learning solutions in production and helps automate, scale, and monitor them. Need customized Machine Learning and Deep Learning solutions? Get in touch!

## Amazon Marketplace Link
The product can be found [here]().
