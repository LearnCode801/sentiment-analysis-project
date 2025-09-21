# Sentiment Analysis Web Application

[![Demo Video](https://img.shields.io/badge/Demo-Video-red.svg)](https://drive.google.com/file/d/1W9i1v48yXyiDBh_cZ6bKTW0--0afTRaP/view?usp=sharing)

A simple web-based sentiment analysis application built with Flask and NLTK's VADER sentiment analyzer. This application allows users to input text and receive real-time sentiment analysis results through a clean web interface.

## Overview

This project demonstrates natural language processing (NLP) capabilities by analyzing the sentiment of user-provided text. It uses VADER (Valence Aware Dictionary and sEntiment Reasoner), which is specifically designed for social media text analysis and works well with informal language.

## Features

- **Real-time Sentiment Analysis**: Instant analysis of text input
- **Web Interface**: Clean and simple HTML form for user interaction
- **VADER Integration**: Uses NLTK's VADER sentiment analyzer
- **Three-class Classification**: Positive, Negative, or Neutral sentiment detection
- **Flask Backend**: Lightweight web framework for easy deployment
- **Compound Scoring**: Uses normalized compound scores for accurate sentiment detection

## Technical Specifications

- **Backend Framework**: Flask
- **NLP Library**: NLTK (Natural Language Toolkit)
- **Sentiment Analyzer**: VADER (Valence Aware Dictionary and sEntiment Reasoner)
- **Frontend**: HTML templates with Flask rendering
- **Scoring Range**: -1 (most negative) to +1 (most positive)
- **Classification Threshold**: score > 0 (positive), score < 0 (negative), score = 0 (neutral)

For questions or support, please create an issue in the GitHub repository.
