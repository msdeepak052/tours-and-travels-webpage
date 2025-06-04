# DK Tours and Travels - Java Web Application

![DK Tours Banner](/images/banner.jpg)

A colorful, responsive tours and travels web application built with Java, Spring Boot, and Maven.

## Features

- 🎨 **Vibrant Color Theme**: Coral, teal, and yellow accent colors on white background
- 📱 **Fully Responsive**: Works on all device sizes
- ✨ **Modern UI Elements**:
  - Animated cards and buttons
  - Floating promotional badges
  - Testimonials with ratings
- 📋 **Key Pages**:
  - Home with featured destinations
  - Booking management
  - Special offers section
  - Customer testimonials

## Technology Stack

- **Backend**: Java 17, Spring Boot 3.1.0
- **Frontend**: 
  - Thymeleaf templates
  - Bootstrap 5.3.0
  - Font Awesome 6.4.0
- **Build Tool**: Maven
- **Styling**: Custom CSS with vibrant color scheme

## Image Requirements

Place these images in `src/main/resources/static/images/`:

| File                | Description                          | Recommended Dimensions |
|---------------------|--------------------------------------|------------------------|
| `logo.png`          | Company logo                         | 200x200px              |
| `banner.jpg`        | Hero banner image                    | 2000x800px             |
| `destination1.jpg`  | Featured destination (e.g., Paris)   | 800x600px              |
| `destination2.jpg`  | Featured destination (e.g., Bali)    | 800x600px              |
| `hero-travelers.png`| Happy travelers image                | 800x600px              |
| `testimonial1.jpg`  | Customer testimonial photo           | 200x200px              |
| `testimonial2.jpg`  | Customer testimonial photo           | 200x200px              |
| `testimonial3.jpg`  | Customer testimonial photo           | 200x200px              |
| `favicon.ico`       | Browser tab icon                     | 32x32px                |

## Color Scheme

```css
:root {
    --primary-color: #FF6B6B;  /* Vibrant coral */
    --secondary-color: #4ECDC4;  /* Teal */
    --accent-color: #FFE66D;  /* Sunny yellow */
    --dark-color: #292F36;  /* Dark slate */
    --light-color: #F7FFF7;  /* Off-white */
    --text-color: #333333;
}

## How to Run

### Prerequisites

- **Java 17+**
- **Maven 3.8+**

### Build and Run

```bash
mvn clean install
mvn spring-boot:run

```

### Access Application
```
Open http://localhost:8080 in your browser.
```