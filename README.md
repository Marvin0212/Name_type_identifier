# Name Classification

## Overview

This project classifies names as first names or last names using two methods:

### 1. N-Gram Model

- **How It Works:** Breaks names into sequences of characters (n-grams), calculates probabilities, and classifies based on the likelihood of n-grams.
- **Performance:** ~75% accuracy; struggles with names that can be both first and last names.

### 2. Rule-Based Model

- **How It Works:** Uses name formatting rules (e.g., commas, prepositions) to improve classification of ambiguous names.