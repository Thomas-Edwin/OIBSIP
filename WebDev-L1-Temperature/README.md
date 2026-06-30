# 🌡️ Temperature Converter

A clean, responsive web app that converts temperatures between **Celsius**, **Fahrenheit**, and **Kelvin** instantly, with built-in input validation.

This project was built as part of the **Oasis Infobyte Web Development Internship — Level 1**.

---

## 📌 Features

- Convert any temperature to **all three units at once** (°C, °F, K)
- Choose the input unit from a dropdown (Celsius / Fahrenheit / Kelvin)
- **Input validation** — rejects empty or non-numeric input with a clear error message
- **Absolute zero check** — prevents physically impossible temperatures (e.g. below -273.15°C)
- Highlights the converted (non-input) units in the result card
- Reference cards showing real-world benchmarks (freezing point, boiling point, body temperature)
- Convert by pressing **Enter** or clicking the button
- One-click **Reset**
- Fully responsive layout for mobile and desktop

---

## 🛠️ Built With

- **HTML5** — structure and semantic markup
- **CSS3** — custom styling, flexbox layout, responsive design
- **JavaScript (Vanilla)** — conversion logic, validation, and DOM manipulation

---

## 🚀 How to Run

1. Download or clone this folder.
2. Open `index.html` in any modern web browser.
3. No build steps, installs, or dependencies required.

---

## 🧮 Conversion Formulas Used

| From → To | Formula |
|---|---|
| Celsius → Fahrenheit | `(C × 9/5) + 32` |
| Celsius → Kelvin | `C + 273.15` |
| Fahrenheit → Celsius | `(F - 32) × 5/9` |
| Kelvin → Celsius | `K - 273.15` |

---

## 📂 Project Structure

```
WebDev-L1-Temperature/
├── index.html       # Full app (HTML + CSS + JS in one file)
└── README.md        # Project documentation
```

---

## 📸 Screenshot

_Add a screenshot of the app here (e.g. `screenshot.png`) and reference it like below:_

```markdown
![Temperature Converter Screenshot](screenshot.png)
```

---

## 🙋 Author

Built as part of the **Oasis Infobyte (OIBSIP) Web Development Internship**.
