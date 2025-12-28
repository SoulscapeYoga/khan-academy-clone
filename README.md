# Khan Academy Clone

A comprehensive online learning platform inspired by Khan Academy, designed to provide educational content, video tutorials, and interactive learning experiences.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Uploading Content](#uploading-content)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Video Learning**: Access to a library of educational videos organized by subject and topic
- **Interactive Exercises**: Practice problems and quizzes to test your knowledge
- **Progress Tracking**: Monitor your learning progress across different courses
- **Content Management**: Easy upload and management of educational materials
- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices
- **User Authentication**: Secure login and user account management
- **Course Organization**: Well-structured curriculum organized by subject and difficulty level

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14.0.0 or higher)
- npm or yarn package manager
- A modern web browser
- Git for version control

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/SoulscapeYoga/khan-academy-clone.git
   cd khan-academy-clone
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory with the following variables:
   ```
   REACT_APP_API_URL=http://localhost:5000
   REACT_APP_ENV=development
   ```

4. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000` to access the application

## Usage

### For Students

1. **Sign Up / Log In**
   - Create a new account or log in with existing credentials
   - Complete your profile setup

2. **Browse Courses**
   - Navigate to the Courses section
   - Filter by subject, level, or search for specific topics
   - Click on a course to view its content

3. **Watch Videos**
   - Select a video lesson from the course
   - Watch the video and take notes
   - Use playback controls for pausing, rewinding, and adjusting speed

4. **Complete Exercises**
   - After watching a video, attempt the practice problems
   - Submit your answers for instant feedback
   - Review detailed explanations for correct solutions

5. **Track Progress**
   - View your learning dashboard
   - Check completion percentages for each course
   - Monitor your performance metrics

### For Instructors / Content Creators

1. **Access Content Management**
   - Log in with instructor credentials
   - Navigate to the Content Management Dashboard

2. **Create Courses**
   - Click "New Course"
   - Enter course title, description, and select subject category
   - Set difficulty level and target audience
   - Save the course structure

3. **Manage Course Content**
   - Add lessons and topics to your course
   - Organize content in a logical sequence
   - Set prerequisites if needed

## Uploading Content

### Video Upload

1. **Navigate to Content Manager**
   - From the dashboard, select "Upload Content" → "Video"

2. **Select Video File**
   - Click "Choose File" and select your video (MP4, WebM, or MKV format)
   - Maximum file size: 2GB
   - Recommended resolution: 1920x1080 (Full HD)

3. **Add Video Details**
   - **Title**: Give your video a clear, descriptive title
   - **Description**: Write a detailed description of the video content
   - **Subject**: Select the appropriate subject category
   - **Topic**: Choose or create a specific topic
   - **Duration**: Auto-detected or manually entered
   - **Difficulty Level**: Select from Beginner, Intermediate, Advanced
   - **Tags**: Add relevant keywords for easy searching

4. **Thumbnail**
   - Upload a custom thumbnail (recommended: 1280x720px)
   - Or let the system auto-generate one from the video

5. **Transcription**
   - Upload subtitle/caption file (SRT or VTT format)
   - Or enable auto-transcription (if available)

6. **Review and Publish**
   - Preview your content
   - Click "Publish" to make it available to users

### Exercise/Quiz Upload

1. **Navigate to Content Manager**
   - Select "Upload Content" → "Exercise"

2. **Create Exercise**
   - Choose exercise type: Multiple Choice, Short Answer, or Problem Set
   - Link to related video content

3. **Add Questions**
   - Enter question text
   - Provide answer options (for multiple choice)
   - Mark correct answer(s)
   - Add explanations for each answer option

4. **Set Difficulty and Points**
   - Assign point value
   - Set difficulty rating
   - Configure time limit (if applicable)

5. **Publish**
   - Review the exercise
   - Click "Publish" to activate

### Document/Resource Upload

1. **Navigate to Content Manager**
   - Select "Upload Content" → "Resource"

2. **Upload File**
   - Supported formats: PDF, DOCX, PPTX, XLSX, TXT
   - Maximum file size: 100MB

3. **Add Metadata**
   - Title and description
   - Subject and topic
   - File type and version
   - Downloadable/View-only settings

4. **Organize**
   - Add to course or make standalone
   - Set availability settings
   - Configure access permissions

## Project Structure

```
khan-academy-clone/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── Navbar/
│   │   ├── VideoPlayer/
│   │   ├── CourseCard/
│   │   └── Dashboard/
│   ├── pages/
│   │   ├── Home/
│   │   ├── Courses/
│   │   ├── ContentManager/
│   │   └── Profile/
│   ├── hooks/
│   ├── utils/
│   ├── styles/
│   └── App.js
├── .env
├── package.json
└── README.md
```

## Contributing

We welcome contributions from the community! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

Please ensure your code follows our coding standards and includes appropriate tests.

## Troubleshooting

### Video Upload Issues
- **File too large**: Compress your video or split into multiple parts
- **Unsupported format**: Convert to MP4 or WebM format
- **Upload timeout**: Try uploading in segments or use a wired connection

### Performance Issues
- Clear browser cache
- Disable browser extensions
- Update to the latest browser version
- Check your internet connection speed

### Login Problems
- Verify email address is correct
- Reset password if forgotten
- Clear cookies and cache
- Contact support for account issues

## Support

For issues, questions, or suggestions:
- Create an issue on GitHub
- Contact: support@khan-academy-clone.local
- Documentation: [Link to full docs]

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by Khan Academy
- Thanks to all contributors and users
- Built with React and Node.js

---

**Last Updated**: December 28, 2025

For the latest updates and announcements, follow our repository and check the Releases section.
