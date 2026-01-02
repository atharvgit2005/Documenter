# NYX: AI Content Automation Engine

## 1. Product Vision & Strategy
NYX is a full-stack **AI content agent** designed to automate the short-form video lifecycle for solopreneurs and high-value creators. By functioning as an "autopilot" system, it allows founders to maintain a consistent brand presence without the mental exhaustion of daily manual creation.

### Core Value Propositions
*   **End-to-End Automation**: Unlike tools that focus on single tasks, NYX manages everything from ideation to ready-to-post video.
*   **Elimination of Filming**: Uses AI avatars and voice cloning to produce content without requiring the creator to pick up a camera.
*   **Trend-Aligned Intelligence**: Dynamically analyzes Instagram content to ensure generated ideas remain relevant to the creator's niche.

---

## 2. Technical Architecture
The engine is built on a modular stack optimized for high-performance 3D graphics and sophisticated AI orchestration.

### Frontend (User Experience)
*   **Framework**: Next.js (React 19) for server-side efficiency.
*   **3D Visuals**: Three.js, React Three Fiber, and Drei for a premium, interactive interface.
*   **Animations**: GSAP (GreenSock) for high-performance UI transitions.

### Backend & Infrastructure
*   **Database & ORM**: PostgreSQL managed via Prisma for type-safe data handling of users and video metadata.
*   **Auth**: NextAuth.js with Bcryptjs for secure session management.
*   **Hosting**: Vercel for serverless deployment and edge caching.

### AI & Media Pipeline
*   **Content Engine**: Google Gemini AI (`@google/generative-ai`) serves as the primary brain for scriptwriting and niche detection.
*   **Data Scraping**: `@aduptive/instagram-scraper` and Cheerio for real-time market data acquisition.
*   **Visual Synthesis**: HeyGen API for generating AI-powered avatar videos.
*   **Voice Synthesis**: ElevenLabs for high-quality, realistic text-to-speech.

---

## 3. The NYX Workflow
1.  **Analysis**: NYX scrapes the user's existing Instagram profile to understand their unique tone and niche.
2.  **Ideation**: Gemini AI generates trend-aligned scripts based on the ingested data.
3.  **Synthesis**: The system creates a digital avatar using a single face-video and voice sample.
4.  **Delivery**: A platform-ready, fully edited video is produced in under a minute.

---

## 4. Roadmap & Evolution
NYX is transitioning from a successful hackathon MVP (CONSTruct 2025) into a scalable AI content agency model.

*   **Phase 1 (MVP)**: Dynamic niche detection and avatar generation.
*   **Phase 2 (Growth)**: Implementation of the "30-Day Content Batcher" for monthly autopilot scheduling.
*   **Phase 3 (Scale)**: Transition to a full-service AI-powered agency handling multi-client portfolios.

---
*Documentation generated for NYX Project Management - 2026 Refresh*