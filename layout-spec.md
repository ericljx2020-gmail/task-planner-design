# Task Planner Layout Specification

## Main Layout
- Full viewport width and height
- Dark theme with background color #121212

### Components

1. **Sidebar (56px width)**
   - Vertical navigation bar
   - Icons:
     - Tasks (✓)
     - Friends (👥)
     - Calendar (📅)
   - Profile icon at bottom (👤)
   - Background: #2a2a2a

2. **Task Panel (320px width)**
   - Header with "Tasks" title
   - Filter and Add buttons
   - Sections:
     - "Due Soon" tasks
     - "Inbox" tasks
   - Task cards:
     - Checkbox
     - Title
     - Due date and duration
     - Background: #2a2a2a
     - Hover: #333333

3. **Calendar (Flexible width)**
   - Header:
     - Month/Year display
     - Date picker
     - Navigation arrows
   - Week view:
     - Days of week header
     - Time slots (24 hours)
     - Hour labels on left
   - Events:
     - Minimum height: 30px
     - Color-coded by category
     - Show time range
     - Checkbox for completion
     - Support for overlapping events

## Typography
- Font: Inter
- Sizes:
  - Headers: 1.5rem (24px)
  - Subheaders: 1.125rem (18px)
  - Body: 1rem (16px)
  - Small text: 0.875rem (14px)
  - Extra small: 0.75rem (12px)

## Grid System
- Hour height: 60px
- Time label width: 64px
- Column borders: rgba(255, 255, 255, 0.1)
- Row borders: rgba(255, 255, 255, 0.1)

## Interactive Elements
- Buttons:
  - Background: #2a2a2a
  - Hover: #333333
  - Border radius: 8px
- Task cards:
  - Border radius: 8px
  - Padding: 12px
  - Hover effect with slight brightness increase
- Calendar events:
  - Border radius: 6px
  - Left border accent: 4px
  - Shadow on hover
  - Scale effect on hover (1.02)