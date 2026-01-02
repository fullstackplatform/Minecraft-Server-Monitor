# Minecraft Server Monitor

A sleek and modern web application to instantly check the status of any Minecraft server. Enter a server address and get real-time information, including player count, message of the day (MOTD), and online player lists.

Built with Next.js, TypeScript, and Tailwind CSS, this tool provides a fast and responsive experience for all Minecraft enthusiasts.



## Features

-   **Real-Time Status**: Instantly see if a server is online or offline.
-   **Player Information**: View the current number of online players versus the maximum capacity.
-   **Online Player List**: See a list of all players currently on the server, complete with their in-game avatars.
-   **Server MOTD**: The server's Message of the Day is displayed, just as you would see it in the Minecraft client.
-   **Server Icon**: The server's custom icon (favicon) is automatically fetched and displayed.
-   **Java & Bedrock Support**: The monitor intelligently checks for both Java and Bedrock servers at the given address.
-   **Modern UI**: A clean, responsive, and Minecraft-inspired user interface built with ShadCN UI components.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need to have [Node.js](https://nodejs.org/) (version 18 or later) and npm installed on your computer.

-   **Node.js**: [Download & Install Node.js](https://nodejs.org/en/download/)

### Installation

1.  **Clone the repository** (or download the project files):
    ```sh
    git clone https://github.com/fullstackplatform/minecraft-server-monitor.git
    ```

2.  **Navigate to the project directory**:
    ```sh
    cd minecraft-server-monitor
    ```

3.  **Install dependencies**:
    This command will read the `package.json` file and install all the necessary libraries into a `node_modules` folder.
    ```sh
    npm install
    ```

4.  **Run the development server**:
    This will start the application on your local machine.
    ```sh
    npm run dev
    ```

5.  **Open the application**:
    Open your web browser and navigate to [http://localhost:9002](http://localhost:9002) to see the application live.

## Tech Stack

This project is built with a modern, efficient, and scalable tech stack:

-   **Framework**: [Next.js](https://nextjs.org/) (with App Router)
-   **Language**: [TypeScript](https://www.typescriptlang.org/)
-   **Styling**: [Tailwind CSS](https://tailwindcss.com/)
-   **UI Components**: [ShadCN UI](https://ui.shadcn.com/)
-   **Server Status API**: [mcsrvstat.us](https://mcsrvstat.us/)
