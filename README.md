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

2. **Modèles & Poids sauvegardés (`.pt` / `.pth`)** :
   - `classifier_state_dict.pt` : Poids du classifieur binaire.
   - `mnist_mlp_model.pth` : Poids du modèle MLP entraîné sur MNIST.
   - `mnist_cnn.pth` : Poids du modèle CNN entraîné sur MNIST.

3. **Visualisations & Graphiques** :
   - `graphe_operations.png` : Visualisation du graphe computationnel PyTorch généré avec `torchviz`.

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

> **Note :** Si vous utilisez `torchviz`, assurez-vous que [Graphviz](https://graphviz.org/download/) est également installé sur votre système d'exploitation.

---

## 💻 Exécution du Notebook

Lancez Jupyter Notebook ou Jupyter Lab :
```bash
jupyter notebook
```
Ouvrez ensuite le fichier `Activité_pratique_Bases_de_Pytorch.ipynb` et exécutez les cellules.

---

## 👤 Auteur
- **Walid Idir** - [GitHub](https://github.com/Walid-Idir)
