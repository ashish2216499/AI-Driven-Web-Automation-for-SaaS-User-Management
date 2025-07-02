# CloudEagle Assignment – AI-Driven Web Automation for SaaS User Management

👋 Hi! I’m Ashish Sharma, and this repository is part of my submission for the **AI Product Manager Intern role at CloudEagle**.

---

## 📌 What This Project Is About

Many SaaS platforms (like Trello, Notion, Dropbox, etc.) let you manage users through a dashboard — but they don’t always offer public APIs to automate those tasks.

That means companies have to manually:
- Log in to each SaaS app
- Search for users
- Add or remove users one by one
- Copy email IDs or roles by hand
- Repeat this for every tool they use

This is time-consuming, repetitive, and hard to scale.

So the challenge was:
> **Can we use AI + automation to log into those dashboards, read user data, and take actions (like add/remove users) without needing APIs?**

---

## 🧠 My Solution (In Simple Words)

I proposed a system that behaves like a **smart assistant**.

It would:
- Log in to admin panels automatically
- Read all the user names, emails, and roles
- Save that info into a file or database
- Click buttons to add or remove users — just like a human would
- Handle things like login pages, “Next” buttons, pop-ups, or confirmation messages

This would save hours of manual work and could be used across different SaaS apps.

---

## 🧪 What’s Inside This Repo

This repo contains a **mini demo script** written in Python using **Selenium**.

The script shows:
- How to open Trello’s login page
- How to log in using email and password (with Atlassian SSO)
- How to navigate to the Members page
- How to scrape and print out member names
- How to take a screenshot as proof

📄 Even though this is a small test, it shows the **starting point** for how we could automate real user management workflows — even without an API.

---

## ⚙️ Tools & Technologies Used

| Tool         | Why I Used It                          |
|--------------|----------------------------------------|
| **Selenium** | Automates the browser like a real user |
| **Python**   | Easy and flexible for scripting        |
| **ChromeDriver** | Controls the Chrome browser         |

I also researched tools like:
- Playwright (alternative to Selenium)
- LangChain (for chaining AI logic)
- OpenAI GPT (to make the system smarter)
- 2Captcha API (to solve login CAPTCHAs if needed)

---

## 📸 Screenshot Proof

The script saves a screenshot (`trello_members.png`) from the Members page — this acts like a visual proof that the automation worked.

---

## 🙋 What I Learned

This project helped me understand:
- Real-world use of RPA + AI
- How PMs must think about both **user problems** and **technical feasibility**
- How to break a big idea into small testable steps
- The value of testing things hands-on — not just theory

---

## 📬 Final Note

I genuinely enjoyed working on this. While I’m still learning tools like Selenium and Playwright in depth, I approached this like a Product Manager — by thinking clearly, understanding real problems, and proposing something practical and scalable.

Thanks for the opportunity! I'm excited to grow, build, and contribute at CloudEagle 🚀

—  
Ashish Sharma  
[ashish2216499@gmail.com](mailto:ashish2216499@gmail.com)  
[linkedin.com/in/ashish-sharma-634974237](https://linkedin.com/in/ashish-sharma-634974237)

