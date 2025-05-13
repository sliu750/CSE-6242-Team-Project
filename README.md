Description: 

This package contains the final submission for Team 4 (Urban Treehuggers). Our project analyzes the conditions that influence the health of urban forestry, and dives deeper into Los Angeles, investigating the environmental factors that determine public health risk. Additionally, we showcase our data and findings through Tableau visualizations.

There are a few components inside this folder. Currently, you are reading the README file, which serves as the user guide.

The DOC folder contains our final report (team004report.pdf) and our final poster (team004poster.pdf). Please note that you might need to zoom in to see the visualizations on the poster in detail.

The CODE folder contains the code for running our models. The team004_runner.ipynb file contains the code you need to run to load the models. This folder also contains the saved models as .sav files. 

Our models for tree health classification are:
- tree_health_ensemble.sav
- tree_health_random_forest_classifier.sav
- tree_health_xgboost.sav


Our models for air quality vs public health risk prediction are:
- air_quality_and_health_dnn.sav
- air_quality_and_health_gradient_boosting.sav
- air_quality_and_health_random_forest_regressor.sav

The VISUALIZATIONS folder contains all of our Tableau visualizations:
- city_health_metrics.png
- city_health.png
- CMU_trees.png
- LA_trees.png
- Pittsburgh_trees.png

Additionally, the VISUALIZATIONS folder contains the script we wrote to process our datasets before visualizing them (file_processing.ipynb) and the code that produces our visualizations (Tableau Visualizations.twb).



Installation:

The scikit-learn, xgboost, tensorflow, and pickle libraries are required for loading the models. These libraries can be installed by entering pip install scikit-learn, etc in your computer’s terminal.



Execution:

Once the necessary modules are installed, go to the CODE folder, open team004_runner.ipynb, run the necessary code for loading the desired models (for tree health classification and/or public health risk prediction), go under the heading titled “User code here”, and call .predict() on the (loaded) model, passing in your own data.
