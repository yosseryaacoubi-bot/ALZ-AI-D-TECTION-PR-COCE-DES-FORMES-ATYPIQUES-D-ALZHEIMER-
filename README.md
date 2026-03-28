# Alz-AI 🧠
### Détection Précoce des Formes Atypiques d'Alzheimer

Alz-AI est une solution conceptuelle d'intelligence artificielle multimodale conçue pour identifier les premiers signaux faibles des formes atypiques de la maladie d'Alzheimer.  
Ce projet a été développé dans le cadre du **Hackathon Talents Tunisie - Forum Méditerranéen de l'IA**.

---

## 📌 Problématique
Le diagnostic d'Alzheimer reste souvent tardif, particulièrement pour les formes atypiques où les symptômes (langage, vision, comportement) divergent du schéma classique de perte de mémoire.  
Un diagnostic précoce est crucial pour ralentir la progression de la maladie et améliorer la qualité de vie des patients.

---

## 🚀 Solution Proposée
Alz-AI repose sur la fusion de quatre modalités complémentaires pour garantir un diagnostic robuste et précoce :

- **IRM cérébrales** : Analyse morphologique via des réseaux de neurones convolutifs (CNN - ResNet).
- **Analyses vocales & langagières** : Détection des altérations du discours via Transformers (BERT).
- **Biomarqueurs sanguins** : Intégration des dosages biologiques (amyloïde β, tau, NfL).
- **Données cliniques** : Prise en compte des tests cognitifs et antécédents médicaux.

---

## 🛠️ Architecture Technique
Le modèle est conçu autour d'une couche de fusion multimodale combinant les représentations issues de différentes architectures :

- **Vision** : ResNet-50 pour l’imagerie cérébrale.  
- **NLP** : BERT/Transformers pour le texte et le discours.  
- **Séquences temporelles** : LSTM/RNN pour les données comportementales.  
- **Explicabilité** : Grad-CAM et SHAP pour fournir un score de risque interprétable par les cliniciens.  

---

## 📈 Vision Long Terme
L’objectif est d’intégrer Alz-AI dans le parcours de soins pour accompagner les professionnels de santé (neurologues, psychiatres) dans leur prise de décision clinique.  
Le projet prévoit également l’usage de **l’apprentissage fédéré** pour garantir la confidentialité des données médicales au sein des hôpitaux.

---

## 🛠️ Stack Technologique Recommandée
- **Deep Learning** : PyTorch / TensorFlow  
- **Traitement d’images** : OpenCV, NiBabel  
- **NLP** : HuggingFace Transformers  
- **Déploiement** : FastAPI, Streamlit, Docker  

---

## 🔗 Remarques
Ce projet est pour l’instant **conceptuel et exploratoire**, développé dans le cadre d’un hackathon.  
Il peut servir de base pour des prototypes de recherche clinique ou des proofs-of-concept.
