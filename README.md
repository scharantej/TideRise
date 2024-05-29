## Flask Application Design for a Tide-Tracking Mobile App

### HTML Files

- **index.html**: The main landing page of the application. Displays a form for selecting a location and retrieving tide data.
- **tide_charts.html**: Displays tide charts for the selected location, allowing users to visualize the tide levels.
- **data_details.html**: Provides detailed information about a specific tide event, including its height, time, and type.

### Routes

- **homepage**: The route for the landing page (`/`). Handles GET requests and displays the `index.html` file.
- **get_tide_data**: The route for retrieving tide data (`/get_tide_data`). Handles GET requests with location information and returns tide data in JSON format.
- **show_tide_charts**: The route for displaying tide charts (`/show_tide_charts`). Handles GET requests with location information and displays the `tide_charts.html` file.
- **tide_details**: The route for providing detailed information about a tide event (`/tide_details`). Handles GET requests with event information and displays the `data_details.html` file.