<h1 align="center">🎥 Video Calling Interview Platform ✨</h1>

![Demo App](https://github.com/Gauravpatil07/Remote-Interview-Platform/blob/0842a81934a59c14f25430169f061de77e00debf/Screenshot.png)

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
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

---

✅ Built for scalability, real-time collaboration, and a smooth developer experience — ready to power any remote interview workflow.
