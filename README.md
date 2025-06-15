# CalendarBuddy

An AI-powered calendar assistant that retrieves and announces upcoming events in a conversational, user-friendly manner. Designed to help users stay informed about their schedule without constantly checking their calendar.

## Features

- **Event Retrieval:** Fetches events from Google Calendar for today and tomorrow.
- **Announcement Modes:**
  - **Manual Mode:** Instantly announces upcoming events with a button press.
  - **Scheduled Announcements:** Runs at fixed times (9 AM for today, 6 PM for tomorrow).
  - **Event-Specific Reminders:** Checks every 15 minutes for events starting soon.
- **Smart Filtering:** Includes relevant events while excluding those that have already started or been announced.
- **Voice-Only, No UI:** CalendarBuddy has no graphical user interface. All interaction is through voice—events are announced via text-to-speech (TTS) only.

## How It Works

1. **Background Fetching:**  
   The system fetches events from Google Calendar once or twice daily and stores them locally to minimize API calls.

2. **Event Announcements:**  
   Events are announced via text-to-speech (TTS), providing a conversational and easy-to-understand summary of upcoming events.

3. **Automation:**  
   Triggered at scheduled times as well as manually, ensuring timely and relevant announcements.



## Usage



## Acknowledgments

- I made this for my mum who has dementia, but I now use it myself as my favourite way to know about what upcoming events I need to know about.
