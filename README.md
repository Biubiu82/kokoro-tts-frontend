# Kokoro TTS Frontend

Simple and beautiful frontend interface for Kokoro Text-to-Speech API.

## Features

- Clean and modern Glassmorphism design
- Support for Japanese and English text
- Adjustable speech speed
- Built with TailwindCSS
- Responsive design

## Development

1. Clone the repository
2. Open `index.html` in your browser
3. Make sure the backend API is running at `http://localhost:8880`

## Deployment

This project is configured for deployment on Vercel:

1. Fork/Clone this repository to your GitHub account
2. Create a new project on Vercel
3. Import your GitHub repository
4. Configure the following settings:
   - Framework Preset: Other
   - Build Command: `(none)`
   - Output Directory: `frontend`
   - Install Command: `(none)`

## Environment Variables

When deploying to production, update the API URL in `index.html`:

```javascript
// Change this line in index.html
const API_URL = 'http://localhost:8880/tts';
// to
const API_URL = 'https://your-backend-url.com/tts';
```

## License

MIT 