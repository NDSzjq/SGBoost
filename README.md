# SGBoost
An Efficient and Privacy-Preserving Vertical Federated Tree Boosting Framework

## Introduction：

####  This project provides an efficient and privacy-preserving vertical federated framework for the boosting tree model, named SGBoost.

## Execution：

####  1. The code in the jar. files uses an absolute path to read data, which needs to be set by the user

#####     C:\SGBoost\sources\Credit-4

####  2. JDK Version: 12.0.1

####  3. Running:

#####   (1) Start CSP service. 

#####     java -cp C:\SGBoost\SGBoost.jar cloud.CloudServiceProvider


#####   (2) Start organizer service.

#####     java -cp C:\SGBoost\SGBoost.jar dataowner.DataOrganizer


#####   (3) Start dataowner service, and start model training.

#####     java -cp C:\SGBoost\SGBoost.jar dataowner.DataOwner 

#####    (4) When training terminates, start model query service.
#####     java -cp C:\SGBoost\SGBoost.jar user.user
