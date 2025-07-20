# 📦 MkDocs Template

This is a ready-to-use MkDocs template designed for quick deployment using **Cloudflare Pages** or **Cloudflare Workers**, with built-in support for **Dependabot** and **Dev Containers**.

## 🛠️ Setup Instructions

### 🔧 GitHub

1. Click **Use this template** on the repository page  
2. Create a new repository from the template  
3. Give it a name and click **Create repository**  

## 🚀 Quick Start (Dev Container)

You can run and develop this project inside a fully configured Dev Container using **Visual Studio Code** and **Docker**.

### ✅ Prerequisites

- [Docker](https://www.docker.com/get-started) installed and running  
- [Visual Studio Code](https://code.visualstudio.com)  
- [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) installed in VS Code

### ▶️ Launch Dev Container

1. Open this repository in VS Code
2. Then follow the instructions for your OS:\
•	macOS: Press Command + Shift + P → type Dev Containers: Reopen in Container → press Enter\
•	Windows: Press Ctrl + Shift + P → type Dev Containers: Reopen in Container → press Enter
4. VS Code will build the container and install all dependencies automatically

Once inside the container, you can serve the site locally:

```bash
mkdocs serve -a 0.0.0.0:8000
```

Then open `http://localhost:8000` in your browser to preview.

### 🌐 Deploy to Cloudflare Pages

Let’s build and deploy the site via **Cloudflare Pages**:

1. Open your [Cloudflare Dashboard](https://dash.cloudflare.com)  
2. Go to **Compute → Workers & Pages** → click **Pages**  
3. Click **Create a project**
4. Connect your GitHub account if prompted  
5. Select the newly created repository  
6. In **Build Settings**, choose **MkDocs** as the framework  
7. Leave the rest as default and click **Save and Deploy**

### ⚡ Deploy to Cloudflare Workers (Optional)

Alternatively, deploy your site via **Cloudflare Workers** for more flexibility:

1. Open your [Cloudflare Dashboard](https://dash.cloudflare.com)
2. Go to **Compute → Workers & Pages**
3. Click **Get Started** under **Import a Repository**
4. Connect your GitHub account (if not already)
5. Select your repository and begin setup
6. Enter a project name
7. Leave other settings as default and click **Create and Deploy**
8. You can customize `wrangler.jsonc` to your own liking.

Feel free to customize the site content, theme, or CI workflow to match your project needs!
