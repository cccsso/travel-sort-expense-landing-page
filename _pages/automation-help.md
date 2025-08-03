---
layout: page
title: Automation Help
include_in_header: true
---

# Apple Pay Integration Help

You can automate expense logging by setting up a Shortcut that triggers when tap and pay using Apple Pay.

> **Note:**  
> ⚠️ It's very important that you have your phone **unlocked** while the shortcut runs and do **not** let your phone go to sleep.
> Also ensure you have a **stable wifi connection**

We do not in any way have access to your card. The only details we collect when you run the automation are:

- the card name seen in your Apple Wallet
- the expense amount
- the expense currency code
- location when you run the automation
- category of expense (Food, shopping, drinks etc)
- any notes you add when you run the automation

## Automation Demo

A demo of the shortcut automation in action:

<div class="responsive-iframe">
  <iframe src="https://www.youtube.com/embed/5fuVE12RUuU" title="Automation Demo" frameborder="0" allowfullscreen></iframe>
</div>

## How to Set up Apple Shortcut to Import Transactions into the app

### Tutorial Video

<div class="responsive-iframe">
  <iframe src="https://www.youtube.com/embed/ttg5-ObEMjo" title="How to set up automation" frameborder="0" allowfullscreen></iframe>
</div>

### Text Instructions

#### Creating a new Automation

![Apple Shortcut Example](/travel-sort-expense-landing-page/assets/automationHelp/shortcut-help1.png)

You can open the [Apple Shortcuts](https://apps.apple.com/us/app/shortcuts/id915249334) app and follow the steps below.

1. Open the [Apple Shortcuts](https://apps.apple.com/us/app/shortcuts/id915249334) app on your iPhone.

2. Go to the **Automation** tab and tap the **➕ Plus button** to create a new automation.

3. **Search for "Transaction"** and select the **Transaction** automation trigger.

4. **Choose the cards** you'll be using for your trip.

5. Make sure **“Run After Confirmation”** is selected, so you can run the automation when you're ready.

6. Select **“New Blank Automation.”**

7. Drag in the **“Import Transactions to Sort”** action.

#### 🔧 Set Input Fields

![Apple Shortcut Example](/travel-sort-expense-landing-page/assets/automationHelp/shortcut-help2.png)

8. Search for **“Get Input from Numbers”** and drag it **above** the import action.

9. Tap the **Input** field in the Numbers action → scroll and select **“Shortcut Input.”**

10. Tap **Shortcut Input again** → change **type to Transaction Amount.**

11. Tap the **empty Amount field** → select the **Numbers variable.**

12. Tap the **Currency Code field** → scroll and select **Shortcut Input.**

13. Tap **Shortcut Input again** → change **type to Currency Amount.**

14. Select **Currency Code** from the variable options.

15. Tap the **Merchant field** → scroll and select **Shortcut Input.**

16. Tap **Shortcut Input again** → change **type to Merchant.**

17. Tap the **Card Name field** → scroll and select **Shortcut Input.**

18. Tap **Shortcut Input again** → change **type to Card or Pass.**

19. For the **Category field**, select **“Ask Each Time.”**

20. For the **Notes field**, also choose **“Ask Each Time.”**

#### ✅ You're Done!

🔁 When you tap your card via Apple Pay and run the automation:

- You'll be asked to enter the category and any notes.
- After submitting, wait a few seconds for the expense to be imported into the Travel Sort Expense app.

### 💡 **Tips**:

- Make sure your phone is **unlocked** before running the automation.
- Requires a **stable Wi-Fi connection** to import properly.
- ⚠️ Heads up: If you don’t get a transaction notification from your Apple Wallet, the shortcut may not run properly. This usually means your phone had trouble connecting. Try stepping outside or moving to an area with stronger Wi-Fi or mobile signal, then run the shortcut automation.
- This automation only works with physical Apple Pay transactions. (Doesn't work for online purchases)

### Advanced set up

If you want a more advanced shortcut, you can add these steps to optionally handle payment errors, capture images or send logs to an iMessage chat

![Apple Shortcut Advanced Example](/travel-sort-expense-landing-page/assets/automationHelp/shortcut-advanced1.png)
