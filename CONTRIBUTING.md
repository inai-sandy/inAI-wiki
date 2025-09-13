# 🤝 Contributing to INAI

Thanks for your interest in contributing!  
We’re building the **open Wikipedia of AI** — every PR helps.

---

## 🚀 Contributor Workflow (GitHub Website Only)

> You can contribute **entirely in your browser** — no command line required.

### 1️⃣ Fork the repo
1. Open the upstream repo: [inai-sandy/inAI-wiki](https://github.com/inai-sandy/inAI-wiki)  
2. Click **Fork** (top-right).  
3. You’ll now have your own copy at:  
   `https://github.com/<your-username>/inAI-wiki`

---

### 2️⃣ Create a feature branch
1. In *your fork*, click the **branch dropdown** (it usually says `main`).  
2. In the search box, type a name (example: `feature/add-latest-page`).  
3. Press **Enter** → GitHub will create and switch you to that branch.  
   - ✅ You are now working on your new branch.

---

### 3️⃣ Edit or add files
1. Navigate to the file you want to change.  
   - Or click **Add file → Create new file** to add a new one.  
2. Click the **✏️ Edit** button.  
3. Make your changes.

---

### 4️⃣ Commit changes
1. Scroll down to the **Commit changes** box.  
2. Select **“Commit directly to the `feature/...` branch”**.  
3. Add a short message (example: `feat: add latest additions page link`).  
4. Click **Commit changes**.

---

### 5️⃣ Open a Pull Request (PR)
1. After committing, GitHub will show a banner:  
   **“feature/add-latest-page had recent pushes. Compare & pull request”** → click it.  
2. Base repo: `inai-sandy/inAI-wiki` (branch: `main`).  
3. Head repo: `<your-username>/inAI-wiki` (branch: `feature/...`).  
4. Fill in title & description → **Create pull request**.

---

### 6️⃣ Review & merge
- If reviewers ask for changes, edit the file(s) again in your branch → commit → PR updates automatically.  
- Once approved, a maintainer merges your PR 🎉

---

## ✍️ Branch & Commit Style
- Branches:  
  - `feature/<what-you-add>`  
  - `fix/<what-you-fix>`  
  - `docs/<what-you-doc>`  

- Commits:  
  - `feat: add agents latest page`  
  - `fix: correct link to tutorials`  
  - `docs: update README preview`

---

## ✅ PR Checklist
- [ ] Clear title & description  
- [ ] Links/screenshots added if submitting Apps/Agents/LLMs  
- [ ] Docs/README updated if behavior or links changed  
- [ ] No secrets or private data included  

---

## 💡 Contribution Ideas
- Add new **AI Apps/Tools**, **Agents**, **MCP servers**, **Chrome Extensions**  
- Submit or update **LLMs/Models** (Hugging Face, evals, fine-tunes)  
- Add **tutorials & workflows**  
- Improve docs (README, links, screenshots, GIFs)  
- Share new **AI news sources**  

---

## 🧰 Optional: Local Git Workflow
If you prefer the command line:  

```bash
# 1. Clone your fork
git clone https://github.com/<your-username>/inAI-wiki.git
cd inAI-wiki

# 2. Create a branch
git checkout -b feature/add-latest-page

# 3. Make changes, then commit & push
git add .
git commit -m "feat: add latest additions link"
git push -u origin feature/add-latest-page
