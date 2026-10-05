# Topic: Basic Data Entry

## 1. Definition & Explanation

**Basic Data Entry** is the process of typing information directly into Excel cells — the foundation every other Excel skill sits on top of. A cell is identified by its column letter + row number (e.g., `A1`), and you enter data by clicking (or navigating to) a cell and typing.

Key behaviors to know:

- **Click a cell → type → press `Enter`** — this confirms the entry and moves you **down** to the next row.
- **Press `Tab`** instead of `Enter` — confirms the entry and moves you **right** to the next column.
- **Press `Esc`** — cancels whatever you were typing, without changing the cell.
- Excel automatically detects the *type* of what you type:
  - Text → left-aligned by default.
  - Numbers → right-aligned by default.
  - Something matching a date pattern (e.g., `12/08/2023`) → auto-converted into a real date value, not text.
- **Double-click a cell** (or press `F2`) to edit its existing content instead of overwriting it.

### Usage Example

Say you're logging a small fruit stand's inventory:

|   | A       | B     |
|---|---------|-------|
| 1 | Product | Price |
| 2 | Apple   | 50    |
| 3 | Mango   | 70    |
| 4 | Banana  | 30    |

To build this:
1. Click **A1**, type `Product`, press `Tab` (moves to B1).
2. Type `Price`, press `Enter` (Excel drops you to A2, following the row you started on).
3. Type `Apple`, `Tab`, `50`, `Enter` — and so on for the remaining rows.

Notice "Product" lands left-aligned (it's text) and "50" lands right-aligned (it's a number) — Excel made that formatting decision for you, automatically, based on what you typed.

---

## 2. Practical Task

Build the following mini attendance sheet from scratch in a blank Excel worksheet, using **only** typing + `Tab`/`Enter` navigation (no copy-paste):

|   | A            | B          | C       |
|---|--------------|------------|---------|
| 1 | Student Name | Date       | Present |
| 2 | Aarav Shah   | 01/07/2026 | Yes     |
| 3 | Diya Mehta   | 01/07/2026 | No      |
| 4 | Kabir Singh  | 01/07/2026 | Yes     |

**Do this, then check yourself:**

1. Type it in exactly as shown, using `Tab` to move across a row and `Enter` to drop to the next row.
2. Click on cell **B2** afterward — does the entry sit right-aligned in the cell? If yes, Excel recognized it as a real date (not text). If it's left-aligned instead, it means Excel stored it as plain text — try re-typing it and check again.
3. Now double-click on **A3** (Diya Mehta) and change it to "Diya Kapoor" *without* retyping the whole cell — just edit the existing text in place.
4. Finally, click cell **C5** and type `=COUNTIF(C2:C4,"Yes")` — this counts how many students are marked Present. What number do you get, and does it match what you'd expect by eye?

This exercise deliberately mixes plain typing, in-place editing, and a first taste of a formula reading the data you just entered — so you can feel how "basic" data entry directly feeds everything built on top of it.
