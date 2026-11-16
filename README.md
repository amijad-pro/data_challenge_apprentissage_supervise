# Data Challenge : Apprentissage Supervisé (M2 Maths & IA, Paris-Saclay)

**Auteurs :** Maud Le Bouedec & Amjad Proietti  
**Branche finale :** `main`

Ce dépôt contient le code permettant de reproduire l'ensemble des pré-traitements, l'entraînement des modèles, la validation croisée et la génération des fichiers de soumission Kaggle pour les deux défis :
1. **Régression (`power/powerlifting_regression_vf.ipynb`)** : prédiction du total réalisé (`TotalKg`) sur les données OpenPowerlifting (métrique : RMSE).
2. **Classification (`hmda/hmda_classification_vf.ipynb`)** : prédiction de l'acceptation d'un prêt immobilier (`accepted`) sur les données HMDA (métrique : ROC AUC).

---

## 1. Installation de l'environnement

Cloner le dépôt et installer les dépendances Python (Python 3.10+ recommandé) :


### Installation et Lancement

Cloner le projet et se placer à la racine du dossier.

```bash
git clone [https://github.com/amijad-pro/data_challenge_apprentissage_supervise.git](https://github.com/amijad-pro/data_challenge_apprentissage_supervise.git)
cd data_challenge_apprentissage_supervise
```

Créer un environnement virtuel (recommandé) :

```bash
python -m venv venv
```

Activer l'environnement virtuel :

Sur Windows :

```bash
.\venv\Scripts\activate
```

Sur macOS/Linux :

```bash
source venv/bin/activate
```

Installer les dépendances :

```bash
python -m pip install --upgrade pip
```

```bash
python -m pip install -r requirements.txt
```
```bash
python -m notebook
```


