# Android Developer Internship at Engage Media TV

## Overview

**Role:** Android Developer (Kotlin)  
**Company:** Engage Media TV  
**Duration:** July 2025 – October 2025 (4 months)  
**Location:** Barcelona, Spain (Hybrid)  
**Team Size:** 4 members

### Team Composition

- **Eleonora "Elly" Filipic** – UI/UX Designer ([LinkedIn](https://www.linkedin.com/in/eleonora-filipic/))
- **Kisandas Antala** – Senior Android Developer ([LinkedIn](https://www.linkedin.com/in/kisandas-antala-631254a4/))
- **Shahar** – Project Owner
- **Myself** – Android Developer

---
## Technical Stack
- **Core Development:** Kotlin, Android SDK, XML layouts, Fragments
- **Networking & Data:** Retrofit
- **Backend & Services:** Firebase (Authentication, Firestore, Remote Config, Crashlytics, Analytics)
- **Version Control:** Git, GitHub, GitKraken 
- **Cloud & Publishing:** Google Cloud, Google Play Console, Amazon Developer Console (Fire TV)
- **Design & Collaboration:** Figma
- **Monetisation:** AdMob, HoneyGain, Monedata
- **Other:** Unity (for one game project)
----
## Projects

During my internship, I contributed to tree distinct projects, each presenting unique technical challenges and learning opportunities.

---
### 1. KishanHub TV & Mobile

**Project Type:** Video-on-Demand (VOD) Application  
**Platforms:** Android Mobile, Android TV, Amazon Fire TV
**Languages:** English, Marathi

**Context:** 
Designed to serve farmers in India with limited access to formal agricultural education. The platform was commissioned and sponsored by **ICL India**, a division of the multinational fertilizer and agricultural products company ICL Group, who also created and provided the tutorial video content.
When I joined the project, the application already existed but had minimal functionality—it simply fetched videos using Retrofit with no Firebase integration or user personalization features. The app was built using traditional Android architecture with XML layouts and Fragments, which was new to me as my previous experience was primarily with Jetpack Compose.

**My Contributions**
- Implemented comprehensive **Firebase integration**, including:
  - Authentication
  - User data storage and personalization
  - Saved video lists
  - Remote Config for dynamic feature control
  - Crashlytics for error monitoring
  - Analytics and custom event tracking
- Developed custom filtering and sorting logic on Retrofit API responses
- Organized tutorials into multiple dynamic lists to improve content discoverability and user experience
- Developed new screens to change all the UI and support user customization
- Implement different revenue strategies, such as Google AdMob and monetization SDKs like Honeygain and Monedata
- Delivered several major app updates that significantly enhanced functionality and transformed the user experience

**Platform-Specific Features**
- **KishanHub TV** —  Android TV and Fire TV devices:
  - Full DPAD navigation support optimized
  - EMTV Ads SDK
- **KishanHub Mobile** — Additional mobile-exclusive features:
  - Google Authentication
  - Google AdMob integration
  - Push notifications
  - Multiple monetization SDKs

**Design, Collaboration & Mentorship**  
- Guided by Kisandas Antala (Sr. Android, IN) – legacy XML / Fragment patterns, code-review, release signing, Play-Console staging.  
- Paired with Eleonora "Elly" Filipic (Product Designer, AU) to use Figma to discuss and iterate on improvements for the UI/UX.
- Guided by Shahar Naim (Project Owner, IL) – roadmap prioritisation, acceptance-criteria sign-off, and weekly OKR reviews

**Publishing & Distribution**
- Google Play Console (mobile)
- Amazon Developer Console (Fire TV / Amazon Fire Stick)

**Store metrics**  
- 10 k+ installs, 4.6★ average, DAU peak 600, Crash-free rate 99.2 %  

---
## Key Deliverables
| Feature                 | Tech Highlight                                          | User / Business Value                                                                              |
| ----------------------- | ------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| Firebase Auth & profile | Coroutines + sealed states                              | Zero-password onboarding for low-bandwidth users                                                   |
| Remote Config           | Real-time toggle paywalls                               | certify new ad SDK versions, silence ads for VIP demos,<br>new content without store update        |
| Async content pre-load  | Repository + interface flows + navigator-level prefetch | Data visible < 200 ms on open, perceived launch time ‑35 %, Play Console “slow render” drops ‑42 % |
| Unified crash dashboard | Crashlytics + custom logs + ANRs                        | Crash-free sessions 99.2 %, fix-turn-around < 24 h                                                 |

---
## Conclusion

This internship at Engage Media TV provided intensive, hands-on experience developing production Android applications that served real users solving real problems. Working on KishanHub, I saw firsthand how technology can make education accessible to underserved communities, while the technical challenges of supporting both mobile and TV platforms pushed me to grow as a developer.

The combination of mentorship from experienced developers, collaboration with talented designers, and responsibility for features used by thousands of users created an ideal learning environment. I emerged from this experience with a much deeper understanding of the Android ecosystem, Firebase services, professional development workflows, and the importance of building stable, user-focused applications.

---

## Links & References

- **Eleonora "Elly" Filipic (Designer):** [LinkedIn Profile](https://www.linkedin.com/in/eleonora-filipic/)
- **Kisandas Antala (Senior Android Developer):** [LinkedIn Profile](https://www.linkedin.com/in/kisandas-antala-631254a4/)
- **ICL Group:** [Company Website](https://icl-industrialproducts.com/)
