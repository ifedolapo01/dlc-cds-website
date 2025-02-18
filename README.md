# CDS Website  

## What’s This About?  
This is the official website for our DLC CDS group. The goal is to create a platform where members can sign up, manage their PPA & accommodation, and access bootcamp resources. I think it's best to build this with **React (Next.js) + Node.js** because it’s fast, secure, and easy to expand when we add more stuff.  

## Tech Stack  
### **Frontend**  
-  **React (Next.js)** – Makes the site load faster and smoother  
-  **Tailwind CSS** – For clean and responsive styling  
-  **NextAuth.js** – Handles user login & authentication  

### **Backend**  
-  **Node.js + Express** – Manages API requests  
-  **PostgreSQL / MongoDB** – Stores user data  
-  **Prisma / Mongoose** – Helps interact with the database  

### **Hosting**  
-  **Frontend** – Vercel  
-  **Backend** – Render / Heroku  
-  **Database** – Supabase / MongoDB Atlas  

## Why React (Next.js) + Node.js?  
I looked at **WordPress** vs. **React (Next.js) + Node.js** and chose this stack because:  

**Scalable** – Can handle more users without slowing down  
**Fast** – Loads pages quickly with optimized rendering  
**Secure** – Protects API routes & supports strong authentication  
**Flexible** – Works well with databases, APIs, and cloud services

## Why Not WordPress?
While WordPress is great for simple websites, it’s not the best choice for this project because:

**Limited scalability** – WordPress can slow down as more users and features are added
**Performance issues** – Plugins and themes can affect speed, making the site less efficient
**Security risks** – WordPress sites are common targets for attacks, and keeping it secure requires constant updates
**Less flexibility** – Customizing features like user authentication, LMS, and PPA management is harder compared to a custom-built solution

## Features (Now & Future)  
User Registration & Login  
PPA & Accommodation Management  
Bootcamp LMS  
Admin Dashboard  
Chat & Notifications  

## Getting Started  
1 **Clone this repo**  
   ```bash
   git clone https://github.com/your-username/cds-website.git
   cd cds-website
   ```  
2 **Install dependencies**  
   ```bash
   npm install
   ```  
3 **Run the project**  
   ```bash
   npm run dev
   ```  

## Want to Contribute?  
- Fork the repo  
- Create a new branch (`feature-branch-name`)  
- Make your changes & commit (`git commit -m "Added XYZ feature"`)  
- Push & open a pull request  

## Questions?  
Got ideas or issues? Open an issue or reach out!  
