# UDP5WA4CF-TU_boardwalk_games

## Scope

### Business goals

1. Increase in-store foot traffic and customer engagement.
1. Showcase the shop services.
1. Increase brand awareness.
1. Provide essential information to clients.
1. Encourage group visits and event participation.

Boardwalk Games will appeal to...
- people who enjoy socialising and playing board games.
- casual gamers and families looking for a fun and relaxed atmosphere.
- board game enthusiasts seeking information about game events and new realeases.
- student gamers interested in budget-friendly entertainment options and discounts.

### User goals

#### Must-haves

##### 1. User friendly navigation and responsive design

" As a first-time visitor, I need easy navigation and a user-friendly design, including a responsive layout for my device, so I can find information quickly and efficiently without frustration. "

Acceptance criteria:
- The website is fully responsive across various devices and screen sizes.
- Site layout and navigation are intuitive, allowing easy access to different sections.

Tasks:
- Apply responsive design principles using Bootstrap to ensure the website is accessible on various devices.
- Arrange the site layout and navigation based on best practices, ensuring all key sections and pages are easily accessible.

##### 2. High quality images and engaging descriptions

" As a Casual Gamer, I want to see high-quality images and engaging descriptions of the café's ambience and some of the available games, so I can decide if it's the right place for me to relax and have fun. "

Acceptance criteria:
- The homepage features a carousel with high-quality images of the café and game selection that rotates automatically and allows manual navigation.
- Engaging descriptions of the café's ambience and available favourite games are displayed clearly and concisely within the site's content.
- The homepage layout prominently features the images and descriptions in an uncluttered manner.

Tasks:
- Integrate provided high-quality images of the café and some of the available games into the website using a carousel.
- Embed the provided engaging descriptions for the café's ambience and list of services available within the site's content.
- Design and implement a homepage layout that prominently features the images and descriptions.

##### 3. Location, contact details and opening hours

" As a Prospective Customer, I need to find essential information such as location, contact details, and opening hours clearly and concisely, so I can easily plan my visit or get in touch with the café. "

Acceptance criteria:
- The website contains a dedicated section for location, contact details, and opening hours.
- This section is clearly visible and accessible from all parts of the website.

Tasks:
- Design and place a section for location, contact details, and opening hours using information provided by the client.
- Ensure the contact section is clearly visible and accessible from all parts of the website, adhering to common design standards.

##### 4. Booking inquiry form

" As a Customer, I want to book a table or join an open game night using a simple booking inquiry form, so I can easily organise a group visit or a special occasion. "

Acceptance criteria:
- A booking inquiry form for private events or game nights is easy to find, and the form is simple and easy to use.
- The form includes all necessary fields to gather event details: Name, Email, Phone Number, Event Type and Message. Event types are: Reserve a table, Dungeons & Dragons, Retro Game Night, Tournament, Kids Party.
- All fields on the form must be completed before the user can submit the form.
- When the form is completed correctly, the user is taken to a success page.

Tasks:
- Implement a booking inquiry form on the website.
- Implement HTML validation on the form to fit the requirements above.
- Create a success page to direct users to after submitting the form.

##### 8. Selected board games displayed on a separate Game Library page

" As a Board Game Enthusiast, I want to explore a selection of featured board games on the website, so I can discover new games and decide which ones I might be interested in trying or buying. "

Acceptance criteria:
- The website has a separate page for the list of board games.
- The game library page utilises the Bootstrap grid and card components for consistency in layout and responsiveness.
- Each card states the relevant game title, image, descriptions, number of players and age range.

Tasks:
- Create a responsive Game Library page featuring a handful of selected games and their relevant details.

#### Should-haves

##### 5. Visible pricing for events and student discount

" As a Student Gamer, I want to find clear information about upcoming events, pricing and student discounts, so I can plan my visit within my budget and time constraints. "

Acceptance criteria:
- Clear and accurate pricing information for events is displayed and easy to find.
- Student discount information stands out near pricing information.

Tasks:
- Display pricing for events using the provided rate information.
- Clearly display student discount information with the pricing for events.

##### 9. Form to reserve a board game on the Game Library page

" As a Board Game Enthusiast, I want to reserve a board game from the list of available games, so I can ensure it's available for me when I visit the shop. "

Acceptance criteria:
- A reservation form is available on the Game Library page.
- The user can fill out their selected game, name, contact information, and preferred date for the reservation.

Tasks:
- Create a reservation form with fields for the user's name, contact information, preferred date and select which game they want to reserve.

#### Could-haves

##### 6. Testimonials

" As a Prospective Customer, I want to read testimonials and reviews from other customers, so I can gauge the experiences of others and feel more confident about visiting Boardwalk Games. "

Acceptance criteria:
- The website includes a section dedicated to displaying customer testimonials and reviews.
- Testimonials are clearly visible and presented in a format that is easy to read and navigate.

Tasks:
- Create a static section on the website for customer testimonials.
- Populate this section with a selection of pre-written testimonials.

##### 7. Newsletter sign up form

" As a Regular Customer, I want to sign up for newsletters and updates, so I can stay informed about special offers, new games, and upcoming events. "

Acceptance criteria:
- The website contains a sign up form for the shop newsletter.
- The sign up form is placed in the footer on every page, so that users can easily find it.

Tasks:
- Integrate the newsletter sign-up form into the website footer.

## Structure

### Wireframes

[Link to the wireframes for this project](https://codeinstitute.s3.eu-west-1.amazonaws.com/Bootstrap/bootstrapM2-02.01.03-boardwalk-games-full-wireframes.pdf).

[Bootstrap](https://getbootstrap.com) was used for basic styling.

### Colour palette

Four colours were selected from [IMAGECOLORPICKER.com](https://imagecolorpicker.com/) using a photo of the store. [Contrast checker](https://webaim.org/resources/contrastchecker) was used to check that accessibility standards are met.

The colours selected were:
- #3A2620 Bistre
- #AA9581 Beaver
- #416A8E Lapis Lazuli
- #7A9FC2 Air superiority blue

Plus black (#000000) and white (#FFFFFF).

### Fonts

Two fonts were selected from [Google Fonts](https://fonts.google.com).

The fonts selected were:
- [Macondo](https://fonts.google.com/specimen/Macondo) for headings
- [Inter](https://fonts.google.com/specimen/Inter) for body

### Icons

[Font Awesome](https://fontawesome.com) was used to source icons.

---
---

## Lighthouse (automated) testing

93
Performance  
100
Accessibility  
100
Best Practices

## CSS Autoprefixer

Prefixed by https://autoprefixer.github.io  
PostCSS: v8.4.14,  
Autoprefixer: v10.4.7  
Browsers: last 4 version

## W3C HTML validation

1. Commit "Remove trailing slash (line 147)"

No errors.

## W3C CSS validation

No errors.

