# Comparaison Systématique des Algorithmes d’Optimisation

Ce dépôt contient les livrables du projet "Comparaison Systématique des Algorithmes d’Optimisation pour l’Apprentissage Automatique et Profond : Étude Empirique et Analyse Critique", réalisé dans le cadre du module **Algorithmes d’optimisation**.

## **Structure du Projet**

### 1. **Rapport Final**
- Fichier : `OPTIMISATION RAPPORT .docx`
- Contient l'analyse complète :
  - Introduction
  - Revue de littérature
  - Méthodologie
  - Résultats et discussion
  - Conclusion et recommandations

### 2. **Annexes**
- **Figures et Graphiques** : Courbes de convergence et autres visualisations (non incluses dans le rapport principal).
- **Notebook d’Exemple** :
  - Un notebook interactif montrant l'entraînement des modèles et l'analyse des résultats.

### 3. **Code Source**
- Scripts Python utilisés pour :
  - Charger les jeux de données (Boston Housing, California Housing).
  - Implémenter les modèles (régression linéaire et réseau de neurones).
  - Comparer les algorithmes d'optimisation (SGD avec momentum, Adam, L-BFGS, Newton-CG).
  - Générer les visualisations.

## **Jeux de Données Utilisés**
- **Boston Housing** : Prédiction des prix médians des maisons basées sur 13 caractéristiques.
- **California Housing** : Prédiction des valeurs médianes des maisons avec 8 caractéristiques.

## **Algorithmes d’Optimisation Étudiés**
1. **SGD avec momentum**
2. **Adam**
3. **L-BFGS**
4. **Newton-CG**

## **Métriques d’Évaluation**
- Vitesse de convergence
- Erreur quadratique moyenne (MSE)
- Généralisation (performance sur l'ensemble de test)
- Sensibilité aux hyperparamètres

## **Exécution des Scripts**
### **Prérequis**
- Python 3.8+
- Bibliothèques :
  - PyTorch
  - Scikit-learn
  - Matplotlib
  - NumPy
  - SciPy

### **Instructions**
1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/nom-du-depot.git
   cd nom-du-depot
   ```
2. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
   ```
3. Lancez le notebook d'exemple :
   ```bash
   jupyter notebook notebooks/example_training.ipynb
   ```

## **Auteur·e·s**
- HOUSSA FATIMA EZZAHRAE
- SAFAA FHAMNI
- El MUSTAPHA CHTIBA

### **Supervisé par**
- Mme BENABBOU FAOUZIA

## **Licence**
Ce projet est distribué sous la licence MIT. Consultez le fichier `LICENSE` pour plus d'informations.

---

Pour toute question ou suggestion, veuillez ouvrir une **issue** ou soumettre une **pull request**.
