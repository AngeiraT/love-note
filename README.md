# 💌 Love Note — A Sweet Daily Message

This project is a personal, hand-crafted page created with love 💛  
It shows a new message every day to remind someone special how much they are loved.

## 🌟 Features
- Soft brown and cream “sticky note” design
- Handwritten-style font
- Fade-in animation
- “See today’s note ❤️” button for a surprise reveal
- Daily message loaded from a JSON file (`notes.json`)

## 🧠 How It Works
1. When the button is clicked, the page fetches `notes.json`.
2. It checks today’s date and shows the message for that date.
3. If there’s no message for today, it shows the “default” one.

## 💾 How to Update Notes
1. Open the `notes.json` file in your GitHub repo.  
2. Add or edit a line like this:
   ```json
   "2025-10-24": "New sweet message here ❤️"
