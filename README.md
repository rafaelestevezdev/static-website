# Azure Static Website with GitHub Actions

This is my first cloud computing project on Microsoft Azure. It is a simple static HTML website hosted on **Azure Blob Storage** with automatic deployment (**CI/CD**) using **GitHub Actions**.

---

## 🚀 Technologies Used

* **HTML5**: Web page content and structure.
* **Git & GitHub**: Version control and code repository.
* **GitHub Actions**: Automatic pipeline for CI/CD.
* **Microsoft Azure**: Blob Storage (Static Website feature).

---

## 🔄 How It Works

1. **Code**: I edit my `index.html` file on my local computer.
2. **Push**: I send the changes to GitHub with `git push origin main`.
3. **Deploy**: GitHub Actions starts automatically and connects to Azure.
4. **Publish**: The workflow updates the static files on the Azure public URL.

---

## ⚙️ Architecture & Setup

1. **Azure Storage Account**: Created a standard storage account with LRS redundancy.
2. **Static Website**: Enabled the static web hosting feature in Azure (`$web` container).
3. **GitHub Secret**: Saved the `AZURE_STORAGE_CONNECTION_STRING` safely in GitHub Secrets.
4. **CI/CD Workflow**: Configured `.github/workflows/deploy.yml` using Azure CLI to sync files automatically.

---

## 👤 Author

Developed by **Rafael Estévez** as part of cloud practice in Azure.
