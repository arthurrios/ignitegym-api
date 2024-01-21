# IgniteGym 2.0
## The App
Manage your gym exercises and routine with IgniteGym. Register the exercises you've done in your history and get notified about your progress.

### Previews
<div style="display: flex; gap: 0.5rem; flex-direction: column">
<div style="display: flex; gap: 0.5rem">
  <img height="560" alt="" title="" src="./assets/logIn.png">
  <img height="560" alt="" title="" src="./assets/home.png">
</div>
<div style="display: flex; gap: 0.5rem">
  <img height="560" alt="" title="" src="./assets/profile.png">
  <img height="560" alt="" title="" src="./assets/exercise.png">
</div>
<div style="display: flex; gap: 0.5rem">
  <img height="560" alt="" title="" src="./assets/history.png">
</div>
</div>

### Techs
1. React Native
2. React
3. Typescript
4. Native Base
5. Phosphor Icons
6. React Hook Form
7. Yup
8. OneSignal

### Functions
- Add exercises to history:
- Edit profile
- Push Notifications (UserTags):
  - `days_since_last_exercise`: `'number'`
  - `exercises_done_last_week`: `'number'`
  - `is_logged_in`: `'true'` or `'false'`


### Steps
1. Clone this repository;
2. Run your preferred command to install dependencies:
- `npm install`
3. Run database seed:
- `npm run seed`
4. Run the app with:
- `npm run dev`
5. Clone the frontend repository and follow its steps:
[Frontend](https://github.com/arthurrios/ignitegym-mobile)