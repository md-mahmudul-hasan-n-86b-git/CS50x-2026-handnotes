# Chapter 7: ASCII

**Lecture 0 — Scratch**  
**Course:** CS50x 2026 | Harvard University

---

## 📝 Handnotes

In electronic devices, all information — whether numbers, letters, images, audio, or video — is stored and represented through various **patterns of binary numbers**.

**ASCII (American Standard Code for Information Interchange)** is a specific standard that defines which **binary pattern** maps to which character, number, or piece of data.

Many years ago, a group of researchers in America sat together and established these rules — ASCII is essentially that agreed-upon set of rules.

### Example
| Binary Pattern | Decimal | Meaning (in a word processor) |
|----------------|---------|-------------------------------|
| `01000001` | 65 | Letter **"A"** |

> **💡 Note:** The same binary pattern can mean **different things** in different programs. For example, the pattern `01000001` (65) represents the letter **"A"** in a word processing program — but that same pattern might represent a specific **colour** in an image editing program.

This is precisely why a file of a specific format can only be opened correctly by specific software:
- A **Word file** → opens in Microsoft Word or Google Docs
- That same file → **cannot** be opened correctly in Microsoft Excel or Google Sheets

---

## 🔑 Key Takeaways

- ✅ All data in computers is stored as **binary patterns**
- ✅ **ASCII** is the standard that maps binary patterns to characters
- ✅ ASCII was established by **American researchers** as a shared agreement
- ✅ The same binary pattern can mean **different things** in different programs
- ✅ `01000001` = **65** = **"A"** in ASCII
- ✅ File formats exist because programs **interpret binary differently**
- ✅ A specific file format requires **specific software** to be read correctly

---

*CS50x 2026 — Lecture 0 | Chapter 7*
