<h1 align="center">🎥 Video Calling Interview Platform ✨</h1>

![Demo App](/public/screenshot-for-readme.png)

<p align="center">
  A full-stack video interview platform built with <b>Next.js</b>, <b>TypeScript</b>, <b>WebRTC</b>, and <b>Socket.io</b>.<br />
  Designed for seamless remote technical interviews with real-time video calling, screen sharing, and authentication.
  <br /><br />
</p>

---

## 🌟 Highlights

- 🚀 **Tech Stack:** Next.js & TypeScript, Stream, Convex, Clerk  
- 🎥 **Video Calling** with WebRTC  
- 🖥️ **Screen Sharing**  
- 🎬 **Screen Recording**  
- 🔒 **Authentication & Authorization** (Clerk)  
- 🧠 **Server Components**, Layouts & Server Actions  
- 🎭 **Client & Server Components** separation  
- 🛣️ **Dynamic & Static Routing**  
- 🎨 Styled with **Tailwind CSS & Shadcn UI**  
- ✨ Uses **Server Actions** for clean logic flow

---

## ⚙️ Quick Setup

```bash
git clone https://github.com/burakorkmez/remote-interview-platform.git
cd remote-interview-platform
npm install
npm run dev
````

> 💡 Make sure the Socket.io server runs on `http://localhost:3001`.

---

## 🔐 Environment Variables

Create a `.env.local` file in the root and add:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

CONVEX_DEPLOYMENT=your_convex_deployment_url
NEXT_PUBLIC_CONVEX_URL=your_convex_public_url

NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
STREAM_SECRET_KEY=your_stream_secret_key
```

---

✅ Built for scalability, real-time collaboration, and a smooth developer experience — ready to power any remote interview workflow.
