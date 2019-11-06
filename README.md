# Room-selection prototype

- For Rooms 2 and above, all Adult and Child selects should start as disabled unless the room checkbox is checked. Any room that is unchecked should return to default values (zeroed-out state).

- If the user checks the room checkbox, all rooms of lesser number should also auto-check. ie, if the user checks the 'Room 4' checkbox, Room 2 and Room 3 should auto-check.

- If the user unchecks the room checkbox, all rooms of higher number should auto-uncheck. ie, if the user unchecks the 'Room 3' checkbox, Room 4 should auto-uncheck.

- Bootstrapped with `create-react-app`.
- User data is persisted across page loads using localStorage.
- On Submit, user data is displayed on the page, and form state is printed to console.
- 7 unit tests written with `jest`, `@testing-library/react` and `jest-dom`
- Deployed to URL https://react-rooms.aarnadlr.now.sh/ via Zeit Now.

