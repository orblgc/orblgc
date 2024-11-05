---

# **👋 Hi there, I'm Orkun!**

I'm a **full-stack developer** with a passion for building efficient and innovative solutions. With over **5 years of experience** in **frontend** and **backend development**, **database management**, and **cloud-based services**, I enjoy creating well-structured and high-performing applications. I have a strong background in automating services and developing APIs that integrate systems seamlessly.

---

# **🛠️ Technologies & Tools:**

- **Languages**: JavaScript, PL/SQL, SQL, Node.js, C#, Java  
- **Frameworks & Libraries**: Oracle APEX, React, Express.js  
- **Database Management**: Oracle, SQL Server, MySQL  
- **DevOps Tools**: CI/CD, Nginx, Linux, Gitlab & Runners - Self Hosted, Jenkins, Docker  
- **Cloud Platforms**: Oracle Cloud, AWS, Google Cloud
- **APIs**: Microsoft Graph API, RESTful APIs  
- **Automation**: Service Automation with Linux, Test Automation with Cypress, Selenium  

---

# **📶 My APIs:**

- **Crypto Trading Indicator Analysis**: [Try API](https://rapidapi.com/orblgc/api/crypto-trading-indicator-analysis)
- **Create Game Rooms**: [Try API](https://rapidapi.com/orblgc/api/create-game-rooms)
  
---

# 🚀 Highlight Projects:

## ⚙️ Using Gitlab for Repo & CI/CD
#### Status: ✅  (Done !)
Before this implementation, i was using github webhooks to trigger my webhook nodejs service which was running shell script in server like a CI/CD but this was not a common way to do that kind of things.

So I created 3 Linux servers: CICD, DEV, and PROD servers. On the CICD server, I installed GitLab and Jenkins. Initially, I tried Jenkins and installed Jenkins agents on the DEV and PROD servers. However, using a webhook for integration with GitLab didn’t seem very efficient also management of two different system is a bit difficult. Therefore, I installed GitLab runners on the DEV and PROD servers. I registered these runners with the GitLab instance on the CICD server using authentication tokens. This way, I can automatically trigger releases through GitLab by defining pipeline files in the .gitlab-ci.yml for events like pushes and merges to GitLab repositories.

If i need to setup these project on a completely new server first thing to do manually would be only installation of gitlab-runner then registering it to my gitlab, then all i need to do is create new branch for that server then merge the installation repository which is for installing necessary packages on system like nginx, nodejs, python, certbot etc. Then i can directly push my api projects on their new branches.

Example Scenario
When I push a Node.js API development to the dev branch in GitLab, the pipeline is triggered and performs certain tasks on the DEV server. These tasks include:

Copy the Nginx configuration file from the repository to the nginx/conf.d folder for the project.
Obtain an automatic SSL certificate using Certbot for the Nginx configuration. If a certificate already exists, it uses the existing one.
Create and start a Linux systemd service with the project’s folder name.
With this example scenario, we successfully deployed to the development environment. After necessary tests are completed, we can merge the project into the production environment and similarly trigger an automatic release and deployment there as well.

## 💰 Crypto Currencies App & Bot 
#### Status: ⏳ (In Proggress)
A cryptocurrency tracking and trading bot application built with Node.js, Python, and Machine Learning. It integrates data from TradingView API and a custom API for detecting market indicators (e.g., SMA, Golden Cross, Death Cross) for real-time analysis. The bot uses Binance API to automatically manage buy/sell or long/short positions based on these indicators. Future plans include machine learning with LSTM neurons to improve trading decisions.

## 🌐 Sale Application & Website
#### Status: ⏳ (In Proggress)
Developed a complete sales application and website using Oracle APEX, Oracle Cloud, Node.js, and Linux. The website is hosted via Nginx, featuring an SMTP mail service running as a Node.js background process. Additionally, it uses a reverse proxy to manage Oracle Cloud's database URLs, ensuring a seamless user experience.

## 🩺 Health Check App 
#### Status: ✅  (Done !)
A tool that checks the status of servers and Linux services using Node.js and Shell scripts. It visualizes the service status through an Oracle APEX interface, offering an at-a-glance view of the health of key infrastructure components.

## 💻 API's & Servers 
#### Status: ✅  (Done !)
Created a set of fully automated APIs (e.g., currency converter, game room, country info) that leverage Node.js, Linux, webhooks, and GitHub to deploy and manage services dynamically. Webhooks are used to trigger service updates on Linux servers upon GitHub commits, ensuring no manual adjustments are required.

## 💬 Google Backend Chat App 
#### Status: ✅  (Done !)
Developed a chat application using Google Cloud with features like Seen, Online/Offline status, and push notifications via Firebase. The front-end was built with Xamarin Forms and C#.

## 📷 AWS Backend Chat App 
#### Status: ✅  (Done !)
A real-time chat application with features like photo and sound sharing, seen status, and user profile management. Built using React Native for the front-end and AWS services like DynamoDB, Cognito, and S3 for the backend.

## 🎮 Online Game 
### Status: 🛑 (Not in Use)
Developed a multiplayer 3D game using Unity for the game environment and Node.js for the backend socket server. Players are matched in real-time and send continuous updates of their positions for synchronized gameplay. The project also integrates with the create game room API to manage player matching and game sessions.

## 🧪 Test Automation (Cypress)
#### Status: ✅  (Done !)
Created a test automation solution using Cypress and JavaScript to automate the testing of various web applications. This project streamlines testing processes by automating repetitive tasks.

## 📦 Stock Control App
#### Status: ✅  (Done !)
Developed a mobile stock control application using Xamarin Forms for Google Cloud and Firebase integration. This app helps businesses manage their inventory in real-time across multiple locations.

## 💬 Socket Server for Chat
#### Status: ✅  (Done !)
Created a socket server using Node.js for real-time group chat functionality. This project integrates with AWS and React Native for front-end messaging.

## 🏥 Hospital Management Application
#### Status: 🛑 (Not in Use)
Built a marketplace for doctors and hospitals using Oracle APEX, PL/SQL, and HTML/CSS to manage appointments and patient records.

---

# **🎓 Education:**

- **Ege University** - Bachelor's Degree in Mechanical Engineering

---

# **📄 Certifications:**

- [Oracle Cloud Infrastructure Architect](https://catalog-education.oracle.com/pls/certview/sharebadge?id=4C5B5F177724BEE9A877845FB625A8E46F7DC9D75FDE540E18C8D7F8D0285181)  
- [Oracle APEX Cloud Developer Certified Professional](https://catalog-education.oracle.com/pls/certview/sharebadge?id=64929BF8AC76F2A984A3AD890D4FCBC1F930CD4A723DA8A98CE331C4D5D1E42D)  
- Quality Engineering and Management - Bilginet Academy 

---

# **💬 Get in Touch:**

- **Website**: [My Portfolio](https://orkun.ordibu.com/)
- **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/orkun-tun%C3%A7-bilgi%C3%A7-03b386113/)  
- **Email**: [Mail Address](mailto:orkunbl@hotmail.com)
- **Phone**: [+905464034708](tel:+905464034708)
- **GitLab**: [My GitLab Profile](https://gitlab.ordibu.com/orblgc)


---
