# Oracle Data Archiving Guide (DCT + Data Pump)

This repository documents real-world Oracle data archiving workflows using DCT tool and Data Pump (impdp).

Focus:
- Large-scale data archiving (millions of rows)
- Partition-based archiving
- SQLLoader / Data Pump usage
- Troubleshooting real production issues

---

## 🔧 Tools Covered

- DCT (Data Copy Tool)
- Oracle Data Pump (impdp)
- SQL*Loader (concept)
- Oracle 11g / 19c

---

## 📊 Key Scenarios

- Archiving ACCT_BOOK
- Archiving ACCT_ITEM (8.6M rows)
- Archiving BILL (High Water Level case)
- Archiving E_INVOICE (Global Index issue)
- Archiving FINANCIAL_TRANSACTION

---

## ⚡ Highlights

- Partition-aware archiving strategy
- Handling Global Index limitations
- High-volume data migration (~8.6M rows in ~3 hours)
- Safe data cleanup after archiving
- Import validation and FK handling

---

## 🧠 Key Learnings

- Difference between SID vs Service Name
- impdp authentication pitfalls (ORA-01017)
- When to use SQLLoader vs INSERT
- Partition pruning strategy
- Impact of Global Index on partition operations

---

## 📁 Documentation

- DCT usage → dct-guide.md
- impdp usage → impdp-guide.md
- Troubleshooting → troubleshooting.md
- Real cases → /cases
