# ALX Travel App 0x00

This project is a travel app API built with Django, featuring models for Listings, Bookings, and Reviews. The app also includes serializers for API data representation and a management command to seed the database with sample data.

---

## Features

1. **Models**:

   - **Listing**: Represents travel listings (e.g., vacation rentals).
   - **Booking**: Represents user bookings for specific listings.
   - **Review**: Represents user reviews and ratings for listings.

2. **Serializers**:

   - Convert Django models (`Listing` and `Booking`) into JSON format for API responses.

3. **Database Seeder**:
   - Populates the database with sample data using a custom management command.
