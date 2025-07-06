---
layout: default
---

<div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; white-space: pre; line-height: 1.6; margin-bottom: 1em; font-size: clamp(1.2rem, 2vw, 2.2rem);">
<span style="color: #B5E853; font-weight: bold;">👋 Hi</span>        Hola     <span style="direction: rtl; unicode-bidi: bidi-override;">שלום</span>     你好      こんにちは
     <span style="color: #B5E853; font-weight: bold;">   I'm</span>   Soy        <span style="direction: rtl; unicode-bidi: bidi-override;">אני</span>         我叫      私の名前は
           <span style="color: #B5E853; font-weight: bold;">Gary</span>           <span style="direction: rtl; unicode-bidi: bidi-override;">גארי</span>       夏戈      ゲイリー
</div>

Former investment banker turned full-stack developer, with 500+ hours of hands-on coding through The Odin Project, Full Stack Open, and App Brewery. Proficient in JavaScript, React, Node.js, and Python, and hold certifications in AI (Azure, AWS), data analysis (IBM), and cloud (AWS). Interested in opportunities to build scalable systems at the intersection of web, data, and emerging technologies.

<span style="color: #B5E853;">*Fun Fact: "In 2013, only 28 babies born in England and Wales were named Gary, leading Garys to be labeled a "dying breed" ~ [Wikipedia](https://en.wikipedia.org/wiki/Gary_(given_name)#cite_note-8){:target="_blank" rel="noopener noreferrer"}*</span>


<br>

## **Table of Contents**

- **[3D Metaverse: Built on Ethereum & Three.js, Powered by AI](#3d-metaverse-built-on-ethereum--threejs-powered-by-ai)**  
  - [Live Demo](https://the-metaverse-by-myopicoracle-demo-v3-565993571311.us-west1.run.app){:target="_blank" rel="noopener noreferrer"}  •  [Repo](https://github.com/myopicOracle/myopic-metaverse){:target="_blank" rel="noopener noreferrer"}
- **[End-to-End AI Infrastructure: Deploy Local LLM Remotely](#end-to-end-ai-infrastructure-deploy-local-llm-remotely)**  
  - [Handling Ollama's Raw Bytes Stream](#handling-raw-bytes-stream-from-ollama-api-endpoint)  •  [Walkthroughs](https://youtu.be/meABLedKNhY){:target="_blank" rel="noopener noreferrer"}  •  [Repo](https://github.com/myopicOracle/run-local-llm-with-gui){:target="_blank" rel="noopener noreferrer"}
- **[YummyBuy E-Commerce](#yummybuy-e-commerce)**  
  - [Live Site](https://www.yummybuy.ca/){:target="_blank" rel="noopener noreferrer"}  •  [Project Board](https://github.com/users/myopicOracle/projects/3){:target="_blank" rel="noopener noreferrer"}
- **[The Simple Library](#the-simple-library)**  
  - [Live Demo](https://myopicoracle.github.io/prototypes-library/){:target="_blank" rel="noopener noreferrer"}  •  [Repo](https://github.com/myopicOracle/prototypes-library){:target="_blank" rel="noopener noreferrer"}
- **[Resume Builder React App](#resume-builder-react-app)**  
  - [Live Demo](https://simple-resume-app.netlify.app/){:target="_blank" rel="noopener noreferrer"}  •  [Repo](https://github.com/myopicOracle/resume-builder){:target="_blank" rel="noopener noreferrer"}
- **[Calcutron 8000 Calculator](#calcutron-8000-calculator)**  
  - [Live Demo](https://calcutron-8000.netlify.app/){:target="_blank" rel="noopener noreferrer"}  •  [Repo](https://github.com/myopicOracle/calcutron-8000){:target="_blank" rel="noopener noreferrer"}
- **[The Joshua Tree Foundation: Sustainable Finance](#the-joshua-tree-foundation-sustainable-finance)**  
  - [Website](https://yuccapalms.org/){:target="_blank" rel="noopener noreferrer"}  •  [Instagram](https://www.instagram.com/joshuatreefoundation/){:target="_blank" rel="noopener noreferrer"}  •  [LinkedIn](https://www.linkedin.com/company/joshua-tree-foundation){:target="_blank" rel="noopener noreferrer"}
- **[Certificates & Bootcamps](#certificates--bootcamps)**  
  - [The Odin Project](#the-odin-project---full-stack-javascript-track)  •  [Full Stack Open](#full-stack-open---core-certificate)  •  [App Brewery Bootcamp](https://www.appbrewery.co/p/full-stack-developer-course){:target="_blank" rel="noopener noreferrer"}  •  [IBM Data Analyst Professional](#ibm-data-analyst-professional)  •  [Microsoft Azure AI-900](#microsoft-azure-ai-900)
- **[Tech Stack](#tech-stack)**
- **[Let's Connect](#lets-connect)**


<br>

## **3D Metaverse: Built on Ethereum & Three.js, Powered by AI**

A proof-of-concept metaverse that combines blockchain technology with AI to create an interactive 3D environment with true digital ownership and intelligent NPCs.

<video autoplay loop muted playsinline style="max-width: 100%; height: auto; border-radius: 6px;">
  <source src="/assets/myopicmetaverse-demo.mp4" type="video/mp4">
  <img src="/assets/myopicmetaverse-demo.gif" alt="MyopicMetaverse Demo">
</video>

**Key Features:**
- **Web3 Authentication**: Secure Sign-In With Ethereum (SIWE) via MetaMask
- **AI-Powered NPCs**: Dynamic characters powered by Google Gemini API
- **3D Environment**: Custom-built interactive world using Three.js
- **Digital Ownership**: Foundation for future fungible digital assets
- **Contextual Awareness**: Advanced prompt engineering for immersive interactions

>### [**Live Demo**](https://the-metaverse-by-myopicoracle-demo-v3-565993571311.us-west1.run.app){:target="_blank" rel="noopener noreferrer"}
- Experience Web3 authentication with MetaMask
- Interact with AI-powered NPCs in real-time
- Explore the custom 3D environment
- No installation required - works directly in your browser

**Tech:** Three.js, Ethereum, Web3.js, Google Gemini API, Node.js  
[Project Repo](https://github.com/myopicOracle/myopic-metaverse){:target="_blank" rel="noopener noreferrer"}

<br>


## **End-to-End AI Infrastructure: Deploy Local LLM Remotely**

**Complete solution** for running large language models locally using Ollama, featuring custom Node.js server architecture, intuitive frontend GUI, and global deployment via ngrok and Vercel. This project demonstrates the full AI development lifecycle from local setup to production deployment.

### **Handling Raw Bytes Stream from Ollama API Endpoint**
<video autoplay loop muted playsinline style="max-width: 100%; height: auto; border-radius: 6px;">
  <source src="/assets/ollama_thumbnail_2.mp4" type="video/mp4">
  <img src="/assets/ollama_thumbnail_2.webp" alt="Handling Raw Bytes Stream from Ollama API">
</video>

**[Watch on YouTube](https://youtu.be/YrV2Q_hCtw8?si=yeECOJN9WFXIBH30&t=230){:target="_blank" rel="noopener noreferrer"}**

**Tech Stack:** Node.js, Express, Ollama API, ngrok, Vercel  
[Documentation](https://github.com/myopicOracle/run-local-llm-with-gui){:target="_blank" rel="noopener noreferrer"} • [Video Walkthroughs on YouTube](https://youtu.be/meABLedKNhY){:target="_blank" rel="noopener noreferrer"}

<br>


## **YummyBuy E-Commerce**

Built for a home business owner who needed a bespoke pre-order and customer/order management system + admin dashboard, but was frustrated with no-code website builders.

<video autoplay loop muted playsinline style="max-width: 100%; height: auto; border-radius: 6px;">
  <source src="/assets/yummybuy-demo.mp4" type="video/mp4">
  <img src="/assets/yummybuy-demo.webp" alt="YummyBuy.ca Loading Animation Demo">
</video>

**Key Features**: 
- SMS auth
- Orders & user maangement
- Data persistence using Cloud Firestore
- Cross-platform native CMS dashboard
- Inventory management
- Business analytics baked into admin view

>### [**Live Site**](https://www.yummybuy.ca/){:target="_blank" rel="noopener noreferrer"}
- Create an account using SMS verification - no email or password required
- Database: Cloud [Firestore] & Storage (Spark Plan Tier)
- Landing Page: Made with [P5.js](https://p5js.org/){:target="_blank" rel="noopener noreferrer"}
- Loading Animation: Created with [Google Veo2](https://deepmind.google/models/veo/){:target="_blank" rel="noopener noreferrer"} (circa April 2025)

**Tech:** React, Node.js, Express, TailwindCSS  
[Project Board](https://github.com/users/myopicOracle/projects/3){:target="_blank" rel="noopener noreferrer"} • [Repository](https://github.com/myopicOracle/YummyBuy.ca){:target="_blank" rel="noopener noreferrer"}

<br>


## **The Simple Library** 
*Constructors & Prototypes - 1st JavaScript Project (Dec. 2024)*

One of my first projects, and also easily one of the most memorable.

#### **Live Demo**

[![Library App Screenshot](/assets/simple-library-v2.png)](https://myopicoracle.github.io/prototypes-library/){:target="_blank" rel="noopener noreferrer"}

➡️ [Try the Live Demo](https://myopicoracle.github.io/prototypes-library/){:target="_blank" rel="noopener noreferrer"}

Built with vanilla JavaScript, this project was my first taste of OOP, getting some reps in for prototypal-inheritance, JS classes, constructor functions, DOM manipulation, and local storage.

#### What I Learned

- Object-oriented programming with JavaScript classes and prototypes
- DOM manipulation and event handling
- Form validation and data persistence
- Responsive web design principles
- Code organization and project structure

[Documentation](https://github.com/myopicOracle/prototypes-library){:target="_blank" rel="noopener noreferrer"}

<br>


## **Resume Builder React App**
*Interactive resume builder with persistent state*

![Resume Builder Screenshot](/assets/simple-resume-app.png)

Clean, functional resume builder demonstrating React fundamentals. Features component-based architecture, form state management with hooks, and seamless edit/display mode switching. Built with DRY principles and reusable components.

**Tech:** React, JavaScript, CSS  
[🔗 Live Demo](https://simple-resume-app.netlify.app/){:target="_blank" rel="noopener noreferrer"} • [Documentation](https://github.com/myopicOracle/resume-builder){:target="_blank" rel="noopener noreferrer"}

<br>


## **Calcutron 8000 Calculator**
*Vanilla JavaScript calculator with elegant UX*

![Calculator Screenshot](/assets/calcutron-8000-v1.png)

Built from scratch using vanilla JavaScript with thoughtful edge case handling (including a snarky "Nice try!" for division by zero). Features proper operation logic, real-time display updates, and polished responsive design.

**Tech:** JavaScript, HTML5, CSS3  
[🔗 Live Demo](https://calcutron-8000.netlify.app/){:target="_blank" rel="noopener noreferrer"} • [Repository](https://github.com/myopicOracle/calcutron-8000){:target="_blank" rel="noopener noreferrer"}

<br>


## **The Joshua Tree Foundation: Sustainable Finance**  
*Non-Profit Sustainable Finance Inititative*

A comprehensive sustainability platform exploring carbon offset initiatives through innovative products like Carbon X-Trace&#x2122; and blockchain-backed NFTrees. Features in-depth analysis of carbon markets, Net Zero frameworks, and accessible environmental education through structured digital storytelling.  

![CarbonXchange Homepage](/assets/jtf-hero.png)
![Mission: Advance #SustainableFinance](/assets/jtf-mission.png)
![Net Zero Framework](/assets/jtf-tech.png)

The Yucca Palms project, also known as The Joshua Tree Foundation, is a sustainable finance initiative that combines environmentalism with blockchain technology.

At its core, the project facilitates the planting of trees to sequester carbon dioxide. When you fund a tree, you receive a digital certificate of ownership in the form of an NFT (Non-Fungible Token), which they call an "NFTree." This token represents the physical tree and is recorded on a blockchain, also granting you a lease on the land where it grows.

As the tree matures and absorbs more CO2, you are intended to share in the benefits of the carbon offsets it generates. The project aims to operate within the voluntary carbon markets and is developing a suite of digital asset products, including a decentralized exchange for carbon credits.

**Focus:** Branding, Sustainable Finance, Fundraising, Sales & Marketing, Climate Tech, Blockchain  
[Joshua Tree Foundation](https://yuccapalms.org/){:target="_blank" rel="noopener noreferrer"} • [Instagram](https://www.instagram.com/joshuatreefoundation/){:target="_blank" rel="noopener noreferrer"} • [LinkedIn](https://www.linkedin.com/company/joshua-tree-foundation){:target="_blank" rel="noopener noreferrer"}

<br>


## **Tech Stack**

### **Languages/Runtimes:** 
- JavaScript / Node.js  
- Python / Flask  
- SQL / R  

### **Frameworks/Libraries:** 
- React / Express  
- TailwindCSS / Bootstrap   
- PostgreSQL / MySQL / SQLite  
- NumPy / Pandas / Scikit-learn
- Matplotlib / Seaborn

### **AI/ML:** 
- API Integration / Function Calling
- Model Deployment / Containerization 
- Prompt Engineering / MCP

### **Blockchain/Web3**
- Solidity / Smart Contracts
- Web3.js / Ethereum  

### **Currently Exploring:** 
- TypeScript / Next.js  
- Golang  
- Svelte  
- Rust  

<br>


## **Certificates & Bootcamps**

### **Completed:**   
##### *The Odin Project (Nov 2024 - Jun 2025)* 
- Foundational training in HTML, CSS, JavaScript, Node.js, Express.js, PostgreSQL, and React.js, in addition to building a robust portfolio of real-world projects, including responsive websites and full-stack applications, demonstrating proficiency in Git, deployment, and collaborative development.

##### [*The Complete Full Stack Web Development Bootcamp*](http://ude.my/UC-118e5203-a255-4989-81d8-38cb83fa120){:target="_blank" rel="noopener noreferrer"} (Oct 2024 - Jun 2025)   
- Full-stack web development with tools like HTML5, CSS3, JavaScript ES6, React.js, Node.js, Express.js, PostgreSQL, and Web3 technologies, building a portfolio of full-stack websites and web apps, including NFT and blockchain projects.

##### [*IBM Data Analyst Professional Certification*](https://coursera.org/verify/professional-cert/2DDH2VYKB4ET){:target="_blank" rel="noopener noreferrer"} (Jan 2025 - May 2025) 
- 11 course Professional specialization awarded for proficiency in Excel, SQL, Python, Jupyter Notebooks, and Cognos Analytics, with hands-on experience in data manipulation, visualization, and presenting insights from real-world datasets.

##### [*Microsoft Azure AI-900*](https://learn.microsoft.com/api/credentials/share/en-us/TheGaryXia/DE5DD36CDAB485C6?sharingId=BB48E30F2DE03E0D){:target="_blank" rel="noopener noreferrer"} (Apr 2025 - Apr 2025) 
- Awarded for demonstrating proficiency in fundamental machine learning, computer vision, natural language processing, and generative AI concepts, with hands-on experience using Azure AI services like Cognitive Services and Vision Studio to implement no-code AI solutions for real-world workloads.

   
### **In-Progress:**  
- AWS Cloud Solutions Architect - Associate [SAA-C03] (Jun 2025 - present)     
- Deeplearning.ai - Machine Learning Specialization (Apr 2025 - present)    
- freeCodeCamp - Certified Full Stack Developer (Sep 2024 - present)       
- University of Helsinki - Full Stack Open (Sep 2024 - present)       

### **Want to Earn:** 
- AWS Certified Developer Associate [DVA-C02]
- Certified Kubernetes Application Developer (CKAD)
- AWS Certified Machine Learning Engineer - Associate [MLA-C01]

### **See Certifications & Licenses**
#### [certified.garyxia.com](https://certified.garyxia.com/){:target="_blank" rel="noopener noreferrer"}

<br>


## **Let's Connect**

Always up for collaborating on interesting projects or discussing the latest in AI and full-stack development.

[**LinkedIn**](https://linkedin.com/in/xiagary){:target="_blank" rel="noopener noreferrer"}  
[**Email**](mailto:garebearcodes@gmail.com)  
[**GitHub**](https://github.com/myopicOracle){:target="_blank" rel="noopener noreferrer"}

> *Last updated: July 5, 2025*
