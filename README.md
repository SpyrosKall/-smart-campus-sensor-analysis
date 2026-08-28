# Smart Campus Sensor Analytics
### Indoor Air Quality, Occupancy Intelligence & Operational Decision Support

This repository contains the complete data analysis and machine learning workflow developed for an undergraduate thesis focused on Smart Campus sensor data.

The project combines heterogeneous environmental and occupancy measurements to study indoor air quality, room usage, short-term CO₂ forecasting, natural ventilation support and potential lighting-related energy waste.

---

## 🇬🇷 Ελληνικά

### Περιγραφή έργου

Το παρόν αποθετήριο περιλαμβάνει τα notebooks, τον κώδικα και τις βασικές ροές επεξεργασίας που αναπτύχθηκαν στο πλαίσιο πτυχιακής εργασίας με αντικείμενο την ανάλυση και αξιοποίηση δεδομένων αισθητήρων σε περιβάλλον Smart Campus.

Η ανάλυση βασίζεται σε δεδομένα από τρεις πανεπιστημιακούς χώρους:

- Room 2.3
- Room 3.9
- Room 4.9

Η Room 4.9 διαθέτει την πληρέστερη διαμόρφωση αισθητήρων και αξιοποιείται στα περισσότερα προχωρημένα σενάρια.

### Βασικοί στόχοι

Το έργο περιλαμβάνει:

- προεπεξεργασία και ενοποίηση δεδομένων αισθητήρων,
- διερευνητική ανάλυση των συνθηκών εσωτερικού περιβάλλοντος,
- εκτίμηση πληρότητας χώρων,
- διόρθωση προβληματικών μετρήσεων people counter,
- πρόβλεψη συγκέντρωσης CO₂ 30 λεπτά στο μέλλον,
- υποστήριξη αποφάσεων φυσικού αερισμού,
- εντοπισμό πιθανών περιπτώσεων ενεργειακής σπατάλης φωτισμού.

---

## 🇬🇧 English

### Project Overview

This repository contains the notebooks, code and analytical workflows developed as part of an undergraduate thesis focused on Smart Campus sensor data.

The analysis is based on heterogeneous measurements collected from three monitored university rooms:

- Room 2.3
- Room 3.9
- Room 4.9

Room 4.9 provides the richest sensor configuration and is therefore used in most of the advanced application scenarios.

### Main Objectives

The project focuses on:

- preprocessing and integration of heterogeneous sensor data,
- exploratory analysis of indoor environmental conditions,
- occupancy estimation,
- correction of anomalous people-counter measurements,
- 30-minute-ahead CO₂ forecasting,
- natural ventilation decision support,
- detection of potential lighting-related energy waste.

---

# Project Workflow

The repository follows the complete analytical workflow of the thesis:

```text
Raw Sensor Data
      │
      ▼
Data Preprocessing
      │
      ▼
Processed Room Datasets
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Applied Scenarios
      │
      ├── Occupancy Estimation
      ├── CO₂ Forecasting
      ├── Natural Ventilation Decision Support
      └── Potential Energy Waste Detection
