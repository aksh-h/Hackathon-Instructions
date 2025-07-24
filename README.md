

# 🚀  AI-Codathon 2025 – Participant Instructions <img width="35" height="35" alt="image" src="https://github.com/user-attachments/assets/48fc7703-6100-4373-b1c5-cc787cdc82cf" />
---
Welcome to the Codathon! This guide provides everything you need to know—from setting up your project, using GitHub Copilot effectively, to submitting your solution.
---

## ⏱️ Codathon Rules & Participation Guidelines

1. **Team-Based Challenge Allocation**  
   - Each team will be assigned a **unique challenge/problem statement**.  
   - Individual contributions are critical to completing the challenge successfully.  
   - Collaboration and communication within the team will be key.

2. **Time Limit**  
   - You will have exactly **2 hours** to complete the challenge.  
   - Ensure your code is committed and pushed before the deadline.

3. **Use of GitHub Copilot**  
   - You must use **GitHub Copilot** as your AI code assistant during the codathon.  
   - Prompt examples, suggestions, and completions will be **evaluated as part of your score**.

4. **Language Flexibility**  
   - You can use any programming language of your choice.  
   - Ensure the language/tooling matches the problem domain and supports testability.

5. **Copilot Access Setup**  
   - If you do not already have GitHub Copilot enabled, you can **activate a free trial** at the link below:  
     👉 [Enable GitHub Copilot](https://github.com/github-copilot/signup?ref_cta=Copilot+trial&ref_loc=about+github+copilot&ref_page=docs)  
   - After signup, log in to your **favorite IDE (VS Code, JetBrains, etc.)** to start using Copilot.
6. **Final Presentation**
   - One member should act as Team Presenter for the final showcase
---

## 📦 What to Build

You are required to build an end-to-end solution based on the given problem statement. It should include:

- Well-documented BRD and TSD
- Modular code with full-stack implementation
- Clean UI (if applicable)
- Unit & integration tests
- CI/CD pipeline
- Security integrations (SAST, SCA, secret scanning)

---

## 🧭 Project Structure

Use the following structure for consistency and easier evaluation:


```
/project-root
│
├── docs/
│   ├── BRD.pdf / BRD.md
│   ├── TSD.pdf / TSD.md
│   └── architecture.png / architecture.md
│
├── src/
│   ├── backend/
│   └── frontend/
│
├── tests/
│
├── .github/
│   └── workflows/
│
├── deploy/
│   ├── azure-pipeline.yml
│   └── docker-compose.yml
│
├── security/
│   ├── sast/
│   └── secret-scanning/
│
└── README.md

```

---

## 🤖 GitHub Copilot Guidelines

You’re encouraged to use GitHub Copilot to boost productivity. Judges will evaluate **how well you use AI to accelerate your development**.

### ✅ Effective Copilot Usage

- Use clear, targeted prompts
- Include useful prompts as code comments
- Annotate your Copilot-generated code where applicable

---

## ✅ Evaluation Criteria (100 points)

| Category                          | Points |
|----------------------------------|--------|
| Business Requirements Document   | 5     |
| Technical Specification Document | 10     |
| Architecture Diagram             | 10     |
| Working Solution                 | 15     |
| Coding Standards                 | 10     |
| Effective Copilot Prompts        | 10      |
| Test Cases                       | 10     |
| CI/CD Pipeline                   | 10     |
| Security Integrations            | 10     |
| Bonus (UX, innovation, logs)     | 10     |
| **Total**                        | **100**|

---

## 🧪 Submission Checklist

✅ Include BRD and TSD in `/docs`  
✅ Architecture diagram as image or Mermaid  
✅ Working application with source code in `/src`  
✅ Automated tests in `/tests`  
✅ CI/CD scripts in `.github/workflows` or `deploy/`  
✅ Include a `README.md` with:
- Setup steps
- Tech stack
- Run/test instructions
- Prompt examples used with GitHub Copilot

---

## 🔐 Suggested Tools

**Tools Flexibility**  
   - You can use tool of your choice for the below areas, not limited to the below mentioned 

| Area           | Tools                            |
|----------------|----------------------------------|
| CI/CD          | GitHub Actions, Azure Pipelines  |
| Testing        | Pytest, xUnit                    |
| SAST           | SonarQube, CodeQL, Snyk          |
| SCA            | OWASP Dependency-Check, Snyk     |
| Secrets Scan   | truffleHog, GitHub Secret Scan   |
| Deployment     | Docker, Azure App Service, AKS   |

---

## 📬 How to Submit

1. Push your code, scripts, etc, generated as part of the hackathon to your GitHub repository.
2. Ensure your repo follows the folder structure.
3. Optional: Record a short demo

---

## 🏆 Bonus Points

Earn extra marks for:
- Great UX design
- Performance optimizations
- Clean logging/observability
- Reusability and scalability

## 🕒 Codeathon Event Timeline

| Activity                   | Time Slot         |
|----------------------------|-------------------|
| 🟢 **Codeathon Kickoff**      | 2:30 PM            |
| 🧠 **Development Time**       | 3 PM – 5:00 PM   |
|   - Implement code          |                   |
|   - Test thoroughly         |                   |
|   - Push code to GitHub     |                   |
|   - Add documentation       |                   |
|   - Submit DB scripts       |                   |
|   - Create basic infra + deploy |             |
| 🔍 **Team Evaluation**    | 5:00 PM – 5:15 PM   |
| 🧑‍⚖️ **Panel Evaluation**      | 5:15 PM – 5:45 PM   |
| 🏆 **Prize Distribution**     | 5:45 PM – 6:00 PM   |

⏱️ Stay on time and make sure your GitHub repo is up-to-date with all required components by **5:00 PM** sharp!

---

## 📢 Need Help?

If you get stuck or need support:
- Ask mentors
- Use Copilot! It’s your assistant throughout

---

Happy Coding! 💻🚀  
**— The Codathon Team**
