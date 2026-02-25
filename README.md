# EcoScore Pakistan 🌱

**A web-based EcoScore calculator to measure personal environmental impact and suggest sustainable actions.**

---

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Built With](#built-with)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Contributing](#contributing)
- [License](#license)

---

## About the Project
EcoScore Pakistan helps individuals understand how their daily habits impact the environment. By entering data such as **public transport usage, flights per year, meat meals, electricity usage, recycling habits, heating type, and shopping frequency**, the app calculates a personalized EcoScore out of 100.  

The project was inspired by the need for **simple, actionable tools** to encourage sustainable behavior.  

Mathematically, the score is calculated as:

$$
\text{EcoScore} = 100 - 2(7 - PT) - 5F - 1.5M - 0.03E + 0.2R + H + S
$$

Where:  
- \(PT\) = public transport days/week  
- \(F\) = number of flights per year  
- \(M\) = meat meals per week  
- \(E\) = electricity consumption (kWh)  
- \(R\) = recycling percentage  
- \(H\) = heating modifier (+5 for solar, -3 for electric, -5 for gas)  
- \(S\) = shopping frequency modifier (-5 for frequent, -2 for occasional, 0 for rare)  

---

## Features
- Calculates a personalized **EcoScore** based on lifestyle habits  
- Highlights positive and negative environmental actions  
- Responsive and professional **UI** for desktop and mobile  
- Easy-to-use **web interface**  

---

## Built With
- **HTML, CSS, JavaScript** – core web technologies  
- **Google Fonts** – Inter font for professional typography  
- **Responsive Web Design** – works across devices  
