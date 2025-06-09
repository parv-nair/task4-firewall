# task4-firewall

# 🔒 Cybersecurity Internship - Task 4: Firewall Setup and Rule Management

## 🧩 Objective:
Configure and test basic firewall rules to allow or block network traffic using Windows Firewall.

---

## 💻 Tool Used:
**Windows Defender Firewall (with Advanced Security)**

---

## 🛠️ What I Did:

1. Opened **Windows Firewall with Advanced Security**.
2. Viewed existing **Inbound Rules**.
3. Created a **new inbound rule** to:
   - Block traffic on **Port 23 (Telnet)** using **TCP protocol**.
   - Applied it to all profiles (Domain, Private, Public).
4. (Optional Step) Created a rule to **Allow Port 22 (SSH)**.
5. Took a **screenshot** of the new rule(s).
6. **Deleted the test rule** to restore the system to its original state.

---

## 🔐 Commands/Steps Used:

### ✅ Block Port 23 (Telnet)
- Inbound Rules → New Rule → Port → TCP → Specific Port: `23`
- Action: Block the connection
- Profile: All
- Name: `Block Port 23`

### ✅ (Optional) Allow Port 22 (SSH)
- Same steps as above, but:
- Action: **Allow the connection**
- Port: `22`
- Name: `Allow SSH`

### ❌ Remove the Block Rule
- Right-click on `Block Port 23` → Delete → Confirm

---

## 📸 Screenshots:
- `block_port_23_rule.png` – Showing the blocked rule for Port 23
- `allow_port_22_rule.png` *(if added)* – Showing the allowed rule for Port 22

---

## 🧠 Key Learnings:

- Learned how to **view**, **create**, and **delete** firewall rules.
- Understood **inbound vs outbound rules**.
- Gained hands-on experience in **network traffic filtering**.

---

## 📁 Folder Structure:


---

## ✅ Outcome:
Basic firewall management skills and better understanding of how firewall filters traffic and protects a system.

