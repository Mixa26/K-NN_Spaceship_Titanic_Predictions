# K-NN_Spaceship_Titanic_Predictions
One of university machine learning projects where we predict the possibility of a passenger surviving.

We have a dataset from a spaceship called Titanic which unfortunately crashed as it's predecessor. 
Our goal is to make a model which could predict if a passenger is likely to survive based on the
data provided. 

This is what our data looks like. The column that we want to predict is Transported.

![features](https://github.com/Mixa26/K-NN_Spaceship_Titanic_Predictions/assets/71144280/0dba30ed-f4dc-4afc-9c3c-6553d4c822a8)

We used the K-NN algorithm for this assignment. You can find the full specification
of the project in the "ML D1 2023.pdf" file. This algorigthm refers to the 3rd exercise only (3a,3b,3c).
To run this you can open the "k_NN.ipynb" in google colab, don't forget to upload in "spaceship-titanic.csv"
in the files folder in google colab as well. The project is briefly explained in the file itself, and there
are visualizations of the data as well.

These are our predictions based solely on RoomService and FoodCort:

![predictions](https://github.com/Mixa26/K-NN_Spaceship_Titanic_Predictions/assets/71144280/6d5faeba-a08e-4941-afb8-7dbbd0b67067)

This is how our accuracy depends on various K parameters with only RoomService and FoodCourt as our features: 

![predictions_17K](https://github.com/Mixa26/K-NN_Spaceship_Titanic_Predictions/assets/71144280/b276d606-81a3-45b6-b948-032cc3171f47)

If we add all the features into training this is how our new diagram looks like: 

![predictions_with_various_K](https://github.com/Mixa26/K-NN_Spaceship_Titanic_Predictions/assets/71144280/dbf22e71-e383-4764-8135-22b25d1805b2)
