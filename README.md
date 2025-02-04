# Backend
This repository reflects the development and production of the back-end logic for the PowerHouse application.

## TODO
- Create and manage FastAPI endpoint
- Deal with async uptime function and make sure it works
  - Make sure to reset uptime every 24 hours
  - After 24 hours add up all the energy and store it in database
- Function for toggling devices (setting status to on or off)
- Change names of devices according to ID
- Implement a cache for profile settings
- Implement energy conservation tips based on uptime
- Automation scheduling (More details TBD)
- Add IP address attribute to each device
## - Set up Google OAuth2 for authentication (Highest Priority)