# Saving-Our-Oceans-with-AI
Link to slides can be found [here](https://drive.google.com/file/d/1tk-sh_Oxp-AWKGXWnT9af0dauIiRyULG/view?usp=sharing)

## ![Introduction](https://drive.google.com/uc?export=view&id=1-K_H17HbCU8n2htvaljvRXM2zEWbiE9u)
'The earth is what we all have in common', a quote by Wendell Berry. This project leverages on AI and MapBox APi to locate, detect and quantify plastic debris in our oceans.

## Inspiration for this challenge

A friend participated in a Global Clean Up Challenge last month and I was motivated by her passion to clean up the environment from plastic pollutants.

## Problem

No proper monitoring and detection system of plastic debris in the oceans

## Solution

An app that leverages on GIS systems to locate, detect and quantify plastic debris in the oceans.

## How does it work?
Web App![Web App](https://drive.google.com/uc?export=view&id=1oTzJGmoGJ-xRZCLB34jbEV1xF1nShDD1) --> AI Model ![AI Model](https://drive.google.com/uc?export=view&id=1HpURkdrk3zFI2ESbZxC88JAsbJEDT0_w) --> Prediction ![Prediction](https://drive.google.com/uc?export=view&id=1v--6i1LY05c_cPe6Qo3qGYuEoNtmTUM2)

Open the Web App --> Take Screenshot of the location --> Send to Model --> Model predicts plastics and quantity --> Sends the results back to the web app

The app can be divided into two:
1. Streamlit app which houses both the Google Earth Engine API and the AI model.
2. AI model + TOPEX/POISEDON data

### AI model

Three processes were 
1. Data Annotation 
![Data Annotation](https://drive.google.com/uc?export=view&id=1i8PCg9SoP7aliPjgzsH9tAIKdg0mXggY)
Mask ![Mask.](https://drive.google.com/uc?export=view&id=1Ru7kXZPYpWbvp6ca8skKNDaKdLDeoiiB)

2. UNet Model Architecture. 

 ![UNet Model Architecture.](https://drive.google.com/uc?export=view&id=1tk_vZibS0E8wkMsh88n-BQab9Ru7kPOm)
This model architecture was used to build the AI model. U-Net is  a convolutional neural network architecture for semantic segmentation that expanded with few changes in the CNN architecture. Looks like a U, from the name though!

3. Results
![Results](https://drive.google.com/uc?export=view&id=1YfNeLlxHEQdWbS0V6ySx91j0GLsUJ9bL)
![Results](https://drive.google.com/uc?export=view&id=1NHqHfwbiHhEdJ_rsdqfaRubSWR-3Jn_L)

## Impact of Our solution

1. To Environmental Protection Agencies: Monitor the rate of garbage dumps in the oceans
2. To Scientists: Identify regions and areas with plastic dumps 
3. To Sea Creatures: Save sea creatures life as they'll be able to breath and move freely.

