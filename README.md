# AI Hackathon

![banner](./images/ai-hackerthon-ms-ndc.jpeg)

## 📑 Table of Contents  

- [AI Hackathon Repository](#ai-hackathon-repository)  
- [Prerequisites](#prerequisites)  
  - [Linux Setup](#linux-setup)  
  - [Windows Setup](#windows-setup)  
- [Hackathon Timetable](#hackathon-timetable)  
- [JavaScript Monorepos Documentation](#javascript-monorepos-documentation)  
  - [What is a Monorepo?](#what-is-a-monorepo)  
  - [Benefits of Monorepos](#benefits-of-monorepos)  
  - [Tools for JavaScript Monorepos](#tools-for-javascript-monorepos)  
- [AI-Assisted Development Documentation](#ai-assisted-development-documentation)  
  - [What is AI-Assisted Development?](#what-is-ai-assisted-development)  
  - [Benefits of AI-Assisted Development](#benefits-of-ai-assisted-development)  
  - [Microsoft Tools for AI-Assisted Development](#microsoft-tools-for-ai-assisted-development)  
  - [Getting Started with AI-Assisted Development](#getting-started-with-ai-assisted-development)  


# AI Hackathon Repository  

Welcome to the official repository for the **AI Hackathon** under the theme **AI-Assisted Development and JavaScript Monorepos**.  
This repository will guide participants with resources, examples, and instructions to explore how artificial intelligence can boost productivity and collaboration in monorepo environments.  

---

## Prerequisites  

Before starting, make sure your environment is set up.  

### Linux Setup  

1. **Update your system packages**
   ```bash
   sudo apt update && sudo apt upgrade -y

2. **Install Git**
    ```bash
        sudo apt install git -y
        git --version

3. **Install Node.js (v18 LTS) & npm**
    ```bash
        curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
        sudo apt install -y nodejs
        node -v
        npm -v

4. **Install VS Code (recommended editor)**
    ```bash
        sudo apt install snap -y
        sudo snap install code --classic

### Windows Setup  

For Windows users, download and install the following:  

- [Git for Windows](https://git-scm.com/download/win)  
- [Node.js (v18 LTS)](https://nodejs.org/en/download/)  
- [Visual Studio Code](https://code.visualstudio.com/download)  

After installation, confirm versions in **PowerShell**:  
```powershell
    git --version
    node -v
    npm -v
```

## Hackathon Timetable

| Time          | Activity                                           |
|---------------|---------------------------------------------------|
| **09:00 – 09:30** | Registration & Icebreaker                        |
| **09:30 – 10:00** | Opening + Explain Theme, Rules & Resources        |
| **10:00 – 12:30** | Hacking Session 1                                |
| **12:30 – 01:30** | Snacks & Networking                              |
| **01:30 – 03:30** | Hacking Session 2 + Mentors Roaming              |
| **03:30 – 04:00** | Demos, Judging, Prizes, and Closing              |



## JavaScript Monorepos Documentation  

### What is a Monorepo?  

A **monorepo** (short for *monolithic repository*) is a single Git repository that contains multiple projects. Instead of managing each project in its own repository, all related codebases live in one place.  

In JavaScript/TypeScript development, monorepos are often used to:  
- Share code between multiple apps and packages  
- Simplify dependency management  
- Improve collaboration across teams  
- Enable consistent tooling, CI/CD pipelines, and testing  

For example, a monorepo might include:  
- A frontend app (React, Vue, or Angular)  
- A backend service (Node.js/Express)  
- Shared UI components or utilities  
- Configuration and scripts for CI/CD  

---

### Benefits of Monorepos  

- **Code Sharing** → Reuse components across multiple projects.  
- **Single Source of Truth** → All code lives in one repo.  
- **Atomic Changes** → Update multiple packages in one commit/PR.  
- **Centralized CI/CD** → One pipeline for testing, building, and deployment.  
- **Scalability** → Supports large codebases and teams.  

---

### Tools for JavaScript Monorepos  

Several tools make working with JavaScript monorepos easier:  

- [**Turborepo**](https://turbo.build/repo) → High-performance build system for JavaScript & TypeScript monorepos.  
- [**Nx**](https://nx.dev/) → Extensible monorepo framework with generators, executors, and caching.  
- [**Lerna**](https://lerna.js.org/) → Popular tool for managing JavaScript projects with multiple packages.  
- [**pnpm Workspaces**](https://pnpm.io/workspaces) → Fast, disk-efficient package manager with workspace support.  
- [**Yarn Workspaces**](https://classic.yarnpkg.com/lang/en/docs/workspaces/) → Workspace support built into Yarn.  

---

## AI-Assisted Development Documentation  

### What is AI-Assisted Development?  

**AI-Assisted Development** is the use of artificial intelligence tools to help developers write, debug, optimize, and maintain code.  
Instead of replacing developers, AI tools act as **co-pilots** — making suggestions, generating boilerplate code, refactoring, and even documenting code automatically.  

In hackathons, AI assistance helps teams move faster, learn new tools, and focus on solving problems instead of repetitive coding tasks.  

---

### Benefits of AI-Assisted Development  

- **Faster Prototyping** → Quickly generate code and try new ideas.  
- **Reduced Boilerplate** → Automate repetitive coding tasks.  
- **Error Detection** → AI can suggest fixes and optimizations.  
- **Learning Tool** → Great for exploring new frameworks or languages.  
- **Collaboration** → AI can serve as a shared assistant across teams.  

---

### Microsoft Tools for AI-Assisted Development  

Since this event is sponsored by Microsoft, here are **free and open-source tools** you can use during the hackathon:  

#### 1. [Visual Studio Code (VS Code)](https://code.visualstudio.com/)  
- Free and open-source editor used worldwide.  
- Rich ecosystem of extensions.  
- Integrates with AI tools like GitHub Copilot.  

#### 2. [GitHub Copilot Free for Students](https://github.com/features/copilot)  
- AI pair programmer that suggests code and completions in real-time.  
- Free for verified students, teachers, and open-source maintainers.  
- Integrates seamlessly with VS Code.  

#### 3. [Semantic Kernel](https://github.com/microsoft/semantic-kernel)  
- Open-source SDK from Microsoft for integrating AI models into apps.  
- Works with Azure OpenAI Service, Hugging Face, and local LLMs.  
- Helps developers combine **AI orchestration + traditional programming**.  

#### 4. [Azure OpenAI Service](https://azure.microsoft.com/en-us/products/ai-services/openai-service/) *(Free Trial Available)*  
- Provides access to OpenAI models (GPT, Codex, DALL·E) via Microsoft Azure.  
- Offers enterprise-grade security, compliance, and scalability.  
- Free credits available with an Azure account for experimentation.  

#### 5. [Azure Machine Learning Studio](https://learn.microsoft.com/en-us/azure/machine-learning/) *(Free Tier)*  
- Cloud-based platform for training and deploying ML models.  
- Drag-and-drop interface + code-first options.  
- Free tier available for beginners and hackathon projects.  

---

### Getting Started with AI-Assisted Development  

#### Install VS Code & GitHub Copilot  

1. [Download and install VS Code](https://code.visualstudio.com/download).  
2. Open VS Code and go to the **Extensions Marketplace**.  
3. Install the [GitHub Copilot extension](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot).  
4. Sign in with your GitHub account.  
5. Start coding — Copilot will suggest completions automatically.  

#### Example: Using Copilot in JavaScript  

```javascript
// Write a comment describing the function
// Copilot will suggest the implementation

// Function to calculate factorial of a number
function factorial(n) {
    if (n <= 1) return 1;
    return n * factorial(n - 1);
}
