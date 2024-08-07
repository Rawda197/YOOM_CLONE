
# A Yoom Clone
<br>
Yoom is an application designed for video conferencing, similar to Zoom. It provides users with a seamless and effective experience for conducting virtual meetings, supporting essential features such as screen sharing and audio-video communication. The app aims to enhance remote communication and facilitate collaboration between teams and individuals.
<br>
📋 Table of Contents
<br>
- 🤖 Introduction
- ⚙️ Tech Stack
- 🔋 Features
- 🤸 Quick Start
- 🕸️ Assets & Code
- 🚀 More
<br>

## 🚨 Tutorial
<br>
This repository contains the code corresponding to an in-depth tutorial available on our YouTube channel, JavaScript Mastery.

If you prefer visual learning, this is the perfect resource for you. Follow our tutorial to learn how to build projects like these step-by-step in a beginner-friendly manner!
<br>

## 🤖 Introduction
<br>
Built with the latest Next.js and TypeScript, this project replicates Zoom, a widely used video conferencing tool. It enables users to securely log in, create meetings, and access various meeting functionalities such as recording, screen sharing, and managing participants.
<br>

## ⚙️ Tech Stack
<br>
- Next.js
- TypeScript
- Clerk
- getstream
- shadcn
- Tailwind CSS
<br>

## 🔋 Features
<br>

👉 **Authentication**: Implements authentication and authorization features using Clerk, allowing users to securely log in via social sign-on or traditional email and password methods, while ensuring appropriate access levels and permissions within the platform.
<br>

👉 **New Meeting**: Quickly start a new meeting, configuring camera and microphone settings before joining.
<br>

👉 **Meeting Controls**: Participants have full control over meeting aspects, including recording, emoji reactions, screen sharing, muting/unmuting, sound adjustments, grid layout, participant list view, and individual participant management (pinning, muting, unmuting, blocking, allowing video share).
<br>

👉 **Exit Meeting**: Participants can leave a meeting, or creators can end it for all attendees.
<br>

👉 **Schedule Future Meetings**: Input meeting details (date, time) to schedule future meetings, accessible on the 'Upcoming Meetings' page for sharing the link or immediate start.
<br>

👉 **Past Meetings List**: Access a list of previously held meetings, including details and metadata.
<br>

👉 **View Recorded Meetings**: Access recordings of past meetings for review or reference.
<br>

👉 **Personal Room**: Users have a personal room with a unique meeting link for instant meetings, shareable with others.
<br>

👉 **Join Meetings via Link**: Easily join meetings created by others by providing a link.
<br>

👉 **Secure Real-time Functionality**: All interactions within the platform are secure and occur in real-time, maintaining user privacy and data integrity.
<br>

👉 **Responsive Design**: Follows responsive design principles to ensure optimal user experience across devices, adapting seamlessly to different screen sizes and resolutions.

and many more, including code architecture and reusability.
<br>

## Screenshots
<br>

### Home Page
![Home Page](../../public/assets/Home.png)
Description: The home page serves as the central hub of the application, providing users with quick access to essential features such as starting a new meeting, joining an existing one, and managing their personal settings. It offers an intuitive layout for easy navigation and includes options for scheduling future meetings and viewing upcoming or past meetings.
<br>

## 🤸 Quick Start
<br>

Follow these steps to set up the project locally on your machine.
<br>

### Prerequisites
<br>

Make sure you have the following installed on your machine:
<br>

- Git
- Node.js
- npm (Node Package Manager)
<br>

### Cloning the Repository
<br>

```bash
<br>
git clone https://github.com/adrianhajdin/zoom-clone.git
cd zoom-clone
Installation
Install the project dependencies using npm:

bash
Copy code
npm install
Set Up Environment Variables
Create a new file named .env in the root of your project and add the following content:

env
Copy code
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=

<br>

Replace the placeholder values with your actual Clerk & getstream credentials. You can obtain these credentials by signing up on the Clerk website and getstream website.
<br>
Running the Project
bash
Copy code
npm run dev
Open http://localhost:3000 in your browser to view the project.
<br>
🕸️ Snippets
<br>
`app/globals.css`
`tailwind.config.ts`
`components/MeetingCard.tsxّ`
<br>
If you need any further assistance or modifications, please feel free to let me know!
