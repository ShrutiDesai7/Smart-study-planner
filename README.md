__📘 Smart Study Planner (AI-Powered)__

🧠 Overview

The Smart Study Planner is a simple AI-inspired Python project that helps students plan their daily study schedule intelligently — without using any external dataset.
It asks for user input such as subjects, available time, and difficulty levels, then applies AI-like logic (weighted priority calculation) to recommend an optimized study plan.

This project simulates the decision-making process of an AI system — balancing difficulty, importance, and available time.

🚀 Features

✅ Takes input for subjects, difficulty, and time available
✅ Calculates priority score using a weighted logic model
✅ Generates a personalized study plan
✅ Suggests ideal study durations per subject
✅ Lightweight — no datasets or external dependencies
✅ Beginner-friendly and easy to expand

⚙️ Tech Stack

Language: Python 3

Libraries: Only built-in modules (random, datetime)

💡 How It Works

The user inputs a list of subjects and rates each on:

Difficulty (1–5)

Importance (1–5)

The system calculates a priority score for each subject using a simple AI-like formula:

priority = (0.6 * difficulty) + (0.4 * importance)


Based on the available study time, it allocates hours per subject proportionally to the priority score.

It then displays an optimized study schedule and motivational tip.
