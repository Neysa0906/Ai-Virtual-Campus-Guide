# AI-Based Virtual Campus Guide

An **AI-based virtual campus guide** built using **Python, Streamlit and RapidFuzz**.  
The app works as a simple intelligent agent that helps students find information about **labs, facilities and clubs** using a searchable knowledge base.

This mini-project was developed in **3rd semester B.Tech CSE (AI & ML)**.

---

## Team Members

- Nandini A S  
- Niverthy Harshitha  
- Neysa Mary Pramod  
- Om Chavhan  

---

## My Contribution

- Helped design the overall agent behaviour and knowledge-base structure  
- Worked on the Streamlit UI layout (Browse / Ask / Admin panels)  
- Assisted with fuzzy-matching logic using RapidFuzz  
- Debugged the search results and JSON loading/saving  

---

## Features

- 🔍 **Search assistant**: type natural queries such as “Where is the AI lab?” or “gym hours”
- 📚 **Knowledge base** stored in `kb.json` (labs, facilities, clubs)
- 🎯 **Fuzzy matching** using RapidFuzz to handle typos and partial queries
- 🧭 **Browse panel** to quickly view entries by category
- 🛠️ **Admin panel** to add or update entries via JSON
- 💾 Knowledge base is persistent and editable without changing the code

---

## Technology Stack

- **Language:** Python  
- **Framework:** Streamlit  
- **Libraries:** RapidFuzz, json, pathlib  
- **Knowledge Representation:** JSON file (`kb.json`) acting as a simple rule-based KB

---

## How It Works

1. The app loads a **JSON knowledge base** (`kb.json`).  
2. When the user searches, the query is compared to all entries using **fuzzy string matching**.  
3. The top matches are displayed with:
   - category (lab / facility / club)  
   - location, hours, contact and notes  
4. Admin users can add new KB entries on the right panel by pasting a JSON object.

---

## Output

![Output 1](https://github.com/user-attachments/assets/568bc320-0c20-4579-ac34-660fca853c57)
![Output 2](https://github.com/user-attachments/assets/4daa8db7-952b-4f34-91d2-a14df6f5dc0d)
![Output 3](https://github.com/user-attachments/assets/7c98ee9c-e08f-40c0-963f-b5e3d84ea38d)
