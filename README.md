# CTI Protocol Simulator Pro - AI-Driven CCaaS Edition

This project is a sophisticated **CTI (Computer Telephony Integration) Protocol Simulator** designed for educational and demonstration purposes. It visualizes complex telecommunications protocols like SIP, WebRTC, MGCP, CSTA, TAPI, SIPREC, and STIR/SHAKEN through interactive sequence diagrams and AI-narrated scenarios.

## 🌟 Key Features

*   **Interactive Simulations:** Run step-by-step simulations of real-world call flows including Inbound, Outbound, Transfer, Conference, and Hold scenarios.
*   **Modern Protocol Support:** Covers legacy standards (MGCP, TAPI) alongside modern cloud technologies (WebRTC, SIPREC, STIR/SHAKEN).
*   **AI Voice Narration:** Utilizes the Web Speech API to provide real-time voiceover explanations for every protocol message, making learning immersive.
*   **Visual Sequence Diagrams:** Dynamically generates sequence diagrams to illustrate message exchanges between participants.
*   **Deep Inspection:** Click on any message to inspect the full raw payload (SDP, XML, SIP headers, JSON) to understand the underlying data structures.
*   **Zero-Dependency Architecture:** Built as a single-file application using Vanilla JavaScript and CSS variables for maximum portability and performance.

## 🚀 Getting Started

Simply open `cti-simulator-pro.html` in any modern web browser (Chrome, Edge, Firefox, Safari). No installation or server setup is required.

## 🛠️ Technology Stack

*   **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3.
*   **Styling:** Modern CSS with CSS Variables, Flexbox, and Glassmorphism effects.
*   **Fonts:** Uses `Outfit` for headings and `Inter` for body text via Google Fonts.
*   **Voice:** Web Speech API (`window.speechSynthesis`).

## 📚 Supported Protocols

1.  **SIP (Session Initiation Protocol):** The standard for VoIP signaling (RFC 3261).
2.  **WebRTC:** Browser-based real-time communication.
3.  **SIPREC:** Protocol for call recording and AI analysis (RFC 7866).
4.  **MGCP (Media Gateway Control Protocol):** Legacy gateway control (RFC 3435).
5.  **CSTA (Computer Supported Telecommunications Applications):** Enterprise CTI standard (ECMA-323).
6.  **TAPI (Telephony Application Programming Interface):** Microsoft's legacy telephony API.
7.  **STIR/SHAKEN:** Caller ID authentication framework for anti-spoofing.
8.  **AI Voice API:** Demonstrates modern LLM-driven voice agent flows.

## 🎨 Customization

The simulator is data-driven. You can easily extend it by modifying the `PROTOCOLS` and `SCENARIOS` constant objects within the `cti-simulator-pro.html` file to add new protocols or custom call flows.

## 📄 License

This project is open-source and available under the MIT License.
