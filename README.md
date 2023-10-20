# Jamming
This project allows authenticated users 👥 to create and customize 🎨 playlists 🎼 and send them to their Spotify account using API technologies.
The app helps users search 🔎 their favorites songs 🎧 and group them into a new playlist, always having the chance to modify it the way they want 😎. <br />
Take a look to the **design solution** in Figma [here](https://www.figma.com/file/ce0bwas2kwugzVs2vS6Hri/Jamming?type=design&node-id=0%3A1&mode=design&t=9YGx22OR99GbAqbZ-1).

You can find our original project, in wich we use `JavaScript`, [here](https://github.com/Matdweb/Jamming)

## Getting Started

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font

## Features
Learn about this app's functionalities and how they work: 

1. Font styling [`Create Global Styles`](https://github.com/Matdweb/Jamming/pull/11)
2. For [`User authentication functionality`](https://github.com/Matdweb/Jamming/pull/14) we used `NextAuth`, learn more [here](https://next-auth.js.org/getting-started/example)
3. State of the app using [createContext()](https://react.dev/reference/react/createContext), [`State Context`](https://github.com/Matdweb/Jamming/pull/21)
4. Add and remove songs from playlist [`Add and Remove functionality`](https://github.com/Matdweb/Jamming/pull/28)

### API requests
Learn how the Backend works for this app: 

1. Requirement for making API request to Spotify API - [`Request access token`](https://github.com/Matdweb/Jamming/pull/22)
2. How to create a new playlist in the user's account - [`Create a new playlist`](https://github.com/Matdweb/Jamming/pull/22)
3. How to search for songs with Spotify API - [`Search for song functionality`](https://github.com/Matdweb/Jamming/pull/35)

### Development Insights
If you'd to like learn more about how we crafted the layout and various interface elements, see here: 
- [Main page](https://github.com/Matdweb/Jamming/pull/18)
- [Background color changer](https://github.com/Matdweb/Jamming/pull/25)
- [Button animations](https://github.com/Matdweb/Jamming/pull/29)
- [Error page](https://github.com/Matdweb/Jamming/pull/34)

Learn also about the way we create commits here [`convencional-commits`](https://www.conventionalcommits.org/es/v1.0.0-beta.2/)

### Experimental code
Before the development process began, three GitHub repositories were set up to contain experimental code for testing the functionalities of this app. Exploring these repositories can be highly beneficial if you wish to gain a deeper understanding of the API requests, Next.js best practices, Next.js endpoints, and other elements used in this application: 
- [Spotify Playlist Retriever v12](https://github.com/Matdweb/Spotiy-Playlist-Retriever-v12)
- [Spotify Playlist Retriever](https://github.com/Matdweb/Spotiy-Playlist-Retriever)
- [Album Searcher](https://github.com/Matdweb/AlbumSearcher-experimental)

## How to Contribute to Jamming

Thank you for showing interest in contributing to our Jamming project! Your help is greatly appreciated. To get started, please follow these steps:

1. **Find a Task:** Browse our project's issues and identify a task you'd like to work on. This helps maintain a clear and organized development process.

2. **Express Your Interest:** Leave a comment on the chosen task with your name and a clear statement indicating your intent to contribute. This helps us track who's working on what.

3. **Task Assignment:** The first contributor to express interest in a task will be assigned to it, provided they confirm their readiness within 24 hours. This ensures efficient task allocation.

4. **Single Contributor per Task:** To ensure focused development, only one contributor may work on a task at a time. However, we welcome feedback and suggestions from everyone.

5. **Time Commitment:** Once a task is assigned to you, coordinate a suitable development timeline with the project's owner or lead developer. Please honor this commitment, as other contributors and project timelines depend on it.

6. **Code Review:** Prior to merging any code, the project owner or lead developer will review your changes to ensure alignment with project standards and objectives.

In cases where you need guidance, don't hesitate to ask for help or refer to relevant resources.

By following these steps and communicating clearly, you can make valuable contributions to our project while keeping the development process organized and collaborative. Happy coding! 👨🏻‍💻

## Showcase Your Contributions to Jamming

We encourage contributors to feature their Jamming project contributions in their portfolios and resumes. This helps you demonstrate your skills and experience to potential employers or collaborators. Here's how:

1. **List Your Contributions:** In your portfolio, create a section for your Jamming project contributions. Provide a brief description of each contribution and its impact.

2. **Link to the Repository:** Include a direct link to the Jamming repository, allowing others to explore your code and the overall project.

3. **Highlight Achievements:** Spotlight specific challenges you tackled, improvements you made, or unique solutions you implemented.

4. **Share Your Experience:** Discuss the valuable experience you gained while working on the project, including collaboration with the development team, adherence to coding standards, and real-world problem-solving.

5. **Connect with Us:** Let us know when you've added your Jamming contributions to your portfolio. We'd love to celebrate your success and promote your work within our community.

Your contributions are a testament to your skills and dedication. We're thrilled to have you as part of our project. Share your portfolio with us, and let's continue to grow and learn together! 🚀


## How to use this app
See the step by step to how to create a playlist with this app:
1. Sign In with your Spotify account <br />
![image](https://github.com/Matdweb/Jamming/assets/110640534/116ed9b7-fc7b-4c7a-902b-a30485723ad6)
2. Search for any song with the `song-name` <br />
![image](https://github.com/Matdweb/Jamming/assets/110640534/a063d64a-552c-4fcc-9e52-7122ccc529b2)
3. Add songs to your new playlists and set it's name <br />
![image](https://github.com/Matdweb/Jamming/assets/110640534/a7045ad2-cd5e-4185-9602-aa4afcba401c)
4. Save the playlist in your Spotify  <br />
![image](https://github.com/Matdweb/Jamming/assets/110640534/b6cb116f-1a6a-42a3-b362-f8fcb3dfcca8)

See a video of how it works [here](https://github.com/Matdweb/Jamming/assets/110640534/7c95b811-2316-4855-95e2-7e95773eb586)

## Tecnologies
- `TypeScript`
- `Next.js 13`
- `NextAuth` - for user authentication
- `createContext()` and `useContext()` - for app's state
- `Spotify API` - for Spotify requests

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.
- [Spotify API documentation]([https://nextjs.org/learn](https://developer.spotify.com/documentation/web-api)) - learn about the API we used
- [useContext() for state](https://react.dev/reference/react/useContext) - learn how we created this app's state

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
