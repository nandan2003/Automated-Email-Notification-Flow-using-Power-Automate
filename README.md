# 📧 Automated Email Notification Flow using Power Automate

## 💡 Project Overview
This project demonstrates how to automate email notifications using **Microsoft Power Automate** and **Microsoft Forms**.

The flow listens for new form responses, applies logic conditions to evaluate user answers, and sends tailored email notifications based on the answers — minimizing manual intervention and ensuring timely communication.

---

## ⚙️ Flow Logic Breakdown

1. **Trigger - New Form Response**
   - When a user submits a response through **Microsoft Forms**, the flow is automatically triggered.

2. **Get Response Details**
   - The flow retrieves the submitted answers for evaluation.

3. **Condition 1: Coming to Event**
   - If the user confirms they are attending, the flow proceeds to nested checks.
   - If not, it sends a thank-you or alternative communication.

4. **Nested Condition 2: If from Hyderabad**
   - If the user is from **Hyderabad**:
     - Sends a customized email (Outlook `Send an email V2` action) acknowledging their RSVP.
   - If not:
     - Sends a different email tailored for non-local participants.

5. **Nested Condition 3: Question**
   - If the answer is `True`:
     - Sends a specific follow-up email.
   - If `False`:
     - Sends an alternative message.

6. **Condition 4: Question 2**
   - If the answer is `True`:
     - Sends a targeted email notification.
   - If `False`:
     - The flow can terminate or branch further depending on design.

---

## 🧰 Tech Stack

- 🏗️ Microsoft Power Automate  
- 📝 Microsoft Forms  
- 📧 Microsoft Outlook  
- 💻 Office 365 Environment  

---

## 💼 Use Case

- Event registration and confirmation workflows.
- Audience segmentation and targeted email follow-ups.
- Automating manual outreach based on form submissions.
- Simplifying RSVP management for events or workshops.

---

## 🚀 Outcome

This flow ensures:
- Immediate communication with users based on their responses.
- Personalized email delivery.
- Zero manual monitoring of form submissions.
- Structured and scalable approach for repeated use.

---

## 🖼️ Flow Diagram

![Power Automate Flow](./image.png)

---

## 🏷️ Tags

`Power Automate` `Microsoft Forms` `Outlook` `Email Automation` `Conditional Flow` `Office365`

---

## 📣 About the Author

Designed and built by **Nandan Vallamdasu** — focused on creating efficient, automated solutions with the Microsoft Power Platform.

---

