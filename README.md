# zoo_audit
Zoo Audit - C++ Programming Patterns assignment focusing on collection management, multisets, and enclosure auditing logic.
Zoo Audit

## 📋 Project Overview
This repository **Zoo Enclosure Audit System** that analyzes a map of enclosures and the animals inside them. The system's responsibility is to maintain a valid zoo ecosystem by auditing enclosures for two main criteria:
1. **Duplicate Species:** Ensuring that there is at most *one* animal of any given species across the entire zoo.
2. **Sick Animals:** Completely removing any animals on the sick list from all enclosures.

---

## 🛠️ Assignment Instructions & Modifications

to modify the existing program so that it fulfills the following behavior:

* **Duplicate Handling:** Remove *only* duplicate animals. An animal is removed from an enclosure **only** if that same animal is kept in another enclosure; otherwise, the animal remains. Put simply, there can be **at most one** animal of any species in the entire zoo.
* **Sick Animals:** Sick animals must still be completely removed from every enclosure they appear in, regardless of duplication status.

### Implementation Guidelines:
1. **`getDuplicates` Function:** Modify this function so that it returns a `std::multiset` containing all the extraneous (to be removed) animals.
2. **`auditEnclosures` Function:** Modify this function so that it removes an animal from your duplicates container as it removes it from the enclosure.

---
