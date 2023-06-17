# FCM-Topic-Modelling
Code for the bachelor thesis of Maria Mouratidi, for the program of Cognitive Science snd Artificial Intelligence at Tilburg University. Spring Semester 2023.

All content presented in this work is my original creation, and I hold the rights to it. Any form of plagiarism or unauthorized use of this work is strictly prohibited. Proper citations and references have been provided for external sources used. 


### Abstract

Social media are an integral part of the modern world. Much of socialization, opinion exchange, and news sharing has shifted from traditional environments to social media platforms. Analyzing social media interactions can be fruitful in discovering online community dynamics or enhancing marketing techniques. For this reason, this study suggests a viable way to extract topics of interest from social networks and bring latent topic interactions to the surface. This objective is achieved with Fuzzy Cognitive Maps, which can elegantly simulate topic evolution scenarios. The use of Fuzzy Cognitive Maps is motivated by their potential to enhance network visualizations and offer more interpretability to the findings. The suggested pipeline specifically uses Latent Dirichlet Allocation to extract latent semantic topics from Twitter posts and Association Rule Mining to establish the association weights between topics. Finally, simulation scenarios are defined and topic presence dynamics are simulated with the aid of the association weights and an evolution function. The current model suggests that introducing a medium non-linearity degree to the evolution function brings the most balance between topic dynamics. Indeed, topics with manually induced presence tend to maintain a high presence while also allowing for more popular topics to dominate. Moreover, regardless of the initial activation of each topic, all topics span a confined range of activations throughout iterations. This suggests that specific presence patterns are encoded during the weight derivation process. Finally, the limitations of this study are discussed along with potential solutions. 

![methodology](https://github.com/codingraven/FCM-Topic-Modelling/assets/101043648/81ab9c5f-1903-4378-ab9c-f8858c534c79)
