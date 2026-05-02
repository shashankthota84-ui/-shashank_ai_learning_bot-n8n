# -shashank_ai_learning_bot-n8n
# AI Fun Learning Bot using n8n

An AI-powered Telegram bot built using n8n, Google Gemini, and Telegram Bot API.

The bot helps students learn coding through quiz battles, coding doubt solving, memes, and friendly roast mode.

## Features

- AI Quiz Battle Mode
- Python, JavaScript, React, HTML, CSS, and SQL quizzes
- Checks answers and gives score
- Coding error explanation
- Friendly coding memes
- Safe roast mode
- Telegram bot integration
- n8n workflow automation
- Gemini AI model integration
- Simple memory for quiz conversations

## Tech Stack

- n8n
- Telegram Bot API
- Google Gemini
- AI Agent Node
- Simple Memory
- Workflow Automation

## Workflow

Telegram Trigger → AI Agent → Google Gemini Chat Model → Simple Memory → Telegram Send Message

## Bot Commands

/start  
hello  
quiz python  
quiz javascript  
quiz react  
quiz html  
quiz css  
quiz sql  
meme coding  
roast me  
end  

## How It Works

1. User sends a message to the Telegram bot.
2. Telegram Trigger receives the message in n8n.
3. AI Agent understands the user request.
4. Gemini generates the response.
5. Simple Memory stores recent chat context for quiz checking.
6. Telegram node sends the reply back to the user.

## Future Improvements

- Google Sheets score tracking
- Leaderboard
- React dashboard
- Daily quiz automation
- PDF certificate generation

## Resume Points

- Built an AI-powered Telegram bot using n8n, Gemini, and Telegram API.
- Designed an automated workflow using Telegram Trigger, AI Agent, Simple Memory, and Telegram Send Message nodes.
- Implemented Quiz Battle Mode with answer checking, scoring, and student-friendly explanations.
- Added entertainment features such as coding memes and friendly roast mode.
