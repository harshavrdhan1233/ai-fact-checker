# AI Fact Checker Chatbot

A responsive web-based AI fact checker chatbot that provides verified information through a local knowledge base of universal truths and facts.

## Features

- Clean, modern UI with responsive design
- Real-time chat interface
- No API key required - works offline
- Built-in knowledge base of universal truths and facts
- Source attribution and citation
- Confidence indicators (Verified, Uncertain, False)
- Typing indicators for better user experience
- Mobile-responsive design

## Included Knowledge Areas

The chatbot has built-in knowledge about:
- Scientific facts (gravity, evolution, etc.)
- Historical facts (moon landing, World War II, etc.)
- Mathematical truths (basic arithmetic, pi, etc.)
- Geography (capitals, continents, etc.)
- Health and science (vaccines, climate change, etc.)

## Setup Instructions

No special setup required! Simply:

1. Download all files
2. Open `index.html` in any modern web browser
3. Start asking questions

## Usage

1. Type a question or statement in the input field
2. Press Enter or click the send button
3. The AI will check its knowledge base and provide a fact-checked response

### Example Questions

Try these example queries to test the fact checker:

- "Is the Earth flat?"
- "Tell me about the moon landing"
- "Did dinosaurs and humans live at the same time?"
- "What is the capital of France?"
- "What happens when water boils?"
- "Is climate change real?"
- "Do vaccines cause autism?"

## Customization

You can customize this chatbot by:

- Editing the `knowledgeBase` object in `script.js` to add more facts
- Modifying the UI by changing the CSS in `styles.css`
- Adding new response patterns in the `processUserMessage` function

## Extending the Knowledge Base

To add new facts to the knowledge base, edit the `knowledgeBase` object in `script.js`:

```javascript
"your-keyword": {
    fact: "Your detailed factual information here.",
    status: "verified", // can be "verified", "false", or "uncertain"
    sources: [{title: "Source Name", url: "https://source-url.com"}]
}
```

## License

This project is licensed under the MIT License - see the LICENSE file for details. 