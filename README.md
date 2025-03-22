# AI Chat Assistant

A modern, responsive AI chat application built with React, TypeScript, and OpenAI's GPT-3.5 Turbo. The application provides a clean, intuitive interface for users to interact with an AI assistant.

![AI Chat Assistant](https://images.unsplash.com/photo-1700403298209-00c6e77b365c?q=80&w=1200&auto=format&fit=crop)

## Features

- 🤖 Real-time AI responses using OpenAI's GPT-3.5 Turbo
- 💨 Built with Vite for lightning-fast development
- 🎨 Sleek UI with Tailwind CSS
- 📱 Fully responsive design
- ⚡ Real-time chat interface
- 🔄 Loading states and error handling
- 💅 Modern and clean design with Lucide icons

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- OpenAI API
- Vite
- Lucide React (for icons)

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- OpenAI API key

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd ai-chat-assistant
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your OpenAI API key:
```env
VITE_OPENAI_API_KEY=your_api_key_here
```

4. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Building for Production

To create a production build:

```bash
npm run build
```

The built files will be in the `dist` directory.

## Project Structure

```
├── src/
│   ├── App.tsx           # Main application component
│   ├── main.tsx         # Application entry point
│   └── index.css        # Global styles and Tailwind imports
├── public/              # Static assets
├── .env                # Environment variables
├── index.html          # HTML template
├── package.json        # Project dependencies and scripts
├── tsconfig.json       # TypeScript configuration
├── vite.config.ts      # Vite configuration
└── README.md           # Project documentation
```

## Features Breakdown

### Chat Interface
- Real-time message display
- User and AI message differentiation
- Loading states during AI responses
- Error handling and user feedback
- Message history preservation
- Clean and intuitive UI

### Styling
- Responsive design that works on all device sizes
- Modern and professional UI using Tailwind CSS
- Smooth animations and transitions
- Clear visual hierarchy
- Accessible color scheme

### Technical Features
- TypeScript for type safety
- Environment variable configuration
- OpenAI API integration
- Error boundary implementation
- Responsive layout system
- ESLint configuration for code quality

## Environment Variables

The following environment variables are required:

- `VITE_OPENAI_API_KEY`: Your OpenAI API key

## Deployment

The application is deployed on Netlify and can be accessed at: [https://gleaming-maamoul-1ce17f.netlify.app](https://gleaming-maamoul-1ce17f.netlify.app)

## Development

### Available Scripts

- `npm run dev`: Start development server
- `npm run build`: Create production build
- `npm run preview`: Preview production build locally
- `npm run lint`: Run ESLint

### Code Style

The project uses ESLint for code linting with the following key configurations:
- React Hooks rules
- TypeScript recommended rules
- React Refresh rules

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [OpenAI](https://openai.com/) for providing the GPT-3.5 API
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Lucide](https://lucide.dev/) for the beautiful icons
- [Vite](https://vitejs.dev/) for the fast development experience