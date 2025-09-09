
A **complete web app** built using **HTML, CSS, and JavaScript only** (no external libraries or frameworks) that:

- Allows the user to upload a CSV file with columns: `category`, `front`, `back`, `front-subtext`, `back-subtext`
- Lets user define:
    - Number of card **rows per printed page**
    - Number of card **columns per printed page**
- Generates printable flashcards such that:
    - **Front side** has the word (`front`) and category
    - **Back side** has synonyms (`back`) and category
- When printed:
    - **Odd pages** = Fronts
    - **Even pages** = Backs (correctly aligned — back of card matches front, not adjacent)
- Cards are centered (vertically & horizontally)
- **Mirror Column Order on Back Pages** - Reverse the column order on the **back pages only**, so that when printed and flipped on the **short edge**, the back matches the front perfectly.
- Includes **category** in top-right corner of both front and back
- Exports as a **printable PDF-ready layout** (user can save as PDF via browser print)

---

### ✅ How to Use:

1. Open it in a modern browser (Chrome, Edge, Firefox)
2. Click **"Upload CSV File"** and select your CSV
3. Adjust **Rows per Page** and **Columns per Page**
4. Click **"Generate Flashcards"**
5. Click **"Print or Save as PDF"**


