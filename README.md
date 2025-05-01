
Built by https://www.blackbox.ai

---

```markdown
# Ask Me Anything 💬

## Project Overview

"Ask Me Anything" is a web-based application that allows users to submit anonymous questions, which can then be managed by an admin through a dedicated interface. The application provides a simple user interface with responsiveness provided by Tailwind CSS. Users can submit questions, and an admin can review and manage these questions through an admin panel.

## Installation

To get started with the "Ask Me Anything" application, follow the steps below:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```

3. Open `index.html` in your web browser to start using the app. For the admin panel, open `admin.html`.

## Usage

- **User Interaction**:
  - Users can input their Instagram ID (optional) and submit questions through the main form on the home page.
  - Upon submission, users will receive a thank you message indicating that their question has been submitted.

- **Admin Interaction**:
  - Admins can access the admin page by entering a predefined password (`admin123`). 
  - They can search for questions based on the user's Instagram ID or the question text.
  - Submitted questions are displayed in a list format.

## Features

- **Anonymous Question Submission**: Users can submit questions without needing to disclose their identity.
- **Admin Panel**: An interface for admins to manage user submissions.
- **Search Functionality**: Enables admins to filter questions by Instagram ID or content.
- **Confetti Animation**: A fun visual effect upon question submission.

## Dependencies

The project includes the following dependencies, which are imported via CDN:

- **Tailwind CSS**: For styling and layout.
- **Font Awesome**: For icons.
- **Firebase**: For potential integration (Firestore) in the admin panel (currently set up as placeholders).

### CDN Links Used
- Tailwind CSS CDN: `https://cdn.tailwindcss.com`
- Font Awesome CDN: `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css`
- Firebase:
  - `https://www.gstatic.com/firebasejs/9.22.1/firebase-app-compat.js`
  - `https://www.gstatic.com/firebasejs/9.22.1/firebase-firestore-compat.js`

## Project Structure

```
/your-project-directory
│
├── index.html         # Main user interface for question submissions
├── admin.html         # Admin panel for managing user submissions
└── styles.css         # Custom styles for the application (if any)
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```