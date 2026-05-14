# DOH Computer-Based Testing Format

## Introduction

The Department of Health (DOH) Abu Dhabi optometry licensing examination is administered through Prometric testing centers, utilizing a sophisticated computer-based testing (CBT) platform. Understanding the testing interface and available tools is crucial for optimal performance.

## Testing Platform Overview

### Prometric Testing Environment

The examination is delivered through Prometric's secure testing platform, which provides:
- Standardized testing conditions worldwide
- Robust security measures
- Reliable performance tracking
- Immediate score calculation

### System Requirements (At Testing Center)
- Desktop computer with webcam
- 17+ inch monitor
- Standard keyboard and mouse
- Adjustable chair and desk
- Adequate lighting
- Climate control

## User Interface Components

### Main Question Screen

```
┌─────────────────────────────────────────────────────────────┐
│ Question 45 of 100                    Time: 01:45:30       │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│ A 52-year-old diabetic patient presents with sudden         │
│ painless vision loss in the right eye. Fundus examination   │
│ reveals flame-shaped hemorrhages in all quadrants with      │
│ macular edema. What is the most appropriate initial         │
│ management step?                                            │
│                                                             │
│ ○ A. Panretinal photocoagulation                            │
│ ○ B. Intravitreal anti-VEGF injection                       │
│ ○ C. Immediate referral to retina specialist                │
│ ○ D. Optical coherence tomography                           │
│ ○ E. Fluorescein angiography                                │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│ [Flag] [Strike-out] [Highlight] [Calculator] [Next] [End]  │
└─────────────────────────────────────────────────────────────┘
```

### Navigation Tools

| Tool | Function | Keyboard Shortcut |
|------|----------|-------------------|
| Next | Proceed to next question | N or Enter |
| Previous | Return to previous question | P or Backspace |
| Flag | Mark for review | F |
| Strike-out | Eliminate wrong options | S |
| Highlight | Mark important text | H |
| Calculator | Open basic calculator | C |
| End Exam | Submit and exit | Ctrl+End |

## Question Interaction Features

### 1. Answer Selection
- Click on the radio button (○) to select an answer
- Selected answer shows as filled circle (●)
- Only one answer can be selected per question
- Selection can be changed before submission

### 2. Strikethrough Feature
- Click "Strike-out" to cross through options
- Useful for eliminating clearly wrong answers
- Helps visualize remaining options
- Can be reversed if needed

**Example:**
```
~~A. Panretinal photocoagulation~~  [Eliminated]
○ B. Intravitreal anti-VEGF injection
~~C. Immediate referral to retina specialist~~ [Eliminated]
○ D. Optical coherence tomography
~~E. Fluorescein angiography~~  [Eliminated]
```

### 3. Highlighting Tool
- Select text in the question stem
- Click "Highlight" to mark important information
- Helps focus on key clinical data
- Useful for complex scenarios

### 4. Flag for Review
- Mark questions to revisit later
- Flagged questions appear in review screen
- No penalty for flagging
- Useful for time management

## Review Screen

### Question Status Display

```
┌────────────────────────────────────────────────────────┐
│ REVIEW SCREEN                              Time: 00:30:00│
├────────────────────────────────────────────────────────┤
│                                                        │
│ Answered: 75 questions                                 │
│ Flagged: 12 questions                                  │
│ Unanswered: 13 questions                               │
│                                                        │
│ Question Status:                                       │
│ 1 ✓  2 ✓  3 F  4 ✓  5 ✓  6 ✓  7 F  8 ✓  9 ✓  10 ✓     │
│ 11 ✓ 12 U 13 ✓ 14 ✓ 15 ✓ 16 ✓ 17 ✓ 18 U 19 ✓ 20 ✓     │
│ ...                                                    │
│                                                        │
│ [Return to Question] [End Exam]                        │
└────────────────────────────────────────────────────────┘
```

### Status Indicators
- ✓ = Answered
- F = Flagged for review
- U = Unanswered
- ✓F = Answered and flagged

## Time Management Features

### Timer Display
- Countdown timer visible at all times
- Shows hours, minutes, seconds
- Changes color as time decreases
- Warning at 15 minutes remaining

### Time Warnings
| Time Remaining | Timer Color | Alert |
|----------------|-------------|-------|
| > 30 minutes | Green | None |
| 15-30 minutes | Yellow | Visual |
| < 15 minutes | Red | Visual + Sound |

### Time Allocation Guidance

The platform may show:
- Average time per question
- Current pace indicator
- Recommended question completion

## Image and Media Display

### Image Questions

When questions include images:
- Full-screen image viewer available
- Zoom and pan functions
- Brightness/contrast adjustment
- Multiple images shown in tabs

### Image Types in Optometry Exam
- Fundus photographs
- OCT cross-sections
- Visual field plots
- Slit lamp photographs
- External eye photos
- Corneal topography maps

## Calculator Tool

### Available Functions
- Basic arithmetic (+, -, ×, ÷)
- Square root
- Percentage
- Memory functions
- Clear and backspace

### Use Cases
- Optical calculations
- IOP conversion
- Prism diopter calculations
- Magnification calculations

## Security Features

### Before the Exam
- Biometric verification (fingerprint)
- Photo identification check
- Palm vein scanning (at some centers)
- Metal detection screening

### During the Exam
- Continuous video monitoring
- Screen recording
- Keystroke logging
- Proctor observation window

### Prohibited Actions
- Looking at other screens
- Speaking or making noises
- Removing items from pockets
- Taking breaks outside designated areas
- Accessing unauthorized materials

## Technical Support

### During the Exam
- Raise hand for proctor assistance
- Use intercom button at workstation
- Technical issues are logged and timed
- Lost time may be compensated

### Common Issues and Solutions

| Issue | Solution |
|-------|----------|
| Screen freeze | Wait 30 seconds, then alert proctor |
| Mouse not working | Try different USB port, alert proctor |
| Keyboard issues | Request replacement |
| Timer not displaying | Alert proctor immediately |
| Image not loading | Request reload or proctor assistance |

## Practice and Familiarization

### Tutorial Session
- 15-minute tutorial before exam starts
- Practice using all tools
- No time counted against exam
- Recommended to complete fully

### Sample Test Interface
- Available through DOH candidate portal
- Practice navigation tools
- Familiarize with question format
- Reduce test-day anxiety

## Accommodations

### Available Accommodations
- Extended time (25-100% additional)
- Screen magnification software
- Screen readers
- Adjustable lighting
- Ergonomic equipment
- Frequent breaks

### Request Process
1. Submit accommodation request 60 days before exam
2. Provide supporting documentation
3. Receive approval notification
4. Confirm accommodation arrangements

## Test-Taking Strategies Using CBT Features

### Efficient Navigation
1. Complete easy questions first
2. Flag difficult questions
3. Use strikethrough to eliminate
4. Return to flagged questions

### Time Optimization
1. Monitor timer regularly
2. Don't spend more than 2 minutes per question initially
3. Reserve 15-20 minutes for review
4. Answer all questions (no negative marking)

### Reducing Errors
1. Read entire question before answering
2. Verify selection before moving on
3. Use highlighting for complex scenarios
4. Check for unanswered questions in review screen

## Post-Exam Procedures

### Submission Process
1. Click "End Exam" button
2. Confirm submission
3. Complete survey (optional)
4. Receive preliminary score (if applicable)

### Score Reporting
- Immediate preliminary result (pass/fail)
- Detailed score report within 2-4 weeks
- Section-by-section breakdown
- Percentile ranking

## References

1. Prometric Candidate Information Booklet
2. DOH Examination Guidelines
3. Computer-Based Testing Best Practices
4. Test-Taking Strategies for Health Professionals

---

*This guide reflects current DOH computer-based testing procedures. Always verify with official DOH and Prometric sources for the most current information.*