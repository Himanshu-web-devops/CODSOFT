# CODSOFT

## Internship task of CodSoft

## This is my First task of internship in which I design a Landing page with the help of html and css..

which consist following things ..

- **Semantic HTML5 Structure**: 
  - Use of `<header>`, `<nav>`, `<section>`, and `<footer>` tags for improved readability and accessibility.

- **Responsive Design**: 
  - Container class with a max-width of 1200px and a 90% width for consistent centering and adaptability to different screen sizes.

- **Modern Aesthetic**: 
  - Clean and simple design with a consistent color scheme and typography.

- **Dark Header and Footer**: 
  - Contrasting dark background with white text to create visual separation from the content sections.

- **Hero Section**: 
  - Prominent welcome message with a dark background.
  - Large heading, descriptive paragraph, and a highlighted call-to-action button.

- **Features Section**: 
  - Display of key features in card-like boxes.
  - Each feature box includes a heading, descriptive text, and subtle shadow and border-radius for a polished look.

- **Interactive Elements**: 
  - Hover effects on navigation links and call-to-action button for enhanced user interactivity.

- **Consistent Spacing and Layout**: 
  - Padding, margins, and line-height adjustments to ensure a cohesive and easy-to-read layout.

- **CSS Styling**: 
  - External CSS file (`LandingPage.css`) to maintain separation of concerns and facilitate styling changes.

These points highlight the main design considerations and techniques used to create the landing page, focusing on aesthetics, functionality, and user experience.


## Second task of internship creating My Portfolio with the help of Html and Css.

which consist following things ..

## Certainly! Here is a detailed explanation of how the portfolio was created and the technologies used:



1. **HTML Structure:**
   - I started by creating the basic structure of the portfolio using HTML5. The document is organized with semantic tags like `<header>`, `<section>`, `<main>`, and `<footer>`, making it easy to navigate and maintain.
   - The header includes a logo and a navigation bar with links to different sections of the portfolio.
   - Each section (Home, About, Skills, Projects, and Contact) is clearly defined with appropriate content.

2. **CSS Styling:**
   - To enhance the visual appeal of the portfolio, I used CSS3 for styling.
   - The CSS file is linked in the `<head>` section of the HTML document. It defines styles for the entire portfolio, including layout, colors, fonts, and responsiveness.
   - I used Flexbox to create a flexible and responsive layout, ensuring that the portfolio looks great on all devices.
   - Background colors and gradients were applied to create a visually appealing design. For instance, the Home section uses a linear gradient background.
   - Custom styles were applied to various elements, such as the navigation links, buttons, and images, to make the portfolio look polished and professional.

3. **Responsive Design:**
   - Ensuring that the portfolio is responsive was a key focus. I used media queries to adjust the layout and styles for different screen sizes.
   - The navigation bar is designed to be user-friendly on both desktop and mobile devices, with a fixed position to stay at the top of the page.
   - Images and text are resized and repositioned based on the screen size to provide a seamless viewing experience.

4. **Icon Integration:**
   - I integrated icons from Boxicons by linking the Boxicons CSS in the `<head>` section.
   - These icons are used for social media links in the Home section, adding a touch of professionalism and interactivity.

5. **Content Organization:**
   - The content is organized into sections for easy navigation. Each section includes headings and text that describe my skills, experience, and projects.
   - The Home section includes a brief introduction and social media links.
   - The About section provides a detailed description of my background and expertise.
   - The Skills section lists my key skills in a visually appealing manner.
   - The Projects section showcases a sample project with an image and description.
   - The Contact section provides my email and phone number, making it easy for visitors to get in touch.

### Technologies Used

1. **HTML5:**
   - Used for creating the structure and content of the portfolio.
   - Semantic tags ensure that the document is well-organized and accessible.

2. **CSS3:**
   - Used for styling the portfolio and making it visually appealing.
   - Flexbox for layout and responsiveness.
   - Media queries for responsive design.
   - Custom styles for buttons, navigation links, and other elements.

3. **Boxicons:**
   - Used for integrating high-quality icons in the portfolio.
   - Enhances the visual appeal and functionality of social media links.

### Conclusion

Creating this portfolio involved a combination of HTML5, CSS3, and Boxicons to build a responsive and visually appealing web page. The focus was on creating a clean and professional design that effectively showcases my skills and projects while providing a great user experience across all devices.


### Third task of My  Internship to creating a Calculator with the help of Html Css and java Script ..


which consist following things ..

### How I Created My Calculator

1. **HTML Structure:**
   - I started by creating the HTML structure for the calculator. The HTML document includes a `<head>` section with metadata and links to the CSS file and a JavaScript file.
   - The body of the HTML document contains a `div` element with the class `calculator`. Inside this `div`, there is another `div` with the class `display` for showing the current input and result.
   - Below the display, there is a `div` with the class `buttons` that contains the calculator buttons. Each button has an `onclick` attribute to call corresponding JavaScript functions when clicked.

2. **CSS Styling:**
   - I used CSS to style the calculator and make it visually appealing.
   - The CSS file is linked in the `<head>` section of the HTML document.
   - I set the body to use Flexbox for centering the calculator on the page and gave it a dark background color.
   - The calculator itself is styled using Grid layout to organize the buttons and display. It has a background color, padding, border-radius, and box-shadow to create a modern look.
   - Each button is styled with background colors, font sizes, padding, and border-radius. Different colors are used for operator buttons and the equals button to distinguish them from number buttons.

3. **JavaScript Functionality:**
   - I added interactivity to the calculator using JavaScript, which is linked at the end of the body section.
   - The JavaScript code defines variables to keep track of the current input, the chosen operator, and the previous input.
   - The `appendNumber` function is used to add numbers to the current input. It checks if the current input is '0' and replaces it if the new input is not a decimal point.
   - The `chooseOperator` function sets the chosen operator and stores the current input as the previous input.
   - The `calculate` function performs the chosen arithmetic operation based on the stored operator and inputs. It updates the current input with the result.
   - The `clearDisplay` function resets all inputs and the operator.
   - The `deleteLast` function removes the last character from the current input.
   - The `updateDisplay` function updates the content of the display `div` to show the current input.

### Technologies Used

1. **HTML5:**
   - Used to create the structure and content of the calculator.
   - The document includes semantic tags and attributes to define the layout and functionality.

2. **CSS3:**
   - Used for styling the calculator and making it visually appealing.
   - Flexbox is used to center the calculator on the page.
   - Grid layout is used to organize the buttons and display within the calculator.
   - Custom styles are applied to buttons and the display to create a modern look.

3. **JavaScript:**
   - Used to add interactivity and functionality to the calculator.
   - Functions are defined to handle number input, operator selection, calculations, clearing the display, deleting the last input, and updating the display.
   - The `onclick` attributes in the HTML buttons call these JavaScript functions to perform the necessary operations.

### Conclusion

Creating this calculator involved using HTML5, CSS3, and JavaScript to build a functional and visually appealing web-based calculator. The focus was on creating a clean and modern design, ensuring that the calculator is easy to use and responsive to user interactions. The combination of these technologies allowed me to deliver a fully functional calculator that performs basic arithmetic operations and provides a good user experience.
