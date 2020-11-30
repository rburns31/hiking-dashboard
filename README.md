# hiking-dashboard

Hiking Dashboard

View at: https://aha1994.github.io/hiking-dashboard/

## Spreadsheet Assumptions

1. The columns need to be in the correct order/placement.
2. The hikes need to be inserted in sorted date order with the oldest hike coming first.
3. The spreadsheet needs to be publicly viewable.

## Backend Info

The code provided in `js/backend.js` is just a point-in-time reference that is not necessarily up-to-date with the actual backend.

The backend is also written in JavaScript and is hosted on Google Scripts so that it can have more seamless connectivity with the backing data stored in Google Sheets. It can be found [here](https://script.google.com/d/1468Bk901jpIpdXxu5Gnp4i4YXXQclZyOfx4tJ6h8zcAiGCjA32OqoSxL/edit).

## Adding Users

In order to add a new user, you need to make 2 changes.

1) Add the new user to the `USERS` array at the top of the `js/logic.js` file.
2) Add the user to sheet id mapping at the top of the backend js (in Google Scripts).
