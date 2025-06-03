# Jakub Karafa Umbrel App Store

This is my personal Umbrel App Store containing tested and working apps that are not part of the [Official Umbrel App Store](https://github.com/getumbrel/umbrel-apps). These apps are packaged to run inside Umbrel OS using Docker.

---

## 🚀 How to Use

1. Open the Umbrel dashboard in your browser.
2. Go to the **App Store**.
3. Click the **three dots** in the top right corner of the App Store.
4. Select **"Community App Stores"**.
5. Paste this URL into the input field:

   ```
   https://github.com/jakubkarafa/umbrel-community-app-store
   ```

6. Click **"Add"**.
7. After the store is added, click the **“Open” button** next to it to browse the apps.

> 📌 **Note:** Apps from this store appear in a separate view and do **not** show up in the main App Store list.  
> To access this store later, repeat the steps: go to the **App Store**, click the **three dots**, go to **Community App Stores**, then click **“Open”** next to this store.

---

## 📦 App Structure

Each app is placed in its own folder and includes the following files:

```
jakubkarafa-app-name/
├── umbrel-app.yml         # App metadata
└── docker-compose.yml     # Docker config for the app
```

- All app IDs begin with `jakubkarafa-` to avoid conflicts.
- Files must be UTF-8 encoded and correctly formatted YAML.

---

## 🧱 Store Metadata

The file `umbrel-app-store.yml` contains the app store's identity:

```yaml
id: jakubkarafa
name: Jakub Karafa's App Store
```

---

## ✅ Example Apps

- `jakubkarafa-jupyter-lab`: Run Jupyter inside Umbrel

---

## 📬 Questions or Contributions?

Open an issue or pull request on [GitHub](https://github.com/jakubkarafa/umbrel-community-app-store).
