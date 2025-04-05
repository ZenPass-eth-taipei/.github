# ZenPass: A POAP Platform for Dynamic AR Event Engagement

ZenPass is a next-generation POAP (Proof of Attendance Protocol) platform that transforms event participation into a dynamic, interactive digital experience. By combining geo-location, augmented reality (AR), AI-Agent powered booth recognition, and multi-chain support via NodIt, CCIP/Chainlink, ZenPass enables attendees to collect unique, branded POAPs that serve as verifiable proof of their participation—minted on the ideal blockchain network based on the event booth detected.

![image](https://github.com/user-attachments/assets/4d8194a9-5716-4ef6-ae63-def239355bcc)

## Key Features

- **Seamless Onboarding & Geo-Verification**  
  Instant user onboarding and geo-verification ensure that only attendees inside the event zone can interact with ZenPass experiences.

- **Immersive AR Activation**  
  When the user opens the camera, AR elements guide and enhance the experience, allowing attendees to interact with booths in a gamified way.

- **AI Booth Recognition**  
  Booth banners are captured and analyzed using AI to identify the brand (e.g., Nodit, Polygon). The booth identity determines the type of POAP to mint and the destination chain.

- **Cross-Chain Minting with CCIP**  
  The mint function is triggered on **Base Sepolia**, with **Chainlink CCIP** used to mint the final POAP on the appropriate chain (e.g., Polygon or others based on booth identity).

- **Nodit Protocol Integration**
  - **Webhook Notifications**: On successful mint, **Nodit webhooks** send instant push notifications to the user.
  - **Web3 Data APIs**: Used to fetch and display the user’s owned POAPs, dynamically rendered and chain-verified.

- **Stylized Memory Generation**  
  Generate shareable Ghibli-style or pixel-art visual representations of the captured AR moment or booth interaction. These dynamic images can be easily posted on social media to showcase attendance and add personal flair.

- **Real-Time Wallet Updates & Error Handling**  
  Minted POAPs reflect instantly in the user's wallet, with retry mechanisms and clean UX in case of camera/AI errors or mint failures.

## Primary Use-Cases

- **Verified Event Participation**  
  Mint geo-bound and booth-specific NFTs as **proof-of-presence**, validated via AR and AI.

- **Brand Engagement through AR**  
  Let booths like **Nodit** and **Polygon** offer branded AR POAPs that are instantly minted on the chain their brand represents.

- **Cross-Chain Activation**  
  Eliminate onboarding barriers by letting users interact with ZenPass once, and receive POAPs on Polygon or other chains using CCIP in the background.

- **Collectibles & Community Building**  
  Build social proof through shareable POAPs and stylized visuals with real-time display via Nodit’s API for profile showcases.

---

