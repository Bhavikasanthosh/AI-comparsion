AI Model Comparison Framework
A comprehensive testing framework for comparing the performance of different AI models (ChatGPT, Gemini, and Claude) across various categories:

Text Generation & Correctness
Code Generation & Correctness
Mathematical Problem Solving & Correctness
Hallucination Detection
Features
Side-by-side comparison of AI model responses
Automated evaluation of responses based on multiple criteria
Support for both text and image inputs
Detailed performance analytics and recommendations
SRH-branded UI with modern design
Prerequisites
Node.js (v18 or higher)
API keys for:
OpenAI (GPT-4 Vision)
Google Gemini
Anthropic Claude
Setup
Clone the repository:

git clone <repository-url>
cd ai-model-comparison
Install dependencies:

npm install
Create a .env file:

cp .env.example .env
Add your API keys to the .env file:

OPENAI_API_KEY=your_openai_api_key_here
GEMINI_API_KEY=your_gemini_api_key_here
ANTHROPIC_API_KEY=your_anthropic_api_key_here
Development
Start the development server:

npm run dev
Testing Categories
1. Text Generation & Correctness
Writing quality assessment
Factual accuracy verification
Language understanding
Multilingual capabilities
2. Code Generation & Correctness
Syntax accuracy
Best practices adherence
Error handling
Documentation quality
Performance optimization
3. Mathematical Problem Solving & Correctness
Basic arithmetic
Complex mathematical concepts
Step-by-step problem solving
Formula derivation
Statistical analysis
4. Hallucination Detection
Fact verification
Source citation accuracy
Confidence assessment
Response consistency
Image interpretation accuracy
Evaluation Criteria
Each response is evaluated based on:

Accuracy (0-1): Correctness of the response
Clarity (0-1): How clear and understandable the response is
Completeness (0-1): Coverage of all required aspects
Reliability (0-1): Consistency and trustworthiness
Project Structure
src/
├── components/          # React components
│   ├── TestRunner.tsx  # Main test execution component
│   ├── TestResults.tsx # Results display component
│   └── ...
├── controllers/        # API controllers
│   └── chatController.ts
├── tests/             # Test cases and runner
│   ├── testCases.ts
│   └── testRunner.ts
├── types/             # TypeScript type definitions
│   └── testing.ts
└── config.ts          # Configuration management
Contributing
Fork the repository
Create a feature branch
Commit your changes
Push to the branch
Create a Pull Request
License
This project is licensed under the MIT License - see the LICENSE file for details.
