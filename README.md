# Nystra - Online Manga Reader

<div align="center">
  <img src="https://raw.githubusercontent.com/kx4x/nystra/main/justine/public/readme/logo.png" alt="Nystra Logo" width="200">
</div>

[![Vercel](https://img.shields.io/badge/deployed%20on-Vercel-black.svg)](https://vercel.com)

Nystra is an online manga reading platform that allows users to explore, read, and track their favorite mangas easily and intuitively. Using the MangaDex API, Nystra offers a smooth reading experience with modern features and a minimalist design.

## Current Features

- **Manga Exploration**: Discover popular, recent, and newly added mangas.
- **Online Reading**: Read manga chapters with an immersive and customizable reading interface.
- **Reading Modes**: Choose between single-page or continuous reading.
- **View Controls**: Adjust zoom and brightness for a comfortable reading experience.
- **Intuitive Navigation**: Easily navigate between pages and chapters.
- **API Proxy**: Configured proxy for the MangaDex API, ensuring functionality in environments like Vercel.

**Note**: This project is in its early stages and may contain some bugs. We are actively working to resolve all issues as soon as possible.

## Screenshots

![Home](https://raw.githubusercontent.com/kx4x/Nystra/refs/heads/main/public/Home.png)

![Header Preview](https://raw.githubusercontent.com/kx4x/Nystra/refs/heads/main/public/HeaderPreview.png)

![Settings](https://raw.githubusercontent.com/kx4x/Nystra/refs/heads/main/public/settings.png)

![Info](https://raw.githubusercontent.com/kx4x/Nystra/refs/heads/main/public/info.png)

## Installation and Usage

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/kx4x/nystra.git
   cd nystra
   ```

2. **Install Dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set Up Environment**
   - Create a `.env.local` file in the project root and add any necessary environment variables.
   - The project is configured to use the MangaDex API directly in development and via proxy in production.

4. **Start the Development Server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Access the Application**
   Open your browser and navigate to `http://localhost:3000`.

### Deploy on Vercel

Nystra is configured to work on Vercel with a custom API proxy to bypass MangaDex restrictions. Simply connect your repository to Vercel and deploy.

## Future Plans

We are continuously working to improve Nystra and add new features. Here are some plans for the future:

- **Account System**: Allow users to create accounts to personalize their experience.
- **Favorites**: Add the ability to mark mangas as favorites for quick access.
- **Continue Reading**: Implement a reading history feature so users can resume where they left off.
- **Anime Support**: Expand the platform to include anime streaming, integrating APIs like AniList or MyAnimeList.
- **Notifications**: Send notifications about new chapters of favorited mangas.
- **Offline Mode**: Enable chapter downloads for offline reading.
- **Custom Themes**: Add options for light and dark themes, along with other UI customizations.
- **Community/Forum Tab**: Create a dedicated tab for community interaction, featuring forums or discussion sections where users can talk about mangas, chapters, and share recommendations.

## Contribution

Contributions are welcome! If you wish to help improve Nystra, follow these steps:

1. Fork the repository.
2. Create a branch for your feature or bug fix (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the remote repository (`git push origin feature/new-feature`).
5. Open a Pull Request.

Please adhere to our [Code of Conduct](CODE_OF_CONDUCT.md) when contributing.


## Acknowledgments

- [MangaDex](https://mangadex.org) for the API that makes this project possible.
- [Next.js](https://nextjs.org) and [Vercel](https://vercel.com) for the framework and hosting.
- [shadcn/ui](https://ui.shadcn.com) for the UI components.

## Contact

If you have questions or suggestions, feel free to open an issue or contact me via [Twitter](https://twitter.com/kx4xxx).

---

Made with ❤️ by [kx4x](https://github.com/kx4x)
