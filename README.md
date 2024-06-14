# 📱 Know Your Government App

Welcome to the **Know Your Government** app! This Android application leverages location services, the Google Civic Information API, and social media integration to provide an interactive list of political officials representing your current or specified location.

## 📝 Description

The **Know Your Government** app helps users identify and interact with their political representatives at various levels of government. With features like dynamic location-based data retrieval, detailed official profiles, and social media links, this app aims to enhance civic awareness and engagement.

## 🚀 Features

- **Location-Based Representation**: Automatically fetches political representatives based on the device's location.
- **Manual Location Entry**: Allows users to manually enter a city/state or zip code to retrieve representative data.
- **Detailed Official Profiles**: Displays detailed information about each official, including contact information and social media links.
- **Social Media Integration**: Provides direct links to officials' social media pages (Facebook, Twitter, Google+, YouTube).
- **Image Handling**: Uses the Picasso library to load official photos, with fallback options for missing or broken images.
- **Interactive UI**: Users can click on various pieces of information to perform actions like opening maps, dialing phone numbers, or visiting websites.

## 📱 Activities

1. **MainActivity**: 
   - Displays a list of government officials representing the current or specified location.
   - Allows manual location entry and access to the About activity.

2. **OfficialActivity**: 
   - Shows detailed information about a selected official.
   - Clicking on the official's photo opens the Photo Detail activity.
   - Contact information and social media links are clickable.

3. **PhotoDetailActivity**: 
   - Displays a full-sized image of the official.
   - Only opens if the official has an image.

4. **AboutActivity**: 
   - Provides information about the application, including author, copyright, and version.

## 📦 Technologies Used

- **Java**: Core programming language for app development.
- **Android Studio**: IDE for building the application.
- **XML**: Layout and UI design.
- **Google Civic Information API**: Fetches data about political representatives.
- **Picasso Library**: Handles image loading and caching.
- **Git**: Version control for the project.

## 🛠️ Setup and Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/YourUsername/KnowYourGovernment.git
   ```
2. **Open the project in Android Studio**:
   - File -> Open -> Navigate to the cloned repository.
3. **Add your Google Civic Information API key**:
   - Obtain your API key from [Google Civic Information API](https://developers.google.com/civic-information/docs/using_api).
   - Replace `Your-API-Key` in `MainActivity.java` with your actual API key.
4. **Run the application**:
   - Ensure your development device or emulator has internet access and location services enabled.
   - Click the Run button in Android Studio.

## 📚 Usage

1. **Initial Launch**:
   - The app will request location permissions to determine your current location.
   - A list of representatives will be displayed based on your location.
   
2. **Manual Location Entry**:
   - Use the menu option to enter a city/state or zip code.
   - The list will update with officials for the specified location.

3. **View Official Details**:
   - Click on a representative to view detailed information.
   - Click on the official's photo to see an enlarged image in the Photo Detail activity.
   - Interact with contact and social media links directly from the official's profile.

4. **About Section**:
   - Access the About section from the menu to view application details.

## 🌟 Acknowledgements

- **Google Civic Information API**: For providing the data on political representatives.
- **Picasso Library**: For handling image loading and caching.



Thank you for using the **Know Your Government** app! Feel free to contribute to this project or report any issues.

---

✨ **Happy Coding!** ✨

---
