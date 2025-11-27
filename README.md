# Benedict's Project Portfolio

> Personal projects where I applied a structured approach to everyday challenges.
> While the use cases are personal, they demonstrate skills such as analytical thinking to solve inefficiencies, eliminate pain points, and design practical and streamlined workflows to gain the tools for better decision-making.
---

## Skills Demonstrated

**Structured Problem-Solving** · **Analytical & Data-Driven Thinking** · **Process & Workflow Design** · **User Experience Design** · **Automation & Efficiency** · **Forecasting & Planning** · **Practical AI Integration**

---

## Projects

### 1. Personal Budgeting & Forecasting

Staying on top of personal spending, while important for financial responsibility, is notoriously difficult. The common approach of scrolling through past transactions to roughly gauge 'normal' spending is simple but lacks reliability. Large infrequent spending behaviours such as purchasing consumer durables and sales-driven bulk buying distort the picture, while hidden expenses such as annual subscriptions are easy to miss. Spreadsheets and budgeting apps, though powerful, demand tedious maintenance.

I built a system designed for seamless tracking and better decision-making. It uses AI to parse raw text into structured data, and sort expenses into three distinct type: Recurring (Periodic), Capital (CapEx), and General (Run Rate). This segmentation enables tailored analytical logic, unlocking a diverse range of capabilities such as inventory tracking and cash flow forecasting. Ultimately, automation and this simple yet robust logic streamlines the tracking and analytics process, empowering me to make spending decisions with foresight and confidence.


![Screenshot_25-11-2025_23545_localhost](https://github.com/user-attachments/assets/520e24fa-e891-4c74-b2f1-692a3ffe8743)


<div align="center">
  <a href="./ai-parse-receipts-demo-compressed.mp4">
    <img src="https://github.com/user-attachments/assets/5195353f-b6eb-4ab6-9445-6dca1b434667" alt="Click to play AI parsing demo video" width="100%" />
  </a>
  <br/>
  <sub><b>AI feature that transforms raw text into structured data, enabling automated parsing of receipts and shopping carts.</b></sub>
  <p><em>Click the image to preview the video on GitHub.</em></p>
</div>


#### Problem

- **Lack of visibility** into future cashflow and financial health.
- **Difficulty understanding** the impact of different spending decisions.
- **Reactive purchasing** due to lack of inventory visibility, leading to frequent, avoidable store trips instead of consolidated runs

##### Issues with alternatives
- Simple “average monthly spend” budgets were misleading due to substantial infrequent purchases.
- Spreadsheets were clunky and required tedious manual data entry.

#### Approach

- Decomposed spending (e.g. recurring, general, capital‑like) to avoid distorted forecasts.
- Used a relational database to link tables such as transactions, categories, and inventory items, ensuring data consistency and ease of maintenance.
- Built a streamlined user experience for ease of use and intuitive analytics, such as forecasted spending with bar charts and inventory levels with gantt charts.
- Integrated AI parsing into the workflow to minimise manual data entry.

#### Impact
- **Future‑proofed for analytics:** The structured, relational design makes it straightforward to add more advanced AI‑driven insights later (e.g. scenario analysis, recommendations), not just text parsing.

##### Time-efficiency
- **Seamless decision‑making:** Easy to review spending decisions, upcoming obligations, and restock needs without relying on memory.
- **Less mental overhead:** The system tracks details so I don’t have to, freeing attention for actual choices rather than bookkeeping.

##### Cash Efficiency
- **Optimised liquidity:** Enables precise allocation between liquid cash and longer-term assets, minimising the opportunity cost of idle capital.

#### Tech

TypeScript, React, Python, FastAPI, SQLite

---

### 2. Screener‑Tracker

<img width="1920" height="1080" alt="Stock Screener Dashboard" src="https://github.com/user-attachments/assets/3442eee0-b2a9-4529-96bf-eef893b02b6e" />

#### Problem

- Analysing stocks meant tediously visiting multiple sources and manually copying data into spreadsheets.
- Reliance on manual updates rendered analysis obsolete from one trading session to the next.

#### Approach

- Automated data retrieval from APIs into a spreadsheet using an integration library instead of manual copy‑paste.
- Let the spreadsheet act as the calculation engine (formulas, historical data functions, custom metrics).
- Fed the calculated outputs back into a focused dashboard so I could track and compare ideas without living inside raw sheets.

#### Impact

- **Up‑to‑date analysis:** Automation makes it realistic to refresh views frequently, not just occasionally.
- **Less mechanical work:** Time spent moving and re‑formatting data is replaced by time spent interpreting results.
- **More consistent evaluation:** Each idea is assessed in a structured manner, reducing ad‑hoc judgement.

#### Tech

Python, Excel (via xlwings and built‑in functions)

---

### 3. Exam Study Tracker

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/82d47faa-813b-495d-b9ba-b8a921851006" />

#### Problem

- For multiple exams, I needed to maximise retention and complete all practice within the time available.
- Traditional apps and earlier strategies (e.g. AI generating schedules that I pasted into Notion, then manually re‑formatted and edited) created a lot of admin work, especially when plans changed.
- Manually updating dates and tasks when falling behind or getting ahead was tedious and discouraged frequent replanning.

#### Approach

- Created a lightweight interface showing what to work on today and how that aligns with each exam, with features that seamlessly allows the user to prioritise, shift dates, and see what's upcoming.
- YAML format intended to be easy for external tools (including AI) to read or write, allowing the use of AI-powered study schedule optimisation based off exam dates and user priorities.

#### Impact

- **Optimised study schedules:** Plans factor in deadlines and required coverage, rather than being a flat list of tasks.
- **Low‑friction replanning:** When reality changes, I update the data file and regenerate instead of manually editing dozens of entries.
- **Stronger AI leverage:** AI can work on a structured representation of the plan, not just produce text that I then have to clean up.

#### Tech

JavaScript, Python, HTML/CSS

---

## Contact

**GitHub:** [@BC-GB](https://github.com/BC-GB)  

Underlying repositories are private but available for review upon request.
