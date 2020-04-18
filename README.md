# Bayseian-Wake-Sleep-Data-Exp


Problem Description
My Garmin Vivosmart watch tracks the time I fall asleep and wake up each day using motion sensing and heart rate monitoring. To augment this data, I have estimated likelihoods that I am asleep based on the condition of my bedroom light (on/off) and if my phone is charging (yes/no). My objective is to use this data to create a model that returns the probability I am asleep at a given time. The final goal can be mathematically expressed as:

$$P(\text{sleep} | \text{time})$$
.

In probability theory terms, this is the posterior probability I am asleep given the time.
