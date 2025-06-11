# Finance AI

An intelligent personal finance assistant powered by AI that helps you learn about money management, create budgets, and visualize your finances.

## Features

### 📊 Monthly Budget Planner
- Interactive AI chatbot to help create your monthly budget
- Get personalized financial advice and recommendations
- Track your budgeting progress with conversational guidance

### 🎓 Personal Finance Tutor
- Ask any finance-related questions and get detailed explanations

### 🧠 Test Your Knowledge
- Take interactive quizzes on personal finance topics
- Get instant feedback on your answers
- Learn from mistakes with AI-powered explanations

### 📈 Visualize Your Finances
- Input your monthly income and expenses
- Generate beautiful charts (pie charts and bar graphs)
- See your spending breakdown at a glance
- Get warnings if you're overspending

## 🚀 Getting Started

### Prerequisites
- Python 3.7 or higher
- Together AI API key (get one at [together.ai](https://together.ai))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/NajmiHassan/Finanace-Buddy.git
   cd finance-ai
   ```

2. **Install required packages**
   ```bash
   pip install streamlit together pandas matplotlib
   ```

3. **Set up your API key**
   
   **Option 1: Environment Variable (Recommended)**
   ```bash
   export TOGETHER_API_KEY="your-api-key-here"
   ```
   
   **Option 2: Enter in App**
   - Run the app and enter your API key when prompted

4. **Run the application**
   ```bash
   streamlit run app.py
   ```

5. **Open your browser**
   - The app will automatically open at `http://localhost:8501`

## 🎯 How to Use

1. **Choose a feature** from the sidebar:
   - Monthly Budget Planner
   - Personal Finance Tutor
   - Test Your Knowledge
   - Visualize Your Finances

2. **Interact with the AI** through the chat interface for learning and budgeting

3. **Input your financial data** in the visualization tool to see your spending patterns

4. **Take quizzes** to test and improve your financial knowledge

## 🛠️ Built With

- **[Streamlit](https://streamlit.io/)** - Web app framework
- **[Together AI](https://together.ai/)** - AI API service
- **[LLaMA 3](https://llama.meta.com/)** - Meta's language model
- **[Matplotlib](https://matplotlib.org/)** - Data visualization
- **[Pandas](https://pandas.pydata.org/)** - Data manipulation

## 💡 Tips for Best Results

- Be specific when asking questions to the AI tutor
- Enter realistic budget numbers for accurate visualizations
- Take multiple quizzes to reinforce your learning
- Use the budget planner regularly to track your progress

## 🔧 Troubleshooting

**API Key Issues:**
- Make sure your Together AI API key is valid
- Check that the environment variable is set correctly

**Chart Not Displaying:**
- Ensure you've entered valid income and expense amounts
- Make sure expense categories have names and amounts > 0

**App Not Loading:**
- Check that all required packages are installed
- Verify you're using Python 3.7+

---
