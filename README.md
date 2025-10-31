# 🌳 Green Paris — Visualisation des arbres plantés à Paris

## Description du projet  
**Green Paris** est un tableau de bord interactif qui présente la répartition et l’évolution des arbres plantés dans la ville de Paris.  
Le projet repose sur les données ouvertes fournies par la Ville de Paris :  
[Arbres plantés par projet — opendata.paris.fr](https://opendata.paris.fr/explore/dataset/arbres-plantes-par-projet/information/?dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJhcmVhIiwiZnVuYyI6IlNVTSIsInlBeGlzIjoiaW5kX2FyYl9wbGFudCIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiM1RDlGQTMifV0sInhBeGlzIjoiZGF0ZV9maW5fdCIsIm1heHBvaW50cyI6IiIsInRpbWVzY2FsZSI6InllYXIiLCJzb3J0IjoiIiwiY29uZmlnIjp7ImRhdGFzZXQiOiJhcmJyZXMtcGxhbnRlcy1wYXItcHJvamV0Iiwib3B0aW9ucyI6e319fV0sImRpc3BsYXlMZWdlbmQiOnRydWUsImFsaWduTW9udGgiOnRydWV9)

L’objectif est de permettre une **analyse claire et visuelle** de l’effort de végétalisation entrepris par la Ville, à travers plusieurs indicateurs clés :  
- Nombre total d’arbres plantés  
- Nombre de projets réalisés
- Aire moyenne végétalisée 
- Répartition des plantations par arrondissement
- Localisation géographique des projets sur une carte interactive

---

## Données utilisées  
- **Source** : [Open Data Paris — Arbres plantés par projet](https://opendata.paris.fr/explore/dataset/arbres-plantes-par-projet/information)  
- **Format** : CSV  
- **Champs principaux** :
  - `Projet` : nom ou description du projet  
  - `Arrondissement` : numéro d’arrondissement de Paris  
  - `Nombre_d'arbres` : nombre d’arbres plantés par projet  
  - `Aire (m²)` : superficie végétalisée  
  - `Statut` : état du projet (Réalisé, En cours, etc.)  
  - `Coordonnées géographiques` : latitude et longitude du projet  

---

## Outils & technologies  
- **Power BI** → création du tableau de bord principal (visualisation, filtrage, cartographie)  
- **Excel** → préparation et nettoyage des données  
---

## Visualisations principales  
1. **Indicateurs clés**  
   - Nombre total d’arbres plantés  
   - Nombre de projets réalisés  
   - Aire moyenne végétalisée  

2. **Tableau des projets réalisés**  
   - Détail par arrondissement, aire végétalisée et statut du projet

3. **Top 5 arrondissements par nombre d’arbres plantés**  
   - Classement dynamique basé sur les totaux cumulés  

4. **Périmètre total par secteur administratif**  
   - Graphique à barres illustrant la longueur totale végétalisée par arrondissement  

5. **Cartographie interactive**  
   - Visualisation géographique de l’ensemble des projets de plantation
   
<img width="1360" height="767" alt="Green Paris Dashbord Screen shot" src="https://github.com/user-attachments/assets/e94c1f2d-d023-4c60-beaa-9cfb4724b62f" />

---

## Objectifs du projet  
- Mettre en valeur l’engagement environnemental de la Ville de Paris 
- Fournir une **analyse visuelle claire et synthétique** des efforts de végétalisation  
- Faciliter l’identification des zones les plus vertes ou les plus actives en termes de projets  

---

## Pistes d’amélioration  
- Intégrer une **analyse temporelle** de l’évolution du nombre d’arbres plantés (par année)  
- Coupler les données avec d’autres jeux de données environnementales (qualité de l’air, zones piétonnes, etc.)  

---

## 📸 Aperçu du dashboard  
![Green Paris Dashboard](./ada25484-0cbe-473c-9ab5-c1d512509666.png)

 
