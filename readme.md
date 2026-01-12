# 💣 VeyraNuker

> A Python-based program created for testing and evaluating Discord anti-nuke / anti-raid protections.

---

## ⚠️ Warning

Please read this section carefully before using the project.

* This project is intended **strictly for testing and educational purposes**, mainly to evaluate Discord anti-nuker or security systems.
* The **developer and contributors are not responsible** for any damage, misuse, bans, or losses caused by using this software.
* You use this project **entirely at your own risk**.
* You are **not allowed to redistribute** or resell this software without explicit permission from the owner.
* Only use this tool on servers **you own or have been given explicit permission to test**.

---

## 🛠 Requirements

* **Python 3.12** (recommended)

  * The project should work on Python 3.12 or newer.
* **pip** available in your system PATH.

All required dependencies are listed in the `requirements.txt` file.

---

## ⚙️ Setup

Follow these steps to prepare the project:

1. Clone or download the repository.
2. Install all required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Make sure your Python environment is correctly configured.

---

## ▶️ How to Use

After completing the setup steps above:

1. Start the application by running:

   ```bash
   python main.py
   ```
2. Enter the **Discord bot token** you want to use when prompted.
3. Choose whether to use proxies (⚠️ deprecated and not recommended).
4. If you see the message **"Bot loaded!"**, the bot has started successfully.
5. Invite the bot to the server you want to test.
6. In the target server, run the command:

   ```
   !nuke
   ```

The bot will begin performing automated actions such as:

* Deleting existing channels
* Creating new channels
* Sending messages and pinging `@everyone`
* Removing members (based on permissions)

---

## 🎓 Intended Use Cases

* Testing Discord anti-nuke / anti-raid systems
* Learning about Discord bot permissions and limits
* Studying REST API behavior under load
* Educational demonstrations of event-driven bots

---

## 👤 Creator & Support

* **Creator:** UhcWolfe
* **Support:** [https://veyradev.com](https://veyradev.com)
* **Website:** [https://www.veyradev.com](https://www.veyradev.com)