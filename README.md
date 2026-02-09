# 🔥 Burning Man 2026 Budget Planners

Interactive budget planning tools for the Swan Forest camp partnership at Burning Man 2026.

## 🔒 Secure Access

**Password Protected** - All budgets require login.

1. Visit: **[Budget Login](https://whiteyruns.github.io/swan-forest-budget/login.html)**
2. Select your camp
3. Enter password: `burningman2026`
4. Session expires after 24 hours

## 📊 Live Budget Links

After logging in:
- **[Swan Forest Budget](https://whiteyruns.github.io/swan-forest-budget/)** - 60 campers (50% partnership share)
- **[Xanadu Budget](https://whiteyruns.github.io/swan-forest-budget/xanadu_budget.html)** - 30 campers (25% partnership share)
- **[Live Edge Entertainment Budget](https://whiteyruns.github.io/swan-forest-budget/live_edge_budget.html)** - 30 campers (25% partnership share)

## 🦢 Partnership Structure

**Total: 120 Burners**

- **Swan Forest:** 60 campers (50 regular @ $2,350 + 10 Class A RV @ $3,250) = $150K revenue
  - Pays 50% of shared expenses
  - Pays 50% of food & beverage
  
- **Xanadu:** 30 campers @ $2,250 = $67.5K revenue
  - Pays 25% of shared expenses
  - Does NOT pay for food & beverage
  - **Camp Director Fee:** $5,000 (100% Xanadu)
  
- **Live Edge Entertainment:** 30 campers @ $2,250 = $67.5K revenue
  - Pays 25% of shared expenses
  - Pays 50% of food & beverage
  - **Camp Director Fee:** $20,000 (100% Live Edge)

## 💰 Expense Categories

**Shared Expenses (50% Swan / 25% Xanadu / 25% Live Edge):**
- Operations & Infrastructure
- Vehicles & Transportation
- Swag & Camp Items
- Forest House & Lodging
- Decor & Art
- Cleaning & Sanitation
- Miscellaneous
- Event Staff

**Food & Beverage:**
- Split 50/50 between Swan Forest and Live Edge only

**Camp-Specific Fees:**
- Xanadu: $5,000 Camp Director Fee (100%)
- Live Edge: $20,000 Camp Director Fee (100%)

## ✏️ How to Use

1. **Log in** at login.html with password
2. **Select your camp** budget
3. **Edit line items** - click "Edit Line Items" to expand
4. **Edit item names** - click directly on any item name to rename it
5. **Edit amounts** - type new values in the number fields
6. **Add items** - click green "+ Add Item" button in any category
7. **Delete items** - click red "✕" button next to any item
8. **Save** - click "💾 Save Changes" button (or changes auto-save)
9. **Real-time sync** - see updates from other users instantly

## 🚀 Features

- **🔒 Password protected** - SHA-256 hashed passwords, 24-hour sessions
- **☁️ Firebase database** - Real-time sync across all users
- **✏️ Fully editable** - Names, amounts, add/delete items
- **💾 Auto-save** - Number changes save automatically
- **📊 Live calculations** - Totals, per-person costs update instantly
- **🎨 Dark theme** - Matches Prodigal Swan branding
- **📱 Responsive** - Works on desktop, tablet, and mobile
- **🔄 Real-time collaboration** - Multiple users can edit simultaneously

## 🔐 Security

### Changing the Password

1. Go to [SHA-256 Hash Generator](https://emn178.github.io/online-tools/sha256.html)
2. Enter your new password
3. Copy the generated hash
4. Edit `login.html` line 84, replace the `PASSWORD_HASH` value
5. Commit and push changes to GitHub
6. Share new password with camp members

### Firebase Database

- **Realtime Database** for live sync
- **Public read/write** (password protects the UI)
- Optional: Add Firebase security rules from `firebase-rules.json`

## 📝 Notes

- Each camp keeps their own camper fee revenue
- All expenses based on 2025 actuals scaled for 120 burners
- Budget amounts are estimates and fully adjustable
- **Changes ARE saved** to Firebase database
- Data persists across sessions and devices

## 🔧 Updates

To update the budgets:
1. Download HTML files from this repository
2. Edit locally or use Firebase migration tool
3. Upload updated files to GitHub
4. Changes live in 1-2 minutes

---

**Questions?** Contact camp leadership or visit [prodigalswan.com](https://www.prodigalswan.com)

*Self-discovery's a bitch when you're flammable* 🔥🦢
