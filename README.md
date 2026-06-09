# IB Study Hub

A modern, responsive, single-page study dashboard built for IB (International Baccalaureate) students. IB Study Hub helps students organize revision, practise key concepts, track topic progress, and manage study sessions from one lightweight browser-based app.

## Overview

IB Study Hub is designed as an all-in-one study workspace for IB students. The current version includes a dark-themed dashboard, subject cards, flashcards, quiz mode, topic checklists, and a study timer.

The project runs entirely in the browser using only HTML, CSS, and vanilla JavaScript. No external frameworks, libraries, installations, or build tools are required.

## Features

### Dashboard Home

* Clean dark-themed interface
* Responsive dashboard layout
* Subject overview cards
* Quick navigation between study tools
* Interactive hover effects
* Mobile-friendly design

### Subject Cards

The dashboard includes subject cards for:

* Mathematics
* Physics
* Chemistry
* Biology
* Economics
* History
* English A
* Environmental Systems & Societies (ESS)
* Theory of Knowledge (TOK)
* Extended Essay (EE)
* Internal Assessments & CAS

Each subject card displays the subject name, icon, IB group, and supported level tags.

### Flashcards

The flashcard system allows students to revise key IB concepts.

Current functionality includes:

* Flashcards across multiple IB subjects
* Subject filtering
* Card flipping animation
* Previous and next card navigation
* Shuffle option
* Simple difficulty rating buttons:

  * Hard
  * Okay
  * Easy

Included flashcard subjects:

* Mathematics
* Physics
* Chemistry
* Biology
* Economics
* History
* English A
* TOK
* Extended Essay
* IAs & CAS

### Quiz Mode

Quiz mode lets students test themselves using multiple-choice questions.

Current functionality includes:

* Subject selection
* Question count selection
* Randomized quiz order
* Shuffled answer options
* Live score tracking
* Progress bar
* Correct and incorrect answer feedback
* Final score screen
* Retry option

Current quiz coverage includes:

* Mathematics
* Physics
* Chemistry
* Biology
* Economics
* History
* English A
* TOK

### Topic Checklist

The topic checklist helps students track revision progress by subject.

Current functionality includes:

* Topic groups by subject
* Checkable revision items
* Per-subject progress counters
* Per-subject progress bars
* Total topic completion progress
* Reset progress button
* Progress saved in browser local storage

Checklist subjects include:

* Mathematics
* Physics
* Chemistry
* Biology
* Economics
* History
* English A
* TOK
* Extended Essay
* IAs & CAS

### Study Timer

The study timer helps students track study sessions.

Current functionality includes:

* Start, pause, resume, and reset controls
* Large timer display
* Timer shown in navigation bar
* Session logging
* Total study time for the day
* Automatic session log after pausing or resetting

### User Interface

The interface includes:

* Modern dark theme
* Consistent color palette
* Card-based layout
* Smooth transitions
* Sticky navigation bar
* Responsive design
* Mobile layout adjustments

## Built With

* HTML5
* CSS3
* Vanilla JavaScript

No external frameworks or dependencies are used.

## Project Structure

```text
project/
│
└── index.html
```

The project is intentionally lightweight and currently contained in a single HTML file.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ib-study-hub.git
```

### 2. Navigate to the project folder

```bash
cd ib-study-hub
```

### 3. Open the app

Open `index.html` directly in your browser.

No installation, package manager, or build process is required.

## Usage

### Navigate the Dashboard

Use the top navigation bar to move between:

* Home
* Flashcards
* Quiz
* Topics
* Study Timer

The study timer can also be opened by clicking the timer display in the navigation bar.

### Use Flashcards

1. Open the Flashcards tab.
2. Choose a subject or keep all subjects selected.
3. Click a card to flip it.
4. Use the previous and next buttons to move through cards.
5. Use the difficulty buttons to rate your recall.

### Take a Quiz

1. Open the Quiz tab.
2. Choose a subject.
3. Select the number of questions.
4. Click Start Quiz.
5. Choose answers and review feedback.
6. View your final score at the end.

### Track Topics

1. Open the Topics tab.
2. Tick topics as you complete them.
3. Progress is saved automatically in your browser.
4. Use Reset to clear all checklist progress.

### Use the Study Timer

1. Click the timer display or open the Study Timer page.
2. Press Start.
3. Pause or reset when finished.
4. Sessions longer than a few seconds are added to the session log.

## Responsive Design

The interface is optimized for:

* Desktop
* Tablet
* Mobile

On smaller screens, the layout adjusts spacing, timer sizing, and navigation labels for better usability.

## Current Status

This version is a functional first prototype of the IB Study Hub platform. It includes the core dashboard, study navigation, flashcards, quizzes, topic tracking, and study timer.

Some subject content is still limited. ESS currently appears as a subject card but does not yet have dedicated flashcards, quiz questions, or checklist topics.

## Roadmap

Planned improvements include:

* Add ESS flashcards, quiz questions, and checklist topics
* Add more Extended Essay and IA/CAS quiz content
* Add user-created flashcards
* Add user-created quizzes
* Add editable topic lists
* Add custom study plans
* Add advanced progress analytics
* Add performance dashboards
* Add resource management
* Add persistent study history
* Add export/import support for progress data
* Improve spaced repetition logic
* Add accessibility improvements

## Known Limitations

* Data is stored locally in the browser only.
* Refreshing does not reset checklist progress, but timer sessions are not permanently stored.
* There is no backend or user account system.
* Flashcard and quiz content is hardcoded in `index.html`.
* ESS content is not yet fully implemented.
* The timer tracks sessions only during the current page session.

## License

MIT License

## Author

Created as a lightweight IB study dashboard prototype.
