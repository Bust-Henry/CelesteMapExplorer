# Celeste Map Sharing Mod

## Project Overview
### Goal
To create a Celeste mod that allows players to browse, download, and play custom maps created with Lönn directly from an in-game menu. Additionally, a website will be developed to host these maps, enabling users to upload, like/dislike, and comment on them. A unique string-based map compression system will also be implemented for easier map sharing.

### Core Features
- **In-Game Map Browser (Mod)**
  - Browse available maps from the online database
  - Download and play maps directly in Celeste
  - Display ratings and comments
  - Search and filter maps

- **Website (Map Sharing Platform)**
  - Upload custom maps (.bin format from Lönn)
  - Browse and search for maps
  - Like/dislike and comment on maps
  - Generate and share unique map codes (compressed map string system)

- **Map Compression System**
  - Convert Lönn-generated maps into a compressed string format ("mapseed")
  - Decompress "mapseeds" back into playable Lönn maps

## Project Roadmap
### Phase 1: Research & Setup
-   Familiarize yourself with Celeste modding using Everest
-   Learn about Lönn and how maps are stored (.bin format)
-   Set up a GitHub repository for the project
-   Choose a web framework (e.g., Next.js, Django, Flask) and database (Firebase, PostgreSQL)

### Phase 2: Map Compression System
-   Study the Lönn .bin file structure
-   Develop a way to convert maps into a compressed string format
-   Create a decompression function to restore maps from the string
-   Implement a testing tool for encoding/decoding maps

### Phase 3: Website Development
-   Build user authentication (optional, but useful for commenting/liking)
-   Create an upload system for .bin files
-   Implement a database to store maps and user interactions
-   Develop map browsing, search, and rating features
-   Implement map code generation for easy sharing
-   Deploy the website

### Phase 4: Celeste Mod Development
-   Create a basic Everest mod
-   Develop an in-game menu for browsing maps
-   Implement a system to download maps from the website
-   Display map details (title, creator, likes, comments)
-   Allow direct loading of downloaded maps
-   Add filtering and search features

### Phase 5: Testing & Optimization
-   Test map encoding/decoding with different map sizes
-   Ensure seamless downloading and importing of maps
-   Optimize UI/UX for both the mod and the website
-   Perform stress tests on the website (handling many maps/users)

### Phase 6: Launch & Community Engagement
-   Release the mod and website
-   Share on Celeste modding forums and Discord
-   Gather feedback and fix bugs
-   Plan future updates (e.g., user profiles, leaderboards, challenges)

## Useful Tools & Links
### Modding & Development
- **Everest API** (Celeste modding framework): [Everest API](https://everestapi.github.io/)
- **Lönn (Celeste Map Editor)**: [Lönn GitHub](https://github.com/CelestialCartographers/Loenn)
- **Celeste Modding Discord**: [Join the Celeste Modding Community](https://discord.gg/3DVuEJ7)

### Programming Resources
- **C# (for modding with Everest)**: [C# Documentation](https://learn.microsoft.com/en-us/dotnet/csharp/)
- **Python or Node.js (for web backend)**: [JavaScript MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- **Database choices (Firebase, PostgreSQL)**: [Firebase](https://firebase.google.com/)

### Web Hosting & Deployment
- **Vercel (for Next.js sites)**: [Vercel](https://vercel.com/)
- **Heroku (for backend hosting)**: [Heroku](https://www.heroku.com/)
- **DigitalOcean (for full-stack hosting)**: [DigitalOcean](https://www.digitalocean.com/)

## Notes & Considerations
- Keep the UI of the mod and website simple and intuitive
- Ensure map compression maintains integrity (test edge cases)
- Consider security measures (e.g., preventing malicious map uploads)
- Community feedback is key—engage with Celeste modders early

---
## License

## Contributing

## Contact


This readme is auto generated
