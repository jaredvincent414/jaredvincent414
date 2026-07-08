<!-- ===== Header / Hero ===== -->
<p align="center">
  <!-- Optional banner -->
  <!-- <img src="path/to/header.png" alt="Header" /> -->
</p>

<h1 align="center">Hi there! I'm Vincent</h1>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com/demo/">
    <img
      src="https://readme-typing-svg.demolab.com?duration=2500&pause=800&center=true&vCenter=true&width=600&lines=Computer+Science+%2B+Economics+%40+Brandeis+University;Software+Engineer+%7C+ML+Enthusiast;Building+across+web%2C+mobile+%26+backend;Always+learning%2C+always+building"
      alt="Typing SVG"
    />
  </a>
</p>

<p align="center">
  <a href="https://vincentjared.com"> Portfolio</a> &nbsp;|&nbsp;
  <a href="mailto:vincentjared18@gmail.com"> Email</a> &nbsp;|&nbsp;
  <a href="https://www.linkedin.com/in/vincentjared"> LinkedIn</a>
</p>

---

## 👨‍💻 About Me
 ```csharp
using System;
using System.Collections.Generic;

public class Vincent
{
    const string Author = "Vincent";
    const string School = "Brandeis University — Computer Science & Economics";
    const string Email  = "vincentjared18@gmail.com";

    static readonly Dictionary<string, string[]> Stacks = new()
    {
        ["Languages"]      = new[] { "C#", "Python", "Java", "JavaScript", "TypeScript", "Rust", "Swift" },
        ["Frontend"]       = new[] { "React", "Next.js", "React Native", "Flutter", "Tailwind CSS", "Three.js" },
        ["Backend"]        = new[] { ".NET", "Node.js", "Express", "NestJS", "Django", "FastAPI", "GraphQL" },
        ["Data & ML"]      = new[] { "NumPy", "Pandas", "scikit-learn", "PyTorch", "TensorFlow" },
        ["Cloud & DevOps"] = new[] { "AWS", "Azure", "Vercel", "Render", "Cloudflare" },
        ["Databases"]      = new[] { "PostgreSQL", "Firebase", "Supabase" },
    };

    public static void Main()
    {
        Console.WriteLine($"👨{Author} | {School}");
        Console.WriteLine($"Reach me at: {Email}");
        Console.WriteLine("Passionate about software engineering, machine learning, and impactful tech.");
        Console.WriteLine("Building across web, mobile, and backend — always exploring new tools.");
        Console.WriteLine("Always learning, always building.");
    }
}
 ```
---

## 🏗️ Featured Projects


#### **[UniMarket](https://github.com/jaredvincent414/Campus-Marketplace)**
A mobile-first, peer-to-peer campus marketplace where students buy and sell within their community, with real-time in-app messaging tied directly to individual listings. Full-stack solo build — from database schema to mobile UI.

**Technologies Used:** React Native (Expo SDK 54) · TypeScript · Node.js · Express · MongoDB (Mongoose) · Socket.IO · GridFS

**Key Design Decisions:**
* Real-time messaging with Socket.IO — room-based architecture (`user:<email>` for inboxes, `conversation:<id>` for live threads)
* Conversations scoped to `(listingId, buyerEmail, sellerEmail)` to guarantee no duplicate threads
* Media upload pipeline storing images/video in MongoDB GridFS (up to 40 MB per file) via multipart form-data
* Listing lifecycle state machine (`available → pending → sold`) with soft-delete and API-layer self-purchase prevention
* File-based routing with Expo Router and a centralized theming + context state architecture

---

#### **Automation: The Game** &nbsp;·&nbsp; [🌐 Live Player Server](https://atg-player-server.jollytree-e1acebab.eastus2.azurecontainerapps.io)
A Dominion-style deck-building card game built as a 4-person team project — featuring a full game engine, a console harness, multiple AI player strategies, and a networked player server deployed to the cloud.

**Technologies Used:** Java · Maven · JUnit · Docker · Azure Container Apps · GitHub Actions

**Key Design Decisions:**
* Pluggable AI strategies behind a common `Player` interface (Big Money, Adaptive, and benchmark bots) for head-to-head comparison
* Card effects modeled as individual `ActionCardHandler` implementations (one class per card) for clean, testable game logic
* Player rating + benchmark harness runs automated match-ups to score strategy performance at scale
* `NetworkPlayer` lets remote agents compete against a publicly deployed player server on Azure Container Apps
* CI via GitHub Actions running the JUnit suite on every push

---

## 🚀 Tech Stack

### 💻 Languages
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white) ![Swift](https://img.shields.io/badge/Swift-F54A2A?style=for-the-badge&logo=swift&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

### 🎨 Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white) ![React Native](https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-8511FA?style=for-the-badge&logo=bootstrap&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### 🛠️ Backend
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express-404D59?style=for-the-badge&logo=express&logoColor=61DAFB) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)

### 📊 Data & Machine Learning
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

### ☁️ Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0072C6?style=for-the-badge&logo=microsoftazure&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)

### 🗄️ Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=firebase&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

### 🧰 Tools & Design
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## 🔗 Connect With Me
<p align="center">
  <a href="https://vincentjared.com"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/vincentjared"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:vincentjared18@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/jaredvincent414"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" /></a>
</p>

---

<p align="center">⭐️ From <a href="https://github.com/jaredvincent414">jaredvincent414</a></p>
