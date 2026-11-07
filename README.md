# YatraAI – Smart India Travel Planner 🇮🇳✈️

An intelligent, AI-powered travel planning companion for exploring India, built with **React**, **TypeScript**, **Vite**, **Tailwind CSS**, and **Google Gemini AI**.

---

## ✨ Features

- 🤖 **AI-Powered Itinerary Generation:** Tailored day-wise travel plans based on duration, budget, and destination using the Google Gemini API.
- 🚆 **Multi-Modal Transport Comparison:** Compare estimated fares and travel times across Trains (Shatabdi, Rajdhani), Flights (IndiGo, Air India), Buses (Volvo Sleeper), and Cabs.
- 🏨 **Accommodations (Stay Options):** Curated lodging suggestions ranging from budget hostels to luxury heritage havelis and resorts.
- 🍽️ **Local Food & Dining Guides:** Recommendations for regional must-try delicacies, iconic street food spots, and scenic rooftop cafes.
- 💰 **Interactive Expense Calculator:** Real-time budget breakdown for food, stay, transport, and activities per traveler.
- 📍 **Maps Integration:** One-click navigation to explore destinations and attractions in Google Maps.
- 🛡️ **Offline / Demo Mode:** Automatic fallback to mock travel data when an API key is absent or quota is limited.

---

## 🛠️ Tech Stack

- **Frontend:** React 19, TypeScript, Vite
- **Styling:** Tailwind CSS
- **AI & LLM:** `@google/genai` (Google Gemini SDK)
- **Icons:** Lucide React

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18.0 or higher recommended)
- `npm` or `pnpm`

### 1. Clone the Repository

```bash
git clone https://github.com/rkp23032005/<repository-name>.git
cd <repository-name>
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env.local` file in the root directory (refer to `.env.example`):

```bash
cp .env.example .env.local
```

Open `.env.local` and add your Google Gemini API Key:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

> **Note:** You can obtain a free Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey).

### 4. Run Locally

```bash
npm run dev
```

Open your browser and visit `http://localhost:3000`.

---

## 📦 Project Scripts

| Command | Description |
| :--- | :--- |
| `npm run dev` | Starts the Vite development server on port 3000 |
| `npm run build` | Builds the optimized production application to `dist/` |
| `npm run preview` | Previews the production build locally |

---

## 📄 License

This project is licensed under the MIT License.
