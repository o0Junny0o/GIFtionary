## Giftionary - A Simple GIF App 

This project is a basic Android application called Giftionary that fetches GIFs from the Giphy API and displays them in a grid layout.
Features

    Fetches trending GIFs from Giphy API.
    Displays GIFs in a grid layout using RecyclerView.
    Clicking on a GIF opens a new activity to view the full image.

Dependencies

This application uses the following libraries:

    Retrofit: Used for making network calls to the Giphy API.
    Gson: Used for parsing JSON data received from the API.
    RecyclerView: Used for displaying GIFs in a scrollable grid layout.
    Glide (not included in this example): You can optionally integrate Glide for efficient image loading and caching.

Architecture

The app uses a simple architecture:

    MainActivity: Fetches trending GIFs from the Giphy API, displays them in a RecyclerView, and handles user interactions.
    DataObject: Represents a single GIF object with relevant information (URL, title, etc.).
    DataResult: Represents the response object from the Giphy API containing a list of GIFs.
    DataService: Interface defining the API call to retrieve trending GIFs.
    GifsAdapter: Manages the RecyclerView adapter, displaying GIFs and handling click events. (SecondActivity not included in this example)

Future Improvements

    Implement error handling for network failures.
    Add functionality to search for specific GIFs.
    Improve UI design and user experience.

Preview

![Print_Gifdictionary](https://github.com/user-attachments/assets/24f10651-948d-4a47-9ad3-d8afb30bf26e)
