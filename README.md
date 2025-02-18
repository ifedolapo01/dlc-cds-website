# CDS Website  

## What’s This About?  
This is the official website for our CDS group. The goal is to create a platform where members can sign up, manage their PPA and accommodation, and access bootcamp resources. I think its best to build this with **React (Next.js) + Node.js** because it’s fast, secure, and easy to expand when we add more features.  

## Tech Stack  
### Frontend  
- **React (Next.js)** – Makes the site load faster and smoother  
- **Tailwind CSS** – For clean and responsive styling  
- **NextAuth.js** – Handles user login and authentication  

### Backend  
- **Node.js + Express** – Manages API requests  
- **PostgreSQL / MongoDB** – Stores user data  
- **Prisma / Mongoose** – Helps interact with the database  

### Hosting  
- **Frontend** – Vercel  
- **Backend** – Render / Heroku  
- **Database** – Supabase / MongoDB Atlas  

## Why React (Next.js) + Node.js?  
I compared **WordPress** and **React (Next.js) + Node.js** and chose this stack because:  

- **Scalability** – Can handle more users without slowing down  
- **Performance** – Loads pages quickly with optimized rendering  
- **Security** – Protects API routes and supports strong authentication  
- **Ease of Integration** – Works well with databases, APIs, and cloud services  

## Why Not WordPress?  
While WordPress is great for simple websites, it’s not the best choice for this project because:  

- **Limited scalability** – WordPress can slow down as more users and features are added  
- **Performance issues** – Plugins and themes can affect speed, making the site less efficient  
- **Security risks** – WordPress sites are common targets for attacks, and keeping it secure requires constant updates  
- **Less flexibility** – Customizing features like user authentication, LMS, and PPA management is harder compared to a custom-built solution  

## Features (Now & Future)  
- User Registration & Login  
- PPA & Accommodation Management  
- Bootcamp LMS  
- Admin Dashboard (Upcoming)  
- Chat & Notifications (Upcoming)  

## Getting Started  
1. Clone this repo:  
   ```bash
   git clone https://github.com/your-username/cds-website.git
   cd cds-website
   ```  
2. Install dependencies:  
   ```bash
   npm install
   ```  
3. Run the project:  
   ```bash
   npm run dev
   ```  

## Want to Contribute?  
- Fork the repo  
- Create a new branch (`feature-branch-name`)  
- Make your changes and commit (`git commit -m "Added XYZ feature"`)  
- Push and open a pull request  

## Questions?  
If you have any ideas or issues, feel free to reach out or open an issue.
