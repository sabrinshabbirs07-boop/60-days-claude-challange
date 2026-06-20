# Day 20/60 - AI-Powered Face Puzzle Game

## Introduction

Today, as part of my **#60DaysOfClaude Challenge**, I built an interactive **Face Puzzle Game** using a single self-contained HTML file generated with Claude AI.

This project combines webcam access, image processing, puzzle generation, drag-and-drop interactions, touch support, game statistics, and a persistent leaderboard into a fun and engaging browser-based experience.

The application captures a user's face using the webcam, transforms the image into puzzle pieces, scrambles them, and challenges the player to reconstruct the original image while tracking performance metrics such as time, moves, and completion accuracy.

## Project Features

### Camera Integration

* Webcam access using the MediaDevices API
* Live camera preview
* Front-facing camera preference
* Photo capture functionality
* Graceful handling of camera permission denial

### Dynamic Puzzle Generation

* Difficulty levels:

  * 3×3 Grid
  * 4×4 Grid
  * 5×5 Grid
* Automatic image slicing
* Random puzzle scrambling
* Puzzle generation from the captured face image

### Interactive Gameplay

* Mouse drag-and-drop support
* Touch gesture support for mobile devices
* Tile swapping mechanics
* Snap-to-grid functionality
* Visual highlighting while dragging
* Correct position indicators

### Performance Tracking

* Real-time timer
* Move counter
* Correctly placed pieces tracker
* Live progress updates

### Results & Leaderboard

* Automatic puzzle completion detection
* Final performance summary
* Completion time tracking
* Top 5 best scores saved using Local Storage
* Persistent leaderboard across sessions

### User Experience

* Modern responsive design
* Mobile-friendly interface
* Retake Photo option
* Play Again functionality
* New Photo workflow
* Cross-browser compatibility

## Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript
* Canvas API
* MediaDevices API
* Local Storage API
* Drag and Drop Events
* Touch Events

## Development Workflow

The project was developed using a detailed Claude prompt that included:

1. Webcam integration requirements
2. Face image capture functionality
3. Puzzle generation logic
4. Drag-and-drop mechanics
5. Touch gesture support
6. Timer and move tracking
7. Win detection system
8. Local storage leaderboard
9. Responsive user interface requirements
10. Cross-browser compatibility

## Testing Process

To verify the functionality of the application, the following steps were performed:

1. Generated the complete HTML application.
2. Saved the generated HTML file.
3. Opened the application in a browser.
4. Allowed webcam permissions.
5. Captured a photo.
6. Selected a puzzle difficulty level.
7. Verified puzzle generation.
8. Tested drag-and-drop interactions.
9. Tested touch controls on mobile devices.
10. Verified timer functionality.
11. Verified move tracking.
12. Checked correct piece detection.
13. Completed the puzzle.
14. Tested leaderboard storage and retrieval.
15. Verified the final results screen.

## Key Learnings

This project helped me gain practical experience in:

* Browser camera APIs
* Image processing with Canvas
* Puzzle game development
* Mobile touch event handling
* Drag-and-drop interfaces
* Local storage persistence
* Responsive web development
* AI-assisted front-end application development


## Outcome

Successfully built a fully functional Face Puzzle Game that allows users to capture their own photo, generate a puzzle from it, solve the puzzle through drag-and-drop interactions, and track their performance through a built-in leaderboard system.

This project demonstrates how AI can accelerate the development of complete interactive web applications while maintaining a strong focus on user experience and functionality.

##  AI-Powered Face Puzzle Game
[html file]()

## snap of the game pages
[image]()


