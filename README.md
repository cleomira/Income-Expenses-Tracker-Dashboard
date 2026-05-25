# Income-Expense-Tracker-Dashboard
This is a personal finance dashboard built in Excel that tracks monthly income and expenses for 2026.
Overview
This is a personal finance dashboard built in Excel that tracks monthly income and expenses for 2026. It features interactive month-based filtering via a slicer, two separate tracker sections (income and expenses), KPI cards with icons, pie charts, and horizontal bar charts — all on a single dashboard sheet.

<img width="713" height="291" alt="Tracker" src="https://github.com/user-attachments/assets/849d7f12-eabd-40f4-b847-dbeed54fe737" />

**Key Features**
1. Clean two-section layout
The dashboard is logically split into an Income Tracker (top half) and Expense Tracker (bottom half), each with its own title, KPI cards, pie chart, and bar chart. This makes scanning effortless.
2. Dynamic slicer filtering
Using a month slicer (Jan–Dec) connected to pivot tables is the right approach. Clicking a month correctly updates all figures and charts in real time. This demonstrates solid understanding of Excel's PivotTable/Slicer workflow.
3. KPI icon cards
The illustrated icon cards (Salary, Freelance, Interest, etc.) are a nice touch — they add visual hierarchy and make categories scannable at a glance. Using different icons per category shows attention to detail.
4. Profit/Loss indicator in top-left
The dynamic Profit / Loss cell (B3:B4) with conditional color (green for profit, red for loss) is a great summary KPI. It correctly flips to "loss" with a negative value when expenses exceed income in a given month.

**Overall Analysis of the Dashboard**
 $1,547,826 income against $1,314,525 in expenses leaves a net profit of $233,301 — a healthy 15% margin overall. 8 out of 12 months were profitable.
**Best months**:
November (+$48,272) and May (+$48,236) are virtually tied as the strongest months. Both combined high freelance income (~$61k) with relatively controlled spending. August (+$45,345) was the third best — notably because expenses dropped to their lowest point all year ($85k), not because income spiked. March (+$41,313) and October (+$40,974) round out the top five.
**Loss months:**
January was the worst by far at -$25,909, driven by the highest dining ($20k) and education ($18k) expenses of the year hitting when income was still low. June (-$13,067) was wrecked by a single spike in Shopping ($85k — likely a one-off large purchase). September (-$2,148) was nearly break-even. December (-$7,007) mirrors January: spending on Bills ($38k) and Dining ($23k) surged into the holiday period.
**What's driving income:** Freelance ($635k, 41%) and Salary ($614k, 40%) together account for 81% of all income. Everything else — bonuses, interest, dividends — is supplementary.
**What's eating into profit:** Rent ($348k, 26%) is the single biggest expense and completely fixed. Shopping ($244k, 19%) is the most volatile and the main reason June turned into a loss. Bills ($191k, 15%) spiked heavily in September and December. These three categories alone account for 60% of all spending.

**Author **
Ugwu Ngozi Cleopatra

Built as part of a data analytics and business intelligence portfolio project
