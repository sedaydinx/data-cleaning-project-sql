# Layoffs Data Cleaning

**Project:** Layoffs Data Cleaning  
**Database:** MySQL  
**Focus:** duplicates, standardization, null handling  

## 🔹 Ziel
Die Layoffs-Daten bereinigen, um saubere, standardisierte Tabellen für Analyse oder Reporting zu erhalten.

## 🔹 Schritte
1. Entfernen von Duplikaten (`ROW_NUMBER` + `DELETE`)  
2. Standardisierung der Daten (`TRIM`, Länder- und Industrie-Korrekturen)  
3. Umgang mit NULL- oder leeren Werten  
4. Entfernen unnötiger Spalten (`row_num`)  

## 🔹 SQL-Features
- CTE (`WITH duplicate_cte AS …`)  
- Window Functions (`ROW_NUMBER() OVER(...)`)  
- `JOIN` für das Auffüllen fehlender Werte  
- `ALTER TABLE`, `UPDATE`, `DELETE`  

## 🔹 Dateien
- `data_cleaning_layoffs.sql` → Haupt-SQL-Script
