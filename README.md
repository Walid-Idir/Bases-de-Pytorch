# Bases de PyTorch 🧠🔥

Ce dépôt contient le notebook complet et les ressources pour la prise en main et la maîtrise des bases du framework **PyTorch** en Deep Learning.

---

## 📋 Contenu du Projet

1. **`Activité_pratique_Bases_de_Pytorch.ipynb`** :
   - **Fondamentaux PyTorch** : Tensors, opérations, gestion du `device` (CPU / GPU CUDA).
   - **Autograd & Graphe de calcul** : Calcul automatique des gradients, vérification analytique et visualisation avec `torchviz`.
   - **Modules & Réseaux (`torch.nn`)** : `nn.Linear`, `nn.Module`, `Sequential`, fonctions d'activation (ReLU, Sigmoid, Tanh).
   - **Optimisation** : Fonctions de coût (MSELoss, CrossEntropyLoss, BCEWithLogitsLoss), optimiseurs (SGD, Adam), boucles d'entraînement (`train()` vs `eval()`).
   - **Gestion des Données** : `TensorDataset`, `DataLoader`, batching et shuffling.
   - **Cas Pratiques & Exercices Complets** :
     - Régression linéaire synthétique.
     - Classification binaire avec frontière de décision.
     - Classification multi-classes sur le dataset **Iris**.
     - Classification d'images sur **MNIST** avec un **MLP** (Multi-Layer Perceptron) et un **CNN** (Convolutional Neural Network).
     - Sauvegarde et rechargement des poids (`torch.save` & `load_state_dict`).

2. **Visualisations & Graphiques** :
   - `graphe_operations.png` : Visualisation du graphe computationnel PyTorch généré avec `torchviz`.

3. **Environnement & Dépendances** :
   - `requirements.txt` : Liste des bibliothèques nécessaires à l'exécution du notebook.
   - `.gitignore` : Configuration excluant les données brutes (`data/`), les caches et les fichiers de poids binaires (`*.pt`, `*.pth`).

---

## 🚀 Installation & Prérequis

### 1. Cloner le dépôt
```bash
git clone https://github.com/Walid-Idir/Bases-de-Pytorch.git
cd Bases-de-Pytorch
```

### 2. Installer les dépendances
Installez les packages nécessaires listés dans `requirements.txt` :
```bash
pip install -r requirements.txt
```

> **Note :** Si vous utilisez `torchviz`, assurez-vous que [Graphviz](https://graphviz.org/download/) est également installé sur votre machine.

---

## 💻 Exécution du Notebook

Lancez Jupyter Notebook ou Jupyter Lab :
```bash
jupyter notebook
```
Ouvrez ensuite le fichier `Activité_pratique_Bases_de_Pytorch.ipynb` et exécutez les cellules. L'entraînement des modèles et la sauvegarde locale des poids (`.pt` / `.pth`) s'effectueront directement lors de l'exécution.

---

## 👤 Auteur
- **Walid Idir** - [GitHub](https://github.com/Walid-Idir)
