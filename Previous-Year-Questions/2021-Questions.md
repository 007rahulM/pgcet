# KEA MCA PGCET 2021 — Previous Year Questions

> **Source:** Based on verified coaching institute compilations and student-recalled questions.

---

## SECTION A: Mathematical Aptitude

**Q1.** Two pipes A and B fill a tank in 20 min and 30 min. Both open together. Tank fills in?
- (A) 10 min  (B) 12 min  (C) 15 min  (D) 25 min

**Answer: (B) 12 minutes**
**Solution:**
- LCM(20, 30) = 60 (total tank capacity in units)
- A fills 60/20 = 3 units/min
- B fills 60/30 = 2 units/min
- Together = 5 units/min
- Time = 60/5 = **12 minutes**

---

**Q2.** A bought a watch at 20% discount on MRP. If MRP = ₹500, what did he pay?
- (A) ₹350  (B) ₹375  (C) ₹400  (D) ₹425

**Answer: (C) ₹400**
**Solution:**
- SP = MP × (100 − D%)/100 = 500 × 80/100 = **₹400**

---

**Q3.** Find 5C3.
- (A) 5  (B) 10  (C) 15  (D) 20

**Answer: (B) 10**
**Solution:**
- 5C3 = 5!/(3! × 2!) = (5×4)/(2×1) = **10**

---

**Q4.** Convert 111₂ to decimal.
- (A) 6  (B) 7  (C) 8  (D) 5

**Answer: (B) 7**
**Solution:**
- 1×4 + 1×2 + 1×1 = 4+2+1 = **7**

---

**Q5.** Ratio of A:B = 3:5 and B:C = 2:7. Find A:B:C.
- (A) 6:10:35  (B) 3:5:7  (C) 3:10:35  (D) 6:5:35

**Answer: (A) 6:10:35**
**Solution:**
- A:B = 3:5, B:C = 2:7
- Make B common: A:B = 6:10, B:C = 10:35
- A:B:C = **6:10:35**

---

**Q6.** A card is drawn from deck of 52 cards. Probability it is a King?
- (A) 1/52  (B) 1/13  (C) 4/52  (D) Both B and C

**Answer: (D) Both B and C**
**Solution:**
- 4 Kings in 52 cards
- P(King) = 4/52 = 1/13 (both 4/52 and 1/13 are same)

---

**Q7.** Ages of 5 people sum to 90. After 5 years, what is new sum?
- (A) 90  (B) 95  (C) 100  (D) 115

**Answer: (D) 115**
**Solution:**
- Each of 5 people ages by 5 years → total increase = 5 × 5 = 25
- New sum = 90 + 25 = **115**

---

**Q8.** Find variance of {3, 5, 7, 9, 11}.
- (A) 4  (B) 6  (C) 8  (D) 10

**Answer: (C) 8**
**Solution:**
- Mean = (3+5+7+9+11)/5 = 35/5 = 7
- Deviations²: (3-7)²=16, (5-7)²=4, (7-7)²=0, (9-7)²=4, (11-7)²=16
- Variance = (16+4+0+4+16)/5 = 40/5 = **8**

---

**Q9.** In how many ways can letters of MISSISSIPPI be arranged?
- (A) 11!  (B) 34650  (C) 11!/4!4!2!  (D) Both B and C

**Answer: (D) Both B and C**
**Solution:**
- M=1, I=4, S=4, P=2
- Ways = 11!/(1! × 4! × 4! × 2!) = 39916800/1152 = 34650 ✅

---

**Q10.** Which statement is logically equivalent to p → q?
- (A) ¬p → ¬q  (B) q → p  (C) ¬q → ¬p  (D) p ↔ q

**Answer: (C) ¬q → ¬p (Contrapositive)**
**Solution:** p → q ≡ ¬q → ¬p (contrapositive). The converse (q→p) and inverse (¬p→¬q) are equivalent to each other but NOT to original.

---

## SECTION B: Computer Awareness

**Q11.** Which traversal of BST gives nodes in ascending order?
- (A) Preorder  (B) Postorder  (C) Inorder  (D) Level order

**Answer: (C) Inorder**

---

**Q12.** Convert 1010₂ to octal.
- (A) 10  (B) 12  (C) 14  (D) 16

**Answer: (B) 12**
**Solution:**
- 1010₂ = 10 in decimal
- 10 ÷ 8 = 1 R 2 → **12₈**
- OR: Group in 3 from right: 001 010 → 1 2 → 12₈ ✅

---

**Q13.** What does DBMS stand for?
- (A) Data Based Management System
- (B) Database Management System
- (C) Data Basic Management System
- (D) Database Managing System

**Answer: (B) Database Management System**

---

**Q14.** Which gate is called "universal gate"?
- (A) OR  (B) AND  (C) NOT  (D) NAND

**Answer: (D) NAND**
**Solution:** NAND gate is called universal gate because ALL other logic gates (AND, OR, NOT, XOR) can be built using only NAND gates. NOR is also a universal gate.

---

**Q15.** The binary addition 1 + 1 = ?
- (A) 10  (B) 11  (C) 2  (D) 0

**Answer: (A) 10**
**Solution:** In binary: 1 + 1 = 10 (write 0, carry 1). This equals decimal 2, but in binary it's written as 10.

---

**Q16.** Which memory cannot be changed after manufacturing?
- (A) RAM  (B) EEPROM  (C) Cache  (D) ROM

**Answer: (D) ROM**
**Solution:** ROM (Read Only Memory) is programmed during manufacturing and cannot be changed by normal operations. EEPROM can be erased electrically. RAM is volatile.

---

**Q17.** What does TCP ensure that UDP does not?
- (A) Speed  (B) Wireless transmission  (C) Reliable delivery  (D) Broadcasting

**Answer: (C) Reliable delivery**
**Solution:** TCP provides error checking, acknowledgements, and retransmission → reliable. UDP is faster but unreliable (used for video streaming, gaming).

---

**Q18.** In C, what is the output of printf("%d", 5/2)?
- (A) 2.5  (B) 2  (C) 3  (D) Error

**Answer: (B) 2**
**Solution:** Both 5 and 2 are integers. Integer division in C truncates: 5/2 = 2 (not 2.5). To get 2.5, need: 5.0/2 or 5/(float)2.

---

**Q19.** Which is NOT a DDL command?
- (A) CREATE  (B) DROP  (C) ALTER  (D) INSERT

**Answer: (D) INSERT**
**Solution:** INSERT is DML (Data Manipulation Language) — it adds data. DDL commands deal with structure: CREATE, DROP, ALTER, TRUNCATE.

---

**Q20.** Which layer of OSI model handles encryption?
- (A) Session  (B) Transport  (C) Application  (D) Presentation

**Answer: (D) Presentation**
**Solution:** Presentation layer (Layer 6) handles data format, encryption, compression, and translation. SSL/TLS work at this layer.

---

## SECTION C: Analytical & Logical Reasoning

**Q21.** In series: A, C, F, J, O, ?
- (A) S  (B) T  (C) U  (D) V

**Answer: (C) U**
**Solution:**
- A(1)+2=C(3)+3=F(6)+4=J(10)+5=O(15)+6=U(21)
- Differences increase by 1: +2, +3, +4, +5, +6

---

**Q22.** Pointing to a photo, Anita says: "His mother is the only daughter of my father." Who is in the photo?
- (A) Father  (B) Brother  (C) Nephew  (D) Son

**Answer: (D) Son**
**Solution:**
- "Only daughter of my father" = Anita herself
- So his mother = Anita
- The person in photo is Anita's **son**

---

**Q23.** All cats are dogs. All dogs are horses. Conclusion: All cats are horses.
- (A) True  (B) False  (C) Partial  (D) Cannot say

**Answer: (A) True**
**Solution:** Using syllogism logic:
- All cats → dogs (given)
- All dogs → horses (given)
- Therefore: All cats → horses ✅ (transitive)

---

**Q24.** Raju stands facing North. He turns 90° clockwise, then 180° clockwise. Now facing?
- (A) North  (B) South  (C) East  (D) West

**Answer: (D) West**
**Solution:**
- Start: North (0°)
- Turn 90° clockwise: East
- Turn 180° clockwise from East: West ✅

---

**Q25.** If P × Q means P is father of Q, P + Q means P is mother of Q, P − Q means P is sibling of Q, then in A × B + C, what is A to C?
- (A) Father  (B) Grandfather  (C) Uncle  (D) Cannot determine

**Answer: (B) Grandfather**
**Solution:**
- A × B → A is father of B
- B + C → B is mother of C (so B is female)
- A's son's child = A is grandfather of C

---

## SECTION D: General English

**Q26.** He is ___ university professor.
- (A) a  (B) an  (C) the  (D) no article

**Answer: (A) a**
**Solution:** "university" starts with /j/ sound (yoo-ni-ver-si-ty) — consonant sound → use "a".

---

**Q27.** Choose correct: "He plays cricket since childhood."
Error is: (A) He  (B) plays  (C) since  (D) childhood

**Answer: (B) plays**
**Solution:** "since childhood" with present perfect: "He has played cricket since childhood."

---

**Q28.** Synonym of "obstinate":
- (A) Flexible  (B) Stubborn  (C) Weak  (D) Timid

**Answer: (B) Stubborn**

---

**Q29.** Fill blank: "I am looking ___ my glasses."
- (A) at  (B) in  (C) for  (D) after

**Answer: (C) for**
**Solution:** "looking for" = searching. "looking after" = taking care of. "looking at" = observing.

---

**Q30.** One-word for "one who walks during sleep":
- (A) Insomniac  (B) Somnambulist  (C) Narcoleptic  (D) Hypnotist

**Answer: (B) Somnambulist**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
