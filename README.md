# Aircraft Damage Prediction

![image](https://github.com/ShreyaPatil1199/Aircraft_Damage_Prediction/assets/135635788/272750da-7b60-4639-b269-9185fab11b07)

![Python 3](https://img.shields.io/badge/Python-3-blue.svg)

## Overview

The Aviation Accident Damage Analysis project, powered by data from the National Transportation Safety Board (NTSB), aims to comprehensively investigate and analyze aviation accidents to gain insights into the root causes and consequences of these incidents.

## Table of Contents

  - [Objective](#objective)
    
  - [Dataset Information](#dataset-information)

  - [Roadmap](#roadmap)

## Objective

The primary objective of the Aviation Accident Damage Analysis project is to investigate and analyze aviation accidents thoroughly. The project seeks to understand the causes and consequences of these incidents, ultimately contributing to improved aviation safety.

## Dataset Information

The dataset used in this project is sourced from the National Transportation Safety Board (NTSB) and contains information related to aviation accidents. Below is a list of columns in the dataset along with brief descriptions:

      Event.Id: A unique identifier for each aviation accident event.
      
      Investigation.Type: Describes the type of investigation conducted for the accident (e.g., "Incident," "Accident").
      
      Accident.Number: A unique identifier for each aviation accident case.
      
      Event.Date: The date when the accident occurred.
      
      Location: The location where the accident took place.
      
      Country: The country in which the accident occurred.
      
      Latitude: The latitude coordinates of the accident location.
      
      Longitude: The longitude coordinates of the accident location.
      
      Airport.Code: A code representing the airport associated with the accident.
      
      Airport.Name: The name of the airport where the accident occurred.
      
      Injury.Severity: The severity of injuries resulting from the accident (e.g., "Fatal," "Serious," "Minor").
      
      Aircraft.damage: Describes the extent of damage to the aircraft (e.g., "Substantial," "Minor," "Destroyed").
      
      Aircraft.Category: Categorizes the aircraft.
      
      Registration.Number: The registration number of the aircraft involved in the accident.
      
      Make: The manufacturer or make of the aircraft.
      
      Model: The model of the aircraft.
      
      Amateur.Built: Indicates whether the aircraft was amateur-built ("Yes" or "No").
      
      Number.of.Engines: The number of engines on the aircraft.
      
      Engine.Type: The type of engine(s) used on the aircraft.
      
      FAR.Description: Description related to Federal Aviation Regulations (FAR) applicable to the accident.
      
      Schedule: Information about the flight schedule (e.g., "Scheduled," "Non-scheduled").
      
      Purpose.of.flight: The purpose of the flight (e.g., "Personal," "Business").
      
      Air.carrier: The name of the air carrier, if applicable.
      
      Total.Fatal.Injuries: The total number of fatal injuries in the accident.
      
      Total.Serious.Injuries: The total number of serious injuries in the accident.
      
      Total.Minor.Injuries: The total number of minor injuries in the accident.
      
      Total.Uninjured: The total number of individuals who were uninjured in the accident.
      
      Weather.Condition: Weather conditions at the time of the accident (e.g., "Clear," "Cloudy").
      
      Broad.phase.of.flight: The phase of flight during which the accident occurred (e.g., "Takeoff," "Cruise").
      
      Report.Status: The status of the accident report (e.g., "Preliminary," "Final").
      
      Publication.Date: The date when the accident report was published.

## Roadmap

    Phase 1: Project Setup and Data Collection
          
              Task 1: Project Inception
                      Define project objectives and goals.
                      
              Task 2: Data Collection
                      Identify and acquire relevant datasets for aircraft damage prediction.
                      Perform data exploration and initial data quality checks.

        
    Phase 2: Data Preprocessing and EDA
    
              Task 3: Data Preprocessing
                      Clean and preprocess the acquired data.
                      Handle missing values and outliers.
                      Feature engineering to create relevant features.
                      
              Task 4: Exploratory Data Analysis (EDA)
                      Conduct comprehensive EDA to understand data patterns.
                      Visualize data distributions and relationships.
                      Identify potential correlations between features and damage.
                
    Phase 3: Model Development
    
              Task 5: Model Selection
                      Research and select appropriate machine learning algorithms for damage prediction.
                      Establish a baseline model for performance comparison.
                      
              Task 6: Model Training and Tuning
                      Train machine learning models using the preprocessed data.
                      Optimize hyperparameters and model architecture.
                      Evaluate models using relevant metrics (e.g., accuracy, precision, recall).
                      
              Task 7: Model Validation
                      Perform cross-validation and testing to assess model generalization.
                      Address overfitting or underfitting issues as needed.
