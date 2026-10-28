# Deadline Buddy

> A student dashboard that tracks assignments, exams and study time in one place, with AI-powered study scheduling.

## The Problem
University students juggle assignments, quizzes, labs and exams across several courses. It's easy to lose track of what is due next and to leave preparation until the last minute.

## Our Solution
Deadline Buddy puts every deadline, exam and study session in one dashboard. It shows what needs attention first, tracks exam readiness, and uses AI to suggest study blocks.

## Features
- **Dashboard:** Next-best-action banner with a live countdown, metrics for pending work and exam readiness, and urgent deadline cards. Tasks can be added, completed, filtered, searched and sorted.
- **My Assignments:** Full list of coursework to manage.
- **Exam Tracker:** Preparation progress per exam, a grade simulator, and an AI assistant that suggests study blocks.
- **Weekly Calendar:** Week view of deadlines and study sessions, with a daily agenda and milestone checklists.
- **Completed Tasks:** Archive of finished work with grades, submission receipts, badges, filters and export.
- **Settings:** Workspace preferences.

## AI Integration
The Exam Tracker uses the **Google Gemini API** to suggest study blocks based on exam readiness and the days remaining.

## Built With
- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Browser localStorage (saves tasks and progress)
- Google Gemini API

## Project Structure
```
Deadline-Buddy/
├── Dashboard.html
├── my application.html
├── ExamTracker.html
├── WeeklyCalender.html
├── completed.html
├── Settings.html
├── config.example.js   # template for your API key
└── config.js           # your real key (not in the repo)
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/manahilnaqvi16-star/Deadline-Buddy.git
   ```
2. Copy `config.example.js` to `config.js` and add your own Gemini API key.
3. Open `Dashboard.html` in your browser.

The app works without an API key. Only the AI study scheduling needs it.

## Future Improvements
- Backend to keep the API key private
- User accounts and cloud sync
- Reminders and notifications
- Integration with Canvas and other learning platforms
- Mobile app

## Team
| Name |
|------|
| Aasia Nadeem |
| Manahil Zehra |
| Umme Habiba |

## License
Made for a hackathon. All rights reserved by the team.
