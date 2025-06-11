# Smart Event Planner

Smart Event Planner is a cloud-based project designed to automate and simplify event management. It focuses on streamlining event logistics, tracking guests, and coordinating vendors, all while leveraging cloud infrastructure to ensure scalability and efficiency.

HEAD
##  Project Title
**The Future of Smart Event Planning**

##  Author
**Praise Onosetalease – Lead Cloud Engineer**

##  Project Pitch

Smart Event Planner is a cloud-based platform that simplifies event planning with modern tools and automation. From RSVPs to vendor coordination, our system saves time and ensures smooth event experiences. It's designed to impress both users and investors with its sleek interface and smart features.

##  Professional Bio

I'm a student at AltSchool of Engineering, passionate about DevOps and cloud technologies. My skills include HTML, CSS, JavaScript, Linux, Git, and AWS. I enjoy building scalable solutions that solve real-world problems and demonstrate technical excellence.

##  Features

- Responsive landing page with personalized content
- Nginx web server hosted on AWS EC2 (Ubuntu)
- JavaScript interactivity
- Tailwind CSS styling and animations
- HTTPS (Let’s Encrypt SSL via Certbot)
- Public IP access

##  Deployment

This web application is deployed on an Ubuntu EC2 instance using:

- AWS EC2 (Ubuntu)
- Nginx as the web server
- TailwindCSS for styling
- Git & GitHub for version control
- Let's Encrypt SSL for HTTPS (optional enhancement)

##  How to Access

To view the deployed landing page, visit:

 [http://34.238.51.99](http://34.238.51.99)

##  Screenshot

![Screenshot of Smart Event Planner](screenshot.png)

##  Folder Contents

## Technologies Used

- **HTML5**: Structuring the content of the landing page
- **Tailwind CSS**: Utility-first CSS for responsive and modern styling
- **JavaScript**: For basic interactivity (e.g., button functionality)
- **AWS EC2**: Hosting the application on a virtual server
- **Nginx**: Web server to serve the static site
- **Git & GitHub**: Version control and repository management

## Project Deployment

The application is hosted on an AWS EC2 instance and accessible via a public IP. Static content is served using Nginx from the `/var/www/html` directory.
9eb21ad (Added professional bio and pitch)

##  Project Structure

```
smart-event-planner/
├── index.html          # Main landing page
├── README.md           # Project documentation
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Onosetalease/smart-event-planner.git
   ```

2. SSH into your AWS EC2 instance:
   ```bash
   ssh -i /path/to/your-key.pem ubuntu@your-ec2-ip
   ```

3. Upload your project files:
   ```bash
   scp -i /path/to/your-key.pem index.html ubuntu@your-ec2-ip:/var/www/html/
   ```

4. Visit the public IP in your browser to view the site.

##  Developer Notes

This project is part of a practical cloud deployment training focused on learning real-world deployment strategies using open-source tools and modern development practices.



###  **About the Developer**

Hi, I'm **Praise Onosetalease Chris**, a cybersecurity student with a keen interest in cloud technologies and digital innovation. With hands-on experience in web development and cloud deployment, I’m passionate about building efficient, secure, and scalable solutions that address real-world challenges. I specialize in tools like **AWS, Git, HTML, TailwindCSS, and JavaScript**, and I’m committed to leveraging technology to improve how we plan and execute events.

---

### **Professional Pitch**

**Smart Event Planner** is a cloud-based solution designed to modernize and simplify event management. It automates key processes such as guest tracking, vendor coordination, and logistics, delivering efficiency and real-time control to event organizers. Built with a lightweight front end and deployed on **AWS using Nginx**, the platform blends user-friendly design with the power of scalable cloud infrastructure—ideal for professionals seeking smarter ways to manage events.
