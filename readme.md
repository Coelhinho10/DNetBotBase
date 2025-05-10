# Discord.Net Bot Base

A solid, modern, and extensible foundation for bots built with [Discord.Net](https://github.com/discord-net/Discord.Net). Designed for developers who value performance, organization, and maintainability from the very first commit.

## 🚀 Getting Started

### Prerequisites

- .NET 7 SDK or higher  
- A bot created on the [Discord Developer Portal](https://discord.com/developers/applications)

### Cloning the Project

To clone the repository, run the following commands in your terminal:

```bash
git clone https://github.com/Coelhinho10/DNetBotBase.git
cd DNetBotBase
```

### Configuration

1. Copy the `.env.example` file to `.env`.  
2. Paste your bot token into the `.env` file:

```env
token=your-bot-token-here
```

> **Important**: Never share your bot token publicly! Keep it safe.

### Running the Bot

To run the bot, use the following command:

```bash
dotnet run
```

## 🧱 Project Structure

```
/DNetBotBase  
├── commands/         # Command modules (slash commands)  
├── services/         # Utility services and dependency injection  
├── main.cs           # Entry point and host builder configuration  
└── .env              # Bot settings
```

## 🧪 Development

- Add new commands in the `commands/` folder.

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue, submit a pull request, or share your suggestions.

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Made with 💻 by Ybson Coelho
