# Reflectify User Stories

A guided journaling app for self-reflection, personal growth, and mindfulness.

---

## 1. Login & Registration

**Title:** As a user, I want to register by entering my username, email, and password, so that I can create an account.  
**Acceptance Criteria:**
1. Users can enter valid details and click “Sign Up” to create an account.
2. An error message is shown if any input is invalid or missing.  
**Story Points:** 3

**Title:** As a user, I want to log in using my email and password, so that I can access my account.  
**Acceptance Criteria:**
1. Users can log in with correct credentials and are redirected to their dashboard.
2. An error message is displayed for incorrect credentials.  
**Story Points:** 3

**Title:** As a user, I want to receive feedback when I attempt to sign up or log in without entering details, so that I can fix the errors.  
**Acceptance Criteria:**
1. Error messages are displayed for missing fields on sign-up or login attempts.  
**Story Points:** 2

**Title:** As a user, I want my details to be stored in local storage, so that my data persists between sessions.  
**Acceptance Criteria:**
1. User details are saved in local storage after registration and used for authentication during login.  
**Story Points:** 3

---

## 2. Homepage

**Title:** As a user, I want a personalized greeting with my name and a title, so that I feel welcomed and encouraged to journal.  
**Acceptance Criteria:**
1. Display “Welcome back, [username]” followed by “How are you feeling today?”  
**Story Points:** 2

**Title:** As a user, I want to see recent journal entries and prompts, so that I can quickly continue where I left off.  
**Acceptance Criteria:**
1. Display a list of recent entries with title, snippet, and date.
2. Highlight one daily journal prompt in a featured card.  
**Story Points:** 3

**Title:** As a user, I want intuitive navigation icons, so that I can easily move around the app.  
**Acceptance Criteria:**
1. Display a logo on top-left and a settings icon on top-right.
2. Provide bottom navigation with tabs: Home, Favorites, Write, Settings.  
**Story Points:** 3

---

## 3. Entry Detail Page

**Title:** As a user, I want an “About this prompt” section for each journaling prompt, so that I can understand its intention.  
**Acceptance Criteria:**
1. Display a brief explanation of the prompt and what it’s meant to explore.  
**Story Points:** 2

**Title:** As a user, I want an input field and rich-text editor, so that I can write and format my responses clearly.  
**Acceptance Criteria:**
1. Provide title input, and a multi-line text field.
2. Allow bold, italic, and bullet point formatting.  
**Story Points:** 5

**Title:** As a user, I want a “Save Entry” button, so that I can save what I’ve written.  
**Acceptance Criteria:**
1. Save entry to local storage or database.
2. Show a success message on save.  
**Story Points:** 3

**Title:** As a user, I want navigation icons for going back and sharing, so that I can easily manage the entry screen.  
**Acceptance Criteria:**
1. Display a back arrow and a share icon at the top of the screen.  
**Story Points:** 2

---

## 4. Add to Favorites

**Title:** As a user, I want to add a journal prompt to my favorites, so that I can quickly find ones I love.  
**Acceptance Criteria:**
1. Display a heart icon labeled “Add to Favorites.”
2. Outlined heart means not favorited.
3. Tapping fills heart, changes text to “Remove from Favorites.”  
**Story Points:** 3

**Title:** As a user, I want to remove a prompt from Favorites, so that I can manage my list.  
**Acceptance Criteria:**
1. Show “Remove from Favorites” and filled heart if prompt is already saved.
2. Tapping removes from list and updates icon/text.  
**Story Points:** 3

**Title:** As a user, I want a “My Favorites” screen, so that I can view and manage all saved prompts.  
**Acceptance Criteria:**
1. Show a scrollable list with title and category.
2. Allow tapping an item to view or start journaling.  
**Story Points:** 3

---

## 5. Daily Reminders

**Title:** As a user, I want to view the current month calendar, so that I can choose a journaling day.  
**Acceptance Criteria:**
1. Display month grid with days.
2. Provide arrows to navigate between months.  
**Story Points:** 3

**Title:** As a user, I want to set a date and time for a journaling reminder, so that I don’t forget to journal.  
**Acceptance Criteria:**
1. Display “Selected Date: None” and a default time (e.g. “20:44”).
2. Allow users to pick both a date and time.  
**Story Points:** 4

**Title:** As a user, I want to add a reminder after selecting a time, so that it gets saved.  
**Acceptance Criteria:**
1. Clicking “Add Reminder” saves the reminder.  
**Story Points:** 2

**Title:** As a user, I want to see all my reminders, so that I can manage or delete them.  
**Acceptance Criteria:**
1. List reminders with date and time.
2. Provide red “Delete” button beside each.  
**Story Points:** 3

---

## 6. Sharing Entries

**Title:** As a user, I want to share journaling prompts or entries with others, so that I can inspire or connect with friends.  
**Acceptance Criteria:**
1. Show a share button/icon on entry detail page.
2. Allow sharing via social media, email, or messaging apps.  
**Story Points:** 3

---

## 7. Logout

**Title:** As a user, I want a clear and visible logout button, so that I can safely sign out.  
**Acceptance Criteria:**
1. Show logout button in the Settings screen.
2. Clicking it clears session and redirects to login page.  
**Story Points:** 2

---

## 8. Theme Settings

**Title:** As a user, I want to switch between light and dark themes, so that I can reduce eye strain and personalize the experience.  
**Acceptance Criteria:**
1. Include a toggle in Settings for Light/Dark Mode.
2. Theme changes immediately on toggle without needing to restart.  
**Story Points:** 3

---

