# Life Affordability Calculator

An interactive budgeting tool that helps users estimate whether a future salary can support their lifestyle in different U.S. cities.

## What it does

The calculator takes a user's annual salary, selected city, monthly student-loan payment, and other monthly spending. It then estimates:

- monthly after-tax income
- total monthly expenses
- money remaining after expenses
- an affordability status: **Comfortable**, **Manageable**, **Tight Budget**, or **Not Affordable**

The current version includes Pittsburgh, Chicago, New York City, and Dallas, with city-specific rent estimates.

## How it works

The project is built with **Quarto, HTML, CSS, and JavaScript**. The calculator converts annual salary into an estimated monthly after-tax income, combines rent and user-entered expenses, and classifies the remaining budget using simple affordability thresholds.

> Note: The current calculator uses a simplified assumption that 75% of salary remains after taxes. It is intended as an exploratory budgeting tool rather than financial advice.

## Project structure

- `index.qmd` — main project page
- `calculator.qmd` — interactive calculator logic and interface
- `about.qmd` — project information
- `styles.css` — custom styling
- `_quarto.yml` — Quarto site configuration

## Why I built it

I created this project to combine software development with economic thinking and make cost-of-living comparisons easier to understand through an interactive tool.
