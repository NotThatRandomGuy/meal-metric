# MealMetric

## Table of Contents

1. Overview
2. Product Spec
3. Wireframes

## Overview

### Description

MealMetric is an iOS application designed to help individuals make more informed nutritional and financial decisions when consuming fast food.

The application retrieves nutritional information for restaurant menu items and processes this information through a custom nutritional analysis engine. Rather than exclusively presenting numerical information, MealMetric generates plain-English explanations of a meal's nutritional characteristics, potential effects on satiety and energy levels, and recommendations for balancing nutritional intake throughout the remainder of the day.

Additionally, users can enter the monetary cost of their meals to calculate economic metrics such as calories per cent, calories per dollar, and protein per dollar.

### App Evaluation

- **Mobile:** MealMetric is designed for convenient use while ordering or consuming food. The application can utilize native mobile capabilities such as location services for nearby restaurant discovery, local notifications for dietary reminders, and the camera for receipt scanning.

- **Story:** Nutritional information is readily available but is not always presented in a manner that is easily understandable. MealMetric bridges this gap by interpreting nutritional information and providing practical explanations and recommendations.

- **Market:** The application targets regular fast-food consumers, college students, budget-conscious individuals, and individuals interested in monitoring their nutritional intake without requiring extensive nutritional knowledge.

- **Habit:** Users may interact with the application multiple times throughout the day when planning, purchasing, or consuming meals. Daily nutritional tracking and meal history encourage repeated use.

- **Scope:** The minimum viable product consists of restaurant menu retrieval, meal construction, nutritional analysis, economic calculations, and daily nutritional tracking. The modular structure allows additional functionality to be implemented incrementally throughout development.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

- [ ] User can browse restaurants and search for individual menu items.
- [ ] User can add, remove, and modify the quantities of items within a meal.
- [ ] User can view the combined nutritional information of a constructed meal.
- [ ] User can receive plain-English nutritional interpretations and potential effects on satiety and energy levels.
- [ ] User can enter the cost of a meal and view economic metrics, including calories per cent and calories per dollar.
- [ ] User can log meals and receive recommendations based on their remaining daily nutritional targets.
- [ ] User can configure their daily calorie target.

**Optional Nice-to-have Stories**

- [ ] User can discover nearby restaurants using location services.
- [ ] User can scan receipts using the device's camera.
- [ ] User can compare the nutritional and economic characteristics of multiple meals.
- [ ] User can receive notifications reminding them to log meals.
- [ ] User can view weekly and monthly nutritional statistics.
- [ ] User can mark restaurants and meals as favorites.
- [ ] User can synchronize nutritional information with Apple Health.

### 2. Screen Archetypes

**Home Screen**

- User can view their daily calorie target and current nutritional intake.
- User can view their remaining daily calorie allocation.
- User can view general dietary recommendations based on logged meals.

**Restaurant Selection Screen**

- User can browse available restaurants.
- User can search for a specific restaurant.
- User can select a restaurant to view its menu.

**Restaurant Menu Screen**

- User can browse and search available menu items.
- User can view individual nutritional information.
- User can add menu items to their meal.

**Meal Builder Screen**

- User can review selected menu items.
- User can modify quantities or remove items.
- User can enter the total monetary cost of the meal.
- User can initiate nutritional analysis.

**Meal Analysis Screen**

- User can view combined nutritional information.
- User can view plain-English nutritional interpretations.
- User can view potential effects on satiety and energy levels.
- User can view economic calculations.
- User can view recommendations for the remainder of the day.
- User can log the meal.

**Meal History Screen**

- User can view previously logged meals.
- User can select a previous meal to review its nutritional analysis.

**Settings Screen**

- User can configure daily nutritional targets.
- User can manage application preferences.

### 3. Navigation

**Tab Navigation (Tab to Screen)**

- Home
- Explore Restaurants
- Meal History
- Settings

**Flow Navigation (Screen to Screen)**

- Home Screen
  - Restaurant Selection Screen
  - Meal History Screen
  - Settings Screen

- Restaurant Selection Screen
  - Restaurant Menu Screen

- Restaurant Menu Screen
  - Meal Builder Screen
  - Restaurant Selection Screen

- Meal Builder Screen
  - Meal Analysis Screen
  - Restaurant Menu Screen

- Meal Analysis Screen
  - Home Screen
  - Meal Builder Screen

- Meal History Screen
  - Meal Analysis Screen (previously logged meal)

- Settings Screen
  - Home Screen

## Wireframes

Wireframe images will be added upon completion of the application wireframing activity.

### Digital Wireframes & Mockups

To be completed.

### Interactive Prototype

To be completed.
