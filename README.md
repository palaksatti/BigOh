BigOh App – Image Gallery and Form Submission

📱 Key Features: Image Gallery with Search Capability:

Endless Scrolling: Fetches high-quality images from Unsplash API with a smooth scroll and pagination. Search Images by Keyword: Allows users to search for specific images using Unsplash’s extensive library. Image Caching: Utilizes SDWebImage for efficient image caching, ensuring a smooth and responsive user experience. User-friendly Loader: Integrated SVProgressHUD loader for a seamless data-fetching experience. TabBar Navigation:

Switch between the Image Gallery and a Form Submission view via the Tab Bar, providing easy navigation across app features. Form Submission with Animation:

Interactive Form: A simple form where users input data with clear validations. Lottie Animations: Upon submission, users are greeted with a visually engaging success animation via the Lottie library. Gradient Button: A gradient effect is applied to the Submit button, making the interface more modern and appealing. Image Collection View:

Grid Layout: Displays images in a 2-column grid layout with responsive cell sizes, ensuring optimal display across different devices.

🛠️ Technologies & Libraries Used: UIKit: For building the user interface and interactions. SVProgressHUD: To show a smooth loading indicator while fetching images from the Unsplash API. SDWebImage: For seamless image loading and caching to enhance performance. Lottie: To integrate engaging animations into the form submission flow. CAGradientLayer: To add gradient effects to the buttons and UI elements.

🚀 Application Flow: On App Launch:

The user lands on the Image Gallery screen, where high-quality images are fetched and displayed in a grid. Pagination ensures continuous loading of images as the user scrolls. Searching for Images:

Users can enter a keyword in the Search Bar to search for specific images. If no images are found for a keyword, an alert prompts the user to try again with another search term. Tab Navigation:

Using the Tab Bar, the user can switch to the Form Submission screen. Form Submission:

Users can enter their name and submit the form. If the name is missing, an alert reminds them to fill in the field. Upon successful submission, a Lottie animation plays to indicate success, creating an engaging user experience. Error Handling:

If the images fail to load (due to a network error or other issues), a friendly alert informs the user, maintaining clear communication and guidance.

🖥️ Installation To run the project locally: Clone the repository. Open the project in Xcode. Make sure to have the required CocoaPods libraries installed: pod install Run the app on your preferred simulator or device.
