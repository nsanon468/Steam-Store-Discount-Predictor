Project Title: Steam Store Discount Predictor
Description: Takes a Steam AppID as input and prints the probability of a discount for that specific title within the next 18 days.
Data Source: Obtains the title of the game, via the AppID, from Steam. Obtains price history data from isthereanydeal.com, using their API. 
Requirements: Pandas, NumPy, scikit-learn, and requests.


final_steamsaleproject.ipynb is the final, working product.

echo_steamsaleproject.ipynb is a relic project - I had the idea to load all of the other games released by the publisher of the target game and use them in the prediction algorithm. However, it was clear after testing that it exclusively introduced background noise data and worsened the regression model so I abandoned the idea. However, it is a more technically impressive project so I kept the file.
