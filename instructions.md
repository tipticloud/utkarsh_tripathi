# PixelRift Gaming Website Instructions

## Project Details

Task Title: PixelRift Gaming Website
Website Type: Online Gaming Website
Website Name: PixelRift
Build a complete online gaming website named **PixelRift**.
Users must browse games, view details, play one browser game, join tournaments, view leaderboards, manage a profile, and contact support.
The website must be responsive, modern, easy to use, and able to run locally without external service dependency.
The final result should feel like a real gaming platform, not only a design page.

## Main Goal

Create a gaming website where users can explore games and understand each game.
Users must be able to play a working browser game.
Users must be able to join sample tournaments.
Users must be able to compare rankings.
Users must be able to update profile details.
Users must be able to send a contact message.
The website should be simple for beginners and polished enough to look like a real product.

## Design Style

Use a modern gaming look.
Include dark background, neon blue and purple accents, white and light gray text, and bold headings.
Use gaming style cards, clear buttons, smooth hover effects, clean spacing, and mobile friendly layout.
Every page should look connected to the same PixelRift brand.
The website must not look empty, copied, old, plain, broken, or unfinished.

## Technology

Use any suitable frontend stack.
Allowed options: HTML, CSS, JavaScript, React, Next.js, Vue, Svelte, Tailwind CSS, or normal CSS.
The project must run locally.
A real backend is not required unless it is simple and easy to run.
Use local storage, sample data, JSON files, or frontend state where needed.

## Required Website Areas

Build these 9 main areas:

1. Home Page
2. Login and Register System
3. Games Listing Page
4. Game Details Page
5. Game Play Page
6. Tournament Page
7. Leaderboard Page
8. User Profile and Contact Page
9. Admin Dashboard
   Each area must work properly and connect with the rest of the website.

## 1. Home Page

Create a home page that clearly introduces PixelRift as a gaming website.
Required content:

* Logo or text logo
* Navigation menu
* Hero section
* Main headline
* Short intro
* Call to action buttons
* Featured games
* Upcoming tournament section
* Top players preview
* Why join section
* Footer
  The main buttons should guide users to Games, Tournaments, or Leaderboard.
  The home page should make the platform feel active and complete.

## 2. Login and Register System

Create login and register pages.
Register must include name, email, username, password, confirm password, and register button.
Login must include email or username, password, login button, and link to register page.
Required behavior:

* Error for empty fields
* Error if passwords do not match
* Error for wrong login details
* Success message after registration
* Success message after login
* Login or logout state should update the navigation
  Real email verification is not required.

## 3. Games Listing Page

Create a games page with at least **12 sample games**.
Each game card must show game image, game name, category, short description, rating, Play button, and View Details button.
Allowed categories: Action, Racing, Puzzle, Strategy, Sports, Battle, and Adventure.
Use original game names only.
Do not use real game titles or copied brand names.
Add search or filter if possible.
Game cards should be clean and easy to scan.

## 4. Game Details Page

Create a details page for each game.
Each page must show game title, image or banner, category, description, rating, difficulty level, number of players, how to play section, Play Now button, and related games section.
Play Now must open the game play page.
Related games should show games from the same or similar category.
The details page should help users understand the game before playing.

## 5. Game Play Page

Create one simple playable browser game.
The game must not be only an image or fake screen.
The page must include game title, game screen area, Start button, Pause button, score display, timer or progress display, and Back to Games button.
The game can be a click target game, reaction timer game, memory card game, or simple puzzle game.
Buttons must respond.
Score must update.
The user should clearly understand how to play.

## 6. Tournament Page

Create a tournament page with at least **5 sample tournaments**.
Each tournament must show tournament name, game name, date, time, number of players, status, and Join button.
A logged in user can join and see a success message.
A logged out user must see a login required message.
Joined tournament should show joined state if possible.
Tournament data can be sample data but should look realistic.

## 7. Leaderboard Page

Create a leaderboard page with at least **15 sample players**.
Leaderboard must show player rank, username, game name, score, wins, and points.
Add sorting or filtering by overall score, game, and weekly rank.
Highlight the top 3 players.
The leaderboard should be readable on desktop and mobile.

## 8. User Profile and Contact Page

Create a profile page with username, email, profile image placeholder, total games played, total wins, total score, joined tournaments, favorite games, and edit profile button.
Edit profile must allow username and profile image link update using local storage or frontend state.
Create a contact page with name field, email field, subject field, message field, Send button, required field validation, and success message after submit.
Real email sending is not required.

## 9. Admin Dashboard

Create an admin dashboard with total users count, total games count, total tournaments count, add new game form, edit game option, delete game option, add tournament form, edit tournament option, and delete tournament option.
Admin actions must update data using local storage, sample data, or frontend state.
The admin page does not need to show in the normal user menu.
It can be reached through a separate route or link.

## Sample Data

Use local sample data only.
Required data:

* At least 12 games
* At least 5 tournaments
* At least 15 leaderboard players
* At least 3 sample users
  Use realistic original names.
  Do not use real gaming company names, copied game titles, or copyrighted content.

## Assets Required

Use safe assets that match the gaming theme.
Required asset types:

* PixelRift text logo or simple logo
* Game images or safe placeholder images
* Navigation and feature icons
* Hero or background visual
* Profile image placeholder
  Allowed image sources: royalty free images, AI generated images, safe placeholder images, or self-created graphics.
  Do not use copyrighted game posters, real company game art, copied brand images, or real game assets.
  All images should match the dark gaming theme.

## UI States

Show clear states where needed:

* Loading
* Empty
* Active
* Joined
* Success
* Error
* Locked
* Logged in
* Logged out
  States can appear as messages, badges, cards, forms, buttons, or banners.
  Show error when login fails and success after valid actions.

## Navigation

Navigation must include Home, Games, Tournaments, Leaderboard, Profile, Contact, and Login or Logout.
Navigation must work on desktop, tablet, and mobile.
On mobile, the menu must open and close easily.

## Responsive Rules

The website must work on desktop, laptop, tablet, and mobile.
Mobile layout must have stacked cards, readable text, easy tap buttons, resized images, clean spacing, and readable or scrollable tables.
Do not allow text to overlap or buttons to go outside the screen.

## Image Rules

Use images only when they support the gaming website.
Images should not make the page slow, messy, or inconsistent.
Game images may be placeholders if they match the theme.
Hero image should support the dark gaming look.
Icons should be simple and readable.
Profile image placeholder should look clean.
Do not use real game posters.
Do not use copied brand images.
Do not use real company game art.
Do not use unclear or low quality images.
All images should fit the layout on mobile.
All images should have proper size or object fit handling.
Use alt text where possible.
Keep the visual style consistent.

## Data Behavior

Use sample data to make the website feel complete.
Games data should connect to game details.
Game details should connect to game play.
Tournament data should connect to join action.
Leaderboard data should show rankings clearly.
Profile data should show user related information.
Admin changes should visibly update the displayed data.
Use local storage if data needs to stay after refresh.
Use frontend state if refresh persistence is not needed.
Do not leave sample sections empty.
Do not create buttons that do nothing.
Do not create pages that only show placeholder text.
Show clear feedback after user actions.
Keep data names original and realistic.

## Quality Rules

All pages should open from navigation.
Buttons should look clickable.
Forms should be readable and easy to fill.
Errors should be clear and helpful.
Success messages should be visible.
Cards should align properly.
Tables should be readable.
Spacing should be clean.
Colors should match the gaming theme.
Text should not overlap images.
Mobile layout should not break.
Admin actions should feel real even with sample data.
Game play should show real interaction.
Contact form should validate required fields.
Login state should affect user actions.
Use simple language in labels and messages.
Keep the website safe and family friendly.
Do not add unrelated pages.
Do not add restricted content.

## Out of Scope

Do not include gambling, betting, casino features, real money games, adult content, real payment gateway, real multiplayer server, real database requirement, external service dependency, copied website design, broken buttons, empty pages, or fake pages with no content.
Frontend sample data and simulated states are enough.

## File Structure

Recommended structure:

```text
pixelrift-gaming/
  public/
    images/
    icons/
  src/
    components/
    pages/
    data/
    styles/
    utils/
  README.md
  package.json
```

Simple structure is also allowed:

```text
pixelrift-gaming/
  index.html
  styles.css
  script.js
  data.js
  README.md
```

## README File

README must include project name, short description, features, pages included, technology used, how to install, how to run, admin access details if needed, and important notes.
Example commands:

```text
npm install
npm run dev
```

## Testing

Before final delivery, test website opening, navigation, all main pages, login and register messages, 12 games, game details, working game play, tournament join action, 15 leaderboard players, profile, contact form, admin add edit delete actions, and mobile layout.

## Final Deliverables

Submit complete source code, all website pages, reusable components, local sample data, images or image links, styles or design files, README file, setup instructions, and working local website.

## Acceptance Checklist

Project is complete only if all 9 areas are built, website runs locally, website is responsive, navigation works, login and register work, game listing has 12 games, game details page works, game play page has working action, tournament page has 5 tournaments, join button works with login state, leaderboard has 15 players, profile page works, contact form shows success message, admin dashboard can add edit and delete sample data, and no restricted or copied content is used.

## Final Success Definition

The final website should feel like a complete gaming platform.
A reviewer should be able to explore games, play one simple game, join tournaments, check rankings, manage a profile, contact support, and manage sample content from the admin dashboard.
