# Phishing Protection Browser Extension

A lightweight browser extension designed to provide proactive protection against phishing websites by analyzing URLs before users access potentially malicious pages.

## Project Overview

Phishing attacks are commonly used to trick users into visiting malicious websites and revealing sensitive information. This project implements a browser-based phishing protection system that evaluates websites using multiple detection techniques and provides users with an early warning or blocking mechanism.

The extension combines **blacklist checking, heuristic-based URL analysis, and machine learning** to identify potentially harmful websites.

## Key Features

- Real-time phishing website detection
- Blacklist-based URL checking
- Heuristic-based URL analysis
- Machine learning-based phishing detection
- Warning/blocking mechanism for suspicious websites
- Browser extension popup interface
- FastAPI backend integration
- Local storage for extension-related data
- Lightweight design with focus on fast detection

## How It Works

1. The user attempts to visit a website.
2. The browser extension captures the navigation event.
3. The website URL is checked against known phishing URLs.
4. If the URL is not found in the blacklist, heuristic and machine learning-based analysis is performed.
5. The system evaluates the risk of the website.
6. Depending on the result, the extension allows the website, displays a warning, or blocks access.

## Technologies Used

- **JavaScript**
- **HTML & CSS**
- **Chrome Extension APIs**
- **Python**
- **FastAPI**
- **Machine Learning**
- **Scikit-learn**
- **XGBoost**
- **Random Forest**
- **SVM**
- **Logistic Regression**

## Project Structure

The project consists of a browser extension component and a Python-based backend for phishing detection and analysis.

## Installation

1. Clone or download this repository.
2. Extract the project files.
3. Open Google Chrome and navigate to:
   `chrome://extensions/`
4. Enable **Developer mode**.
5. Select **Load unpacked**.
6. Select the browser extension folder.
7. The extension will be added to Chrome.

## Purpose

The main purpose of this project is to provide an additional layer of protection against phishing attacks by detecting suspicious websites before users interact with them.

## Project Type

**Final Year Project (FYP)**  
**Domain:** Cybersecurity / Machine Learning  
**Application:** Browser-based Phishing Protection
