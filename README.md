# ML-Spotify-Genre-Classification
### This project was done for a Data Science Fundamentals course at UCLA in a team of four: Maxwell Chu, Pei Lee, Marissa Meng, and Jack Stapholm.
### Spotify Dataset: https://huggingface.co/datasets/maharshipandya/spotify-tracks-dataset
- Preprocessed a data set of 114,000 rows and 20 columns and conducted EDA with visualizations.
- Classified the genre of a track (song) with several ML techniques, achieving a best accuracy of 64.1%.
- Reduced model complexity by using LASSO logistic regression and random forest to do feature selection, yielding similar results.
- Tuned model hyperparameters via grid search and prevented neural network from overfitting with dropout, batch normalization, and weight decay techniques.
- Wrote a concise report detailing the process, results, limitations, and improvements.
- Initiated team meetings, assessed individual strengths to divide labor, and created project goals and methods.

### Limitations and Improvements
- Deal with heavy class imbalances in predictors such as "explicit" and "time_signature".
- Optimize random forest and neural network models to reduce computational/time costs, for instance employing early stopping.
- Write cleaner code with more comments in the context of the problem.
- The Spotify Dataset is highly complex, yet music is even more complex of an entity. The often loose definitions and bounds of song genres are generally ambiguous and ever-changing, so predicting them is and will always be difficult. It isn't outlandish to claim that prediction accuracy will never reach past 85%, give or take.
