# SmartMarket AI Africa

Final project for the Building AI course

## Summary

SmartMarket AI Africa est une plateforme d’intelligence artificielle qui aide les petits commerçants africains à prévoir les ventes, gérer leurs stocks et mieux comprendre les besoins des clients.

Building AI course project

## Background

De nombreux commerces africains perdent de l’argent à cause des ruptures de stock et du manque d’outils numériques intelligents.

Cette solution aide les commerçants à utiliser l’intelligence artificielle pour améliorer leurs décisions.

* mauvaise gestion des stocks
* pertes financières
* faible digitalisation

## How is it used?

Les commerçants utilisent une application mobile ou web.

L’IA analyse les ventes et prédit les produits les plus demandés.

Exemple :
“Les ventes de boissons augmenteront ce week-end.”

## Data sources and AI methods

Sources de données :
* ventes des commerces
* météo
* tendances locales

Techniques IA :
* Machine Learning
* prédiction
* analyse de données

```python
from sklearn.linear_model import LinearRegression
import numpy as np

x = np.array([1,2,3,4,5]).reshape(-1,1)
y = np.array([20,25,30,35,40])

model = LinearRegression()
model.fit(x,y)

print(model.predict([[6]]))
```

## Challenges

Le projet dépend :
* d’une bonne connexion internet
* de données fiables
* de l’accès à la technologie

## What next?

Le projet pourrait évoluer avec :
* paiements mobiles
* IA vocale
* langues africaines
* intégration WhatsApp

## Acknowledgments

Merci au cours Building AI.

Inspiré par OpenAI, Scikit-learn et la communauté open source.
