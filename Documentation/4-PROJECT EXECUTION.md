# 👓 PROJECT OVERVIEW

## D. EXECUTING THE PROJECT

## Flowchart



## Chatbot Implementation 

1. Start by creating an agent on Dialogflow
<img width="368" alt="image" src="https://user-images.githubusercontent.com/55356959/150527260-ab4ef39b-027e-4f51-8054-cd9825ef2cff.png">

2. Create intents with suitable names
<img width="593" alt="image" src="https://user-images.githubusercontent.com/55356959/150527353-b61da8b8-f0a6-4de3-96c1-5f9939b245f3.png">

Intents can be hardcoded or created via GUI. These are the intents created by our team for this project.

<img width="610" alt="image" src="https://user-images.githubusercontent.com/55356959/150528142-dbb94d98-3f63-405e-b7bd-af4f7d32496c.png">

3. Inside the intent you may customise many user esperience outputs such as quick replies, adding images and useful hyperlinks.
   Due to space constraint using images as there are many intents which contains parameters and responses, the hardcoding produced by our team in this project under the `intents`    and `entities`, here we have fully customised every intent file in our chatbot to its functionality.
   
4. Create a knowledge base

<img width="606" alt="image" src="https://user-images.githubusercontent.com/55356959/150529069-8ba28398-1ee2-4188-86e9-9d039c707c11.png">

This is a snippet of the FAQ we scraped from the WHO and MOH website.

<img width="598" alt="image" src="https://user-images.githubusercontent.com/55356959/150530269-645286a1-a708-4150-9b73-2a28df8d63b1.png">

There is a total of 50 questions scraped as most of it are not Malaysian based and or repeating.
The knowledge base file can be found under `covid_FAQ - covid_FAQ.csv`


5. Train and test the Chatbot. Can be done on GUI for time conservation purposes. 

Training :

<img width="597" alt="image" src="https://user-images.githubusercontent.com/55356959/150530605-b1cecb55-a80e-4168-a020-383d39e8a57a.png">

 GUI testing:
 
<img width="177" alt="image" src="https://user-images.githubusercontent.com/55356959/150530497-241dada7-52e1-410b-8f66-51d3de67bce5.png">

## Chatbot deployment

Deployed on Telegram for easy access.

1. Choose Telegram integration

<img width="593" alt="image" src="https://user-images.githubusercontent.com/55356959/150532629-25599afb-2ddb-4da6-9194-b02480585a6f.png">

2. Save the given token.

3. Deploy on telegram using BotFather and choose appropriate username

<img width="593" alt="image" src="https://user-images.githubusercontent.com/55356959/150538935-e1bad59a-1d69-41bd-93dc-e9a3fb0f29de.png">

---
