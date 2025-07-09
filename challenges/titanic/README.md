# Titanic - Machine Learning from disater

ML stand for "Machine Learning"

DL stand for "Deep Learning"

## French part

### **Important !!**  

Les jeux de données utilisés pour ce challenge **ne sont pas disponibles dans ce dépôt** par respect pour la plateforme qui héberge ce challenge.  

Vous pouvez les récupérer à tout moment en créant un compte sur cette plateforme.  

---

### **Introduction**  

#### **Challenge**  
Ce challenge est un challenge de **machine learning** disponible sur la plateforme **Kaggle** à l'adresse suivante :  
**[Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)** 

#### **Prérequis**  
Ce challenge a été écrit sur **Jupyter Notebook**, à l'aide de **Python 3.10** et des dépendances suivantes :  

**- numpy**  
**- pandas**  
**- tensorflow**  
**- keras**  

#### **Description**  
Ce challenge vise à prédire la survie (ou non) d'un ensemble de personnes présentes à bord du Titanic.  

Pour cela, **Kaggle** met à disposition un jeu de données d'entraînement contenant différents paramètres sur chaque personne (Nom, Âge, Sexe, etc.), ainsi qu'un paramètre indiquant si la personne a survécu.  

Le but est donc de créer un modèle de **ML/DL** et de l'entraîner sur ce jeu de données.  

#### Choix variables

Parmis l'ensemble des caractéristiques disponible sur chaque individu, j'ai fais le choix de ne retenir que l'age, le sex, la classe du voyageur (1ere, 2nd, 3eme), le prix du billet, son nombre de frère/soeurs ainsi que son nombre de parents/enfants. Ce choix **n'est que le miens** et chaque personne est libre de choisir plus ou moins de variable si celles-ci lui semblent en corrélation avec la survie du voyageur.

En effet j'ai pensé que l'age, le sex et la classe sociale avait un impact direct sur la survie de la personne (ex: "Les femmes et les enfants d'abords")

De plus, j'ai voulu garder aussi le prix du billet, car celui-ci impact le confort du voyageur et surement sa sécurité ?

Quant au nombre de frères/soeurs, parents/enfants, j'ai préféré les garder pour avoir un modèle plus complexe en imaginant que le comportement d'un parent envers son enfant dans ce genre de catastrophe, profiterait à plein de personne en détresse sur le bateau.

#### Prédictions

Vient ensuite la phase de prédiction sur le jeu de données de test, dans lequel nous disposons de toutes les caractéristiques de chaque personne sans savoir si celle-ci a survécu ou non.  

Une fois notre modèle entraîné, nous pouvons effectuer une prédiction sur les personnes qui font partie du jeu de données de test. Le fichier **results.csv** est un exemple de prédiction.  


## English Part

### **Important !!**  

The datasets used for this challenge **are not available in this repository** out of respect for the platform hosting this challenge.  

You can retrieve them at any time by creating an account on this platform.  

---

### **Introduction**  

#### **Challenge**  
This challenge is a **machine learning** competition available on the **Kaggle** platform at the following address:  
**[Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)**  

#### **Prerequisites**  
This challenge was written in **Jupyter Notebook**, using **Python 3.10** and the following dependencies:  

**- numpy**  
**- pandas**  
**- tensorflow**  
**- keras**  

#### **Description**  
This challenge aims to predict the survival (or not) of a group of people aboard the Titanic.  

To do this, **Kaggle** provides a training dataset containing various parameters for each person (Name, Age, Gender, etc.), as well as a parameter indicating whether the person survived.  

The goal is to create a **ML/DL** model and train it on this dataset.  

#### Chosen variables

Among all the available features for each individual, I chose to retain only age, gender, the passenger class (1st, 2nd, 3rd), the ticket price, the number of siblings/spouses, and the number of parents/children. This choice **is mine alone**, and each person is free to select more or fewer variables if they seem to be correlated with the passenger's survival.

Indeed, I thought that age, gender, and social class had a direct impact on the survival of the person (e.g., "Women and children first").  

Moreover, I also wanted to keep the ticket price, as it impacts the comfort of the passenger and probably their safety?

As for the number of siblings/spouses and parents/children, I preferred to keep them in order to have a more complex model, imagining that a parent's behavior towards their child in such a catastrophe could help many people in distress on the ship.

#### Predictions

Next comes the prediction phase on the test dataset, where we have all the characteristics of each person but do not know whether they survived or not.  

Once our model is trained, we can make predictions for the people in the test dataset. The **results.csv** file is an example of predictions.  
 



