# 📄 PaperSaver-Edu-PDF

**Έξυπνος Μετατροπέας PDF 2-σε-1 (A4 Portrait σε A5 Landscape) για Εκπαιδευτικούς**  
*Optimized A4 to A5 PDF Converter for Teachers & Schools*

---

## 📌 Στοιχεία Προγράμματος & Ταυτότητα

- **Έκδοση:** `v2.1.0`
- **Program Architect:** George Petrakis
- **Copyright:** © 2025 George Petrakis
- **Άδεια Χρήσης:** [GNU General Public License v3.0 (GPLv3)](LICENSE)

---

## ✨ Περιγραφή & Χαρακτηριστικά

Το **PaperSaver-Edu-PDF** είναι ένα αυτόνομο (client-side) εργαλείο σχεδιασμένο ειδικά για εκπαιδευτικούς, φροντιστήρια και σχολεία με στόχο τη δραστική μείωση της κατανάλωσης χαρτιού και του κόστους εκτύπωσης/φωτοτυπιών.

Μετατρέπει τυπικά έγγραφα PDF μεγέθους A4 Portrait σε 2-σε-1 A4 Landscape, ιδανικά διαμορφωμένα ώστε με ένα κόψιμο στη μέση να παράγονται δύο αυτόνομα φυλλάδια A5 που επικολλώνται τέλεια στα τετράδια των μαθητών.

### Κύρια Πλεονεκτήματα:
1. **100% Client-Side & Ιδιωτικότητα (Privacy First):**
   - Καμία επεξεργασία δεν γίνεται σε εξωτερικό διακομιστή (server). Όλες οι μετατροπές εκτελούνται τοπικά στο πρόγραμμα περιήγησης (browser).
2. **Έξυπνη Διάταξη Σελίδων (Smart Imposition - "Teacher's Logic"):**
   - **Μονή Σελίδα (1 page):** Διπλασιάζεται αυτόματα δίπλα-δίπλα (2-σε-1) σε ένα φύλλο A4 Landscape (`_2in1_landscape_SINGLE.pdf`).
   - **Ζυγός Αριθμός Σελίδων (2, 4, 6...):** Συνδυάζει κανονικά τα ζεύγη σελίδων (1-2, 3-4, κ.λπ.) σε ένα αρχείο (`_2in1_landscape_FULL.pdf`).
   - **Περιττός Αριθμός Σελίδων (>1, π.χ. 3, 5...):** Χωρίζει έξυπνα την έξοδο σε **δύο** ξεχωριστά αρχεία:
     - **Part A (`_PART_A_FULL_PAGES.pdf`):** Όλα τα πλήρη ζεύγη σελίδων (π.χ. σελίδες 1 & 2).
     - **Part B (`_PART_B_LAST_PAGE_DOUBLE.pdf`):** Την τελευταία μονή σελίδα διπλασιασμένη δίπλα-δίπλα.
3. **Οδηγός Κοπής (Cutting Guide):**
   - Αυτόματη διακεκομμένη διακριτική γραμμή ακριβώς στο κέντρο για ακρίβεια στην γκιλοτίνα/κόπτη χαρτιού.
4. **Standalone Λειτουργία:**
   - Μπορεί να λειτουργήσει πλήρως αυτόνομα ως ενιαίο αρχείο `index.html` χωρίς καμία ανάγκη εγκατάστασης node ή server.

---

## 💡 Οικονομική Στρατηγική Εκτύπωσης για Σχολεία

**Παράδειγμα:** Έχετε ένα διαγώνισμα/φυλλάδιο 3 σελίδων και τμήμα 20 μαθητών.
- **Κλασικός τρόπος εκτύπωσης:**  
  20 μαθητές × 3 φύλλα A4 = **60 φύλλα A4**.
- **Μεθοδολογία PaperSaver-Edu-PDF:**  
  - Εκτυπώνετε **20 αντίτυπα** του **Part A** (Σελίδες 1 & 2).
  - Εκτυπώνετε μόνο **10 αντίτυπα** του **Part B** (Σελίδα 3 διπλή). Κόβετε στη μέση και έχετε 20 φυλλάδια για τη σελίδα 3!
- **Τελικό Αποτέλεσμα:** Χρησιμοποιήθηκαν μόνο **30 φύλλα A4** αντί για 60. **50% εξοικονόμηση χαρτιού & κόστους!**

---

## 🛠️ Τρόπος Χρήσης

1. Ανοίξτε το `index.html` σε οποιονδήποτε σύγχρονο περιηγητή (Chrome, Firefox, Safari, Edge).
2. Σύρετε (drag & drop) ή επιλέξτε το αρχείο PDF A4.
3. Το εργαλείο επεξεργάζεται ακαριαία το αρχείο και ξεκινά αυτόματα τη λήψη των βελτιστοποιημένων αρχείων.
4. Εκτυπώστε και κόψτε στη διακεκομμένη γραμμή!

---

## 📜 Άδεια Χρήσης (License)

Το παρόν λογισμικό διατίθεται υπό τους όρους της **GNU General Public License v3.0 (GPLv3)**.

```
PaperSaver-Edu-PDF
Copyright (C) 2025 George Petrakis

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.
```

---
*Σχεδιασμένο με μεράκι για εκπαιδευτικούς που νοιάζονται για το περιβάλλον και την εξοικονόμηση πόρων στο σχολείο.*
