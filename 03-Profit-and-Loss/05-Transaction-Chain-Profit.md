# Transaction-Chain Profit — Multi-Person Buy/Sell Questions

## 🔍 How to Recognize This Pattern

Look for:
- "A bought from B, B bought from C"
- "Middle seller made 25%, first seller made 20%"
- "Find the original cost price"
- Questions that move **backward through multiple transactions**

---

## 📐 Core Idea

In chain transactions, do **not** jump directly.
Work **one sale at a time in reverse**.

### Reverse Profit Formula
> If selling price is known and profit = `p%`, then
> **Cost Price = SP × 100 / (100 + p)**

### Reverse Loss Formula
> If selling price is known and loss = `l%`, then
> **Cost Price = SP × 100 / (100 - l)**

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** Arun bought a laptop from Sanchit for ₹112500. Sanchit earned a profit of 25% on the laptop. Ramesh sold the laptop to Sanchit at a gain of 20%. How much did Ramesh pay to buy the laptop?

**💡 What I'll use:** Reverse the 25% profit first, then reverse the 20% profit.

**✏️ My Solution:**

Step 1: Find Sanchit's cost price
- Sanchit's SP = ₹112500
- Profit = 25%
- CP = 112500 × 100 / 125 = **₹90000**

Step 2: Find Ramesh's cost price
- Ramesh's SP = ₹90000
- Profit = 20%
- CP = 90000 × 100 / 120 = **₹75000**

**✅ Answer: ₹75000**

---

### Example 2

**❓ Question:** A shopkeeper sold an item for ₹1440 after making 20% profit. He had bought it from a wholesaler who made 12.5% profit. Find the wholesaler's cost price.

**✏️ My Solution:**

Step 1: Shopkeeper's CP = 1440 × 100 / 120 = ₹1200

Step 2: Wholesaler's CP = 1200 × 100 / 112.5 = 1200 × 8 / 9 = **₹1066.67**

**✅ Answer: ₹1066.67**

---

### Example 3

**❓ Question:** A trader sells a machine at 10% loss for ₹18000. The person who bought it sells it at 20% profit. Find the final selling price.

**✏️ My Solution:**

Step 1: First trader's cost price
- 18000 = 90% of CP
- CP = 18000 × 100 / 90 = ₹20000

Step 2: Final selling price after 20% profit
- Final SP = 20000 × 120 / 100 = **₹24000**

**✅ Answer: ₹24000**

---

### Example 4

**❓ Question:** A wholesaler sold a book to a retailer at 25% profit. The retailer marked it up by 20% and then gave a discount of 10%. If the final selling price is ₹270, find the wholesaler's cost price.

**💡 What I'll use:** Reverse discount, then reverse retailer markup, then reverse wholesaler profit.

**✏️ My Solution:**

Step 1: Reverse 10% discount
- Marked price = 270 × 100 / 90 = ₹300

Step 2: Reverse 20% markup
- Retailer's CP = 300 × 100 / 120 = ₹250

Step 3: Reverse wholesaler's 25% profit
- Wholesaler's CP = 250 × 100 / 125 = **₹200**

**✅ Answer: ₹200**

---

## ⚡ 60-Second Shortcut

For chain transactions:
1. Start from the **last known price**
2. Move **backward** transaction by transaction
3. Reverse each profit using `×100/(100+p)`
4. Reverse each loss using `×100/(100-l)`

**Exam rule:** In multi-person sale questions, **backward is faster than forward**.

---

## 📝 Practice Problems

1. A sold an article to B for ₹960 at 20% profit. B sold it to C at 25% profit. Find C's price.

2. A sold a phone to B for ₹13200 at 10% profit. B sold it to C at 20% profit. Find A's cost price.

3. A book is sold by a wholesaler at 25% profit and by a retailer at 20% profit for ₹900. Find the wholesaler's cost price.

4. A trader sells an item at 10% loss for ₹540. The buyer sells it at 20% profit. Find the final SP.

5. A dealer marks an item 25% above cost and then gives 20% discount. If final SP is ₹1200, find cost price.

---

> 📖 **[See detailed step-by-step solutions →](./05-Transaction-Chain-Profit-Answers.md)**
