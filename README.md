# PumpItUp
This code is a jupyter notebook which is created within a competition of http://DrivenData.org competition 'PumpItUp'.
I choosed this competition because it is about discrete data only.
My approach was to use random-forest-classifier. Also I did some experiments with other classifiers but they did not perform as well. 
My best estimator was found at 
n_estimators= 1600,
min_samples_split= 5,
min_samples_leaf= 1,
max_depth= 100,
bootstrap= True,
max_features= auto

It should deliver an accuracy of around 81%. Also I did some experiments with different cleansing-approaches but with no gain in accuracy.