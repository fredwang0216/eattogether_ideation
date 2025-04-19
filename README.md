# EatTogether App Prototype

EatTogether is a mobile application that connects users for shared dining experiences with strangers based on their availability, location preferences, and restaurant choices.

## Prototype Overview

This high-fidelity prototype has been created using HTML, CSS, and JavaScript and includes all the core features of the application. It's designed to be fully interactive, providing a realistic user experience.

### Design Update
This updated version features a streamlined 3-step meal planning process and enhanced matching preferences, allowing users to specify gender and age preferences for better compatibility.

## Features

1. **3-Step Meal Planning**:
   - **When**: Set date, choose from primary meal options (lunch, dinner) or secondary options (breakfast, brunch, afternoon tea), and select time
   - **Where**: Choose from saved locations or explore new areas
   - **Who**: Define group size, gender preference, and age range
   
2. **Default Preference Settings**: Save matching preferences in your profile for quicker meal planning
   
3. **Location Management**: Save frequently used locations and search for new ones
   
4. **Explore Available Meetups**: Browse existing dining opportunities with other users

5. **Get Notifications**: Receive notifications for match requests, confirmed bookings, and other alerts

6. **Manage Profile**: Set dining preferences, matching preferences, and personal information

## Pages

### Home Page (home.html)
- Quick access buttons for setting meal availability
- Overview of the 3-step process
- Display of upcoming matches
- Recent notifications
- User representation via icons instead of profile pictures

### Availability Page (availability.html) - Step 1: When
- Progress indicator showing the 3-step process
- Date picker for selecting available dates
- Meal type selection (breakfast, lunch, dinner)
- Time selection

### Location Selection Page (location-selection.html) - Step 2: Where
- Map view showing nearby locations
- Saved locations list
- Search functionality for finding new locations

### Matching Preferences Page (matching-preferences.html) - Step 3: Who
- Group size preference
- Gender preference options
- Age range selection using dual sliders
- Option to save preferences as defaults

### Restaurant Selection Page (restaurant-selection.html)
- Map view showing nearby restaurants in Singapore
- List view with restaurant details
- Filters for cuisine type, distance, and price
- Featured restaurant: UNA, a Michelin Guide Spanish restaurant at The Alkaff Mansion

### Profile Page (profile.html)
- Personal information
- Matching preferences section (group size, gender, age range)
- Dining preferences (cuisine types, dietary restrictions)
- App settings and preferences
- Generic user icon instead of profile picture

### Notifications Page (notifications.html)
- Match notifications with details
- Action buttons to accept/decline invitations
- Message notifications and system alerts
- User icons instead of avatars for privacy

### Explore Page (explore.html)
- Map view showing available dining options
- List view of all available meals
- Filtering by date and meal type
- Join functionality for existing tables
- User counts instead of profile pictures

## How to Use the Prototype

1. **Access the Prototype**: Open `index.html` in a web browser to start.

2. **Navigation**: Use the bottom navigation bar to move between main sections of the app:
   - Home
   - Explore
   - Availability
   - Notifications
   - Profile

3. **Plan a Meal in 3 Steps**:
   - **Step 1**: Select date, meal type (with lunch and dinner as primary options), and time
   - **Step 2**: Choose a location (saved or new)
   - **Step 3**: Set matching preferences (group size, gender, age range)
   - Then select restaurants and finalize

4. **Save Default Preferences**: Configure default matching preferences in the profile section to streamline future meal planning

5. **Explore Available Meals**:
   - Browse the Explore page to see dining options
   - Toggle between map and list views
   - Filter by date and meal type
   - Click "Join this Table" to request to join

6. **Manage Notifications**:
   - Check notifications for matches and requests
   - Accept or decline match invitations
   - View message notifications

7. **Edit Profile**:
   - Update personal information
   - Set matching preferences (group size, gender, age range)
   - Configure dining preferences and dietary restrictions
   - Configure app settings

## Technical Implementation

This prototype uses:
- HTML5 for structure
- CSS3 for styling with custom properties for theming
- JavaScript for interactivity
- FontAwesome for icons and user representation
- Mapbox for map functionality
- Responsive design for mobile-first approach

## iOS App Development

This prototype is ready for iOS development. The structure and UI components follow iOS design guidelines and can be easily translated to Swift or React Native code.

Key considerations for developers:
- Follow the established color scheme and typography
- Implement real map functionality using iOS MapKit or Google Maps SDK
- Connect to a backend for user authentication and data persistence
- Implement push notifications for real-time alerts
- Use native iOS UI components for optimal performance
- Maintain privacy-focused design with no profile pictures

## Future Enhancements

Potential enhancements for the full application:
- Chat functionality for users before and after meals
- Integration with restaurant reservation systems
- User ratings and reviews for restaurants and dining experiences
- Advanced matching algorithms based on dining preferences and social compatibility
- Event creation for themed dining experiences
