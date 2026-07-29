# How to Contribute Translations

## Method 1: The Easiest Way (No Git required)
1. Open [`./{your_language}/{file_you_want_to_translate}`](https://github.com/F-l-a/Alphapedia-translations/tree/main/) (usually `extra.json`).
   - If the file you are looking for is missing for your language, open the template from `./translations/template/`.
2. Download the file.
3. Edit the file using any text editor. The structure is as follows:
    ```json
    "ENGLISH_KEY (don't touch it)": "TRANSLATED_KEY (put the translation here)"
    ```
4. [Open an Issue here](https://github.com/F-l-a/Alphapedia-translations/issues/new) and attach the file, or send it in the [Alphapedia's Official Discord](https://discord.gg/Qeuc9k4yMw).
5. If you have any questions or issues, join the Discord and feel free to ask.
---

## Method 2: Using the GitHub Web Interface
1. **Fork the repository**: Go to the [Alphapedia-translations repository](https://github.com/F-l-a/Alphapedia-translations) and click the **Fork** button in the top right corner to create a copy on your account.
2. **Sync your fork**: If you forked the repository a while ago, make sure it is up to date. On your fork's main page, click **Sync fork** and then **Update branch** if it says your branch is behind.
3. **Edit the file**: Navigate to the language file you want to translate within your forked repository. Click the pencil icon ✏️ in the top right corner of the file view to edit it.
4. **Translate**: Edit the file directly in the browser. The structure is as follows:
    ```json
    "ENGLISH_KEY (don't touch it)": "TRANSLATED_KEY (put the translation here)"
    ```
5. **Commit your changes**: Click the green **Commit changes...** button at the top right, add a brief message (e.g., "Update [YOUR_LANGUAGE] translation"), and confirm.
6. **Open a Pull Request**: Go to the main page of your fork, click **Contribute**, and then **Open pull request**.

---

## Method 3: Using the Command Line Locally (For Expert Users)
1. **Fork the repository**: Go to the [Alphapedia-translations repository](https://github.com/F-l-a/Alphapedia-translations) and click the **Fork** button.
2. **Clone your fork** to your local machine (replace `YOUR_USERNAME` with your actual GitHub username) and enter the directory:
    ```bash
    git clone https://github.com/YOUR_USERNAME/Alphapedia-translations.git
    cd Alphapedia-translations
    ```
3. **Create a new branch** for your translations:
    ```bash
    git checkout -b update-translations
    ```
4. **Edit the file** using any text editor. The structure is as follows:
    ```json
    "ENGLISH_KEY (don't touch it)": "TRANSLATED_KEY (put the translation here)"
    ```
5. **Commit your changes and push** them to your forked repository:
    ```bash
    git add .
    git commit -m "Add/Update [YOUR_LANGUAGE] translation"
    git push origin update-translations
    ```
6. **Open a Pull Request (PR)**:
    * Go to the original [repository page on GitHub](https://github.com/F-l-a/Alphapedia-translations).
    * Click the green **Compare & pull request** button that appears at the top of the page.
    * Add a brief description of your changes and click **Create pull request**.
