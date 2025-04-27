# Budgeting-Simplified.-Powered-by-AI
This is my git repository which is an intelligent web-based expense management platform that empowers users to monitor, optimize, and plan their monthly, daily, and yearly budgets using AI-based predictions and smart suggestions.
🚀 Features
📊 Track day-wise, month-wise, and year-wise expenses

📉 Visualize spending trends via dynamic charts

🔥 AI-powered future expense prediction

🎯 Smart budget allocation and saving suggestions

⚡ Real-time alerts when budget limits are about to breach

📑 Generate monthly spending reports (PDF Export)

🔐 Secure authentication with JWT

📚 How It Works
1. User signs up and sets an initial monthly budget.
2. User adds daily expenses categorized under various heads.
3. Backend collects data and stores securely in MongoDB.
4. AI Engine processes spending patterns to:
   - Predict future expenses.
   - Suggest optimized budget adjustments.
5. Dashboard visualizes data and provides actionable insights.
6. Users get notified if they exceed budgets or if optimizations are recommended.


⚡ Installation and Setup
# Clone the repo
git clone https://github.com/yourusername/smart-budget-allocation-system.git

# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install

# Set up MongoDB and environment variables (.env file)
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

# Start frontend and backend
npm run dev  # For frontend
npm run server  # For backend


🎯 AI/ML Model Approach
Expense Prediction: Linear Regression model trained on user spending history.

Spending Behavior Clustering: KMeans clustering to group users into spending categories.

Budget Optimization Engine: Simple rule-based and predictive suggestions.



