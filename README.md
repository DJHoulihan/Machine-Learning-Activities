# Machine-Learning-Activities
Various personal machine learning projects.

# Highlights

## Activity: Python Keras
A Machine Learning activity taken from the hands-on sessions at the 2023 Exotic Beam Summer School at Michigan State (FRIB), pulled from the following GitHub: https://github.com/alpha-davidson/ICTP-IAEA-2023. 
Constructs a dense neural network to predict the invariant mass of a particle from its energy, momentum, (and charge). Note that this task does not require machine learning. We choose a task with a known mapping to help us create, debug, and tune our first neural network.
<img src="https://github.com/user-attachments/assets/1c6351eb-21a7-49aa-bb9a-c7c84966eb4f" alt="trainingandval" width="600" height="400">

## Activity: Titanic Dataset
This activity involved using an incomplete dataset of Titanic passengers to simulate how many actual survivors and deaths there were. Preliminary exploratory analysis was done to determine the affect of various factors such as age, sex, ticket price, ticket class, and cabin designation had on survival. Synthetic data was created based upon the assumption that the total number of passengers and crew can be represented as a normal distribution with a mean of 2,224 people and a standard deviation of 400. Gender, age, ticket price, and ticket class were provided to each synthetic person based on the distributions seen in the original dataset. The same procedure was done on a separate dataset containing crew members aboard the ship. The ratio of crew to passengers was 0.59, based upon estimates of how many of each were on the ship. 
### Results
Average people:2199.2
Average deaths:1429.6
Average survivors 769.6
Average survival rate 0.3496917959271756
95% Confidence interval for survivors: (680.274, 858.926)
95% Confidence interval for deaths: (1271.966, 1587.234)
95% Confidence interval for survival rates: (0.347, 0.352)
