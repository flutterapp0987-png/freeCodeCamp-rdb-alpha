# 😂 Random Joke Generator

A simple, responsive web application that fetches random jokes from an external API and displays them with a beautiful UI.

## Features

✨ **Key Features:**
- Fetches random jokes from the Official Joke API
- Clean and modern responsive UI
- Copy joke to clipboard functionality
- Loading state indicator
- Error handling
- Mobile-friendly design

## Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling with gradients and animations
- **JavaScript (ES6+)** - Async/await for API calls
- **External API** - [Official Joke API](https://official-joke-api.appspot.com)

## How to Use

1. Open `index.html` in your web browser
2. Click the **"Get a Joke"** button to fetch a random joke
3. Click the **"Copy Joke"** button to copy the joke to your clipboard
4. Enjoy the jokes! 😄

## Project Structure

```
freeCodeCamp-rdb-alpha/
├── index.html      # Main HTML file
├── style.css       # Styling
├── script.js       # JavaScript logic
└── README.md       # Documentation
```

## API Used

**Official Joke API** - Free API for getting random jokes
- Endpoint: `https://official-joke-api.appspot.com/random_joke`
- Returns: JSON object with setup and delivery fields
- No authentication required

## Example API Response

```json
{
  "type": "general",
  "setup": "Why did the scarecrow win an award?",
  "delivery": "Because he was outstanding in his field!",
  "id": 1
}
```

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

- [ ] Add categories filter (Programming, Knock-knock, etc.)
- [ ] Save favorite jokes
- [ ] Dark mode toggle
- [ ] Share jokes on social media
- [ ] Add animation effects

## License

This project is free to use for educational purposes.