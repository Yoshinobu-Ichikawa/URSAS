URSAS
Universal Rail Safety Alert System
Sharing “Unexpected Motion” in Advance for a New Public Transportation Experience

🌐 Language & White Papers
English — You are viewing the English README
📘 URSAS 5.4 English White Paper
Full Technical White Paper (PDF)
日本語 README — Japanese Version
📕 URSAS 5.4 Japanese White Paper
日本語版技術白書 (PDF)

Creating time for passengers to prepare before unexpected motion occurs.
🖼️ URSAS — Universal Rail Safety Alert System
![URSAS — Universal Rail Safety Alert System](images/URSAS%20hero.png.jpg)


📚 Contents
What Is URSAS?
URSAS in 3 Minutes
White Paper
Roadmap
Vision

What Is URSAS?
URSAS (Universal Rail Safety Alert System) is a public transportation safety platform designed to enhance passenger safety and comfort by providing advance notice of unexpected motion and sudden deceleration that may occur during transit.
Conventional railway safety systems have primarily evolved to ensure the safe operation and control of trains.
However, risks still remain inside passenger vehicles.
Unexpected motion or sudden deceleration can cause standing passengers to lose their balance, come into contact with others, or experience anxiety—especially when these events occur without warning.
URSAS focuses on a different dimension of safety:
Safety as experienced by passengers.
Rather than attempting to eliminate vehicle motion or directly control train operation, URSAS provides passengers with relevant information slightly in advance.
This creates valuable preparation time, allowing passengers to:
become aware of what is about to happen;
adjust their posture;
secure their balance;
hold onto available support; and
take appropriate safety action.
The core philosophy of URSAS is:
Reducing Unexpectedness
Even a few seconds of preparation can transform an unexpected event into one for which passengers are mentally and physically prepared.
URSAS therefore proposes a new passenger-centered approach to public transportation safety:
Create time for passengers to prepare before motion occurs.

URSAS in 3 Minutes
URSAS reduces unexpectedness by combining three prediction and information-sharing technologies with an integrated warning architecture.
The system can be understood through the following seven steps.

STEP 1｜A New Public Transportation Experience
🖼️ A New Public Transportation Experience
![A New Public Transportation Experience](images/hero-interior.jpg.jpg)

URSAS envisions public transportation in which:
Safety × Comfort × Experience Value
work together in harmony.
The goal is not simply to warn passengers of danger, but to create an environment in which people can travel with greater confidence, safety, and comfort.

STEP 2｜Why Was URSAS Created?
🖼️ Why Was URSAS Created?
![Why Was URSAS Created?](images/before-after.jpg.jpg)

Unexpected motion and sudden deceleration occur during everyday railway operation.
The greatest difficulty for passengers may not always be the motion itself.
The problem is often that:
It occurs without warning.
URSAS seeks to reduce this unexpectedness by providing relevant information slightly in advance and giving passengers time to prepare.

STEP 3｜SCE — Statistical Complement Engine
🖼️ SCE — Statistical Complement Engine
![SCE — Statistical Complement Engine](images/sce-overview.jpg.jpg)

Route Motion-Risk Information Sharing
SCE uses historical motion data and route characteristics to identify and share information about sections where significant motion is more likely to occur.
All URSAS-equipped trains share and accumulate Observed Motion data during daily operation.
SCE statistically analyzes this accumulated information and generates:
risk-related information for Tier 1
SCE does not determine the final Risk Level.
The final Risk Level is determined by the Risk Evaluator.

STEP 4｜DPE — Deceleration Prediction Engine
🖼️ DPE — Deceleration Prediction Engine
![DPE — Deceleration Prediction Engine](images/dpe-overview.jpg.jpg)

Predicting the Possibility of Rapid Deceleration
DPE uses current train speed, location information, operational conditions, and historical data to predict the possibility of sudden deceleration or strong braking.
DPE provides:
deceleration-risk information
to the Risk Evaluator.
This enables URSAS to provide passengers with preparation time before possible rapid deceleration.
DPE does not determine the final Risk Level.

STEP 5｜DCPE — Deterministic Chain Prediction Engine
🖼️ DCPE — Deterministic Chain Prediction Engine
![DCPE — Deterministic Chain Prediction Engine](images/dcpe-overview.jpg.jpg)

Observed Motion Sharing and ETA Calculation
DCPE uses actual Observed Motion detected by a preceding vehicle as a reference.
Based on this information, DCPE calculates:
ETA — Estimated Time of Arrival at the Motion Point
and shares this information in advance with the vehicle immediately behind it.
The V-Referencer selects the appropriate Reference Vehicle according to operating conditions so that useful preparation time can be provided whenever possible.
Through this vehicle-to-vehicle information-sharing structure, DCPE supports highly localized advance warning based on actual Observed Motion.

STEP 6｜Risk Evaluator × Tier Core × Universal Warning
🖼️ Universal Warning
![Universal Warning — Risk Levels](images/universal-warning1.jpg.jpg)

![Universal Warning — Multimodal Warning System](images/universal-warning2.jpg.jpg)



From Prediction to Passenger Notification
URSAS clearly separates:
Prediction → Risk Evaluation → Warning Policy → Notification Delivery
The Tier Engine determines:
Why should passengers be warned?
The Risk Evaluator determines:
How strongly should passengers be warned?
The Risk Evaluator integrates information from SCE, DPE, DCPE, and relevant operational conditions to determine the appropriate Risk Level:
Risk Level 1 — Attention
Risk Level 2 — Caution
Risk Level 3 — High Alert
The Tier Core integrates the warning reason (Tier) and warning intensity (Risk) and determines the final warning policy.
Universal Warning then distributes the notification to passengers through multiple sensory channels, including:
large onboard displays and LED lines;
audible notifications;
handrail and support-bar vibration;
floor vibration;
projectors; and
smartphone notifications.
This multimodal approach is designed to communicate essential safety information intuitively to passengers with different needs and circumstances.

STEP 7｜Public Transportation Experience
🖼️ Public Transportation Experience
![Public Transportation Experience](images/passenger-experience.jpg.jpg)

URSAS is not designed to pursue safety alone.
During normal operation, the same platform can provide passenger-experience functions such as:
G-Sync immersive experiences;
tourism and destination information;
multilingual information services;
environmental and spatial effects;
advertising; and
sponsored content.
Whenever a safety notification becomes necessary:
Safety always takes priority.
URSAS aims to create a new public transportation platform in which:
Safety × Experience Value × Sustainable Operation
can coexist.

📄 White Paper
For the complete URSAS concept, system architecture, prediction engines, Risk evaluation, warning design, safety mechanisms, and passenger-experience functions, please refer to the official white paper.
📘 URSAS 5.4 — English White Paper
The white paper includes detailed descriptions of:
URSAS safety philosophy
Reducing Unexpectedness
Safety Experience
Overall System Architecture
Tier-Based Safety Experience Control
SCE — Statistical Complement Engine
DPE — Deceleration Prediction Engine
DCPE — Deterministic Chain Prediction Engine
V-Referencer
ETA Calculation
Chain Responsibility Structure
Risk Evaluator
Tier Core
Universal Warning
Kill-Switch
G-Sync
Public Transportation Experience
📥 URSAS 5.4 English White Paper (PDF)

🚀 Roadmap
✅ Concept Design
✅ URSAS White Paper v5.4
✅ English White Paper v5.4
✅ GitHub Public Release
🚧 Prototype Development
🚧 Demonstration
🚧 Academic Publication
🚧 Railway Field Trial

Vision
URSAS is more than a technology for warning passengers about motion.
By becoming aware of what is about to happen just a little earlier, people can prepare themselves, support one another, and travel with greater confidence.
URSAS aims to establish a new standard for public transportation in which:
Safety
Comfort
Experience Value
work together in harmony.

URSAS
Universal Rail Safety Alert System
Sharing “Unexpected Motion” in Advance for a New Public Transportation Experience.

URSAS is an evolving research and development project.
Feedback, technical discussion, research collaboration, and proposals for future development are welcome.
