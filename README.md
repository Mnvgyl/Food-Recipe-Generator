# Food-Recipe-Generator
This project, no surprises here, is related to food. So if you’re not already intrigued, hold your horses, you soon will be. Here, I worked towards building a product that takes in a food picture as input and generates a recipe and the cherry on top is that it assesses the given meal to see if it’s nutritious.

We know that food is fundamental to the human experience. It has deep ties to our health, our livelihood, our emotions,and our culture. More and more these days, people want to learn about what they are eating in order to make better nutritional decisions, but many struggle to find a place to start. Our application aims to empower people to better understand and have control over their food intake in order to help achieve their health goals.

1) Dataset: Used kaggle based dataset from website called food.com. This dataset did not contain images but image URLs. In order to get access to the images, I built an Image scraper using REST APIs. The final data set which was divided into files: Image dataset (15 GB) and Recipe dataset (1.5 GB).

2) Data Processing: Dropped irrelevant columns to our problem statements such as user ratings and reviews from the recipe dataset, records that didn’t have an image URL.

3) Model: Leveraged 
