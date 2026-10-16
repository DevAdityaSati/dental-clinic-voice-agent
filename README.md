# 🦷 Dental Clinic Voice Agent

An AI-powered dental clinic voice assistant built using **Vapi and OpenAI** to handle patient conversations, collect appointment requests, and automate appointment confirmation emails through connected workflows.

## 🚀 Project Overview

Dental clinics regularly receive phone calls from patients looking to schedule appointments or ask basic questions. Handling these repetitive interactions manually can increase the workload for reception staff.

This project demonstrates how an AI voice agent can streamline patient interactions by communicating naturally, collecting appointment details, and connecting to an automated email workflow.

The goal is to improve the patient experience while reducing repetitive administrative tasks.

## ✨ Features

- **AI-Powered Voice Conversations:** Communicates with patients using natural-language voice interactions.
- **Appointment Requests:** Collects patient details and preferred appointment dates and times.
- **Conversational Information Gathering:** Asks relevant questions one at a time.
- **Email Confirmations:** Sends appointment confirmation emails through the configured workflow.
- **OpenAI Integration:** Understands patient requests and generates conversational responses.
- **Workflow Automation:** Connects the voice agent with external tools and email services.
- **Patient-Friendly Experience:** Guides patients through the appointment request process.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Vapi | Voice assistant configuration and call handling |
| OpenAI | Conversational AI |
| Zapier / MCP integration | Workflow automation and tool integration |
| Gmail | Appointment confirmation emails |

*The exact integrations depend on the configured implementation.*

## ⚙️ How It Works

1. **Patient Interaction:** A patient calls and interacts with the voice assistant.
2. **Request Understanding:** The agent identifies whether the patient wants to book an appointment or ask a question.
3. **Information Collection:** It gathers the required patient details and preferred appointment time.
4. **Appointment Processing:** The configured workflow processes the appointment request.
5. **Email Automation:** Once the appointment is successfully confirmed, the email workflow sends a confirmation.
6. **Final Response:** The voice assistant communicates the outcome to the patient.

## 🔄 Workflow Architecture

```text
Patient Phone Call
        |
        v
   Vapi Voice Agent
        |
        v
  OpenAI Conversation
        |
        v
Collect Patient Details
        |
        v
Appointment Workflow
        |
        v
 Email Automation
        |
        v
Gmail Confirmation
```

*This diagram represents the logical workflow. Actual appointment booking requires a configured booking system or calendar integration.*

## 💬 Example Interaction

**Patient:** Hello, I want to book a dental appointment.

**Voice Agent:** Of course! May I know your name?

**Patient:** Rahul Sharma.

**Voice Agent:** What date and time would you prefer for your appointment?

The assistant continues gathering the required information and processes the request through the configured workflow. It communicates the booking status once the outcome is verified.

## 🔧 Setup and Configuration

### Prerequisites

- A [Vapi](https://vapi.ai/) account
- An [OpenAI Platform](https://platform.openai.com/) account
- A configured email account, such as Gmail
- A workflow automation platform, such as Zapier, if used in the implementation

### Setup Steps

1. Create a voice assistant in Vapi.
2. Configure the system prompt with the clinic's information, conversation rules, and appointment-handling instructions.
3. Connect the required OpenAI model.
4. Configure the tools and integrations required to process appointment requests.
5. Set up the email automation workflow.
6. Test sample calls and verify the booking status and email delivery.

## 🔐 Security and Privacy

- Never upload API keys, access tokens, passwords, or credentials to GitHub.
- Store credentials securely in the relevant platform.
- Use dummy patient information during testing.
- Do not publish private patient conversations or personal information.
- Never claim an appointment is confirmed unless the booking system verifies it.
- Refer urgent or complex concerns to appropriate clinic staff.

## 🔮 Future Improvements

- Integrate real-time calendar availability.
- Add appointment cancellation and rescheduling.
- Send automated appointment reminders.
- Support multiple languages.
- Integrate a dental clinic management system.
- Add human handoff for complex patient enquiries.

## 🎯 Learning Outcomes

- AI voice agent development
- Prompt engineering
- Conversational AI
- API and tool integrations
- Workflow automation
- Automated email notifications

## 👨‍💻 Author

**Devaaditya Sati**

- GitHub: [@DevAdityaSati](https://github.com/DevAdityaSati)
- Profile: https://github.com/DevAdityaSati

## 📄 License

Add a `LICENSE` file if you intend to define permissions for using, modifying, and distributing this project.
