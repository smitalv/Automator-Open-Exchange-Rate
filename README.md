# Automator-Open-Exchange-Rate

This quick action for Automator allows you to convert between any currencies. Open Exchange Rates API is used to retrieve up to date rates. USD is used as an intermediary currency.

# Configuration steps

- Create an account on https://openexchangerates.org/signup/free (1000 calls per month is a current limit as of 07/2021 and no credit card is required)
- Get your App ID on https://openexchangerates.org/account/app-ids
- Download provided script
- Modify it up to your needs in Automator
  - Insert your App ID to the desiganted place
  - Replace your default currencies in an array called **currencies**
- Install it
- Open **System Preferences** - **Keyboard** - **Shortucts** - **Services**
- Configure shortcuts for your new workflow
