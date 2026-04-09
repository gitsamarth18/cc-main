# 💪 Health Calculator - BMI & Calorie Tracker

**Programmed & Developed by: Samarth Mahale**

## Overview

Welcome to your personal Health Calculator! This is a modern, interactive web application designed to help you track your BMI (Body Mass Index) and calculate your daily calorie needs with ease. Perfect for anyone starting their fitness journey!

## Features

### 📊 BMI Calculator
- **Easy Input**: Enter your weight (in kg) and height (in cm)
- **Instant Calculation**: Get your BMI value instantly
- **BMI Categories**: 
  - 🔵 **Underweight**: BMI < 18.5
  - 🟢 **Normal Weight**: BMI 18.5 - 24.9
  - 🟠 **Overweight**: BMI 25.0 - 29.9
  - 🔴 **Obese**: BMI ≥ 30
- **Reset Function**: Clear inputs and results with a single click

### 🔥 Calorie Calculator
- **Comprehensive Inputs**:
  - Age (years)
  - Gender (Male/Female)
  - Weight (kg)
  - Height (cm)
  - Activity Level
- **Activity Level Options**:
  - 🛋️ Sedentary (little to no exercise)
  - 🚶 Light Activity (1-3 days/week)
  - 🏃 Moderate Activity (3-5 days/week)
  - 💪 Very Active (6-7 days/week)
- **Mifflin-St Jeor Formula**: Uses scientifically-backed BMR (Basal Metabolic Rate) calculation
- **Reset Function**: Clear all inputs and results easily

## Design Highlights

- **Modern UI**: Beautiful gradient backgrounds with smooth animations
- **Responsive Design**: Works perfectly on desktop and mobile devices
- **Glassmorphism Effect**: Frosted glass card design for a contemporary look
- **Smooth Animations**: Fade-in, slide-in, and gradient shift animations
- **Dark Mode**: Easy on the eyes with a professional dark theme
- **Welcome Modal**: First-time users are greeted with an introduction

## How to Use

1. **For BMI Calculation**:
   - Enter your weight in kilograms
   - Enter your height in centimeters
   - Click "Calculate BMI"
   - View your BMI value and category

2. **For Calorie Calculation**:
   - Enter your age
   - Select your gender
   - Enter your weight in kilograms
   - Enter your height in centimeters
   - Select your activity level
   - Click "Calculate Calories"
   - View your recommended daily calorie intake

## Technical Stack

- **HTML5**: Semantic markup
- **CSS3**: Advanced styling with gradients, animations, and media queries
- **JavaScript**: Vanilla JS for calculations and DOM manipulation

## Calculations Explained

### BMI Formula
```
BMI = Weight (kg) / Height (m)²
```

### Calorie Calculation (Mifflin-St Jeor Equation)

**For Males**:
```
BMR = (10 × weight) + (6.25 × height) - (5 × age) + 5
Daily Calories = BMR × Activity Factor
```

**For Females**:
```
BMR = (10 × weight) + (6.25 × height) - (5 × age) - 161
Daily Calories = BMR × Activity Factor
```

## Getting Started

Simply open the `bmi-calc.html` file in your web browser to start using the calculator. No installation or dependencies required!

## Browser Compatibility

- Chrome/Edge (recommended)
- Firefox
- Safari
- Any modern browser supporting ES6 JavaScript

## Features

✅ Real-time calculations
✅ Color-coded results
✅ Local storage for welcome modal state
✅ Input validation
✅ Responsive mobile design
✅ Smooth animations and transitions
✅ Easy reset functionality
✅ No external dependencies

## Tips

- For accurate BMI calculation, ensure your height is in centimeters
- The calorie calculation is based on the Harris-Benedict variant (Mifflin-St Jeor)
- Adjust your calorie intake based on your fitness goals (typically -500 to maintain, +500 to gain)
- Consult a healthcare professional for personalized dietary advice

---

**Enjoy tracking your health journey! 💪**
