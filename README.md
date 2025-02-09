# MedicalReportSummarization

🏥 Projet : Résumé de Rapports Médicaux avec OCR et LLM

📊 Introduction

Le but de ce projet est de développer un modèle capable d'extraire et de résumer automatiquement des rapports médicaux en utilisant l'OCR (Reconnaissance Optique de Caractères) et des Modèles de Langage (LLM).

Ce système peut aider les médecins et les professionnels de santé à analyser rapidement des documents médicaux volumineux et à obtenir des résumés concis et pertinents.

📑 Fonctionnalités Principales

📚 Collecte de Données : Utilisation de datasets de rapports médicaux (ex: Medical Transcriptions Dataset de Kaggle).

🔄 Nettoyage et Prétraitement : Suppression du bruit textuel et normalisation des données.

⚖️ Extraction d'Entités Médicales (NER) : Identification des maladies, traitements et termes cliniques avec spaCy.

📈 Résumé Automatique : Génération de résumés courts et informatifs grâce au modèle T5 Transformer.


🔍 Prérequis

Avant de commencer, assurez-vous d'avoir installé les bibliothèques suivantes :

pip install pandas numpy transformers torch spacy scispacy

Pour télécharger un modèle NLP spécialisé en médecine :

pip install https://s3-us-west-2.amazonaws.com/ai2-s2-scispacy/releases/v0.5.3/en_core_sci_sm-0.5.3.tar.gz


👩‍🎓 Améliorations Futures

🔄 Fine-tuning de T5 sur un dataset médical plus spécifique.

🌐 Déploiement en API pour une intégration dans des systèmes hospitaliers.
