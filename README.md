# 🌐 COULIB - Country-Based File Access Portal

Developed and Designed by **Engineer Syed Ather Rizvi (Full Stack Developer)**  
Title: **Specialist, MI Global Data In Quality at NielsenIQ**

---

## 📖 Project Overview

**COULIB** (Country Upload & Link Interface Base) is a lightweight, responsive web application designed to facilitate **country-based file access** for internal teams. It offers an intuitive UI that allows users to search by country code and instantly access related files or portals in one click.

---

## 🎯 Purpose

The primary goal of COULIB is to **streamline access to country-specific data files** for internal and external stakeholders in a clean, distraction-free interface. It replaces the manual process of remembering or navigating to multiple URLs based on country abbreviations or teams.

---

## ❗ Problem Statements Solved

1. **❌ Scattered Access Points**  
   Country-specific portals or files were hard to navigate or remember, especially when links changed or were inconsistent across teams.

2. **❌ Time-Consuming Search**  
   Users wasted time searching through bookmarks or documentation for a specific country’s data access point.

3. **❌ No Centralized UI**  
   No unified platform existed to input a simple 2-letter country code and get direct access.

---

## ✅ Key Features

| Feature | Description |
|--------|-------------|
| 🔍 **Dynamic Search Bar** | Type country code (e.g., `AE`) and get matching results with full country name. |
| 🎯 **Keyboard Navigation** | Use `↑`, `↓`, and `Enter` keys to navigate through suggestions. |
| 🧠 **Autocomplete Suggestions** | Automatically suggests available countries that match input. |
| 💼 **Direct File Access Links** | One-click access to files or portals mapped to country codes. |
| 🎨 **Animated Background** | Uses animated linear gradient for a modern visual appeal. |
| 🖼️ **Company Branding Tooltip** | Hover effect displays company name above logo (NielsenIQ). |
| 🧑‍💻 **Developer Hotkey** | Press `/` to quickly focus on the search bar (like modern productivity tools). |
| 📱 **Responsive Design** | Optimized for both desktop and mobile views. |

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3** (with gradients and media queries)
- **Vanilla JavaScript**
- **Favicon and Branding Assets**

---

## 🚀 How to Use

1. Open the portal in your browser.
2. Enter a **2-letter country code** (e.g., `AE` for UAE) in the search bar.
3. Choose the suggestion using your mouse or arrow keys + enter.
4. Click on the generated link to open the associated file or portal.

---

## 🗂️ Example Country Data (Customizable)

```javascript
const countryLinks = [
    { code: "AE", name: "United Arab Emirates", url: "#" },
    // Add more countries here as needed.
];
