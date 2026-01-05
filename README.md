# Forkify

A recipe search application built with vanilla JavaScript.

This project focuses on **structure, data flow, and maintainability** rather than UI frameworks or abstractions.

---

## Overview

Forkify allows users to:

- Search recipes from an external API  
- View detailed recipe information  
- Update servings dynamically  
- Bookmark recipes  
- Persist state across sessions  

The goal was not speed of development, but **clarity of architecture**.

---

## Architecture

The app follows a strict **MVC pattern**:

- **Model**  
  Handles state, API communication, and business logic

- **View**  
  Responsible for rendering and DOM updates

- **Controller**  
  Coordinates application flow and user interactions

Each part has a single responsibility.  
Nothing knows more than it needs to.

---

## Tech

- JavaScript (ES6+)
- HTML
- SCSS
- Parcel
- Public recipes API

No frameworks. No magic.

---

## Why this project exists

This project exists to:

- Practice real state management without libraries  
- Understand async JavaScript deeply  
- Build a non-trivial app without hiding complexity  
- Write code that can be reasoned about months later  

It is intentionally not “clever”.

---

## Running locally

```bash
npm install
npm start
