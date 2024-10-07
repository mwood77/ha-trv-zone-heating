## Root Level Changes

These files apply to your Home Assistant system, not automations. In reality, this means adding a couple system sensor, so it's easier for you to log / keep and eye on the heating automations.

### `configuration.yml`

Add the attached sensors in `configuration.yml` to create a few sensors. These:
- "HVAC Activity;" this must be added to make the other template sensors work.
- "Thermostat Heating This Week;" tracks the total amount of running time your heating has been on, this week.
- "Thermostat Heating Today;" tracks the total amount of running time your heating has been on, today.
