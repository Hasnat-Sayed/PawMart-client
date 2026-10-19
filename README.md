# 🐾 PawMart - Pet Adoption & Supplies Marketplace

**Live Site URL:** [Click Here](https://pawmart-2099.netlify.app/)

## 📋 About PawMart

PawMart is a comprehensive pet adoption and supplies marketplace platform that connects pet lovers with adorable pets looking for homes and provides a one-stop shop for all pet-related products. Whether you're looking to adopt a furry friend or shop for premium pet supplies, PawMart makes it easy and enjoyable.

## ✨ Key Features

- **🐶 Pet Adoption Platform** - Browse and adopt pets from verified listings with detailed information including health records, temperament, and adoption requirements. Free adoption for all pets with a transparent process.

- **🛒 Complete Pet Supplies Marketplace** - Shop from four comprehensive categories: Pet Food, Accessories, and Pet Care Products. Each listing includes detailed descriptions, pricing, and pickup information.

- **👤 User Dashboard & Management** - Personalized user experience with dedicated pages to manage your listings, track your orders, and update or delete your posted items with real-time updates.

- **🌓 Dark/Light Theme Toggle** - Seamless theme switching with persistent preferences that adapt the entire interface for comfortable viewing in any lighting condition.

- **📱 Fully Responsive Design** - Optimized user experience across all devices - desktop, tablet, and mobile - with smooth animations, hover effects, and intuitive navigation using DaisyUI components.

## 🛠️ Technologies Used

### Frontend
- **React.js** - Component-based UI development
- **React Router** - Client-side routing and navigation
- **Tailwind CSS** - Utility-first styling
- **DaisyUI** - Pre-built component library
- **Firebase Authentication** - Secure user authentication
- **React Icons** - Comprehensive icon library
- **React Toastify** - Beautiful notifications
- **Axios** - HTTP client for API requests

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Firebase** - Authentication and hosting

## Dependencies
 
**Client**
 
| Package | Used for |
|---|---|
| react, react-router | UI and routing |
| firebase | Authentication |
| tailwindcss, daisyui | Styling |
| axios | API requests |
| react-icons | Icons |
| react-toastify | Toast notifications |
 
**Server**
 
| Package | Used for |
|---|---|
| express | Web server and REST API |
| mongodb | Database driver |
| cors | Cross-origin requests |
| dotenv | Environment variables |
 
## Run Locally
 
**Prerequisites:** Node.js, a MongoDB Atlas cluster, and a Firebase project with authentication enabled.
 
### 1. Server
 
```bash
git clone https://github.com/Hasnat-Sayed/PawMart-server.git
cd PawMart-server
npm install
```
 
Create a `.env` file in the project root:
 
```env
DB_USERNAME=your_mongodb_username
DB_PASSWORD=your_mongodb_password
```
 
Replace the cluster address in the MongoDB connection string with your own, then start the server (runs on port 3000):
 
```bash
node index.js
```
 
### 2. Client
 
```bash
git clone https://github.com/Hasnat-Sayed/PawMart-client.git
cd PawMart-client
npm install
```
 
Create a `.env.local` file with your Firebase config (use the variable names from the project's Firebase config file), and make sure the client's API requests point to your local server at `http://localhost:3000`.
 
```bash
npm run dev
```
 
## Links
 
- **Live site:** [pawmart-2099.netlify.app](https://pawmart-2099.netlify.app/)
- **Client repository:** `https://github.com/Hasnat-Sayed/PawMart-client`
- **Server repository:** `https://github.com/Hasnat-Sayed/PawMart-server`
- **Author:** Hasnat Bin Sayed — [GitHub](https://github.com/Hasnat-Sayed) · [LinkedIn](https://linkedin.com/in/hasnat-bin-sayed)


---

Made with ❤️ for pet lovers everywhere