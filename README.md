
# 🔍 TrueCheck AI — Product Authenticity Checker

### Helping users make safer and smarter online shopping decisions.

TrueCheck AI is a full-stack web application designed to help users assess the authenticity of online products and identify potentially counterfeit or suspicious listings.

The platform aims to analyze available product information, barcode data, seller details, and product images to provide users with an evidence-based verification report.

> 🚧 **Project Status:** Under Development

## ✨ Key Features

- 🔎 **Product Verification:** Submit product information to initiate an authenticity check.
- 📦 **Barcode & QR Scanning:** Scan supported product codes to retrieve identifying information.
- 🖼️ **Image Analysis:** Explore visual differences between submitted product images and trusted reference images.
- 🛍️ **Seller Verification:** Compare seller information with available authorized seller records.
- 🤖 **AI-Powered Analysis:** Planned integration for analyzing product details and potential authenticity indicators.
- 📊 **Verification Reports:** Display findings, risk indicators, and reasons behind the result.
- 🕘 **Verification History:** Keep track of previously checked products.
- 🔐 **Secure Authentication:** Planned user authentication and protected routes.

## 🎯 Project Objective

Online shopping makes products accessible to everyone, but counterfeit products and misleading listings can make purchasing decisions difficult.

TrueCheck AI aims to simplify product verification by bringing available product information and authenticity indicators together in one place.

The goal is to help users make more informed purchasing decisions through accessible technology and transparent verification results.

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript
- Tailwind CSS
- HTML5 & CSS3

### Backend
- Node.js
- Express.js
- REST APIs

### Database
- MongoDB
- Mongoose

### AI & Verification
- Barcode and QR code scanning
- Image comparison and computer vision
- Product and seller data validation
- AI-based analysis (planned)

### Tools & Deployment
- Git & GitHub
- Vercel
- Render
- MongoDB Atlas

*Technologies and integrations will be finalized as development progresses.*

## ⚙️ How It Works

1. **Submit a Product:** Enter a product link, barcode, or supported product details.
2. **Analyze Available Data:** The system checks the submitted information against available reference records.
3. **Evaluate Authenticity Indicators:** Product details, seller information, and supported image comparisons are evaluated.
4. **View the Report:** Review the findings and understand which checks passed, failed, or could not be completed.

## 📋 Verification Status

TrueCheck AI aims to provide clear, evidence-based results:

- ✅ **Verified:** Authenticity confirmed by a reliable supported verification source.
- ⚠️ **Suspicious:** One or more indicators require further investigation.
- ❓ **Unable to Verify:** Available evidence is insufficient to determine authenticity.

A matching barcode or product image alone does not prove that a product is genuine. Verification depends on the reliability of the available data and supported sources.

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

- Node.js
- npm
- Git
- MongoDB or a MongoDB Atlas connection

### 1. Clone the Repository

```bash
git clone https://github.com/shivanisamadhiya/truecheck-ai.git
```

### 2. Navigate to the Project

```bash
cd truecheck-ai
```

### 3. Install Dependencies

Install frontend and backend dependencies after their respective project folders and `package.json` files have been created.

```bash
cd client
npm install
```

```bash
cd ../server
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside the `server` directory.

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secure_secret
```

Replace the example values with your actual configuration. Never commit credentials or secret keys to GitHub.

### 5. Run the Application

Start the backend:

```bash
cd server
npm run dev
```

Start the frontend in a separate terminal:

```bash
cd client
npm run dev
```

*Note: These commands will work after the corresponding scripts and application files have been configured.*

## 🗺️ Development Roadmap

- [ ] Project planning and requirements
- [ ] Responsive React frontend
- [ ] Product submission and image upload
- [ ] Express.js REST API
- [ ] MongoDB database integration
- [ ] Barcode and QR code scanning
- [ ] Product and seller data validation
- [ ] Evidence-based verification reports
- [ ] Image comparison functionality
- [ ] AI analysis integration
- [ ] Authentication and verification history
- [ ] Testing and deployment

## 🔮 Future Enhancements

- Browser extension for supported shopping websites
- Manufacturer verification API integrations
- Unique product authentication codes
- Improved image-based counterfeit detection
- Community-based suspicious listing reports
- Mobile-friendly product scanning experience

## ⚠️ Limitations & Disclaimer

TrueCheck AI is an informational tool intended to assist users in assessing product authenticity.

The accuracy of its results depends on the availability and reliability of verification data. Not every product or seller can be independently verified, and counterfeit products may use copied barcodes or packaging.

The platform does not guarantee that a product is genuine unless confirmation is available from a reliable authorized source.

## 👩‍💻 Author

**Shivani Samadhiya**

- GitHub: [@shivanisamadhiya](https://github.com/shivanisamadhiya)
- LinkedIn: [Shivani Samadhiya](https://www.linkedin.com/in/shivani-samadhiya-3ab768287/)

## 🤝 Contributions

Suggestions, feedback, and contributions are welcome as the project develops.

## 📄 License

This project is intended for educational and portfolio purposes during its initial development. A formal open-source license can be added when the licensing terms are decided.
