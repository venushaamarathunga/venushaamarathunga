const fs = require('fs');

const readmeContent = `
# 👋 Hi, I'm Venusha Amarathunga

## 🧑‍💻 About Me
I am a **dedicated and passionate software engineer** with 4 years of experience in software development. I thrive on learning and embracing new technologies, with strong fundamental knowledge that empowers me to contribute meaningfully. Currently, I am exploring opportunities to enhance my expertise in **Spring Boot, React.js, Angular, AWS, Node.js, Next.js, and C#.NET**.

I am a **team player and self-driven individual** who believes in continuous learning and collaboration to solve challenging problems and create impactful solutions.

---

## 🌍 Location
📍 **Colombo, Sri Lanka**

---

## 🛠️ Technical Skills
### Programming Languages  
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)  
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  

### Web Development  
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)  
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)  
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)  

### Databases  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)  
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)  

### Tools and IDEs  
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)  
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white)  
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)  

---

## 🌟 Interests
- Building scalable software solutions
- Exploring new web development frameworks
- Cloud architecture and automation
- AI-driven applications

---

## 🎯 Free Time
- 📖 Reading about the latest tech trends  
- 🎮 Gaming  
- ✍️ Writing blogs on technology  
- 🚶‍♂️ Taking nature walks  

---

## 📫 How to Reach Me
- **📧 Email**: [avenusha95@gmail.com](mailto:avenusha95@gmail.com)  
- **🔗 LinkedIn**: [venushaamarathunga](https://www.linkedin.com/in/venushaamarathunga)  
- **📁 GitHub**: [venushaamarathunga](https://github.com/venushaamarathunga)  

---

`;

fs.writeFileSync('README.md', readmeContent, (err) => {
  if (err) {
    console.error('Error writing README file:', err);
  } else {
    console.log('README.md file created successfully!');
  }
});
