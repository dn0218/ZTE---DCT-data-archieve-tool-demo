# DCT Tool Usage Guide

## 1. Purpose

DCT is used for archiving large datasets from source DB to target DB.

---

## 2. Basic Workflow

1. Identify table
2. Check partition / filter condition
<img width="462" height="267" alt="image" src="https://github.com/user-attachments/assets/02000db0-2f5f-4054-aa07-695a752aa01d" />
<img width="397" height="248" alt="image" src="https://github.com/user-attachments/assets/db72bb46-0875-4a2c-80f2-4e4ce7368d30" />
3. Configure DCT
   <img width="1160" height="768" alt="image" src="https://github.com/user-attachments/assets/e8431eb9-a656-4a76-9e75-bcce4f4eee5a" />

4. Execute archiving
5. Verify target data
<img width="1175" height="620" alt="image" src="https://github.com/user-attachments/assets/3dce2117-6009-4d3a-8154-19e7d153de7d" />

6. Clean source data
<img width="593" height="291" alt="image" src="https://github.com/user-attachments/assets/297807c5-52f9-4edc-aeb4-01f2b0c94f52" />
---

## 3. Key Considerations

- Data volume
- Index impact
- Partition usage
- FK constraints
