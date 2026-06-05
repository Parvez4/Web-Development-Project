# Web Development Project - College Sikhsha

College Sikhsha is a simple PHP/MySQL college prediction system with login, signup, and an entrance-score based predictor.

## Live Demo

View the deployed static demo: [https://college-sikhsha-demo.vercel.app](https://college-sikhsha-demo.vercel.app)

## Project Overview

The original project is a student-facing web application built with PHP, MySQL, Bootstrap, and custom CSS. It includes authentication screens and a predictor form that suggests possible engineering college options based on board percentage and exam scores.

## Features

- Login and signup pages backed by a MySQL user table
- PHP session handling for authenticated navigation
- College predictor form for board percentage, JEE, BITS, SRMJEE, and VITEEE scores
- Rule-based eligibility output for IIT, NIT, BITS, SRM, and VIT
- Screenshots showing the original app flow

## Predictor Logic

The predictor checks:

- Board percentage must be at least 60
- Weighted board/JEE average above 87 suggests IIT eligibility
- Weighted board/JEE average above 60 suggests NIT eligibility
- BITS score above 280 suggests BITS eligibility
- SRMJEE score above 140 suggests SRM eligibility
- VITEEE score above 80 suggests VIT eligibility

## Tech Stack

- PHP
- MySQL / MariaDB
- Bootstrap
- HTML
- CSS
- JavaScript

## Note

The live demo is a static Vercel-hosted showcase that recreates the predictor logic and presents the original screenshots. The source project itself is a PHP/MySQL application intended for a local Apache/MySQL environment.
