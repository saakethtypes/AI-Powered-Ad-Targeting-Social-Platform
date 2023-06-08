# AI-Powered-Ad-Targeting-Social-Platform

The goal of this project is to create a personalized product recommendation system based on user interests extracted from image captions. Users can perform actions such as liking images or uploading images, which will be sent to an image captioning model to generate captions. The subjects and nouns extracted from these captions will be stored as user-specific interests. These interests will then be used to generate potential product recommendations using OpenAI. The product recommendation list will be displayed to users, and the interests database will be used to show relevant ads to users with similar interests.



Utilizing the ViT-GPT2 visual transformer model as the core image captioning model for extracting meaningful insights from image captions.
Implementing user interactions such as image liking and uploading through AWS Lambda for API services, and storing relevant data in AWS DynamoDB for efficient database management.
Employing Snowpark in Snowflake to store generated captions as User-Defined Functions (UDFs) for streamlined access and retrieval.
Utilizing TextBlob for noun extraction to extract subjects and nouns from the captions, enabling the creation of user-specific interests.
Leveraging OpenAI's LLM API to generate potential product recommendations based on user interests, ensuring personalized suggestions.
Displaying the product recommendation list to users, enhancing their experience and increasing engagement.
Utilizing the interests database to display relevant ads to users with similar interests, enhancing targeted advertising efforts.
Conducting Exploratory Data Analysis (EDA) on user clicks, analyzing patterns such as user clicks on specific product categories at different times of the day.
