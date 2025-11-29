

# DOCTOR APPOINTMENT SYSTEM :
<img width="2816" height="1536" alt="Gemini_Generated_Image_yq01b8yq01b8yq01" src="https://github.com/user-attachments/assets/46c24d35-ade1-4340-95ff-c5aff8115085" />


# **Project Title**

AI-Powered Doctor Appointment Booking System

---

# **Project Subtitle :**

An Intelligent Telegram Agent for Seamless Healthcare Scheduling

---

# **Project Description :**

---

## **Problem Statement**

- Healthcare facilities struggle with manual appointment scheduling, leading to long wait times and administrative burden
- Patients face difficulties booking appointments outside clinic hours (9 AM - 5 PM)
- Phone-based booking creates bottlenecks and human errors in scheduling
- Staff spend excessive time managing appointments instead of patient care
- Double bookings and missed appointments reduce clinic efficiency
- **Why this matters:** Poor scheduling directly impacts patient satisfaction and healthcare delivery quality

---

## **Why Agents?**

- **24/7 Availability:** AI agents work round-the-clock, unlike human staff
- **Instant Response:** Patients get immediate confirmation without waiting on hold
- **Natural Conversation:** Users interact in simple language through Telegram, no complex forms needed
- **Automated Processing:** Agent handles booking, checking availability, and updating records automatically, Rescheduling And cancellation
- **Scalability:** One agent manages unlimited simultaneous booking requests
- **Error Reduction:** Eliminates human mistakes in scheduling and data entry

---

## **What I Created**

**Overall Architecture:**

1. **Frontend Layer:** Telegram chatbot acts as patient interface
2. **Processing Layer:** n8n workflow automation handles business logic
3. **Data Layer:** Google Sheets stores and manages appointment records

**System Flow:**

- Patient initiates conversation with Telegram bot
- AI agent asks for required details (name, date, time, email etc.)
- n8n processes the request and checks availability in Google Sheets
- System confirms booking and updates the database
- Patient receives instant confirmation message

---

## **Demo Scenario**

**User Interaction Example:**

1. Patient: "I need an appointment"
2. Bot: "Please provide your name"
3. Patient: "John Smith"
4. Bot: "Which date would you prefer?"
5. Patient: "December 5"
6. Bot: "Available slots: 10 AM, 2 PM, 4 PM"
7. Patient: "2 PM"
8. Bot: "Appointment confirmed for December 5 at 2 PM. Booking ID: #1234567892"

**Result:** Complete booking in under 2 to 5 minutes with zero human intervention

---

## **The Build**

**Technologies Used:**

- **Telegram Bot API:** Provides conversational interface accessible on any device
- **n8n Workflow Automation:** Connects all components and implements booking logic
- **Google Sheets API:** Acts as database for storing patient and appointment data

**Key Features:**

- Real-time availability checking
- Automatic time slot management
- Duplicate booking prevention
- Easy data retrieval for clinic staff

---

## **If I Had More Time**

- Integrate payment gateway for consultation fees
- Add doctor-specific scheduling for multi-doctor clinics
- Create admin dashboard for better appointment overview
- Include patient medical history integration
- Add voice message support for elderly patients
- Implement multi-language support

---

## **Conclusion**

This AI agent system transforms appointment booking from a time-consuming manual process into an instant, automated experience. By combining Telegram's accessibility, n8n's automation power, and Google Sheets' simplicity, the system solves real healthcare scheduling problems efficiently. Patients book appointments anytime, staff workload reduces significantly, and clinics operate more smoothly—proving that intelligent agents are the practical solution for modern healthcare management.
