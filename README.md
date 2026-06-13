 WEDO5020-POE-
Diepkloof Gaming Lounge Website

Student Information
- Name: Trinity Sabelo Mhlathi
- Student Number: ST10497070
- Institution: Rosebank College Braamfontein
- Module: WEDE5020 Web Development

Project Overview
This is a gaming lounge website for a fictional business based in Diepkloof, Soweto. 
The site provides information about available games, pricing plans, session booking 
and contact details. It is designed to attract gamers and give potential customers 
everything they need to visit or book a session.


Website Goals and Objectives
- Provide clear pricing information to potential customers
- Allow users to book a gaming session through an online form
- Showcase the games and platforms available at the lounge
- Display location, contact information and opening hours
- Create an engaging and professional online presence for the lounge



 Key Features and Functionality
- Consistent navigation across all five pages
- Booking form with multiple input types including date, time and platform selection
- Embedded Google Maps showing the lounge location
- Pricing cards and membership plan layouts
- Image gallery of gaming zones
- Space themed design with gaming typography


Timeline and Milestones

| Part | Focus | Due Date | Status |

 Part 1  HTML Structure  20 April 2025  Complete 
 
 Part 2  CSS Styling  29 May 2025  Complete
 
Part 3  JavaScript  13 June  Complete


PART 1 DETAILS
Focus: HTML only, no CSS or JavaScript

Pages created:
- index.html - Home page with hero section, offers and popular games
- contact.html - Contact information, opening hours and embedded map
- form.html - Booking form with multiple input types
- games.html - FPS and esports game listings with image gallery
- pricing.html - Gaming rates, group packages and membership plans

Key HTML concepts used:
- Semantic tags including header, nav, section and footer
- Tables for structured data like pricing and opening hours
- Forms with text, email, date, time, number and radio inputs
- Embedded iframe for Google Maps
- Images with alt attributes
- Navigation linking all five pages


 Sitemap

 Home (index.html)
 
 Games (games.html)
 
Pricing (pricing.html)

Contact (contact.html)

Form (form.html)



 PART 2 DETAILS
Focus: CSS styling, removing all HTML inline styling

CSS file:style.css linked to all five pages

Key CSS concepts used:

- Google Fonts import for Orbitron and Rajdhani typefaces
- CSS reset using universal selector for consistent spacing
- Background image with fixed attachment and dark overlay using body::before
- Flexbox for navbar, card layouts and gallery
- Sticky header with z-index layering
- rgba colours for transparent card backgrounds
- Hover effects and transitions on buttons, cards and navbar links
- Transform translateY for card lift effect on hover
- Box-shadow for red glow effect on hover
- Responsive form styling with full width inputs
- Table styling with dark red header rows
- Three breakpoints using media queries: desktop, tablet (768px), mobile (480px)
- Navbar stacks vertically on mobile using flex-direction column
- Cards switch to single column layout on mobile
- Font sizes scale down progressively on smaller screens
- Responsive images using srcset and sizes attributes
- rem and em units used throughout for font sizes and spacing
- Percentage based widths for responsive layouts

Changes from Part 1:
- Removed all bgcolor, font color, center and align attributes
- Replaced table based navbar with CSS flexbox nav
- Replaced table based card layouts with CSS flex containers
- Replaced br tags used for spacing with CSS margin and padding
- Replaced hr dividers with CSS border and section spacing
- All colours, spacing and typography moved to stylesheet

New files added:
- style.css - main stylesheet

Responsive design breakpoints:

 Breakpoint  Screen Size Changes Applied 

Desktop  Above 768px  Full multi-column layout, large fonts 
Tablet  768px and below  Two column cards, reduced font sizes 
Mobile  480px and below  Single column layout, stacked navbar 

 Part 3 Details
Focus:JavaScript interactivity, SEO, form functionality and validation

JavaScript files added:
- animations.js - runs across all pages
- index.js - homepage specific
- games.js - games page specific
- contact.js - contact page specific
- form.js - booking form specific
- pricing.js - pricing page specific
- search.js - search results page specific

Key JavaScript concepts used:
- DOM manipulation to dynamically update page content
- Event listeners for click, input, change and scroll events
- localStorage to persist data across pages and sessions
- IntersectionObserver API for scroll fade in animations
- setInterval for live countdown timer
- URLSearchParams to read search queries from the URL
- Form validation with real time error messages
- EmailJS integration for sending emails from the browser
- Leaflet.js for interactive map rendering

Features implemented:

| Feature | Page | Description |

| Form validation | form.html | Validates all fields before submission |
| EmailJS booking form | form.html | Sends booking details to email |
| EmailJS contact form | contact.html | Sends general messages to email |
| Lightbox gallery | games.html | Click images to view in larger overlay |
| Game search filter | games.html | Real time filter of game listings |
| Tournament countdown | index.html | Live countdown to next tournament |
| Session cost calculator | pricing.html | Calculates cost by platform and duration |
| Accordion FAQ | pricing.html | Expandable frequently asked questions |
| Leaflet interactive map | contact.html | Zoomable map with location marker |
| Dynamic content loading | games.html | Load more games button |
| Scroll animations | all pages | Sections fade in on scroll |
| Back to top button | all pages | Appears after 300px scroll |
| Dark/light mode toggle | all pages | Theme preference saved in localStorage |
| Cookie consent banner | all pages | Accept or decline with localStorage |
| Tournament registration | games.html | Register and store entries in localStorage |
| Animated loading screen | all pages | Progress bar on page load |
| Character counter | contact.html | Live count with colour warnings |
| Session builder | pricing.html | Build and store session in localStorage |
| Global search | all pages | Search across all site content |
| 404 error page | 404.html | Custom page not found |

SEO implemented:
- Meta charset, viewport, description, keywords and author on all pages
- Descriptive title tags on all pages
- robots.txt instructing search engine crawlers
- sitemap.xml listing all pages with last modified dates
- Descriptive alt text on all images
- Semantic HTML structure with proper heading hierarchy

Form functionality:
- Client side validation on both forms
- Real time error messages displayed below fields
- Email format validation using regex
- Phone number format validation using regex
- EmailJS used for AJAX style form submission without page reload
- Success message displayed on successful submission
- Form resets after successful submission
- Booking form pre-fills from session builder selections

New files added:
- animations.js
- index.js
- games.js
- contact.js
- form.js
- pricing.js
- search.js
- search.html
- 404.html
- print.css

 
 CHANGELOG

Version 1.0 - Part 1 (20 April 2025)
- Created initial five page HTML structure
- Built semantic layout using header, nav, section and footer tags
- Added navigation linking all pages
- Created booking form with relevant input types
- Embedded Google Maps on contact page
- Built pricing tables and game listings

 Version 2.0 - Part 2 (29 May 2025)
 CSS Stylesheet Added
- Created style.css and linked to all five pages
- Removed all HTML inline styling attributes including bgcolor, 
  font color, center tags and align attributes

Typography
- Imported Google Fonts: Orbitron for headings, Rajdhani for body text
- Converted all font sizes to rem units for consistency
- Added letter spacing to headings and navbar links

 Layout
- Replaced table based navbar with CSS flexbox nav
- Replaced table based card layouts with CSS flex containers
- Added sticky header that stays at top when scrolling
- Added max-width constraints on sections and form

 Visual Design
- Applied space background image with fixed attachment
- Added dark overlay using body::before for text readability
- Added red accent borders on cards, form and tables
- Added hover effects on navbar links and buttons
- Added card lift effect using transform translateY on hover
- Added red glow effect using box-shadow on hover
- Styled form inputs, textareas and select dropdowns
- Added dark red header row styling on tables

 Responsive Design
- Implemented three breakpoints: desktop, tablet (768px), mobile (480px)
- Navbar stacks vertically on mobile screens
- Cards and gallery items switch to single column on mobile
- Font sizes reduce progressively on smaller screens
- Iframe map resizes for tablet and mobile
- Added srcset and sizes attributes to all images for responsive loading

 New Files Added
- style.css - main stylesheet

 Part 3 Changelog

 Version 3.0 - Part 3 (13 June 2026)

 SEO
- Added meta charset, viewport, description, keywords and author to all pages
- Created robots.txt to guide search engine crawlers
- Created sitemap.xml listing all five pages

 Form Functionality
- Added JavaScript validation to booking form with error messages
- Added JavaScript validation to contact form with error messages
- Integrated EmailJS to send booking form details to email
- Integrated EmailJS to send contact form messages to email
- Added success message on form submission
- Added pre-fill functionality from session builder to booking form

 Interactive Elements
- Added lightbox gallery on games page
- Added accordion FAQ section on pricing page
- Replaced Google Maps iframe with Leaflet interactive map on contact page
- Added global search bar in navbar linking to search results page

Dynamic Content
- Added load more games button on games page
- Added tournament registration system with localStorage on games page
- Added session builder with localStorage on pricing page
- Added global search results page

 Animations and Transitions
- Added scroll fade in animations using IntersectionObserver on all pages
- Added animated loading screen with progress bar on all pages
- Added navbar scroll effect that intensifies on scroll

 Additional Features
- Added back to top button on all pages
- Added dark/light mode toggle with localStorage on all pages
- Added cookie consent banner with localStorage on all pages
- Added live character counter on contact form message field
- Added session cost calculator on pricing page
- Added tournament countdown timer on homepage
- Added custom 404 error page
- Added print stylesheet for pricing page

REFERENCES

Freepik (2025) 3D space sky background image. Available at:
https://www.freepik.com/free-photo/3d-space-sky-background_3267756.htm
(Accessed: 02 April 2025).

Twitch Streamers Community (2025) FPS games image. Available at:
https://www.facebook.com/groups/twitchstreamerscommunity/posts/1052104020067689/
(Accessed: 02 April 2025).

FIFA Infinity (2025) Esports gaming image. Available at:
https://www.fifa-infinity.com/ea-sports-fc/how-ea-sports-fc-25-madden-nfl-25-and-college-football-25-capture-the-essence-of-their-sports/
(Accessed: 02 April 2025).

TripAdvisor (2025) Gaming lounge PC zone image. Available at:
https://www.tripadvisor.co.za/Attraction_Review-g2222168-d26893021-Reviews-UFO_Gaming_Lounge-Jal_el_Dib_Mount_Lebanon_Governorate.html
(Accessed: 02 April 2025).

Day Out With The Kids (2025) Gaming lounge PlayStation zone image. Available at:
https://www.dayoutwiththekids.co.uk/attractions/elite-gaming-lounge-8rrloqwu
(Accessed: 02 April 2025).

Day Out With The Kids (2025) Gaming lounge Xbox zone image. Available at:
https://www.dayoutwiththekids.co.uk/attractions/elite-gaming-lounge-8rrloqwu
(Accessed: 02 April 2025).

Google (2025) Google Fonts. Available at:
https://fonts.google.com
(Accessed: 02 April 2025).

Google (2025) Google Maps. Available at:

Google (2025) Google Fonts: Orbitron. Available at:
https://fonts.google.com/specimen/Orbitron
(Accessed: 02 May 2025).

Google (2025) Google Fonts: Rajdhani. Available at:
https://fonts.google.com/specimen/Rajdhani
(Accessed: 02 May 2025).
https://maps.google.com
(Accessed: 02 April 2025).

EmailJS (2026) *EmailJS Browser SDK*. Available at:
https://www.emailjs.com
(Accessed: 09 June 2026).

Leaflet (2026) *Leaflet: an open-source JavaScript library for 
mobile-friendly interactive maps*. Available at:
https://leafletjs.com
(Accessed: 09 June 2026).

OpenStreetMap (2026) *OpenStreetMap*. Available at:
https://www.openstreetmap.org
(Accessed: 09 June 2026).
