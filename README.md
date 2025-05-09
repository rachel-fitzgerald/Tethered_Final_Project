# Tethered: A Conceptual Support App for Couples

**Tethered** is a conceptual software solution designed to support couples in building emotional intimacy and healthy communication habits through small, daily check-ins. Inspired by existing apps like *Paired* and *Lasting*, Tethered fills key gaps in personalization, conflict support, and emotional transparency.

> “Connection is why we’re here.” – Brené Brown

## 📄 Final Presentation

- [Tethered_Final.pdf](./Tethered%20Final.pdf): Full PDF presentation including research, solution design, pseudocode, UI mockups, and open questions.

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

## 📌 Overview

**Tethered** helps couples:
- Build emotional connection through daily micro-reflections
- Develop healthier communication habits
- Feel secure and supported through personalized, affirming interactions

## ❓ Problem Statement

While several apps aim to support relationships, most fall into two categories: **fun but shallow** (e.g., Paired) or **clinical and rigid** (e.g., Lasting). Few adapt to the unique dynamics of a couple or offer support for both routine connection and conflict repair.

## 💡 Solution: Tethered

Tethered provides:
- Daily prompts for reflection and communication
- Asynchronous participation with synced reveal
- Adaptive activities based on partner responses
- Balance of individual privacy and shared experience

## 🌟 Key Features

- 📝 Daily Questions: Personalized prompts for both partners  
- 🔒 Private Responses: Hidden until both have answered  
- ✅ Matched Answers → Shared Activity  
- 🔄 Mismatched Answers → Growth Activity  
- ⏰ Custom Reminders  
- 🔔 Real-time partner notifications  

## 🧠 Design Approach

- Grounded in relationship science (Gottman, Stanley & Markman)
- Focused on *low-pressure*, *high-consistency* habits
- Evolved from conflict-centered design to micro-reflection format based on peer feedback
- Inclusive design for long-distance and neurodiverse couples

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
