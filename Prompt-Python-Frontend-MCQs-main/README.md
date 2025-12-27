# Frontend Design MCQs Exam Application

A comprehensive, interactive multiple-choice question (MCQ) exam platform built with HTML, CSS, and JavaScript. This application provides online assessments for various technical subjects with real-time progress tracking, instant feedback, and detailed performance analytics.

## Features

### Core Features
- **Multiple Exam Categories**
  - Frontend Development MCQs
  - Python Programming MCQs
  - AI Prompt Engineering MCQs
  - Dashboard with exam management

- **Interactive Quiz Interface**
  - Clean, modern user interface with responsive design
  - Real-time progress tracking with visual progress bars
  - Question navigation with numbered indicators
  - Immediate feedback on answer selection
  - Timer display for time-based assessments

- **Dashboard & Analytics**
  - Comprehensive exam management dashboard
  - Performance statistics and metrics
  - Interactive charts for score visualization
  - Exam history tracking
  - Detailed result analysis

- **User Experience**
  - Responsive design that works on all devices
  - Smooth animations and transitions
  - Color-coded feedback (correct/incorrect answers)
  - Keyboard navigation support
  - Clean, professional styling with gradient themes

## Project Structure

```
Frontend-Design-MCQs Exam/
├── README.md                              # Project documentation
├── CLAUDE.md                              # Claude configuration and guidelines
├── frontend-index.html                    # Frontend Development MCQ Exam
├── python-index.html                      # Python Programming MCQ Exam
├── ai-prompt-engineering-index.html       # AI Prompt Engineering MCQ Exam
├── dashboard-index.html                   # Exam Dashboard & Analytics
└── .claude/
    └── skills/
        └── frontend-design/
            └── SKILL.md                   # Frontend design skill configuration
```

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or server setup required

### Installation

1. **Clone or download the project:**
   ```bash
   git clone https://github.com/Connect-Munir/Prompt-Python-Frontend-MCQs.git
   cd "Frontend-Design-MCQs Exam"
   ```

2. **Open the application:**
   - **For Dashboard:** Open `dashboard-index.html` in your web browser
   - **For Frontend Quiz:** Open `frontend-index.html` in your web browser
   - **For Python Quiz:** Open `python-index.html` in your web browser
   - **For AI Prompt Engineering Quiz:** Open `ai-prompt-engineering-index.html` in your web browser

### Running Locally

Simply double-click any `.html` file to open it in your default browser, or:

```bash
# Using Python's built-in server (Python 3)
python -m http.server 8000

# Using Node.js http-server
http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Usage

### Taking a Quiz

1. **Select an Exam:** Choose from the available exam categories
2. **Read Questions:** Carefully read each multiple-choice question
3. **Select Answer:** Click on one of the provided options
4. **View Feedback:** Immediately see if your answer is correct
5. **Navigate:** Move to the next question using the navigation buttons
6. **Submit Results:** Complete the exam to see your final score

### Dashboard

The dashboard provides:
- **Quick Stats:** Total exams, average score, completion rate
- **Exam Cards:** Overview of all available exams
- **Performance Charts:** Visual representation of scores
- **Exam History:** Records of all completed assessments

## Features Details

### Quiz Interface
- **Progress Bar:** Visual representation of quiz completion
- **Question Counter:** Know your position (e.g., "Question 3 of 10")
- **Timer:** Track time spent on the exam
- **Score Display:** Real-time score updates

### Design & UI
- **Color Scheme:** Green gradient theme (#19A26C, #148A5A) for professional appearance
- **Responsive Layout:** Adapts to different screen sizes
- **Accessibility:** Clear contrast, readable fonts
- **Interactive Elements:** Smooth hover effects and transitions

## Technical Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Charts:** Chart.js for data visualization
- **Styling:** CSS3 with modern features (Flexbox, Grid)
- **Browser APIs:** LocalStorage for data persistence

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## File Descriptions

### Quiz Files
- **frontend-index.html** - Comprehensive frontend development assessment with questions covering HTML, CSS, JavaScript, and responsive design
- **python-index.html** - Python programming MCQs covering syntax, data structures, libraries, and best practices
- **ai-prompt-engineering-index.html** - AI and prompt engineering assessments for LLM interactions

### Dashboard
- **dashboard-index.html** - Central hub for exam management with performance analytics and student insights

## Customization

### Adding New Questions
Edit the respective HTML file and modify the `questions` array in the JavaScript section:

```javascript
const questions = [
  {
    id: 1,
    text: "Your question here?",
    options: ["Option 1", "Option 2", "Option 3", "Option 4"],
    correctAnswer: 0 // Index of correct option
  },
  // Add more questions...
];
```

### Styling Changes
Modify the CSS `<style>` section in the HTML files to customize:
- Color scheme
- Fonts and typography
- Layout and spacing
- Animations and transitions

### Adding New Exam Categories
1. Create a new `.html` file
2. Copy the structure from an existing quiz file
3. Update the title, questions, and styling
4. Add a link in the dashboard

## Features for Future Enhancement

- User authentication and accounts
- Database integration for persistent storage
- Admin panel for quiz management
- Detailed result reports and PDFs
- Leaderboards and rankings
- Mobile app version
- Multi-language support
- Timed assessments with auto-submission
- Question bank randomization
- Difficulty level selection

## Troubleshooting

### Quiz Not Loading
- Ensure JavaScript is enabled in your browser
- Check browser console for errors (F12 > Console)
- Try clearing browser cache

### Scores Not Saving
- Check if browser allows localStorage
- Try a different browser
- Disable browser extensions that might interfere

### Chart Not Displaying
- Verify Chart.js CDN is accessible
- Check internet connection
- Try refreshing the page

## License

This project is for educational purposes. Modify and distribute as needed for your use case.

## Support

For issues, questions, or feature requests, please contact the development team or open an issue in the project repository.

---

**Last Updated:** December 2025

**Version:** 1.0.0

**Status:** Production Ready
