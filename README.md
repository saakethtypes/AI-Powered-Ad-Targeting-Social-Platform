# AI-Powered-Ad-Targeting-Social-Platform

* The goal of this project is to create a personalized product recommendation system based on user interactions on posts on a social media paltform. 
* Users can perform actions such as liking images or uploading images, which will be sent to an Visual Transformer image captioning model to generate captions. 
* The nouns extracted from these captions will be stored as user-specific interests. These interests will then be used to generate potential product recommendations using OpenAI.
* The product recommendation list will be displayed to users, and the interests database will be used to show relevant ads to users with similar interests.
* Utilizing the ViT-GPT2 visual transformer model as the core image captioning model for extracting meaningful insights from image captions.

## Tech Stack 
* Implementing user interactions such as image liking and uploading through AWS Lambda for API services, and storing relevant data in AWS DynamoDB for efficient database management.
* Employing Snowpark in Snowflake to store generated captions as User-Defined Functions (UDFs) for streamlined access and retrieval.
* TextBlob for noun extraction from the captions.
* Leveraging OpenAI's LLM API to generate potential product recommendations based on user interests, ensuring personalized suggestions.
* Conducting Exploratory Data Analysis (EDA) on user clicks using plotly, analyzing patterns such as user clicks on specific product categories at different times of the day.
  
## Project Flow
![download (1)](https://github.com/saakethtypes/AI-Powered-Ad-Targeting-Social-Platform/assets/47172497/b6572bd1-abe6-4b98-8eed-d1832b4c5403)

Documentation - https://codelabs-preview.appspot.com/?file_id=18qScGcxVTydmxhaIO8eRmhzS3TcmaczcPK5606xLQdM#0

## Flow
User Action -> Liked post of the woman sitting on the beach
![s](https://github.com/saakethtypes/AI-Powered-Ad-Targeting-Social-Platform/assets/47172497/98bc727a-7545-4eb3-9b3c-5ca240a29d3b)

Image processing -> Fetched relavant Ads
![ss](https://github.com/saakethtypes/AI-Powered-Ad-Targeting-Social-Platform/assets/47172497/28095c5b-f6be-41dd-bb3e-43e8771f05fa)
