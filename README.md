# THEO7_ChatBot_Build
A beginner-friendly chatbot project built using Replit + OpenAI
# THEO7_ChatBot_Build 🤖🔥

This project demonstrates a **beginner-friendly Python chatbot** built on [Replit](https://replit.com/) using the [OpenAI Python SDK](https://pypi.org/project/openai/). It was created as a simple proof-of-concept to show how you can build your own AI chatbot from scratch and document the process in a clean and visual way.

---

## 💻 Tech Stack

- **Python** (3.10+)
- **OpenAI API** (`gpt-3.5-turbo`)
- **Replit** (cloud-based IDE)

---

## 📸 Screenshots Included

| Step | Description |
|------|-------------|
| `01_Replit_Homepage.png` | Replit homepage interface, where users begin. |
| `02_replit_dashboard_existing_project.png` | Shows the existing chatbot project already created. Make sure new users click the green **"Create"** button circled in green in this image if starting fresh. |
| `03_chatbot_code_mainpy_view.png` | Full view of the `main.py` code. |
| `04_Theo7_Secrets_API_Key.png` | Location where your OpenAI API key must be added under the **"Secrets"** tab in Replit. |
| `05_Theo7_Run_Button_and_Console_Switch.png` | Shows how to click **Run** and switch over to the Console tab to start interacting. |
| `07_Theo7GPT_Quota_Error_Tutorial_Purpose.png` | Shows example of hitting OpenAI’s quota limit (included for tutorial purposes only). This does **not** mean your code is broken. |

---

## 🧠 How It Works

- The code connects to the OpenAI API using your secret key stored in Replit's environment variables.
- You interact with the chatbot through the Replit **Console**, where your messages are printed and responded to.
- The chatbot runs in a loop until you type `exit`.

---

## 📂 File Breakdown

| File | Purpose |
|------|--------|
| `main.py` | Core chatbot logic. Handles user input, API call, and printed response. |
| `.replit` | Config file for Replit (optional). |
| `README.md` | You're reading it. |
| `Secrets` | Securely stores your API key — never hardcode it into your script. |

---

## ⚠️ Notes

- This is an **educational build** for demonstration purposes.
- If your OpenAI credits are used up, you'll see a **quota exceeded error** — this is normal.
- API key must be valid and set in Secrets with the name `OPENAI_API_KEY`.

---

## ✨ Final Notes

This is an example of a hands-on chatbot build anyone can do in under 30 minutes. This repo also documents visual progress with clean screenshots for beginner clarity.

Feel free to fork, clone, or remix for your own chatbot builds. This is part of the ongoing Theo7 educational projects using Replit, OpenAI, and GitHub for digital proof-of-work.

---

🔗 **Author**: [Theo7Collectives LLC](https://github.com/Theo7Labs)


