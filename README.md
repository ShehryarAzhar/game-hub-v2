# 🎮 Game Hub v2

An enhanced version of [Game Hub](https://github.com/ShehryarAzhar/game-hub) — a video game discovery app built with **React** and **TypeScript**, powered by the [RAWG Video Games Database API](https://rawg.io/apidocs).

This version introduces advanced features including data fetching with **React Query**, client-side routing with **React Router**, global state management with **Zustand**, and **infinite scrolling** for a seamless user experience.

🔗 **Live Demo:** [game-hub-v2-three.vercel.app](https://game-hub-v2-three.vercel.app)

---

## 📸 Preview

![Game Hub v2 Preview](https://github.com/user-attachments/assets/dbf38137-d728-45f1-a7a7-d41d0ef55fcb)

---

## ✨ Features

Everything from [Game Hub v1](https://github.com/ShehryarAzhar/game-hub), plus:

- ⚡ **React Query** — Efficient server state management with caching, background refetching, and deduplication
- 🗺️ **React Router** — Full client-side routing with dedicated game detail pages
- 🧠 **Zustand** — Lightweight global state management for filters and UI state
- ♾️ **Infinite Scrolling** — Seamlessly load more games as you scroll, no pagination clicks needed
- 🔍 **Game Search** — Instantly search from a massive library of video games
- 🎛️ **Filtering** — Filter games by genre, platform, and more
- 📊 **Sorting** — Sort results by relevance, rating, release date, and more
- 🌗 **Light & Dark Mode** — Toggle between themes for a comfortable browsing experience
- 💀 **Loading Skeletons** — Smooth skeleton loaders while content is being fetched

---

## 🛠️ Tech Stack

| Technology   | Purpose                      |
| ------------ | ---------------------------- |
| React        | UI framework                 |
| TypeScript   | Type safety                  |
| Chakra UI    | Component library & theming  |
| React Query  | Server state & data fetching |
| React Router | Client-side routing          |
| Zustand      | Global state management      |
| RAWG API     | Video game data source       |
| Vercel       | Deployment                   |

---

## 🚀 Getting Started

### Prerequisites

- Node.js `v18+`
- A free [RAWG API key](https://rawg.io/apidocs)

### Installation

```bash
# Clone the repository
git clone https://github.com/ShehryarAzhar/game-hub-v2.git
cd game-hub-v2

# Install dependencies
npm install
```

### Environment Variables

Create a `.env` file in the root of the project:

```env
VITE_RAWG_API_KEY=your_api_key_here
```

### Running Locally

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Building for Production

```bash
npm run build
```

---

## 📁 Project Structure

```
game-hub-v2/
├── src/
│   ├── assets/             # Static assets (images, icons, ...)
│   ├── components/
│   │   ├── ui/             # Auto-generated Chakra UI components
│   │   └── ...             # Reusable app components
│   ├── data/
│   │   ├── genres.ts       # Genre definitions
│   │   └── platforms.ts    # Platform definitions
│   ├── entities/           # TypeScript interfaces / domain models
│   ├── hooks/              # Custom React hooks (React Query hooks)
│   ├── pages/              # Route-level page components
│   ├── services/
│   │   ├── api-client.ts   # Axios / API setup
│   │   └── image-url.ts    # Image URL helper
│   └── ...
└── ...
```

---

## 🌐 Deployment

This app is deployed on **Vercel**. To deploy your own instance:

1. Push your code to GitHub
2. Import the repository on [Vercel](https://vercel.com)
3. Add your `VITE_RAWG_API_KEY` as an environment variable
4. Deploy 🚀

---

## 🔗 Related

This is the enhanced version of the original project. Check out [Game Hub v1](https://github.com/ShehryarAzhar/game-hub) for the foundational version.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
