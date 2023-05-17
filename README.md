# i-POP-Interpretable---Probability-of-Payment-model

- The Probability of Payment (POP) model is a risk scoring model that calculates a POP estimate for each  credit contract at origination.
- Inherently interpretable models provide accurate explanation but sacrifice model performance to an extent.
- To combat, we developed a high-performing intrinsically interpretable POP model (i-pop) using an explainable neural network (xNN)  based on Generalized Additive Models   with structured Interactions (Yang et al,2021).   
- ROC (train -95.81 % & test -81.4 %) show that i-pop model has high discriminatory power than the current models.
- DeLong's test show that the AUCs of the current and previous models are statistically different.
- The model is deployed in the GCP -Vertex AI environment. 

Conference presentation:

iPOP : Interpretable Probability of Payment ModeliPOP : Interpretable Probability of Payment Model
3rd Ford Artificial Intelligence and Machine Learning Conference (Ford Greenfield Labs, Palo Alto, CA) · Dec 7, 2022

 <a href="https://github.com/sprasadhpy/i-POP-Interpretable---Probability-of-Payment-model/blob/main/i-POP%20Interpretable%20%20Probability%20of%20Payment%20model.pdf" target="_blank">Slides</a>

 <a href="https://github.com/sprasadhpy/i-POP-Interpretable---Probability-of-Payment-model/blob/main/015-video.mp4.mp4" target="_blank"> Presentation Video</a>

<a href="https://github.com/sprasadhpy/i-POP-Interpretable---Probability-of-Payment-model/blob/main/UK_COMM_(Latest)%20(Rahul).ipynb" target="_blank"> Notebook </a>

Number of main and interaction effects in the i-POP model


![Number of main and interaction effects](https://user-images.githubusercontent.com/40602129/219279477-b4842114-d152-40d6-aefa-53ae18d98980.png)


 Main effects Feature importance plots: 
![Feature _importance plots](https://user-images.githubusercontent.com/40602129/219279972-de27b7cc-3da2-45f1-9801-eea7a340ea3f.png)

Interaction effects- Feature importance plots: 
![Feature _importance plots2](https://user-images.githubusercontent.com/40602129/219280102-ab8f7812-9709-4998-a3a8-6ad002cd514a.png)
