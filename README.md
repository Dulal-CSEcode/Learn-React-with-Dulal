# React Introduction and Setup Guide

This document provides an introduction to React, a popular JavaScript library for building user interfaces, and guides you through setting up a React environment using two common tools: **Create React App (CRA)** and **Vite**. Additionally, it covers the basics of JSX and React components.

---

## Table of Contents
1. [What is React?](#what-is-react)
2. [Advantages of React](#advantages-of-react)
3. [Setting up a React Environment](#setting-up-a-react-environment)
   - [Using Create React App (CRA)](#using-create-react-app-cra)
   - [Using Vite](#using-vite)
4. [JSX Basics](#jsx-basics)
5. [Components in React](#components-in-react)
   - [Functional Components](#functional-components)
   - [Class Components](#class-components)

---

## What is React?

React is a JavaScript library developed by Facebook for building user interfaces, especially for single-page applications (SPAs). It allows developers to create reusable UI components that update efficiently in response to data changes. React follows a component-based architecture and uses a **virtual DOM** for optimized rendering.

---

## Advantages of React

React offers several advantages that make it a popular choice for front-end development:

1. **Component-Based Architecture** - Code is divided into reusable components, making development and maintenance easier.
2. **Virtual DOM** - React updates only the necessary parts of the UI, improving performance.
3. **Unidirectional Data Flow** - Ensures better control over data and prevents unintended side effects.
4. **Fast and Efficient** - Uses a lightweight representation of the real DOM (virtual DOM) for optimal performance.
5. **Strong Community Support** - A large ecosystem of developers, tools, and third-party libraries.
6. **React Native** - Allows mobile app development using the same React principles.

---

## Setting up a React Environment

There are multiple ways to set up a React environment. Below are two commonly used methods:

### Using Create React App (CRA)

Create React App (CRA) is a boilerplate tool that sets up a new React project with a good default configuration.

#### Steps to set up a React project using CRA:

1. Install **Node.js** (which includes npm or yarn).
2. Open a terminal and run the following commands:

   ```bash
   npx create-react-app my-app
   cd my-app
   npm start
