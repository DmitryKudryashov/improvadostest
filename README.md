# improvadostest

1.Target variable - costs increase or decrease status
	a. I found the difference between the last and previous months to create the "Direction(Predict_LR in future)" variable.
	b. All we need to know -  is whether the costs is going to grow or not? So we don't need to know the correct amount. We can just use a classification model.
2.I used python,pandas,sklearn,matplotlib for data preparation. Also i used LogisticRegression classification model because it showed the best score then others.
4.I chose the second dataset because it allows us to create more samples for model training. Also it allows us to track the costs dynamics for a longer time.
	a. We can check if the data is present in the required volume. We can also check the dynamics of growth or drop in spending, check how many zero values we have.
	b.Incorrect data will produce noises in our model. They also will make our model less reliable.
5.We can take a longer time series, use days instead of months, and use external signs to determine seasons and trends. We can analyze information about each company as a time series.To work with this dataset, we can remove bad and unsuitable data, or we can replace it using the trend or mods.
