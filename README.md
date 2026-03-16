# Smart Event Dashboard

A simple **Smart Event Dashboard** built using **HTML, CSS, and Vanilla JavaScript**.  
The application allows users to create, manage, search, edit, and delete events dynamically using DOM manipulation.

Events are stored in **localStorage**, so they remain saved even after refreshing the page.

Website: https://smart-event-dashboard-apurvamarya.vercel.app/

---

## Features

- Add new events with:
  - Event Title
  - Event Date
  - Category
  - Description
- Edit existing events
- Delete individual events
- Clear all events
- Add sample events
- Search events by title
- Events automatically sorted by date
- Persistent data storage using **localStorage**
- Clean and responsive UI

---

## Tech Stack

- **HTML5** – Page structure
- **CSS3** – Styling and layout
- **Vanilla JavaScript** – DOM manipulation and event handling
- **LocalStorage API** – Data persistence

---

## Project Structure

smart-event-dashboard
│
├── index.html # Main HTML structure
├── style.css # Styling for the dashboard
├── script.js # Application logic
└── README.md # Project documentation


---

## How It Works

### 1. Add Event
Users enter event details and click **Add Event** to create a new event card.

### 2. Event Rendering
JavaScript dynamically creates event elements and displays them in the **My Events** section.

### 3. Search Events
The search bar filters events by title in real time.

### 4. Edit Event
Click **Edit** to load the event details back into the form and update them.

### 5. Delete Event
Click the **red X button** to remove an event.

### 6. Clear All Events
Removes all events from the dashboard.

### 7. Data Persistence
All events are stored in **localStorage**, allowing them to remain after page reloads.

---

