# Weather Application

A modern weather application built with Next.js and OpenWeatherMap API. This application provides current weather information and a 3-day forecast for any city around the world.

![Weather App Screenshot](/placeholder.svg?height=300&width=600)

## Features

- 🔍 Search for weather by city name
- 🌡️ Toggle between Celsius and Fahrenheit
- 🌤️ Display current weather conditions with icons
- 📅 Show 3-day weather forecast
- 💨 Wind status information
- 💧 Humidity information
- 📱 Responsive design for all devices

## Technologies Used

- **Frontend**: Next.js 14, React, TypeScript, Tailwind CSS
- **API**: OpenWeatherMap API
- **Components**: Shadcn UI components
- **Icons**: Lucide React icons

## Installation

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   \`\`\`

2. Install dependencies:
   \`\`\`bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   \`\`\`

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add your OpenWeatherMap API key:
   \`\`\`
   OPENWEATHER_API_KEY=your_api_key_here
   BACKEND_URL=your_backend_url_here
   \`\`\`

4. Run the development server:
   \`\`\`bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   \`\`\`

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Environment Variables

| Variable | Description |
|----------|-------------|
| `OPENWEATHER_API_KEY` | Your OpenWeatherMap API key |
| `BACKEND_URL` | URL to your backend service (if using a separate backend) |

## Usage

1. Enter a city name in the search box and press Enter or click the search icon.
2. Toggle between Celsius and Fahrenheit using the temperature unit buttons.
3. View current weather information in the left panel.
4. Check the 3-day forecast in the cards below the search bar.
5. View additional weather details like wind speed and humidity at the bottom.

## API Information

This application uses the following OpenWeatherMap API endpoints:

- Geocoding API: To convert city names to coordinates
- Current Weather API: To get current weather data
- 5-day Forecast API: To get forecast data

You can get your API key by signing up at [OpenWeatherMap](https://openweathermap.org/api).

## Project Structure

\`\`\`
weather-app/
├── app/
│   ├── api/
│   │   ├── forecast/
│   │   │   └── route.ts
│   │   └── weather/
│   │       └── route.ts
│   ├── globals.css
│   ├── layout.tsx
│   ├── loading.tsx
│   └── page.tsx
├── components/
│   ├── forecast-card.tsx
│   ├── humidity-card.tsx
│   ├── info-card.tsx
│   ├── search-bar.tsx
│   ├── temperature-toggle.tsx
│   ├── ui/
│   ├── weather-card.tsx
│   ├── weather-icon.tsx
│   └── wind-card.tsx
├── public/
├── .env.local
├── next.config.js
├── package.json
├── README.md
├── tailwind.config.ts
└── tsconfig.json
\`\`\`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API
- [Next.js](https://nextjs.org/) for the React framework
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Shadcn UI](https://ui.shadcn.com/) for UI components
- [Lucide React](https://lucide.dev/) for icons
\`\`\`

This README provides comprehensive documentation for your weather application, including installation instructions, features, usage guidelines, and project structure. You can customize it further by:

1. Adding actual screenshots of your application
2. Updating the GitHub repository URL
3. Adding any specific deployment instructions
4. Including any additional features you might add in the future

Would you like me to make any changes or additions to this README?

<Actions>
  <Action name="Add screenshots to README" description="Add actual screenshots of the application to the README" />
  <Action name="Create a .gitignore file" description="Add a .gitignore file for Next.js projects" />
  <Action name="Add deployment instructions" description="Add instructions for deploying to Vercel or other platforms" />
  <Action name="Create a contributing guide" description="Add a more detailed CONTRIBUTING.md file" />
</Actions>

\`\`\`

