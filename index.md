# Inroduction

Display advertising can give the company much more benifit. Modern advertising recommendation mechanism predict the users' behavior by predicting advertisement Click-Through Rate (CTR). By giving a user and the page he is visiting, the algorithm will come with the probability that he will click on the given advertisement. The algorithm would make a huge profit to the companies by doing this.

The algorithm would help the company to meet the users' needs and make the functions efficient. For those multi-media companies like YouTube and Tiktok, it would help them put the related advertisement into specific videos which would increase the possibilty the user clicks on the advertisement and buys the related products. For those online shopping websites like Amazon and eBay, the algorithm can also be used to recommend related items based on the items the user is browsing. By using the algorithm, the user would get a better user experience in using the product which would bring more possibility for the sellers to sell their products and offer their services.

The project is a recommendation model, even though we are predicting CTR. We would like to show the potential users the advertisements have higher probability to be clicked. It is the recommender system which is considered one among the most powerful tools in the present digital world. In the field of recommender systems there are various methods and approaches which have been implemented. We use xDeepFM and AFM in our project. They are a state-of-the-art algorithms which has been widely used in industry.

# Algorithms Detail
## xDeepFM
### Model Structure

xDeepFM use a Compressed Interaction Network (CIN) to learn both low and high order feature interaction explicity and use a Multilayer Perceptron (MLP) to learn feature interaction implicitly. In each layer of CIN, first compute outer products between ![x^k](https://user-images.githubusercontent.com/49369552/117372253-d3e5a900-aefb-11eb-9085-19fcba04317a.png)
 and $x_0$ to get a tensor $Z_{k+1}$, then use a 1D convolutional layer to learn feature maps $H_{k+1}$ on this tensor. Finally, apply sum polling on all the feature maps $H_k$ to get one vector. The vector is used to compute the logit that CIN contributes.
### Results

## AFM
### Model Structure

### Results

