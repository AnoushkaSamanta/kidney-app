# CKD Diet Chart 🥗💙

**A Comprehensive Diet Management Application for Chronic Kidney Disease Patients**

CKD Diet Chart is a specialized web application designed to help patients with Chronic Kidney Disease (CKD) manage their nutrition through personalized diet planning, meal tracking, and nutrient monitoring. Built with medical professionals' guidance, it provides tailored recommendations based on CKD stages and individual health conditions.

## ✨ Key Features

### 🔐 **Secure Authentication & Account Management**
- **Secure Login/Sign-Up/Logout** functionality
- **Profile Management** for updating personal information (age, weight, contact details)
- **Privacy-focused** design for sensitive medical data

### 📋 **Comprehensive Onboarding Questionnaire**
Collect essential patient data to personalize the experience:
- **Referral Source**: Track how users discovered the application
- **CKD Stage Classification**: Support for CKD stages 1-5 and undiagnosed patients
- **Dialysis Status**: Yes/No tracking for dialysis patients
- **Comorbidity Assessment**: Diabetes and hypertension screening
- **Personalized Recommendations** based on collected data

### 🎯 **Intelligent Nutrient Target Setting**
Three flexible approaches for daily nutrition goals:

**1. Custom Values**
- User-defined macro and micronutrient targets
- Complete control over daily intake goals

**2. Age-Based Defaults**
- System presets based on age and gender demographics
- Evidence-based nutritional recommendations

**3. CKD-Stage Specific Defaults**
- Medically-tuned presets for each CKD stage (1-5)
- Kidney-specific nutrient restrictions and recommendations

**Tracked Nutrients:**
- **Macronutrients**: Calories, Protein, Carbohydrates, Fats, Water
- **Critical Micronutrients**: Potassium, Phosphorus, Sodium, and more

### 📊 **Advanced Diet Chart & Meal Tracking**

**Daily Intake Dashboard**
- **Visual Progress Tracking**: Interactive progress bars and charts
- **Target vs. Consumed**: Real-time comparison of goals and intake
- **Comprehensive Metrics**: Grams, milliliters, and calorie tracking

**Smart Food Management**
- **Intelligent Search**: Keyword search with autocomplete functionality
- **Detailed Nutrient Breakdown**: Complete nutritional information per serving
- **Portion Guidance**: Serving size options and portion suggestions
- **Recent Items**: Quick access to recently searched foods
- **Favorite Foods**: Bookmark system for frequently consumed items
- **Custom Recipes**: Create and save personalized meals with automatic nutrient calculation
- **Water Intake Tracker**: Dedicated fluid intake monitoring

### 💾 **Export & Sharing Capabilities**
- **Diet Plan Snapshots**: Save daily charts and meal plans
- **Export Options**: PDF generation for sharing with healthcare providers
- **Meal Plan Templates**: Save and reuse favorite daily menus
- **Progress Reports**: Track nutrition trends over time

## 🚀 Tech Stack

- **Frontend**: React.js with TypeScript for type-safe development
- **Styling**: Tailwind CSS for responsive and modern UI design
- **Authentication**: JWT 
- **Database**: MongoDB
- **API**: RESTful API design
- **Charts & Visualization**: Recharts for nutrition tracking
- **Export**: jsPDF for PDF generation

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ckd-diet-chart.git
   cd ckd-diet-chart
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Environment Configuration**
   Create a `.env.local` file:
   ```env
   REACT_APP_API_URL=your_api_endpoint
   REACT_APP_AUTH_SECRET=your_auth_secret
   REACT_APP_SMS_SERVICE_KEY=your_sms_service_key
   REACT_APP_DATABASE_URL=your_database_url
   ```

4. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```

5. **Access the application**
   Open [http://localhost:3000](http://localhost:3000) in your browser

## 📱 Usage Guide

### Getting Started
1. **Create Account**: Sign up with email and verify via 2FA
2. **Complete Onboarding**: Fill out the medical questionnaire
3. **Set Nutrition Goals**: Choose your preferred target-setting method
4. **Start Tracking**: Log meals and monitor progress

### Daily Workflow
1. **Check Daily Totals**: Review daily targets and progress
2. **Log Meals**: Search and add foods to your daily intake
3. **Monitor Water**: Track fluid intake throughout the day
4. **Review Progress**: Analyze charts and adjust as needed

### Advanced Features
- **Create Custom Recipes**: Build personalized meal combinations
- **Export Reports**: Generate PDFs for healthcare provider visits
- **Save Templates**: Create reusable meal plans for easy logging

## 🏥 Medical Disclaimer

This application is designed to assist with diet management but is not a substitute for professional medical advice. Always consult with healthcare providers and registered dietitians before making significant dietary changes, especially when managing CKD.

## 🤝 Contributing

We welcome contributions from developers, healthcare professionals, and the CKD community!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/HealthyFeature`)
3. Commit your changes (`git commit -m 'Add kidney-friendly feature'`)
4. Push to the branch (`git push origin feature/HealthyFeature`)
5. Open a Pull Request

### Development Guidelines
- Follow TypeScript best practices
- Maintain responsive design principles
- Ensure accessibility compliance (WCAG 2.1)
- Include unit tests for new features
- Document medical/nutritional assumptions

---

![image](https://github.com/user-attachments/assets/2fa44a15-d558-47e9-9ba5-9054b24e2a6a)

![image](https://github.com/user-attachments/assets/e36a6dc0-46cc-4425-92e6-bfb2d9a0fb86)

![image](https://github.com/user-attachments/assets/b666c694-f426-402c-937e-a8696bfbadde)

![image](https://github.com/user-attachments/assets/209a7504-fd82-400e-b068-801f252e6536)

![image](https://github.com/user-attachments/assets/9752545b-6848-4342-b2e6-786a39996993)

![image](https://github.com/user-attachments/assets/7601ea8b-f028-4480-9202-9552fa99db6e)






**Empowering CKD patients with personalized nutrition management** 💚

*Built with care for the kidney health community*
