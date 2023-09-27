# 635_project_pollution_detect
umass amherst ece 635 project(wzk, sc)

Name: City Air Pollution prediction 



# Motivation
With the departure of the COVID-19 craze, our lives are gradually returning to the right track. However, there has been no significant improvement in the issue of environmental pollution leading to diseases such as influenza. We believe that we cannot fundamentally solve environmental pollution problems (such as car exhaust and factory emissions), and can only use relevant air testing (PM2.5) to remind residents to protect themselves through other means (masks, preventive drugs, travel planning, etc.). We cannot obtain comprehensive air indicator data through my existing equipment, so we process the model by publishing data through environmental protection stations in various regions. We will use neural network models to adapt these data, hoping to predict the level of pollution in the next hour to warn residents.

 
# Design goals
Fortunately, we have found a complete paper on the internet that shares our motivation. I believe our initial goal is to replicate the results based on the dataset provided in the paper
Processing data. So, I think we will three goals for our project:
1.Reprocessing Datasets

2.Reproducing CNN-LSTM neural network model

3.Compare model results

# Deliverables
1.Recreation of Neural Network Models


2.Project report


# System blocks
![image](https://github.com/EX1cyclone/635_project_pollution_detect/assets/48908740/3a9748c4-b833-4600-940d-632534ebfc5b)


# Hw/sw requirements
Sw requirements: Scikit-Learn, Keras,native TensorFlow and other Python packages

Hw requirements: any pc which could run google colab

# team memebers responsibilities
Chang Shen : data collecting，data processing，model training

Zikun Wei: model training,compare  results, improve model

# project timeline
Oct: Processed all data

Nov： model training&test，

Doc： compare results， improve model， finish report

# references
Paper:https://journalofbigdata.springeropen.com/articles/10.1186/s40537-021-00548-1#Bib1

database:https://archive.ics.uci.edu/dataset/501/beijing+multi+site+air+quality+data
