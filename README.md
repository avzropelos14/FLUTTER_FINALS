Guitar Haven - E-commerce UI Project

Student Name: Ropelos, Angelo V.
Student ID:2023-2110078

---

Project Description

**Guitar Haven** is intended to offer a targeted and easy-to-use platform for guitar purchases. Users may explore a selection of guitars, examine comprehensive product information, and add goods to a shopping cart for purchase with ease thanks to the app's simple and user-friendly interface.

In contrast to other online shopping apps, Guitar Haven is designed with guitar enthusiasts in mind, providing a simplified user experience with features that emphasize product images, details, and usability. The project demonstrates how Flutter can be used practically to create cross-platform applications and demonstrates how graphical user interface programming can be used to create practical solutions.

This project focuses on implementing UI/UX design principles using Flutter and demonstrates the application of navigation, layout structuring, and state handling—all using mock data without backend integration.

---
  
Home/Product Listing Screen 
1. Home Screen<br><br>
**Main Purpose**<br>
  - Serves as the app's landing page, welcoming users and showcasing guitar products. <br><br>
**Key UI Elements**<br>
  - App logo and welcome banner
  - Featured product carousel or grid view
  - Navigation bar (Home, Shop, Cart)<br><br>

2. Product Screen Detail<br><br>
**Main Purpose**
  - Displays the details of the selected item. <br><br>
**Key UI Elements**
  - High-resolution product image
  - Product name, price, and description
  - “Add to Cart” button
  - "Color" select button
  - "Quantity" button

3. Cart Screen<br><br>
**Main Purpose**
  - Edit and manage items users have added to their cart.<br><br>
**Key UI Elements**
  - Quantity adjustment controls
  - Total price calculation
  - “Checkout” button

4. Checkout Screen <br>br>
**Main Purpose**
  - Confirms selected products and final total price.<br><br>
**Key UI Elements**
  - Order summary
  - Thank you/confirmation message

---

Unique Design Choices & Creativity

**Niche**
- By concentrating solely on guitars, we were able to customize the user experience for guitarists and guitar fans.  Our use of guitar-related images and product presentation style was all impacted by this niche.

Color Palette
- Our color palette reflects the natural materials of guitars — mainly brownish tones, khaki, and white — to evoke a warm, wooden, and musical feel.

Typography
- A mix of bold sans-serif fonts for headings (to capture attention) and clean, readable fonts for body text.

Iconography & Branding
  - Used custom guitar-themed icons (e.g., shopping cart and home icons) to reinforce the app’s branding.

---

Challenges Faced & Solutions

1. Dynamic List Rendering and State Management
Problem: Managing product data across different screens without a backend.
Solution: We used a simple in-memory list with stateful widgets to hold product data. Flutter’s `setState()` was used to update UI when items were added or removed from the cart.

2. UI Consistency Across Devices
Problem: Ensuring the UI looked good on different screen sizes and orientations.
Solution: We used `MediaQuery`, `Flexible`, and `Expanded widgets` to build a responsive layout.

---

Guitar Haven Demo Video
- https://drive.google.com/file/u/0/d/1A48fcAkuT9g0204i65vYeRY6vp9Epjz2/view?usp=classroom_web
