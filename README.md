# ⚡ Greeting Automation
A simple yet effective n8n workflow automation created to **automatically send personalized birthday greeting emails** to recipients on their birthdays. This workflow runs daily to check birthdays and send personalized greeting emails automatically.

# 🚀 Getting Started
1. Download `greeting-automation.json`.
2. Log in to your n8n account.
3. Click + `New Workflow`.
4. Click the `three dots (⋮)` menu.
5. Select `Import from File`.
6. Choose your saved JSON file.
7. Adjust the necessary parts to fit the owner’s settings.

# 🧩 How it works?
1. **Trigger**: Runs daily.
2. **Data**: Reads Name, Email, and Birthday from Google Sheets.
3. **Check**: IF today matches birthday.
4. **Email**: Sends a personalized birthday greeting.
