# B.T.S. | Best Travel Solutions

A responsive travel-discovery landing page for finding things to do, places to stay, restaurants, hidden spots, and family-friendly experiences.

## Features

- Dark B.T.S. navigation bar with desktop links and a mobile menu toggle.
- Travel categories for activities, hotels, restaurants, and hidden spots.
- Search interface with price-range and rating filter controls.
- Bootstrap-powered image carousel using three travel images.
- Interest sections for food, outdoor activities, culture, and water sports.
- Nearby destination suggestions, including Coimbatore, Ooty, Kerala, and Kashmir.
- Recommended experience cards with ratings, prices, discounts, and favorite icons.
- Responsive layout for desktop, tablet, and mobile screen sizes.
- Footer with exploration links, company links, social icons, and legal links.

## Tech Stack

- HTML5 for the page structure and content.
- CSS3 with Flexbox and media queries for layout and responsiveness.
- Bootstrap 4 carousel for the rotating hero images.
- Font Awesome for interface and social icons.
- Google Fonts: Playfair Display and Gabarito.

## Project Structure

```text
best-travel-services/
├── index.html          # Main landing page
├── style.css           # Layout, typography, components, and responsive rules
├── README.md           # Project documentation
└── images/
	├── logo.png        # B.T.S. logo and favicon
	├── s1.jpg          # Carousel image 1
	├── s2.jpg          # Carousel image 2
	├── s3.jpg          # Carousel image 3
	├── food.jpg        # Food category image
	├── outdoor.jpg     # Outdoor category image
	├── culture.jpg     # Culture category image
	├── water.jpg       # Water sports category image
	└── c1.jpg-c4.jpg   # Recommended experience images
```

## Run Locally

This is a static website and does not require a build step or package installation.

1. Open `index.html` directly in a browser, or open the project folder in VS Code.

## Notes

- Bootstrap, jQuery, Popper, Font Awesome, and Google Fonts are loaded from CDNs, so an internet connection is needed for those features and fonts.
- The carousel is configured to advance every two seconds.
- Search, filters, navigation links, favorite icons, social links, and legal links currently provide the visual interface only; they are not connected to a search service, routing layer, authentication, or backend.
- Travel content and prices are sample content intended for the front-end layout.

## Future Improvements

- Add JavaScript to make search and filters update the displayed experiences.
- Connect destinations and experience cards to real detail pages or an API.
- Add working authentication and saved favorites.
- Replace placeholder links with real routes and contact/help pages.
- Add accessibility improvements such as clearer focus states and more descriptive image text.