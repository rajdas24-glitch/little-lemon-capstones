Little Lemon API Endpoints for Peer Review

Authentication Endpoints (Djoser):
* POST /auth/users/ (Create a new user)
* POST /auth/token/login/ (Generate authentication token)
* POST /auth/token/logout/ (Destroy authentication token)

Menu API Endpoints:
* GET /api/menu-items/ (List all menu items)
* POST /api/menu-items/ (Create a new menu item)
* GET /api/menu-items/<id>/ (View a single menu item)
* PUT/PATCH /api/menu-items/<id>/ (Update a menu item)
* DELETE /api/menu-items/<id>/ (Delete a menu item)

Table Booking API Endpoints:
* GET /api/bookings/ (List all table reservations - Requires Authentication)
* POST /api/bookings/ (Create a new table reservation - Requires Authentication)
* GET /api/bookings/<id>/ (View a single reservation - Requires Authentication)
* DELETE /api/bookings/<id>/ (Cancel a reservation - Requires Authentication)