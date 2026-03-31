# Oracle Data Pump (impdp) Guide

## 1. Basic Command

impdp user/password@host:port/service \
directory=DIR \
dumpfile=file.dump \
logfile=import.log

---

## 2. Common Options

- table_exists_action=replace
- exclude=statistics,index
- remap_schema
- remap_tablespace

---

## 3. Performance Tips

- Use parallel=n
- Exclude index for faster import
- Rebuild index after import

---

## 4. Common Errors

### ORA-01017

Cause:
- Wrong password
- Wrong service_name
- PDB vs CDB confusion

Fix:
- Verify using sqlplus
- Check service_names

---

### FK Constraint Issue
<img width="692" height="350" alt="image" src="https://github.com/user-attachments/assets/2a0364b9-c40e-4b4d-a342-544b09690dd1" />

Solution:
- Import data first
- Create FK later
