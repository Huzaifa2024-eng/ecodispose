# EcoDispose — E-Waste Disposal Prototype

## Project summary
EcoDispose is a student-built web prototype that demonstrates a digital workflow for recording electronic waste disposal requests, exploring disposal options, and tracking sample request statuses.

## Run locally
1. Extract `ecodispose_project.zip`.
2. Open `index.html` in a modern browser.
3. Submit a sample request and test the dashboard, filters, status controls, and CSV export.

No installation or internet connection is required for the core demo.

## Input → Processing → Output
- **Input:** device category, quantity, condition, locality/area, preferred disposal method, optional notes.
- **Processing:** browser-side validation, item categorization, unique demo request ID generation, request storage, filtering, and summary calculations.
- **Output:** request confirmation, dashboard totals, status tracking, and CSV export.

## Technologies
- HTML5: page structure and forms.
- CSS3: responsive layout and styling.
- JavaScript: validation, request workflow, filtering, status updates, dashboard totals, CSV export.
- Browser `localStorage`: stores demo requests locally on the same browser/device.

## Data and sources
The prototype uses user-entered sample data and does not connect to live sensors, official databases, GPS, or real recyclers. Collection option cards are generic categories, not verified business listings. In a real deployment, collection-center information should be checked against official government pollution-control/recycler directories and providers.

## Expected environmental benefits
1. Encourages proper collection instead of disposal with ordinary waste.
2. Helps prevent improper e-waste handling that can contaminate soil and water.
3. Supports material recovery and reuse through appropriate recycling channels.
4. Makes disposal options and request status easier to understand.
5. Can improve awareness and participation in responsible e-waste management.

## Limitations and safety
- This is a prototype, not a live collection service.
- Data stays in browser local storage; it is not sent to a server and is not shared across devices.
- Status changes are manual and do not verify that collection occurred.
- Use fictional information when demonstrating it.
- Do not dismantle electronics or puncture batteries; follow local safe-handling guidance.

## Suggested architecture
User → Web form (HTML/CSS) → JavaScript validation and categorization → Browser localStorage → Dashboard / status tracker / CSV export.
