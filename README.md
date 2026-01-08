# NLP Environmental Policies Pipeline

A lightweight, reusable NLP data pipeline for processing real-world Reddit discussions about environmental policies and generating structured, sector-level sentiment metrics.

## Overview

This pipeline transforms noisy, unstructured text data into structured outputs through a standardized workflow:

Raw text (CSV)
→ Text cleaning & normalization
→ Sentiment scoring (VADER)
→ Sector keyword mapping
→ Aggregation
→ Output CSV

The same pipeline can be reused for new subreddits or time periods without changes to the core logic.

## How to Run

Install dependencies:
python3 -m pip install -r requirements.txt

Prepare input data:
Place a CSV file in nlp_pipeline/data/raw/ with a column named `text`.

Run the pipeline:
python3 nlp_pipeline/run_pipeline.py

## Output

The pipeline produces:
nlp_pipeline/data/processed/final.csv

The output contains sector-level sentiment aggregates, comment counts, and mean VADER compound scores.

## Design Choices

- Sentiment Analysis: VADER for transparent, rule-based scoring
- Sector Mapping: Keyword-based lookup tables for interpretability
- Preprocessing: Standardized and configurable text cleaning
- Pipeline Design: Modular components with a single entry point

## Technologies

- Python
- pandas
- vaderSentiment

