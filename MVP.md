# Phishing Websites Classification 
The goal of this project is to build the best model that can compare and differentiate between phishing and non-phishing links based on the link's features.

To meet the expectations of the project's goal, First we balance the data as you can see in the below graph, it represents which links are phishing and which aren't.

<img width="484" alt="Screen Shot 2021-12-15 at 8 58 16 PM" src="https://user-images.githubusercontent.com/93079431/146240024-cbd2d9b2-78d5-4419-90fb-2d5559825342.png">

We used different classification models to determine which one fits the best.
Therefore, we take the features that affect the models and check the importance of them listed by the top 15.

<img width="1018" alt="Screen Shot 2021-12-15 at 9 11 01 PM" src="https://user-images.githubusercontent.com/93079431/146241820-89c78881-d99a-4223-bc88-71a0e533c73b.png">

From this analysis, We can figure out that the most effective features are "The quantity of the slashes in URL" which is the highest one then comes the "Directory length" and "The quantity of the slashes in the directory".. etc

All these features consider as a red flag to notify and warn the user about the links if they are suspicious to be phishing or not.
