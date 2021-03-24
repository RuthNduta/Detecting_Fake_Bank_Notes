# Detecting_Fake_Bank_Notes :moneybag: :money_with_wings:
# Overview
Banknotes are one of the most important assets of a country. Some miscreants introduce fake notes which bear a resemblance to original note to create discrepancies of the money in the financial market. It is difficult for humans to tell true and fake banknotes apart especially because they have a lot of similar features.

![banknotes](https://user-images.githubusercontent.com/70197110/112374696-77378180-8cf3-11eb-9377-2c9519319f27.png)



There has been a drastic increase in the rate of fake notes in the market :chart:. Fake money is an imitation of the genuine notes and is created illegally for various motives. These fake notes are created in all denominations which brings the financial market of the country to a low level. The various advancements in the field of scanners and copy machines have led the miscreants to create copies of banknotes.

> It is difficult for human-eye to recognize a fake note because they are created with great accuracy to look alike a genuine note. Security aspects of banknotes have to be considered and security features are to be introduced to mitigate fake currency. Hence, there is a dire need in banks and ATM machines :credit_card: to implement a system that classifies a note as genuine or fake.

*Source of Information: A research paper on Analysis of Banknote Authentication System using Machine Learning Techniques by Sumeet Shahani, Aisa Jagiasi and Priya RL at International Journal of Computer Applications (0975 – 8887) Volume 179 – No.20, February 2018)*

# Objective
To come up with an efficient deep learning model that accurately predicts if a note is genuine or not.

# Evaluation Criteria
Submissions are evaluated using Accuracy Score. The loss function used is the binary cross entropy.

# About the Data
Data was extracted from images that were taken for the evaluation of an authentication procedure for banknotes -- genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object grey-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool was used to extract features from images.
[Dataset]("https://raw.githubusercontent.com/dphi-official/Datasets/master/bank_note_data/training_set_label.csv" )

# Data Description
> - VWTI: Variance of Wavelet Transformed Image
> - SWTI: Skewness of Wavelet Transformed Image
> - CWTI: Curtosis of Wavelet Transformed Image
> - EI: Entropy of Image
> - Class: Class (1: genuine, 0: forged)



