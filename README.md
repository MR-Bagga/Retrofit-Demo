
# Retrofit Demo
This is a simple Android app demonstrating the use of Retrofit library to consume a RESTful API. The app fetches and displays a list of albums and allows uploading a new album.

# Pre-requisites
Android Studio\
Retrofit library\
Gson library\
OkHttp Logging Interceptor

# Libraries used
Retrofit - A type-safe HTTP client for Android and Java.\
Gson - A Java library that can be used to convert Java Objects into JSON format.\
OkHttp Logging Interceptor - A logging interceptor for OkHttp that logs HTTP requests and responses.\
# Code Structure
The app has the following main components:

Model Classes - Album, AlbumItem\
API Service Interface - AlbumService\
Retrofit Instance - RetrofitInstance\
Main Activity - MainActivity\

# Model Classes
Album and AlbumItem classes represent the data structure for albums. Album is a list of AlbumItem objects.

# API Service Interface
AlbumService is an interface that defines the API endpoints for fetching and uploading albums. It uses Retrofit annotations to describe the API endpoints.

# Retrofit Instance
RetrofitInstance creates and configures the Retrofit instance with the base URL, OkHttp client, and Gson converter factory.

# Main Activity
MainActivity initializes the Retrofit service, fetches albums using the service, and displays them in a TextView. It also demonstrates uploading a new album using the service.

# How to run the app
Clone the repository.\
Open the project in Android Studio.\
Run the app on an emulator or a physical device.
