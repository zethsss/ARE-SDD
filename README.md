## Baisc tree classification using Naive Bayes and K-Nearest Neighbors


# Dataset Description

## 📂 Fichiers

- `train.csv` — Les données d'entraînement  
- `prev.csv` — Les données à prévoir  
- `benchmark.csv` — Un exemple de fichier de soumission  

---

## 🏷️ Légendes

### `type_sol`  
- `P` — paillage  
- `G` — gazon  
- `S` — stabilisé  
- `Gr` — grille  
- `GR` — grave  
- `MA` — massifs  
- `E` — enrobé  
- `CS` — couvre-sol  

### `classe_age`  
- `A` — adulte (20 à 40 ans)  
- `JA` — jeune adulte (10 à 20 ans)  
- `J` — jeune (< 10 ans)  
- `AM` — adulte mûr (50 à 70 ans)  

### `classe_hauteur`  
- `H1` — 0 à 5 m  
- `H2` — 5 à 10 m  
- `H3` — 10 à 15 m  
- `H4` — 15 à 20 m  
- `H5` — 20 à 25 m  

### `classe_circonference`  
- `C1` — 0 à 0,5 m  
- `C2` — 0,51 à 1 m  
- `C3` — 1,01 à 1,5 m  
- `C4` — 1,51 à 2 m  
- `C5` — 2,01 à 2,5 m  
- `C6` — 2,51 à 3 m  
- `C7` — 3,01 à 3,5 m  

### `port_arbre`  
- `SL` — semi-libre  
- `L` — libre  
- `R5` — rideau à 5 faces  
- `RR` — réduit relâché  
- `A` — architecturé  

### `vigueur_pousse`  
- `P` — poussant  
- `PP` — peu poussant  
- `MP` — moyen poussant  
- `D` — dépérissant  

### `plaie_collet`  
- `RCPPL` — pas de plaie  
- `RCPLS` — plaie saine  
- `RCPLNS` — plaie nécrosée avec suintement  
- `RCPLNC` — plaie nécrosée avec cavité  
- `RCPLC` — plaie cicatrisée  

### `fissure_tronc`  
- `TPF` — pas de fissure  
- `TFO` — fissure ouverte  
- `TFF` — fissure fermée  

### `plaie_tronc`  
- `TPLS` — plaie saine  
- `TPLCF` — cavité fermée  
- `TPLNC` — plaie nécrosée avec cavité  
- `TPLC` — plaie cicatrisée  
- `TPPL` — pas de plaie  

### `fissure_houppier`  
- `HPF` — pas de fissure  
- `HFO` — fissure ouverte  

### `bois_mort_houppier`  
- `HBMI` — bois mort isolé  
- `HPBM` — pas de bois mort  
- `HBMU` — bois mort uniforme  

### `plaie_houppier`  
- `HPLC` — plaie cicatrisée  
- `HPLS` — plaie saine  
- `HPPL` — pas de plaie  
- `HPLNC` — plaie nécrosée avec cavité  

### `esperance_maintien`  
- `1` — > 15 ans  
- `2` — 10 à 15 ans  
- `3` — 5 à 10 ans  
- `4` — < 5 ans  
