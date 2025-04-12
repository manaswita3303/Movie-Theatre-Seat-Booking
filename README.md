# Project Overview
This projects implements a user-friendly theatre seat booking system that allows user to select movies, show-times, and seats with an intuitive visual interface. The UI is fully responsive and adapts to different screen sizes, providing a seamless booking experience across devices.

**Live Site:** [https://tickettap.netlify.app](https://tickettap.netlify.app)

## Features
+ Interactive Seat Selection: Visual seat grid with intuitive click-to-select functionality
+ Responsive Design: Optimized for desktop, tablet, and mobile devices
+ Real-time Booking Summary: Dynamic updates of selected seats and total costs
+ Dynamic Pricing: Support for different movie prices and premium seat pricing (50% markup)
+ Visual Status Indicators: color-coded seats (available, selected, booked, premium)
+ Movies & Showtime Selection: Options to choose different movies, dates, and times
+ Booking confirmation: Modal with booking details after successful reservation
+ Accessible Design: Clear visual cues and intuitive interactions

## Implementation Details

### Core Structure
The application consists of three main components:
1. Selection Panel: for choosing movies, dates, and times
2. Seat Grid: Visual representation of the theatre with interactive seats
3. Booking Summary: Real-time display of selections and total cost

### Technical Approach

#### HTML Structure
+ Semantic HTML5 elements for improved accessibility and SEO 
+ Container-based layout for responsive design
+ Modal implementation for booking confirmation
#### CSS Styling
+ Flexbox and CSS grid for responsive layout
+  Mobile-first design approach
+ Transition effects for interactive elements
+ CSS variables for consistent colour scheme
#### Javascript Logic
1. Initialization
+ Set minimum date to today
+ Generate the seat grid dynamically
+ Initialize movie and showtime information
2. Event Handling
+ Seat selection toggle
+ Movie, date, and time change events
+ Booking confirmation
3. Dynamic Updates
+ Seat status tracking
+ Price calculation with premium seat logic
+ Selected seats display in booking summary
4. Data Management
+ Seat status simulation (can be connected to backend)
+ Booking information tracking

### Usage
1. Select a movie, date, and showtime
2. Click on available seats to select them (click again to deselect)
3. Review your selection and total cost in the booking summary
4. Click "Book Tickets" to confirm your reservation

## Future Enhancements
+ Backend integration for real seat availability
+ User authentication and booking history
+ Payment processing integration
+ Email confirmation for bookings
+ Seat recommendation based on group size
+ Accessibility improvements for screen readers

## Project Outcome
The final project delivers a complete front-end solution for theater seat booking that is both visually appealing and functionally robust. The interface is intuitive enough for users of all ages and technical abilities, while still providing all the necessary information for making booking decisions.

The responsive design ensures that the experience works well on all devices, from desktop computers to mobile phones, making it practical for real-world deployment.

Acknowledgements
+ Design inspiration from modern movie booking platforms
