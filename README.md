# DataScience
Fun with data, while learning Python, numpy, pandas, matplotlib, scikit, TensorFlow & more.

(*Please note that these are just snippets of very simple code intended to test and learn, if it was intended for production it would be properly formatted and documented.*)

- [An automated STEAM review analyzer using GPT (OpenAI)](#an-automated-steam-review-analyzer-using-gpt-openai)
- [A love poem generator using GPT-3 and DALL-E (OpenAI)](#a-love-poem-generator-using-gpt-3-and-dall-e-openai)
- [Dog breed identification from a photo](#dog-breed-identification-from-a-photo)
- [Animated GIS Map of Canada and the US](#animated-gis-map-of-canada-and-the-us)
- [Quebec's Covid data](#quebecs-covid-data)

## An automated STEAM review analyzer using GPT (OpenAI) 
I explored the possibility of automating the analysis of Steam reviews and creating a summary of the most common issues reported by the users (providing the review ids and relevant keywords). The result is not perfect, but keep in mind that this is just with GPT-3, ChatGPT (GPT-3.5) or GPT-4 would probably give much  better results and would also permit to include many more reviews. [Google Colab Project](https://github.com/BenoitFries/DataScience/blob/main/Automated_Steam_review_analysis_with_GPT.ipynb)

![An automated STEAM review analyzer using GPT](https://github.com/BenoitFries/DataScience/blob/main/GPT_Steam_Reviews.png?raw=true)

## A love poem generator using GPT-3 and DALL-E (OpenAI)
Being a great romantic, I delegated the creation of love poems to GPT, with illustration by DALL-E. I'm sure that my wife will be delighted! [Google colab project](https://github.com/BenoitFries/DataScience/blob/main/An_illustrated_love_poem_generator_using_GPT_and_DALL_E_(OpenAI).ipynb).

![A love poem generator using GPT-3 and DALL-E](https://github.com/BenoitFries/DataScience/blob/main/poems.png?raw=true)

## Dog breed identification from a photo
This was part of the "[Complete ML & Data Science bootcamp 2022](https://www.udemy.com/course/complete-machine-learning-and-data-science-zero-to-mastery/learn/lecture/18041737#overview)", with a dataset of 10K labelled dog images + 10K unlabelled test images from Kaggle. We use TensorFlow 2.0 to train a Deep Learning model using Transfer Learning. [Google colab project](https://github.com/BenoitFries/DataScience/blob/main/dog_vision.ipynb).

![Dog Breed Identification](https://github.com/BenoitFries/DataScience/blob/main/dogvision.png?raw=true)

## Animated GIS Map of Canada and the US
I wanted to try GeoPandas, so I created a map by combining two different GIS sources, and added a layer with drought data over it. [Link to Jupyter Notebook](https://github.com/BenoitFries/DataScience/blob/main/GIS%20Map%20of%20US%20and%20Canada%20with%20drought%20data.ipynb).

![NorthAmerica_Map_Drought](https://user-images.githubusercontent.com/40205456/146647247-047bbc31-a9e5-4555-9185-2a9ccc8380db.gif)

## Quebec's Covid data
The graphs we usually see with just the cases can give the impression that things are getting worse, each wave getting bigger than the previous one. Adding deaths (dot colors) and CFR (red line) tells a different story. At the beggining of the pandemic we had more that 1/8th of the cases ending in death, and now it's less that 1/500th. This is us getting better at detecting covid cases, protecting and treating the vulnerable, and vaccinating. [Link to Jupyter Notebook](https://github.com/BenoitFries/DataScience/blob/main/Exploring%20Quebec's%20COVID%20data.ipynb).

![QC_Covid_Cases_and_Deaths](https://github.com/BenoitFries/DataScience/blob/main/QC_Covid_Cases_and_Deaths.png?raw=true)

