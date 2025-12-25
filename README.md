# JO_Prediction — Prédiction des performances olympiques

Projet visant à analyser et prédire les performances des pays aux Jeux Olympiques à partir de données économiques, géographiques et historiques.

## Auteurs

@Matheo Ballester

@Mano Dinat-Creusier

@Alexis Dieu

## Contenu

- `Projet_MIDL_3.ipynb` : Notebook principal d’analyse et de modélisation
- `DataParis/`, `DataTokyo/` : Jeux de données olympiques
- `pib_pays.csv`, `imf-dm-export-20241229.csv` : Données économiques
- `ne_110m_admin_0_countries/` : Données cartographiques (Natural Earth)
- `Rapport.pdf` : Rapport final du projet
- `Rapport.docx` : Version modifiable du rapport
- `requirements.txt` : Dépendances Python du projet

**Important :** pour télécharger `Rapport.pdf` ou `Rapport.docx`, utilisez **Raw → Save As** sur GitHub.

(L’aperçu GitHub peut échouer pour les fichiers PDF volumineux.)

## Lancer le projet

```bash
git clone git@github.com:matheo407/JO_Prediction.git
cd JO_Prediction
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

Ouvrez `Projet_MIDL_3.ipynb` et exécutez toutes les cellules.

## Données

Natural Earth : https://www.naturalearthdata.com/

Données économiques FMI

Données de performances olympiques (Tokyo & Paris)
