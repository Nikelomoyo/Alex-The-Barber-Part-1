# Alex the Barber Website

## Student Information

**Student Name:** Nikelo Moyo
**Course:** Software Development
**Year:** 1st Year
**Project:** Website Project
**Client:** Alex the Barber
**Academic Year:** 2026

---

# 1. Project Overview

Alex the Barber is a professional barbering website designed to provide customers with information about the barbering business, its services, prices, locations and contact information.

The website provides customers with an easy way to explore available grooming services, view examples of previous work, learn more about the barber and make an appointment enquiry.

The website was developed using HTML5, CSS3 and JavaScript. The website uses a consistent visual design across all pages and includes responsive layouts so that the content can adapt to desktop, tablet and mobile screen sizes.

The website currently contains six main pages:

* Home
* About Us
* Services
* Gallery
* Enquiry
* Contact

---

# 2. Website Goals and Objectives

The main goal of the website is to create a professional online presence for Alex the Barber.

The objectives of the website are to:

* Introduce customers to Alex the Barber.
* Provide information about the barbering business.
* Display available services and prices.
* Showcase previous barbering and styling work.
* Provide contact information and business locations.
* Display opening hours.
* Allow customers to submit appointment enquiries.
* Provide a professional and consistent visual identity.
* Make the website accessible on desktop, tablet and mobile devices.
* Provide simple and clear navigation between all website pages.

---

# 3. Key Features and Functionality

The website includes the following features:

### Navigation

A consistent navigation bar is displayed throughout the website.

The navigation provides links to:

* Home
* About Us
* Services
* Gallery
* Enquiry
* Contact

The current page is highlighted in the navigation using the gold colour scheme.

### Services

The Services page displays the barber's available services, descriptions and prices.

Services include:

* Classic Haircut
* Fade Haircut
* Kids Haircut
* Beard Trim
* Hair Styling
* Professional Shave
* Buzz Cut
* Burst Fade

### Gallery

The Gallery page displays examples of barbering and styling work using a responsive CSS Grid layout.

Gallery items include:

* Fresh Fade
* Braiding
* Kids Cut
* Beard Trim
* Modern Styling
* Taper Fade
* Buzz Cut
* Burst Fade

### Enquiry Form

The Enquiry page contains a form that allows customers to provide:

* Full name
* Email address
* Phone number
* Preferred service
* Preferred date
* Preferred time
* Additional message

JavaScript is used to provide confirmation after the form is submitted and to prevent users from selecting a date in the past.

### Contact Information

The Contact page provides:

* Business locations
* Telephone numbers
* Email address
* Opening hours
* Embedded Google Maps location

### Responsive Design

The website has responsive layouts for:

* Desktop computers
* Tablets
* Mobile phones
* Small mobile devices

CSS media queries are used to change layouts, navigation, typography, grids and spacing according to screen size.

---

# 4. Website Pages

## 4.1 Home Page

**File:** `index.html`

The Home page is the main landing page of the website.

It contains:

* Hero section
* Welcome message
* Introduction to Alex the Barber
* Popular services
* Reasons to choose the business
* Call-to-action sections
* Links to services and appointment enquiries

The hero section uses a large background image and a prominent call-to-action button.

---

## 4.2 About Us Page

**File:** `about.html`

The About Us page introduces Alex the Barber and explains the history and purpose of the business.

It contains:

* Meet Alex section
* Business story
* Business highlights
* Company values
* Call-to-action section

The page focuses on building trust and explaining the professional approach of the barber.

---

## 4.3 Services Page

**File:** `services.html`

The Services page provides detailed information about the barber's services.

Each service includes:

* Service image
* Service name
* Description
* Price
* Enquiry link

CSS Grid is used to create a responsive two-column layout on larger screens.

---

## 4.4 Gallery Page

**File:** `gallery.html`

The Gallery page displays examples of previous barbering work.

The gallery uses CSS Grid and responsive styling to create a professional image layout.

Each gallery image contains:

* Image
* Descriptive alternative text
* Service/style name
* Short description

---

## 4.5 Enquiry Page

**File:** `enquiry.html`

The Enquiry page allows customers to submit an appointment enquiry.

The form uses HTML form controls including:

* Text input
* Email input
* Telephone input
* Date input
* Select/drop-down menus
* Textarea
* Submit button

Required fields are validated using HTML5 form validation.

JavaScript provides a confirmation message when the form is submitted.

---

## 4.6 Contact Page

**File:** `contact.html`

The Contact page provides customers with ways to contact and locate Alex the Barber.

The page contains:

* Johannesburg location
* Sandton location
* Opening hours
* Telephone numbers
* Email address
* Embedded Google Maps

The page includes more than one business location as required by the website brief.

---

# 5. Sitemap

The website follows the following sitemap structure:

```text
                         HOME
                      index.html
                          |
       -----------------------------------------
       |          |          |        |        |
       |          |          |        |        |
    ABOUT      SERVICES    GALLERY  ENQUIRY  CONTACT
    about      services    gallery  enquiry  contact
    .html       .html       .html    .html    .html
```

All pages contain links back to the Home page and links to the other main sections of the website.

---

# 6. File and Folder Structure

The project is organised into separate folders for HTML, CSS, JavaScript and images.

```text
Alex-The-Barber/
│
├── index.html
├── about.html
├── services.html
├── gallery.html
├── enquiry.html
├── contact.html
├── README.md
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
└── images/
    ├── logo.png
    ├── alex.png
    ├── alex2.png
    ├── kid.png
    ├── trimming.png
    ├── styling.png
    ├── shaving.png
    ├── chantell.png
    ├── taper.png
    ├── buz.png
    └── burst.png
```

### File Organisation

HTML files are stored in the root project folder.

The external stylesheet is stored in the `css` folder.

JavaScript is stored in the `js` folder.

Images used throughout the website are stored in the `images` folder.

This organisation makes the project easier to maintain and allows files to be located quickly.

---

# 7. Technologies Used

## HTML5

HTML5 is used to create the structure and content of the website.

Semantic HTML elements are used throughout the website, including:

* `<header>`
* `<nav>`
* `<main>`
* `<section>`
* `<article>`
* `<aside>`
* `<figure>`
* `<figcaption>`
* `<footer>`
* `<form>`

---

## CSS3

CSS3 is used to control the visual appearance and layout of the website.

The stylesheet includes:

* CSS reset
* Typography
* Colours
* Spacing
* Borders
* Shadows
* Buttons
* Navigation
* CSS Grid
* Flexbox
* Responsive design
* Media queries
* Hover effects
* Focus states
* Active states
* Image layouts

---

## JavaScript

JavaScript is used for basic website interactivity.

The current JavaScript functionality includes:

* Enquiry form submission feedback
* Form reset after submission
* Preventing users from selecting dates in the past

---

# 8. Part 1 – Content and Structure

Part 1 focused on planning and creating the initial website structure.

The following activities were completed:

* Selected Alex the Barber as the proposed client.
* Researched suitable content for the website.
* Planned the website pages.
* Created the sitemap.
* Organised the website files.
* Created the HTML pages.
* Added navigation between pages.
* Added images and alternative text.
* Added service information.
* Added contact information.
* Added the enquiry form.
* Added the gallery.
* Created the initial GitHub repository.
* Created the initial README documentation.

---

# 9. Part 2 – CSS Styling and Responsive Design

Part 2 focused on developing the visual design and responsive behaviour of the website.

## 9.1 External Stylesheet

An external stylesheet was created:

```text
css/style.css
```

All HTML pages link to the same stylesheet using:

```html
<link rel="stylesheet" href="css/style.css">
```

Using one external stylesheet allows the website to maintain a consistent visual identity across all pages.

---

# 9.2 CSS Reset

A CSS reset was implemented to remove inconsistent default browser margins and padding.

The reset also uses:

```css
box-sizing: border-box;
```

This makes sizing elements more predictable across different browsers.

---

# 9.3 Colour Scheme

The website uses a black, dark grey, white and gold colour palette.

| Colour      | Purpose                                    |
| ----------- | ------------------------------------------ |
| Black       | Navigation and footer                      |
| Dark grey   | Main backgrounds                           |
| Medium grey | Cards and content areas                    |
| White       | Main text                                  |
| Light grey  | Secondary text                             |
| Gold        | Branding, headings, buttons and highlights |

The gold colour used throughout the website is:

```text
#d4af37
```

The colour scheme was selected to create a professional barber-shop appearance.

---

# 9.4 Typography

Typography was designed to create a clear visual hierarchy.

Different font sizes and weights are used for:

* Main headings
* Section headings
* Subheadings
* Body text
* Navigation
* Buttons
* Labels

Relative units such as `rem` are used in many areas of the stylesheet to help the design scale across different screen sizes.

---

# 9.5 Layout

CSS Grid and Flexbox are used throughout the website.

### CSS Grid

CSS Grid is used for:

* Service cards
* Full services page
* Gallery
* Footer
* Contact locations
* About page layouts
* Enquiry page layout

### Flexbox

Flexbox is used for:

* Navigation
* Navigation alignment
* Hero buttons
* Service pricing rows
* Other smaller alignment requirements

---

# 9.6 Visual Styling

The website includes:

* Rounded borders
* Gold accents
* Card borders
* Box shadows
* Image cropping
* Button styling
* Hover animations
* Navigation effects
* Gallery effects
* Focus states

Interactive elements use CSS pseudo-classes such as:

```css
:hover
:focus
:active
```

For example, service cards move slightly upwards when the user hovers over them.

---

# 10. Responsive Design

Responsive design was implemented so that the website can adapt to different screen sizes.

The website has three main responsive stages:

### Desktop

Large screens use:

* Multi-column layouts
* Larger typography
* Horizontal navigation
* Larger gallery grids
* Multiple service cards per row

### Tablet

Medium screens reduce the number of columns and adjust spacing and typography.

For example, service cards change from four columns to two columns.

### Mobile

Small screens use:

* Single-column layouts
* Stacked navigation
* Smaller typography
* Full-width buttons
* Single-column service cards
* Single-column gallery
* Stacked form fields

---

# 11. CSS Breakpoints

The main responsive breakpoints are:

```css
@media (max-width: 1000px)
```

Used for tablet-sized screens and smaller desktop displays.

```css
@media (max-width: 700px)
```

Used for mobile devices.

```css
@media (max-width: 400px)
```

Used for smaller mobile devices.

These breakpoints allow the website layout to change according to available screen width.

---

# 12. Relative Units

Relative units are used throughout the stylesheet to improve responsiveness.

Examples include:

```text
%
rem
vh
```

Examples include:

```css
width: 90%;
font-size: 1rem;
padding: 5rem 2rem;
min-height: 85vh;
```

Using relative units helps the website adapt to different screen sizes.

---

# 13. Responsive Images

Images are styled so that they do not exceed the width of their containing elements.

The stylesheet includes:

```css
img {
    max-width: 100%;
    height: auto;
}
```

Images used in cards and galleries also use `object-fit` to maintain a consistent visual layout.

Further responsive image optimisation using `srcset`, `sizes` and multiple image resolutions can be added when separate image resolutions are available.

---

# 14. Browser Testing

The website was tested using browser developer tools.

Chrome DevTools was used to test different screen sizes and identify layout problems.

The following approximate screen sizes were used:

### Desktop

```text
1440 × 900
```

The following areas were checked:

* Navigation
* Hero section
* Service grid
* Gallery
* Footer
* Overall spacing

### Tablet

```text
768 × 1024
```

The following areas were checked:

* Navigation
* Service grid
* Typography
* Page spacing
* Contact sections

### Mobile

```text
390 × 844
```

The following areas were checked:

* Stacked navigation
* Buttons
* Forms
* Service cards
* Gallery
* Contact information
* Footer

---

# 15. Testing and Iteration

During development, the website was continuously tested and adjusted.

Problems identified during development included:

* Content being hidden behind the fixed navigation.
* Inconsistent navigation styling between pages.
* Excessive spacing between navigation links.
* Fixed footer overlapping page content.
* Images having inconsistent sizes.
* Service information being displayed inconsistently.
* Invalid or unnecessary inline CSS.
* Duplicate HTML elements.
* Mobile layouts requiring additional spacing and restructuring.

These issues were corrected by moving styling into the external stylesheet, restructuring the HTML and introducing responsive CSS rules.

---

# 16. Accessibility

Accessibility was considered during development.

The website includes:

* Descriptive `alt` text for images.
* Semantic HTML elements.
* Labels connected to form controls.
* Required form fields.
* Visible focus states.
* Clear navigation.
* Sufficient contrast between the main background and text.
* Descriptive page titles.

For example:

```html
<img src="images/logo.png"
     alt="Alex the Barber logo">
```

Form fields use labels such as:

```html
<label for="email">
    Email Address
</label>
```

---

# 17. GitHub Repository

The project is maintained using Git and GitHub.

Git is used to track changes during development.

Changes are committed using descriptive commit messages rather than generic messages.

Examples include:

```text
Added initial project structure and HTML pages
Added external CSS styling and desktop layout
Added responsive tablet and mobile layouts
Added gallery layout and hover effects
Improved enquiry form styling
Fixed navigation and page spacing
Tested responsive layouts and fixed styling issues
Updated README documentation
```

The final GitHub repository link will be submitted through the LMS.

**GitHub Repository:**

[Insert GitHub repository link here]

---

# 18. Changelog

## Version 1.0 – Part 1 Initial Website

* Created the Alex the Barber website project.
* Created the initial HTML page structure.
* Created Home page.
* Created About Us page.
* Created Services page.
* Created Gallery page.
* Created Enquiry page.
* Created Contact page.
* Added navigation links.
* Added business information.
* Added service information and prices.
* Added images.
* Added gallery content.
* Added enquiry form.
* Added contact information.
* Added Google Maps embed.
* Created initial project folder structure.
* Created GitHub repository.
* Added initial README documentation.

---

## Version 2.0 – Part 2 External CSS

* Created external `css/style.css` stylesheet.
* Linked the external stylesheet to all HTML pages.
* Removed unnecessary inline styling.
* Added CSS reset.
* Established a consistent black, grey, white and gold colour scheme.
* Added consistent typography.
* Added heading hierarchy.
* Styled navigation.
* Added active navigation indicators.
* Added hover effects.
* Added focus states.
* Added active states.
* Styled buttons.
* Redesigned the Home page hero section.
* Added service card styling.
* Added card borders and shadows.
* Added image styling.
* Added CSS Grid layouts.
* Added Flexbox layouts.
* Redesigned the Gallery page.
* Redesigned the Services page.
* Redesigned the Enquiry page.
* Redesigned the Contact page.
* Redesigned the footer.

---

## Version 2.1 – Responsive Design

* Added tablet responsive styling.
* Added mobile responsive styling.
* Added small-mobile responsive styling.
* Changed multi-column layouts into single-column layouts on mobile.
* Adjusted navigation for mobile screens.
* Adjusted typography for smaller screens.
* Adjusted service card layouts.
* Adjusted gallery layout.
* Adjusted enquiry form layout.
* Adjusted contact location layout.
* Improved page spacing on mobile devices.
* Tested website layouts using browser developer tools.

---

## Version 2.2 – Corrections and Improvements

* Removed duplicate `<header>` elements.
* Removed fixed footer styling that could overlap content.
* Removed unnecessary inline CSS.
* Corrected navigation structure.
* Improved semantic HTML structure.
* Corrected service card structure.
* Removed duplicated service content.
* Improved image sizing.
* Added descriptive image alternative text.
* Improved form structure.
* Added required fields to the enquiry form.
* Added preferred appointment time.
* Added additional service options.
* Improved accessibility.
* Improved navigation consistency across all pages.

---

# 19. Current Project Status

The website currently contains:

* Six completed HTML pages.
* One external CSS stylesheet.
* One JavaScript file.
* Responsive desktop, tablet and mobile layouts.
* Consistent navigation.
* Responsive service cards.
* Responsive gallery.
* Styled enquiry form.
* Contact locations.
* Embedded map.
* Responsive footer.
* Hover and focus effects.
* Updated project documentation.

The next development stage can include additional responsive image optimisation using multiple image resolutions and further testing across different browsers and devices.

---

# 20. Future Development

Possible future improvements include:

* Connecting the enquiry form to a real backend.
* Sending appointment enquiries through email.
* Adding online appointment booking.
* Adding a mobile navigation menu.
* Adding customer reviews and testimonials.
* Adding social media links.
* Adding more gallery images.
* Adding additional barbering services.
* Adding responsive image versions using `srcset` and `sizes`.
* Adding a database for appointment management.
* Adding an administrator dashboard.
* Adding online payments.
* Improving search engine optimisation.
* Adding Google Business integration.

---

# 21. Conclusion

The Alex the Barber website provides a professional online platform for presenting the business, its services, previous work and contact information.

The project progressed from the initial HTML structure developed during Part 1 to a more complete visual solution during Part 2. An external CSS stylesheet was introduced to provide consistent styling, while CSS Grid, Flexbox, media queries and relative units were used to create a responsive website.

The website was also tested at desktop, tablet and mobile screen sizes to identify and correct layout issues.

The project demonstrates the use of HTML5, CSS3, responsive web design principles, basic JavaScript and Git version control.

---

# 22. References

References used during the development of the website and its documentation should be recorded below according to the required Harvard referencing format.

Mozilla Developer Network (MDN) Web Docs. (n.d.) *HTML: HyperText Markup Language*. Available at: https://developer.mozilla.org/en-US/docs/Web/HTML (Accessed: 18 September 2026).

Mozilla Developer Network (MDN) Web Docs. (n.d.) *CSS: Cascading Style Sheets*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS (Accessed: 18 September 2026).

Mozilla Developer Network (MDN) Web Docs. (n.d.) *CSS Grid Layout*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout (Accessed: 18 September 2026).

Mozilla Developer Network (MDN) Web Docs. (n.d.) *CSS Flexible Box Layout*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout (Accessed: 18 September 2026).

Mozilla Developer Network (MDN) Web Docs. (n.d.) *Using media queries*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries (Accessed: 18 September 2026).

Mozilla Developer Network (MDN) Web Docs. (n.d.) *HTML forms*. Available at: https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms (Accessed: 18 September 2026).
