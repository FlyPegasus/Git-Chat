# Git-Chat
A Chat application for Github users, where they can directly message each other.

## Vision
To create a seamless, real-time communication channel directly integrated with the GitHub ecosystem. Git-Chat aims to connect developers, collaborators, and open-source-A enthusiasts by allowing them to message each other directly, using their existing GitHub identity.

## Scope
The initial version (MVP) of Git-Chat will focus on the core functionality of a 1-to-1 chat application.
- In-Scope (MVP):
    - Secure user authentication via GitHub OAuth.
    - Ability to search for any GitHub user.
    - Initiating a 1-to-1 private chat.
    - Real-time message sending and receiving.
    - Persistent chat history (messages are saved).
- Out-of-Scope (For Later Versions):
    - Group chats.
    - File/image/code snippet uploads.
    - Read receipts or "is typing" indicators.
    - Profile editing (will use GitHub profile data).

## Target Users
- Any registered GitHub user.
- Open-source contributors looking to connect with maintainers.
- Developers who want to quickly discuss a project or PR outside of formal issues.

## Planned Features
- GitHub Authentication: Securely log in using your GitHub account.
- User Search: Find and start conversations with any other user on GitHub.
- 1-to-1 Messaging: Private, real-time chat between two users.
- Chat Persistence: Conversations and messages are saved to the database and can be viewed upon re-logging in.

## Tech Stack
- Frontend: React
- Backend: Node.js, Express.js
- Database: MongoDB (with MongoDB Atlas for hosting)
- Real-time Communication: Socket.IO
- Authentication: GitHub OAuth
- Deployment: TBD (Targeting a cloud-native/DevOps-heavy approach)

## Roadmap
| Phase | Milestone | Status |
|-------|-----------|--------|
| 1 | Planning | ✅ Complete |
| 2 | Design | ⏳ Not Started |
| 3 | Implementation | ⏳ Not Started |
| 4 | Testing | ⏳ Not Started |
| 5 | Deployment | ⏳ Not Started |