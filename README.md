# navigational-funnels
Navigation from screen-to-screen can often get complex if we need to persist certain navigational progress, re-compose how our screens are presented, and reuse logic accross screens. Navigational funnels is a design pattern help to relieve the three issues with screen composition:

1. **Pre-defined** navigation e.g. when the app starts which screen should it start from?
2. **Flexible Navigation** e.g. if the user is on the payment page and subscribes we want to take them back to that page instead of setting route.
3. **Screen Reusability** e.g. we want to re-use the "ChooseFavouriteBrandsScreen" from the signup process and edit brands from the profile.
