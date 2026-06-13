# cooktodo

# 🍳 AI Cooking To-Do Planner

> Built for **PromptWars** — Google for Developers × H2S × Build with AI

A simple AI-powered micro-app that generates a personalized daily cooking plan based on your day, dietary preferences, and budget.

## ✨ Features

- **Meal Plan** — Breakfast, Lunch & Dinner suggestions with prep/cook time and calories
- **Grocery List** — Auto-generated shopping list based on your meals
- **Smart Substitutions** — Ingredient swaps with reasons (budget, dietary, availability)
- **Budget Feasibility** — Visual budget tracker with per-meal cost breakdown

## 🚀 Live Demo

👉 [https://arnav7777.github.io/cooktodo](https://arnav7777.github.io/cooktodo)

> You'll need your own [Anthropic API key](https://console.anthropic.com) to use the app. Your key stays in your browser only — never stored or shared.

## 🛠 Tech Stack

- Vanilla HTML, CSS, JavaScript — zero dependencies, zero frameworks
- Anthropic Claude API (`claude-sonnet-4-6`)
- Hosted on GitHub Pages

## 📸 How It Works

1. Enter number of people, budget, dietary preferences, and describe your day
2. Optionally tell it what's already in your pantry
3. Hit **Generate** — Claude plans your entire day of meals
4. Get your grocery list, substitutions, and budget check instantly

## 🏗 Run Locally

```bash
git clone https://github.com/arnav7777/cooktodo.git
cd cooktodo
# Open index.html in your browser — no build step needed
```

## 🔑 API Key

This app calls the Anthropic API directly from the browser. Enter your API key in the input field on the app — it is never sent anywhere except Anthropic's servers.

Get your key at [console.anthropic.com](https://console.anthropic.com)

## 📋 PromptWars Challenge

**Challenge:** A cooking to-do list  
**Requirements covered:**
- ✅ Breakfast / Lunch / Dinner meal plan
- ✅ Grocery list
- ✅ Substitutions
- ✅ Budget feasibility logic

---

Built with ❤️ using Claude AI
