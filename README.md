# Smart City Sentiment Analysis

This repository contains the full workflow and materials for my MSc thesis:  
**"Using Sentiment Analysis to Evaluate Participatory Governance in Smart Cities"**

**Cities analyzed**: Singapore, Amsterdam, and Barcelona  
**Tools used**: Python · Azure Cognitive Services · PRAW · Power BI

## Overview

This project explores how public sentiment, expressed through Reddit posts, can be used to evaluate smart city initiatives. By analyzing emotional responses to urban issues like mobility, surveillance, and sustainability, the project demonstrates a scalable and reproducible model for linking citizen feedback to policy insights.

## Technologies Used

- **Python** – for automation and data processing  
- **PRAW** – Reddit API wrapper for data collection  
- **Azure Text Analytics API** – for sentiment scoring  
- **Pandas & Matplotlib** – for data wrangling and visualizations  


## Project Structure

- `data/` — CSV files with raw and processed Reddit posts  
- `notebooks/` — Jupyter notebooks for scraping and sentiment analysis  
- `visuals/` — charts used in the final analysis and thesis  
- `README.md` — project documentation  
- `CITATION.cff` — academic citation metadata  
- `requirements.txt` — Python dependencies

## How to Use

1. Clone this repository  
2. Install the required libraries  
3. Add your Azure API key and endpoint  
4. Run the notebooks in sequence:  
   - Scrape Reddit posts  
   - Clean and preprocess the text  
   - Send to Azure for sentiment analysis  
   - Visualize and export results

## Outputs

- Sentiment scores by city and by topic  
- Keyword-level emotional insights  
- Topic–sentiment network graphs  
- Power BI dashboards

## Thesis Summary

This work was completed as part of my MSc in Big Data & AI for Business at Montpellier Business School. It demonstrates how citizen feedback can be analyzed at scale to inform smarter, more responsive urban policies.

## Citation

If you use or reference this project, please cite:

**Atsenokhai, H. (2025).** *Using Sentiment Analysis to Evaluate Participatory Governance in Smart Cities*. MSc Thesis, Montpellier Business School.

## Contact

Henrietta Atsenokhai  
📧 [henrietta.atsenokhai@gmail.com]  
