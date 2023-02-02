
# Advertisement Analysis




## Business Problem

- Companies show ads to promote their products or services to a large audience and increase brand awareness. By showing advertisements, companies aim to attract new customers, retain existing ones and generate more sales and revenue. Advertisements also help companies differentiate themselves from their competitors and create a positive image in the minds of potential customers.

- That's why it's  very crucial to recommend the most relevent advertisements to customers so that the chances they'll buy the product will increase significantly.
## Aim

Recommending the most relevent Advertisement to users in order to to get maximum  click through rate (CTR)
## Approach














## Data Cleaning

- First data  cleaning 

- It includes dealing with outliers and missing values 
## EDA

- Second part is Exploratory Data Analysis (EDA) .

- Here we'll explore the data to get as much insights we can get from  it.
## Model Building

- Here we'll feed the cleaned data to the machine learnning model to predict the future senario.
## Results 
## EDA results


## Campaign analysis

- Among all campaigns campaign 359520 has reached   maximum people  .

- Campaign 405490 has achieved 2nd best success among all and campaign 360936 has 3rd best success among all in terms of reach.

- The plot below shows how every campaign has performed.



![ad-1](https://user-images.githubusercontent.com/72175654/216300947-b8f2a5df-d58a-40b4-9eb3-053f11706bd6.png)

- The plot below shows the relative success of the campaigns than the previous year.

![ad-2](https://user-images.githubusercontent.com/72175654/216300930-80f8853e-d79d-4915-b92a-67c9501dcd6b.png)

- Relatively speaking campaigns 360936 , 396664 and 414149 performed poorly as compared to their previous campaigns.
- It's advised that they  revert back to the previous strategies that made the previous campaigns successfully reach more people.

- In terms of how many people have actually clicked the advertisement campaign 405490 has performed the best and campaign 359520 performed 2nd best in terms of number of pleple clicking the advertisement as it's evident from the plot below.

![ad-3](https://user-images.githubusercontent.com/72175654/216300936-26292f91-95f5-4fd1-857a-4c31c33ad60a.png)

- But in terms of percentage of people clicking the advertisement compared to total number of people who saw the advertisement 405490 still performms the best with  **9.13%** CTR , 2nd is campaign 404347 with **7.75%** CTR and 3rd is 98970 with **7.68%** CTR.

![ad-4](https://user-images.githubusercontent.com/72175654/216300941-a94b89ba-99fd-4797-84d7-a5f8fa438c91.png)

## Model results

I've trained a Random Forest Classifier model which successfully predicted whether the user click the advertisement or  not with **93.1%** accuracy.

## Conclusion

From the EDA we got to know that campaign 405490 has performed best in terms of Click through Rate (CTR) that is **9.13%** and we should continue to use the same strategy we've used in that campaign in order to maintain that CTR until a better model comes into action.
