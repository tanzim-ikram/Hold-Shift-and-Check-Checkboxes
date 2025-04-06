# Hold-Shift-and-Check-Checkboxes

A fun and interactive project that mimics the checkbox selection behavior found in email clients like Gmail. When you hold the **Shift** key and click between two checkboxes, all checkboxes in between are also selected automatically.

## 💡 Features

- ✔️ Select individual checkboxes by clicking.
- 🔁 Hold **Shift** and click another checkbox to select all in-between.
- 🧼 Clean and minimal layout inspired by inbox UI.
- 🧠 Built using **vanilla JavaScript**—no libraries or frameworks!

## 🛠️ How It Works

1. Click a checkbox.
2. Hold down the **Shift** key.
3. Click another checkbox further down.
4. All checkboxes between the two clicks will be checked.

## 📁 Project Structure

- `index.html`: Main HTML file containing layout and logic.
- Embedded `<style>`: Handles the appearance of the inbox.
- Embedded `<script>`: Contains the JavaScript to implement the shift-click functionality.

## 🔧 Code Explanation

- We use `querySelectorAll` to select all checkboxes inside the `.inbox`.
- When a checkbox is clicked, we check if the **Shift** key was pressed and the box is being **checked** (not unchecked).
- A flag (`inBetween`) toggles to mark which checkboxes should be selected between the current click and the last checked box.

## 🚀 Usage

Simply open `index.html` in your browser and test the Shift-click checkbox functionality.

## 🧪 Demo

Try checking a checkbox, then holding Shift and checking another one. All checkboxes between the two will be selected!

## 📸 Screenshot
![Project SS](<Hold Shift to Check Multiple Checkboxes.png>)