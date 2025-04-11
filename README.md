# Pawsitive Futures Website

## Project Overview
The **Pawsitive Futures Website** is a responsive and user-friendly platform designed and created by me, Javier Pachano, to promote pet adoption, fostering, donations, and volunteering opportunities. It aims to connect animal lovers with pets in need, providing a seamless experience for users to explore adoption profiles, learn about fostering, donate to the cause, and participate in events.

Below is a list of all the images (JPG files) used in the project and my opinions.

---

1. **Wireframing**: Created a basic wireframe to outline the structure of the website, including the homepage.
2. **Content Organization**: Organized the content into logical sections to ensure clarity and ease of navigation.
3. **Created my personal template**: Created the index.html page first using almost all the resources necesary for the creation of all pages.

### Development
1. **HTML Structure**: Built the HTML structure for one page, then copied it and went full Gung-ho editing and recreating all of it.
2. **Styling**: Used Bootstrap for responsive design and custom CSS for branding consistency.
3. **Interactivity**: Incorporated forms for user input (e.g., adoption applications, volunteer sign-ups) and ensured proper redirection to a "Thank You" page.
4. **Testing**: Tested the website on multiple devices and browsers to ensure responsiveness and functionality, then proceeded to send it to different family members for testing in different mobile devices and OS

---

## Challenges and Solutions
### Challenge 1: **Form Submission Not Redirecting**
- **Problem**: The forms were not redirecting to the `thankyou.html` page due to browser restrictions when testing locally.
- **Solution**: Switch to a method="get"and worked perfectly.

### Challenge 2: **Responsive Design**
- **Problem**: Ensuring the website looked good on all screen sizes, especially for sections with multiple images and text.
- **Solution**: Used Bootstrap's grid system (`row-cols-*` classes) to create responsive layouts that adapt seamlessly to different devices.
-**My opinion**: Such a powerful tool should be taught sooner! What a way to help programmers with responsive design! Just amazing.

### Challenge 3: **Consistent Navigation**
- **Problem**: Maintaining consistent navigation across all pages while linking to the correct files.
- **Solution**: Carefully reviewed and updated all `href` attributes in the navbar and footer to ensure proper linking.

### Challenge 4: **Navigation Menu/Footer**
- **Problem**: The menu was not responding and didn't react to user input.
- **Solution**: Used <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script> (Popper) and it solved all issued.

### Challenge 5: **ALL OF IT**
- **Problem**: Being real though, everything was so difficult the first 24 hours, once I deciphered how it works, it was smooth sailing.
- **Solution**: Bang.Head.Againts.Monitor.

---

## Lessons Learned
1. **Responsive Design Techniques**: Gained a deeper understanding of Bootstrap's grid system and how to create layouts that adapt to various screen sizes, also the logic behind Bootstrap even though is definetly not perfect.
2. **Debugging Skills**: No one likes to bang their head againts the keyboard, but debugging literally taught me more than all the research on the web combined.
4. **Project Organization**: Learned the importance of organizing assets for better maintainability, naming conventions are waaaay more important that we give it credit for.

---

## Assets and Resources
### Frameworks and Libraries
- **Bootstrap 5.3.2**: Used for responsive design and prebuilt components.
- **Popper.js**: Included for Bootstrap's interactive components.

### Fonts
- **Google Fonts**: 
  - [Poppins](https://fonts.google.com/specimen/Poppins): Used for a clean and modern typography style.


### Tools
- **Visual Studio Code**: Used as the primary code editor.
- **Live Server Extension**: Used for local testing of form submissions.

---


## Acknowledgments
Special thanks to my Web Development teacher, it has been an absolute honor to be guided by him. Also the creators of Bootstrap and Google Fonts for providing free and accessible resources that made this project possible.

---

All images are provided by www.freepik.com

My personal premium license is used for the adquisition of the images utilized in this project, which allows me full use and edit of said images https://support.freepik.com/s/article/What-are-Freepik-Premium-licenses?language=en_US

## Images Used

### **Home Page (index.html)**
1. `images/dogs sleeping.jpg` - Sleeping dogs image in the "Dogs" section.
2. `images/cats together.jpg` - Two cats sitting together in the "Cats" section.
3. `gallery-C/home-second.jpg` - Dogs hugging image in the fostering section.
4. `gallery/gallery1.jpg` - Gallery image 1 in the donation section.
5. `gallery/gallery2.jpg` - Gallery image 2 in the donation section.
6. `gallery/gallery3.jpg` - Gallery image 3 in the donation section.
7. `gallery/gallery4.jpg` - Gallery image 4 in the donation section.
8. `gallery/gallery5.jpg` - Gallery image 5 in the donation section.
9. `gallery/gallery6.jpg` - Gallery image 6 in the donation section.
10. `gallery-C/home-third.jpg` - Dogs litter image in the adoptable pets section.
11. `gallery-B/7.jpg` - Ned's profile image in the adoptable pets section.
12. `gallery-B/8.jpg` - Jon's profile image in the adoptable pets section.
13. `gallery-B/9.jpg` - Davos's profile image in the adoptable pets section.
14. `gallery-B/10.jpg` - Jamie's profile image in the adoptable pets section.
15. `gallery-B/11.jpg` - Cersei's profile image in the adoptable pets section.
16. `gallery-B/12.jpg` - Stannis's profile image in the adoptable pets section.

---

### **Adoption Page (adoption.html)**
1. `gallery-C/adoption-second.jpg` - Paperwork image in the "Application Review" section.
2. `gallery-C/adoption-third.jpg` - Meet and greet with a dog image in the "Meet & Greet" section.
3. `gallery-C/adoption-fourth.jpg` - Home visit image in the "Home Visit/Interview" section.
4. `gallery-C/adoption-fifth.jpg` - Person holding a pug image in the "Adoption Agreement" section.

---

### **Foster Page (foster.html)**
1. `gallery-C/Foster-first.jpg` - Dogs image in the first image section.
2. `gallery/C.jpg` - Sleeping dogs image in the gallery section.
3. `gallery/D.jpg` - Two cats sitting together image in the gallery section.
4. `gallery-C/Foster-second.jpg` - Dogs image in the second image section.

---

### **Donate Page (donate.html)**
1. `gallery-D/ontetimedonation.jpg` - One-time donation image in the donation options section.
2. `gallery-D/monthlypartner.jpg` - Monthly paw partner image in the donation options section.
3. `gallery-C/donation-first.jpg` - Dogs image in the "Be the Hero They Need" section.
4. `gallery-C/donation-second.jpg` - Dogs image in the "How Your Donation Helps" section.

---

### **Events Page (events.html)**
1. `gallery-C/events-first.jpg` - Dogs hugging image in the "Charity Walk" section.
2. `gallery-C/events-second.jpg` - Dogs at a pet-friendly event image in the "Bark & Brew" section.

---

### **Contact Us Page (contact-us.html)**
1. `gallery-C/contact-us.jpg` - Dogs hugging image in the hero section.

---

### **Thank You Page (thankyou.html)**
1. `gallery-C/thank-you.jpg` - Happy dog with message.

---