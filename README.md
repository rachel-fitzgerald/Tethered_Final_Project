
# Tethered: A Conceptual Support App for Couples

**Tethered** is a conceptual software solution designed to support couples in building emotional intimacy and healthy communication habits through small, daily check-ins. Inspired by existing apps like *Paired* and *Lasting*, Tethered fills key gaps in personalization, conflict support, and emotional transparency.

> “Connection is why we’re here.” – Brené Brown

---

## 📄 Final Presentation

- [Tethered_Final.pdf](https://github.com/rachel-fitzgerald/Tethered_Final_Project/blob/main/Tethered%20Final.pdf): Full PDF presentation including research, solution design, pseudocode, UI mockups, and open questions.

---

## 🧭 Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Solution: Tethered](#solution-tethered)
- [Key Features](#key-features)
- [Design Approach](#design-approach)
- [Pseudocode](#pseudocode)
- [User Journey](#user-journey)
- [Real-World Applications](#real-world-applications)
- [Open Questions](#open-questions)
- [Citations](#citations)
- [Assignment Coverage](#assignment-coverage)

---

## 📌 Overview

**Tethered** helps couples:
- Build emotional connection through daily micro-reflections
- Develop healthier communication habits
- Feel secure and supported through personalized, affirming interactions

---

## ❓ Problem Statement

While several apps aim to support relationships, most fall into two categories: **fun but shallow** (e.g., Paired) or **clinical and rigid** (e.g., Lasting). Few adapt to the unique dynamics of a couple or offer support for both routine connection and conflict repair.

---

## 💡 Solution: Tethered

Tethered provides:
- Daily prompts for reflection and communication
- Asynchronous participation with synced reveal
- Adaptive activities based on partner responses
- Balance of individual privacy and shared experience

---

## 🌟 Key Features

- 📝 Daily Questions: Personalized prompts for both partners  
- 🔒 Private Responses: Hidden until both have answered  
- ✅ Matched Answers → Shared Activity  
- 🔄 Mismatched Answers → Growth Activity  
- ⏰ Custom Reminders  
- 🔔 Real-time partner notifications  

---

## 🧠 Design Approach

- Grounded in relationship science (Gottman, Stanley & Markman)
- Focused on *low-pressure*, *high-consistency* habits
- Evolved from conflict-centered design to micro-reflection format based on peer feedback
- Inclusive design for long-distance and neurodiverse couples

---

## 💻 Pseudocode

```python
If new_day:
    prompt_user1 = generate_prompt()
    prompt_user2 = generate_prompt()
    send_to_users(prompt_user1, prompt_user2)

If response_received:
    store_response(user_id, timestamp)
    check_if_both_responded()
        if yes:
            unlock_joint_reflection()
```

Additional pseudocode includes:
- Response handling
- Notification logic
- Reminder system

(See full pseudocode in the PDF)

---

## 📱 User Journey

1. **Morning**: Prompt sent — Partner A responds privately  
2. **Afternoon**: Partner B responds after reminder  
3. **Evening**: Responses revealed — Suggestion based on match or difference  
4. **Optional**: Reflect together in shared journal  

---

## 🌍 Real-World Applications

- Long-distance relationships  
- Post-conflict emotional repair  
- Couples in life transitions (parenthood, moving)  
- Supplement to therapy or coaching  
- Low-effort daily emotional alignment  

---

## 🔎 Open Questions

- How to balance privacy and emotional safety in shared reflections?  
- How can we affirm non-traditional or neurodiverse relationship models?  
- What prompt styles best support post-conflict healing?  

---

## 📚 Citations

- Gottman Institute. (n.d.). *Card Decks App*. https://www.gottman.com/couples/apps/
- Paired. (n.d.). *Paired - Couples App*. https://www.paired.com/
- Lasting. (n.d.). *Lasting - Marriage Counseling App*. https://www.getlasting.com/
- Stanley, S. M., Markman, H. J., & Whitton, S. W. (2002). Communication, conflict, and commitment. *Family Process, 41*(4), 659–675.

---

## ✅ Assignment Coverage

| Requirement                             | Status     |
|----------------------------------------|------------|
| Real-world problem identified          | ✅ Complete |
| Research and existing solutions        | ✅ Complete |
| Proposed software solution             | ✅ Complete |
| Pseudocode and design logic            | ✅ Complete |
| User interaction and journey           | ✅ Complete |
| Visual mockups                         | ✅ Complete |
| Real-world applications explored       | ✅ Complete |
| Open questions identified              | ✅ Complete |
| Citations included                     | ✅ Complete |
| Presentation PDF in repo               | ✅ Complete |

---

🧠 *This repository demonstrates how programming and thoughtful design can address real-world emotional and relational challenges.*
