# mushroom-edibility

For this project, I took information surrounding the attributes of mushrooms to determine whether they were safe to eat or poisonous. I used a random forest selection and were able to create a model with 100% accuracy and reduce the amount of features it took significantly to save on required space to run. Once done, I dropped in some test data to determine the edibility of these new mushrooms. This can be found in the file titled, "Mushroom Classification".

Next, I took a quick look into how some key features correlated to the edibility of mushrooms from our sample set and was able to identify 2 gill colors whose mushrooms were 100% poisonous and another 2 whose mushrooms were 100% edible which would be useful information to have should you find yourself lost in the forest with only mushrooms to eat. I also looked at gill size and found a pretty significant difference in relative edibility between the two classifications. Lastly, I observed how cap color impacted the odor of mushrooms and found 2 cap colors that always had the same odor. That file is titled, "Mushroom Data Deep Dive".

Source Data: https://www.kaggle.com/datasets/ulrikthygepedersen/mushroom-attributes?resource=download
