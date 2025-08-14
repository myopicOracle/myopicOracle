# 👋 <span style="color: #FFF2E0;">Hi</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Hola&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;שלום&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;你好&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;こんにちは<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color: #FFF2E0;">I'm</span>&nbsp;&nbsp;&nbsp;Soy&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;אני&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;我叫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;私の名前は<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color: #FFF2E0;">Gary</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;גארי&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;夏戈&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ゲイリー

Former investment banker turned full-stack developer, with 500+ hours of hands-on coding through The Odin Project, Full Stack Open, and App Brewery. Proficient in JavaScript, React, Node.js, and Python, and hold certifications in AI (Azure, AWS), data analysis (IBM), and cloud (AWS). Interested in opportunities to build scalable systems at the intersection of web, data, and emerging technologies.

<span style="color: #FFF2E0;">*Fun Fact: "In 2013, only 28 babies born in England and Wales were named Gary, leading Garys to be labeled a "dying breed" ~ [Wikipedia](https://en.wikipedia.org/wiki/Gary_(given_name)#cite_note-8)*</span>


<br>

## **Table of Contents**

- **[Pollyglot - AI Language Learning Assistant](#pollyglot---ai-language-learning-assistant)**  
  - [Live Demo](https://project-pollyglot.vercel.app/)  •  [Repo](https://github.com/myopicOracle/ai-eng-build-with-me/tree/main/project-pollyglot/)
- **[3D Metaverse: Built on Ethereum & Three.js, Powered by AI](#3d-metaverse-built-on-ethereum--threejs-powered-by-ai)**  
  - [Live Demo](https://the-metaverse-by-myopicoracle-demo-v3-565993571311.us-west1.run.app)  •  [Repo](https://github.com/myopicOracle/myopic-metaverse)
- **[End-to-End AI Infrastructure: Deploy Local LLM Remotely](#end-to-end-ai-infrastructure-deploy-local-llm-remotely)**  
  - [Handling Ollama's Raw Bytes Stream](#handling-raw-bytes-stream-from-ollama-api-endpoint)  •  [Walkthroughs](https://youtu.be/YrV2Q_hCtw8?si=4jOrmUvKViu6QonI&t=12)  •  [Repo](https://github.com/myopicOracle/run-local-llm-with-gui)
- **[YummyBuy E-Commerce](#yummybuy-e-commerce)**  
  - [Live Site](https://www.yummybuy.ca/)  •  [Project Board](https://github.com/users/myopicOracle/projects/3)
- **[The Simple Library](#the-simple-library)**  
  - [Live Demo](https://myopicoracle.github.io/prototypes-library/)  •  [Repo](https://github.com/myopicOracle/prototypes-library)
- **[Resume Builder React App](#resume-builder-react-app)**  
  - [Live Demo](https://simple-resume-app.netlify.app/)  •  [Repo](https://github.com/myopicOracle/resume-builder)
- **[Calcutron 8000 Calculator](#calcutron-8000-calculator)**  
  - [Live Demo](https://calcutron-8000.netlify.app/)  •  [Repo](https://github.com/myopicOracle/calcutron-8000)
- **[The Joshua Tree Foundation: Sustainable Finance](#the-joshua-tree-foundation-sustainable-finance)**  
  - [Website](https://carbonxtrace.com/)  •  [Instagram](https://www.instagram.com/joshuatreefoundation/)  •  [LinkedIn](https://www.linkedin.com/company/joshua-tree-foundation)
- **[Certificates & Bootcamps](#certificates--bootcamps)**  
  - [The Odin Project](#the-odin-project---full-stack-javascript-track)  •  [Full Stack Open](#full-stack-open---core-certificate)  •  [App Brewery Bootcamp](#app-brewery-bootcamp)  •  [IBM Data Analyst Professional](#ibm-data-analyst-professional)  •  [Microsoft Azure AI-900](#microsoft-azure-ai-900)  
- **[Tech Stack](#tech-stack)**
- **[Let's Connect](#lets-connect)**


<br>

## **Pollyglot - AI Language Learning Assistant**
*Interactive language tutor powered by OpenAI*

**[Live App: project-pollyglot.vercel.app](https://project-pollyglot.vercel.app/)**

Built to cement concepts from Scrimba's ["The AI Engineer Path"](https://scrimba.com/the-ai-engineer-path-c02v) course - specifically OpenAI API integration, zero-shot vs few-shot prompting, and parameter tuning (temperature, stop-sequences, frequency/presence penalties). 

Beyond the core implementation, I explored OpenAI's ecosystem including their [Fine-Tuning](https://platform.openai.com/finetune) tool, [Playground](https://platform.openai.com/chat) for model experimentation, and [Model Evaluation](https://platform.openai.com/evaluations) capabilities. For developers seeking cost-effective alternatives, I've documented how to adapt the OpenAI library to work with [Gemini API's OpenAI compatibility](https://ai.google.dev/gemini-api/docs/openai) layer.

*Adapted Learning Resources:* [API Implementation Guides](https://github.com/myopicOracle/ai-eng-build-with-me/tree/main/project-pollyglot/docs) • [Alternative API Implementations](https://github.com/myopicOracle/ai-eng-build-with-me/tree/main/project-pollyglot/gemini-alt)

![Pollyglot Language Learning Interface](/assets/project-pollyglot-demo.png)

AI-powered language learning application that helps users practice 12 languages through interactive translation and conversation. Built with React and powered by OpenAI's GPT models, featuring advanced few-shot prompt engineering for consistent, encouraging responses from a patient instructor persona.

#### **[Live Demo](https://project-pollyglot.vercel.app/)**
- Practice 12 languages with an AI language instructor
- Get instant translations and cultural context
- Experience beginner-friendly explanations
- No registration required

**Tech:** React, Vite, Node.js, Express, Cloudflare Workers, OpenAI API  
[Project Repo](https://github.com/myopicOracle/ai-eng-build-with-me/tree/main/project-pollyglot/)

**AI Usage:** Made a deliberate effort to minimize AI use, turning off tab-complete and even React snippets. It came at the cost of less design polish, but paid back in full in the form of my own sanity and helping me remember that I'm still capable of writing a full stack React/Node app without it. I used AI to generate the README.md file, and to ask for clarification on dependencies, CORS configuration, and to debug the server setup, but I did not use AI to generate any of the actual code for this project. 

<br>


## **3D Metaverse: Built on Ethereum & Three.js, Powered by AI**

A proof-of-concept metaverse that combines blockchain technology with AI to create an interactive 3D environment with true digital ownership and intelligent NPCs.

![Myopic Metaverse 3D Environment Demo](/assets/myopicmetaverse-demo.gif)

**Key Features**:
- **Web3 Authentication**: Secure Sign-In With Ethereum (SIWE) via MetaMask
- **AI-Powered NPCs**: Dynamic characters powered by Google Gemini API
- **3D Environment**: Custom-built interactive world using Three.js
- **Digital Ownership**: Foundation for future fungible digital assets
- **Contextual Awareness**: Advanced prompt engineering for immersive interactions

#### **[Live Demo](https://the-metaverse-by-myopicoracle-demo-v3-565993571311.us-west1.run.app)**
- Experience Web3 authentication with MetaMask
- Interact with AI-powered NPCs in real-time
- Explore the custom 3D environment
- No installation required - works directly in your browser

**Tech:** Three.js, Ethereum, Web3.js, Google Gemini API, Node.js  
[Project Repo](https://github.com/myopicOracle/myopic-metaverse)

<br>


## **End-to-End AI Infrastructure: Deploy Local LLM Remotely**

Complete solution for running large language models locally using Ollama, featuring custom Node.js server architecture, intuitive frontend GUI, and global deployment via ngrok and Vercel. This project demonstrates the full AI development lifecycle from local setup to production deployment.

### **Handling Raw Bytes Stream from Ollama API Endpoint**
![Handling Raw Bytes Stream from Ollama API](/assets/ollama_thumbnail_2.gif)  
[Watch on YouTube](https://youtu.be/YrV2Q_hCtw8?si=4jOrmUvKViu6QonI&t=12)

**Tech Stack:** Node.js, Express, Ollama API, ngrok, Vercel  
[Project Repo](https://github.com/myopicOracle/run-local-llm-with-gui) • [Video Walkthroughs on YouTube](https://youtu.be/YrV2Q_hCtw8?si=4jOrmUvKViu6QonI&t=12)

<br>


## **YummyBuy E-Commerce**

Built for a home business owner who needed a bespoke pre-order and customer/order management system + admin dashboard, but was frustrated with no-code website builders.

![YummyBuy E-commerce Platform Demo](/assets/yummybuy-demo.gif)

**Key Features**: 
- SMS auth
- Orders & user maangement
- Data persistence using Cloud Firestore
- Cross-platform native CMS dashboard
- Inventory management
- Business analytics baked into admin view

#### **[Live Site](https://www.yummybuy.ca/)**
- Create an account using SMS verification - no email or password required
- Database: Cloud Firestore & Storage (Spark Plan Tier)
- Landing Page: Made with P5.js
- Loading Animation: Created with Google Veo2 (circa April 2025)

**Tech:** React, Node.js, Express, TailwindCSS  
[Project Board](https://github.com/users/myopicOracle/projects/3) • [Repository](https://github.com/myopicOracle/YummyBuy.ca)
[Project Board](https://github.com/users/myopicOracle/projects/3) • [Repository](https://github.com/myopicOracle/YummyBuy.ca)


<br>

## **The Simple Library** 
*Constructors & Prototypes - 1st JavaScript Project (Dec. 2024)*

One of my first projects, and also easily one of the most memorable.

#### **Live Demo**

[![Library App Screenshot](/assets/simple-library-v2.png)](https://myopicoracle.github.io/prototypes-library/)

➡️ [Try the Live Demo](https://myopicoracle.github.io/prototypes-library/)

Built with vanilla JavaScript, this project was my first taste of OOP, getting some reps in for prototypal-inheritance, JS classes, constructor functions, DOM manipulation, and local storage.

#### **What I Learned**

- Object-oriented programming with JavaScript classes and prototypes
- DOM manipulation and event handling
- Form validation and data persistence
- Responsive web design principles
- Code organization and project structure

[Project Repo](https://github.com/myopicOracle/prototypes-library)


<br>

## **Resume Builder React App**
*Interactive resume builder with persistent state*

![Interactive Resume Builder Interface](/assets/simple-resume-app.png)

Clean, functional resume builder demonstrating React fundamentals. Features component-based architecture, form state management with hooks, and seamless edit/display mode switching. Built with DRY principles and reusable components.

**Tech:** React, JavaScript, CSS  
[🔗 Live Demo](https://simple-resume-app.netlify.app/) • [Project Repo](https://github.com/myopicOracle/resume-builder)


<br>

## **Calcutron 8000 Calculator**
*Vanilla JavaScript calculator with elegant UX*

![Calcutron 8000 Calculator Interface](/assets/calcutron-8000-v1.png)

Built from scratch using vanilla JavaScript with thoughtful edge case handling (including a snarky "Nice try!" for division by zero). Features proper operation logic, real-time display updates, and polished responsive design.

**Tech:** JavaScript, HTML5, CSS3  
[🔗 Live Demo](https://calcutron-8000.netlify.app/) • [Repository](https://github.com/myopicOracle/calcutron-8000)


<br>

## **The Joshua Tree Foundation: Sustainable Finance**  

*"A Double-Bottoms Sustainable Finance Inititative"*

In 2023, I turned 6,000 acres of tax-draining Mojave Desert land into an environmental asset by connecting three disconnected system - conservation law, carbon markets, and blockchain.

In the early 2000s, the company I work for (Cador) acquired a strategic portfolio of over 6,000 acres in the Mojave Desert (2,000 acres directly owned, another 4,000 managed on behalf of real estate investors). These parcels were concentrated around Yucca Valley (CA), Kingman (AZ), and Lake Havasu (AZ).

The original investment thesis was shaped by the momentum behind projects like Interstate 11 (I-11), envisioned as a high-speed, multimodal corridor connecting Mexico to Canada via Phoenix and Las Vegas, the Brightline West high-speed rail (originally DesertXpress/XpressWest), and Kinder Morgan’s Calnev Pipeline expansion.

In parallel, our company had launched a $150M luxury resort project in Kingman, Arizona, meant to capitalize on the expected traffic and tourism from I-11. The 2008 financial crisis, followed by infrastructure setbacks and capital withdrawal, forced the project’s cancellation by 2011.

As a result, what had once been a promising speculative land play became a financial burden. By the 2020s, the land was generating no income and only property tax obligations.

That’s the context in which I began rethinking the value of this land.

While visiting these parcels, I noticed our acreage hosted a dense population of Yucca Brevifolia (aka Joshua Trees), which aside from the musical festival, I knew little about. As I dug deeper, I realized that this species thrives mainly in Lost Horse Valley in Joshua Tree National Park and only a few other regions - one being Mohave County, Arizona, where our land was located. That made our property one of the few dense, naturally occurring (and commercially-available) populations outside a national park.

Then in June 2023, California passed the Western Joshua Tree Conservation Act, classifying the plant as threatened due to climate change and imposing penalties of up to $2,500 for removal, relocation, or trimming of limbs (including dead trees and limbs!).

As a student of economics, I saw asset scarcity where others saw increased regulatory burden. That's why I launched "The Joshua Tree Foundation", to turn these protected trees into crypto assets called “NFTrees.” Each NFT represented an individual tree and included carbon offset rights and land leasing access.

The project attracted 200+ LinkedIn followers, 100+ Instagram followers, and board members including a former US Head of IT at Santander, an ExxonMobil VP, and a ClimateTech VC partner. But the crypto winter and AI's rise shifted attention away from carbon offsets, so I put it on the backburner (though the site is still live at [*carbonxtrace.com*](https://carbonxtrace.com/)).

More importantly, struggling to build the technical infrastructure myself sparked my transition from finance to software engineering. I spent the last 1.5 years learning full-stack development, AI integration, and ML deployment

> **"Tokenizing the Future of Carbon Finance"**

![CarbonXchange Homepage](/assets/jtf-hero.png)
![Mission: Advance #SustainableFinance](/assets/jtf-mission.png)
![Net Zero Framework](/assets/jtf-tech.png)

The voluntary carbon market (VCM) is projected to become a $100 billion industry by 2030 (Morgan Stanley), yet it remains opaque, illiquid, and challenged by transparency issues. The Joshua Tree Foundation began as an initiative to build the high-integrity financial infrastructure for this new era of environmental assets.

It started with an implausible idea. That by leveraging the recently endangered status of Yucca Palms (aka Joshua Trees), we could commoditize this natural asset through blockchain and gamification, dramatically increasing its revenue-generating potential while driving conservation.

Our ambitious plan protects over 6,000 acres of privately held family forests in the Mojave Desert (including 4,167 acres in Mohave County), mostly arable land suitable for Joshua Tree reforestation. These iconic plants grow only in California’s Joshua Tree National Park, the Mojave Desert, and parts of northern New Mexico.

Joshua Trees made history as California’s first plant species listed as threatened due to climate change (June 28, 2023). Without intervention, UC Riverside scientists predict their global population could fall to just 2% by century’s end.

We're developing a comprehensive sustainability platform starting with a novel, high-integrity asset: the NFTree. Each NFTree is a blockchain-based certificate representing a specific, planted tree - granting the holder a lease on the land and a share in the verified carbon offsets it generates. This isn't just about planting trees; it's about creating a transparent, liquid, and tradable asset class.

We also aim to perfect an immutable, traceable ledger - Carbon X-Trace™ - to deliver unparalleled transparency and verification. Paired with a decentralized exchange, this system will unlock global liquidity for carbon and other environmental assets. 

Visit - [*carbonxtrace.com*](https://carbonxtrace.com/) - to discover how we're revolutionizing conservation economics.

**TL;DR:**  
A comprehensive sustainability platform exploring carbon offset initiatives through innovative products like Carbon X-Trace™ and blockchain-backed NFTrees. Features in-depth analysis of carbon markets, Net Zero frameworks, and accessible environmental education through structured digital storytelling.  

**Focus:** Branding, Sustainable Finance, Fundraising, Sales & Marketing, Climate Tech, Blockchain  
[🌳 Joshua Tree Foundation](https://carbonxtrace.com/) • [Instagram](https://www.instagram.com/joshuatreefoundation/) • [LinkedIn](https://www.linkedin.com/company/joshua-tree-foundation) 


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
##### **[The Odin Project](https://www.theodinproject.com/) (Nov 2024 - Jun 2025)** 
- Foundational training in HTML, CSS, JavaScript, Node.js, Express.js, PostgreSQL, and React.js, in addition to building a robust portfolio of real-world projects, including responsive websites and full-stack applications, demonstrating proficiency in Git, deployment, and collaborative development.

##### **[The Complete Full Stack Web Development Bootcamp](http://ude.my/UC-118e5203-a255-4989-81d8-38cb83fa120) (Oct 2024 - Jun 2025)**   
- Full-stack web development with tools like HTML5, CSS3, JavaScript ES6, React.js, Node.js, Express.js, PostgreSQL, and Web3 technologies, building a portfolio of full-stack websites and web apps, including NFT and blockchain projects.

##### **[IBM Data Analyst Professional Certification](https://coursera.org/verify/professional-cert/2DDH2VYKB4ET) (Jan 2025 - May 2025)** 
- 11 course Professional specialization awarded for proficiency in Excel, SQL, Python, Jupyter Notebooks, and Cognos Analytics, with hands-on experience in data manipulation, visualization, and presenting insights from real-world datasets.

##### **[Microsoft Azure AI-900](https://learn.microsoft.com/api/credentials/share/en-us/TheGaryXia/DE5DD36CDAB485C6?sharingId=BB48E30F2DE03E0D) (Apr 2025 - Apr 2025)** 
- Awarded for demonstrating proficiency in fundamental machine learning, computer vision, natural language processing, and generative AI concepts, with hands-on experience using Azure AI services like Cognitive Services and Vision Studio to implement no-code AI solutions for real-world workloads.

   
### **In-Progress:**  
- **AWS Cloud Solutions Architect - Associate [SAA-C03]** (Jun 2025 - present)     
- **Deeplearning.ai - Machine Learning Specialization** (Apr 2025 - present)    
- **freeCodeCamp - Certified Full Stack Developer** (Sep 2024 - present)       
- **University of Helsinki - Full Stack Open** (Sep 2024 - present)       

### **Want to Earn:** 
- AWS Certified Developer Associate [DVA-C02]
- Certified Kubernetes Application Developer (CKAD)
- AWS Certified Machine Learning Engineer - Associate [MLA-C01]

### **See Certifications & Licenses**
#### **[certified.garyxia.com](https://certified.garyxia.com/)**


<br>

## **Let's Connect**

Always up for collaborating on interesting projects or discussing the latest in AI and full-stack development.

[💼 LinkedIn](https://linkedin.com/in/xiagary)  
[📧 Email](mailto:garebearcodes@gmail.com)  
[🐙 GitHub](https://github.com/myopicOracle)

> *Last updated: August 6, 2025*
