# Customer Support Agents

A Python-based autonomous agent system designed to automate customer support interactions for engineering and energy companies. Built with CrewAI, this project demonstrates how AI agents can answer customer inquiries, provide company information, and showcase portfolio projects in a conversational manner.

## 🚀 Features

- **Agentic Customer Support**: Specialized agents handle customer inquiries, generate responses, and provide detailed company/project information.
- **Conversational AI**: Simulates realistic customer conversations, including greetings, company introductions, and portfolio presentations.
- **Customizable Inputs**: Easily modify the customer, person, and inquiry for different scenarios.
- **Modular Design**: Add or update agents in `utils.py` for new support tasks or industries.
- **Environment Configurable**: API keys and settings via `.env` file.

## 🧩 Main Agents

- **Support Agent**: Responds to customer inquiries and provides relevant information.
- **Portfolio Agent**: Shares details about completed and ongoing projects.
- **Company Info Agent**: Presents company background and expertise.

## 🏗️ How It Works

1. **Setup**: Add your OpenAI API key and other settings to the `.env` file.
2. **Run the App**: Execute `main.py` to start the agent workflow.
3. **Agent Collaboration**: Agents process the inquiry and generate a comprehensive response.
4. **Output**: The system prints the AI-generated reply to the customer's question.

## 📦 Installation

```bash
git clone <repo-url>
cd customer-support-agents
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## ⚙️ Usage

1. Set up your `.env` file with required API keys.
2. Run the main script:
   ```bash
   python main.py
   ```
3. Modify the `inputs` dictionary in `main.py` to simulate different customer scenarios.

## 📝 Example

```
$ python main.py
[SupportAgent] Received inquiry from Peter at Company X...
[PortfolioAgent] Presenting recent solar power plant projects...
[CompanyInfoAgent] Sharing company background...
AI-generated response:
Hello Peter, thank you for your interest in our company. We have developed several solar power plants in the USA, including...
```

## 🛠️ Customization

- Add new agent logic in `utils.py` or separate files.
- Integrate with external APIs for real-time project data.
- Adapt for other industries or customer support scenarios.

## 📚 Dependencies

- Python 3.8+
- CrewAI (or your agent framework)
- Requests, dotenv, and other packages in `requirements.txt`

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss your ideas.
