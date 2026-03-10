# Health Facility Locator — Google Maps Integration

A web feature that helps users find the nearest health facilities (hospitals, clinics, laboratories, pharmacies) using Google Maps API.

## Project Status
🟡 In Progress

## Features
- [ ] Google Maps integration
- [ ] User geolocation detection
- [ ] Facility type filtering (hospital, clinic, lab, pharmacy)
- [ ] Service-based filtering (immunization, radiology, etc.)
- [ ] Facility detail cards (name, address, hours, contact)
- [ ] Mobile responsive UI
- [ ] Search by location name

## Tech Stack
- Frontend: React.js
- Maps: Google Maps JavaScript API + Places API
- Backend: Node.js / Express
- Database: MongoDB

## Setup Instructions
1. Clone the repository
2. Run `npm install`
3. Add your Google Maps API key to `.env`
4. Run `npm start`

## Folder Structure
```
src/
  components/   → UI components (Map, FilterPanel, FacilityCard)
  api/          → API calls and Google Maps integration
  utils/        → Helper functions
docs/           → Project documentation
tests/          → Unit and integration tests
```

## Contributing
All work is managed via feature branches. See TASKS.md for open tasks.
