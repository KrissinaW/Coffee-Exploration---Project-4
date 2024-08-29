# Coffee-Exploration

Project-4

Whether you're a casual drinker or a coffee connoisseur, this tool aims to make your coffee selection process both enjoyable and tailored to your specific needs.

![istockphoto-1467739359-612x612](https://github.com/user-attachments/assets/07b6ed75-a47f-4ccc-98c9-71dc4500d0ae)

*Image credit: [istockphoto.com](https://www.istockphoto.com/photos/coffee)*

## *Description:*

This project leverages a comprehensive dataset of coffee, encompassing various categories such as type, cost, origin, flavor profile, and more, to build an interactive recommendation model. The model is designed to analyze consumer preferences entered into the system—such as desired taste, budget, and preferred coffee origin—and output personalized coffee recommendations. By utilizing advanced data analysis and machine learning techniques, the model helps consumers discover new coffee varieties that align with their tastes and preferences, offering a unique, customized coffee-buying experience. 

## *Technologies Used:*

### - Lucid Chart-Flow Chart:

  Our [process flow chart](https://lucid.app/lucidchart/fd780518-75bf-4bc6-890b-131cea1d39eb/edit?view_items=pWN5zXSXMqBs&invitationId=inv_c2623e5c-ff20-4a38-9f1d-3fc05ed588fa) was created as a visual tool to assist with project management, ensuring that each stage of our project is clearly defined and efficiently executed. The chart outlines the key phases of the project, from problem definition and data collection to model deployment and reporting. By assigning specific tasks to team members and visually representing the workflow, the chart helps us track progress, manage tasks effectively, and maintain clear communication within the team. This structured approach ensures that all project elements are aligned and contributes to a successful outcome.

### - Data Collection and Processing:

We scraped data from [The Coffee Review.com](https://www.coffeereview.com/), ensuring that we followed legal guidelines for data usage. After extracting the relevant information, we cleaned and processed the data to remove any inconsistencies and prepare it for analysis. This process involved normalizing pricing formats, handling missing values, and structuring the data effectively, resulting in a reliable dataset ready for further exploration.

### - Data Cleaning and Analysis:

### - Machine Learning:
  
    #### - Feature Engineering
      
We preprocessed the text descriptions to enhance model performance by converting text to lowercase, removing punctuation and stopwords, and applying stemming. The ratings for Aroma, Acid, Body, Flavor, and Aftertaste were doubled from a 0-10 scale to a 0-20 scale to increase prediction granularity.
 
    #### - Initial Model Development
    
The dataset was split into an 80% training set and a 20% testing set. We built a machine learning pipeline that includes scaling, text transformation, and encoding steps, with a RandomForestRegressor used to predict the quality ratings across multiple targets.

    #### - User Input and Prediction
    
The final model allows users to input coffee details (cost, origin, roast level, description) and receive predictions for the quality ratings based on the trained model.

### - Dashboard:

### - Word Cloud:

 We created the word cloud by first selecting relevant text data column and then cleaning it by removing common stopwords, punctuation, and converting everything to lowercase for consistency. We then calculated the frequency of each word to determine its prominence in the word cloud. Using a word cloud generator, we input the processed text, adjusting the shape and colors to highlight key themes. The result visually represents the most frequent terms, allowing for a quick grasp of the main ideas within the dataset

### - Final Project Presentation:

For the final presentation, we used Google Slides to organize and present our findings in a clear and visually engaging way.

## *Looking Ahead:*

### Possible Improvements: 

### Ideas for Development

### Project Expansion:
Looking ahead, after the coffee exploartion project, we see an opportunity to expand our research into the impacts of climate change on coffee production. By studying how changing climates affect coffee-growing regions, we could explore ways to predict and mitigate these effects, contributing valuable insights to both the coffee industry and broader environmental discussions.
