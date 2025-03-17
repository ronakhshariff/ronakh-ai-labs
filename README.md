# RonakhAILabs 🤖

To run: https://ronakh-ai-labs-backend.onrender.com/

A comprehensive AI platform featuring multiple specialized AI assistants powered by Google's Generative AI (Gemini 1.5 Pro). Built with a modern, responsive UI and secure architecture, RonakhAILabs provides intelligent assistance across various domains.

## Features

- Multiple AI personas (Finance, Movie, Schedule, Cravings, Fitness, Study, Coding, Mental Health, News, Job Search, and Merp AI)
- Modern UI theme with smooth transitions
- Real-time chat interface
- Responsive design
- Dynamic search and filtering
- Secure API key handling

## Prerequisites

- Python 3.8 or higher
- Google Generative AI API key (Gemini 1.5 Pro)

## Security Setup 🔐

1. **API Key Protection**
   - Never commit your API key to version control
   - The `.env` file is included in `.gitignore` by default
   - Use the provided `.env.example` as a template

2. **Setting Up Environment Variables**
   ```bash
   # Copy the example environment file
   cp .env.example .env
   
   # Edit .env and add your Google API key
   # Replace 'your-secret-api-key-here' with your actual API key
   GOOGLE_API_KEY=your-secret-api-key-here
   ```

3. **Verify Security**
   - Check that `.env` is in your `.gitignore`
   - Never share your API key
   - Rotate your API key if accidentally exposed

## Installation

1. Clone this repository
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your environment variables (see Security Setup above)

## Running the Application

```bash
python app.py
```

The application will be available at `http://localhost:5001`

## AI Assistants

### 💰 Finance AI
- Financial advice and guidance
- Investment decisions
- Financial concepts explanation

### 🎬 Movie AI
- Movie and TV show recommendations
- Film information
- Similar content suggestions

### ⏰ Schedule AI
- Time management assistance
- Scheduling help
- Productivity tips

### 🍳 Cravings AI
- Recipe recommendations
- Meal planning
- Cooking tips

### 💪 Fitness AI
- Workout plans
- Exercise guidance
- Health tips

### 📚 Study AI
- Academic assistance
- Learning strategies
- Subject explanations

### 💻 Coding AI
- Programming help
- Code review
- Development guidance

### 🧘 Mental Health AI
- Emotional support
- Wellness tips
- Stress management

### 📰 News AI
- Current events updates
- News summaries
- Topic analysis

### 💼 Job Search AI
- CS job listings in Canada
- Career guidance
- Industry insights

### 🎨 Merp AI
- CSS art generation
- Creative coding
- Visual design

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## Security Note

This application uses environment variables for secure API key management. Never commit your actual API keys to version control. The `.env` file is included in `.gitignore` to prevent accidental commits of sensitive information. 
