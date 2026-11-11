# AutoShop AI 🛒🤖

> **Autonomous AI Shopping Agent powered by PayPal**  
> *Submitted for the PayPal AI Hackathon 2026*

AutoShop AI is a high-performance C++ autonomous shopping agent designed to turn natural user shopping requests into ready-to-pay PayPal checkouts.

---

## 🚀 Key Features

* **Natural Intent Parsing:** Translates plain language shopping prompts into item criteria and budget limits.
* **Automated Decision Engine:** Matches user requirements with target items while keeping costs under budget.
* **Direct PayPal Integration:** Securely communicates with PayPal's infrastructure to generate real-time order payloads and launch payment portal links.
* **High Performance:** Core engine built in native C++ for speed, efficiency, and low footprint.

---

## 🛠️ Architecture & Tech Stack

* **Language:** C++11 / C++17 (Dev-C++ / GCC)
* **Networking & Protocols:** `libcurl` for HTTP/HTTPS requests & OAuth 2.0 authorization
* **Data Processing:** C++ String Parsing & JSON Payload formatting
* **Target Environment:** Windows 11 / Microsoft Edge integration

---

## ⚙️ How to Build & Run

1. Clone or download this repository.
2. Open `main.cpp` in **Dev-C++** (or your preferred C++ IDE).
3. Ensure `libcurl` is linked to your project.
4. Compile and run (`F11` in Dev-C++).
5. Enter a prompt like:
   ```text
   Find an ergonomic desk setup under $150 and buy it.
   **Fatima Alshaikhnasser** – *Developer & Creator*
