# Day_19
The AI Support Triage Agent is an n8n workflow that automates customer support. It receives support requests through an HTML form, uses AI to classify messages by category and urgency, sends automatic replies for routine queries, and forwards urgent or sensitive cases to a human reviewer via Gmail, improving response time and support efficiency.


## **AI Support Triage Agent using n8n**

### **Project Description**

The **AI Support Triage Agent** is an intelligent n8n automation workflow that automatically receives customer support requests through a web form, analyzes them using an AI model, classifies each request by category and urgency, and routes it to the appropriate action. Routine support requests receive an automatic AI-generated reply, while urgent, sensitive, or ambiguous requests are escalated to a human reviewer for manual handling. This workflow reduces response time, improves support efficiency, and ensures important cases receive proper attention.

---

## **Workflow**

**HTML Form/Webhook → AI Agent → IF Node → Gmail (Automatic Reply) / Gmail (Human Review)**

---

## **What I Did**

* Created an **HTML form** to collect customer details (Name, Email, and Support Message).
* Connected the form to an **n8n Webhook** to receive support requests.
* Used an **AI Agent** to analyze the customer's message.
* Classified each request into categories such as **Billing, Technical, General, Account, or Feedback**.
* Assigned an urgency level (**Low, Medium, High**) and determined whether the request was **Routine, Sensitive, or Ambiguous**.
* Used an **IF node** to make a decision based on the AI classification.
* Sent an **automatic email reply** for routine support requests.
* Escalated urgent or sensitive requests to a **human reviewer** through Gmail.
* Added **retry/error handling** to improve workflow reliability.
* Tested the workflow with multiple support requests to verify correct routing.

---

## **Features**

* AI-powered support ticket classification.
* Automatic categorization of customer queries.
* Urgency detection (Low, Medium, High).
* Human-in-the-loop for sensitive or ambiguous cases.
* Automatic email responses for routine requests.
* Manual review notifications for high-priority cases.
* Web-based support request submission.
* Faster customer response time.
* Reduced manual workload for support teams.
* Reliable workflow with built-in error handling.

This project demonstrates how **AI and workflow automation** can streamline customer support by intelligently handling routine queries while ensuring that complex or high-risk issues are reviewed by a human.
