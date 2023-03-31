# Vasu-Khanna-BYOP-23
Raw code written and executed at Google Colab :
FOR END-EVALUATION : https://colab.research.google.com/drive/1MVInaCIV1e6-wl8eQYNFZxDdpwdni7Tz#scrollTo=4I1UOMg9Lpo7                             
SECONDARY GOALS : https://colab.research.google.com/drive/1rZsGGzT0ODys4J72z4R8XwwISMivBYq_#scrollTo=8Uwn4Lte_eEM    

I have finished the code for LDA model, trained the model, tuned the model, calculated the Coherence Score
( it came out to be 0.37524 compared to the optimal value of 0.454) and also I finished the part of secondary goal which was the sentiment analysis of the reviews. 
I have created Flask Interface for Secondary goals part but it might not display any rating beacuse of some bug & I could not correct it as of the time of submission but I will surely fix the bug asap & will merge the two files to create a final model which can show both the proportion of words in the review as well as the nature of the review( +ve/-ve ).
My Flask API Link : http://127.0.0.1:5000
I have attached all the files I created & used.
 
How to interpret the LDA model ?                                                  
The given image shows the output of an LDA model which shows the AVERAGE TOPIC COHERENCE along with the tokens(words) with their proportions in the document we created in LDA.
![image](https://user-images.githubusercontent.com/117103753/229208053-6ccce290-2f5c-4803-b897-b84f470f2ae4.png)
The image below shows the visualisation of the topics created using the python pyLDAvis library . Just move the cursor on the topics shown in circle to see the frequency of the different terms.
![image](https://user-images.githubusercontent.com/117103753/229208971-b70221e4-03c6-47e7-bb98-18d1118431eb.png)
Happy Topic Modelling :)
