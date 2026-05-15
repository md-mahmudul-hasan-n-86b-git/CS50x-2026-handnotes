# Chapter 8: Unicode

**Lecture 0 — Scratch**  
**Course:** CS50x 2026 | Harvard University

---

## 📝 Handnotes

**ASCII** is fundamentally an older system that uses only **7 or 8 bits** — meaning it can represent a maximum of **256 distinct characters**. This is sufficient for English uppercase letters, lowercase letters, numbers, and punctuation marks.

However, the problem is — the world has far more than just English. There are countless other languages and symbols that ASCII simply cannot accommodate.

**Unicode** was created to overcome this limitation, and it is now used worldwide. The Unicode system uses significantly more bits (such as **16, 24, or 32 bits**), making it possible to represent approximately **4 billion distinct characters**.

This is precisely why we can use such a **diverse range of emojis** today — after assigning codes to every character of every language in the world, there are still enormous numbers of remaining bit combinations left over, and those are being used to create things like emojis. 🙃

However, one important distinction is that **Unicode only determines** which binary pattern corresponds to which character or emotion emoji. It does **not** determine what that emoji looks like (its design). The visual design is handled by individual **digital service companies**.

This is why the **same emoji looks different across different platforms**. For example, the *Face with Tears of Joy* (😂) emoji looks different on Messenger versus Telegram — Telegram's version is notably more animated.

Ultimately, the core purpose of the Unicode system is to make it possible to **digitally represent all languages and symbols** — past, present, and future — and it continues to be updated regularly.

---

## 🔑 Key Takeaways

- ✅ **ASCII** uses only 7–8 bits → max **256 characters** (English only)
- ✅ **Unicode** uses 16/24/32 bits → supports ~**4 billion characters**
- ✅ Unicode enables the use of **all world languages** and symbols digitally
- ✅ **Emojis exist** because Unicode had leftover bit combinations after covering all languages
- ✅ Unicode defines **what a character means** — not what it looks like
- ✅ The **visual design** of emojis is determined by each platform/company
- ✅ Same emoji can look **different** on Messenger vs Telegram vs other platforms
- ✅ Unicode is **continuously updated** to include future languages and symbols

---

*CS50x 2026 — Lecture 0 | Chapter 8*
