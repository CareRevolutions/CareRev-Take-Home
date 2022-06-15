# Thank you for applying to CareRev!

Below are instructions to set up a React project from scratch using some of the technologies we use on the CareRev Engineering team. The project will consist of one page that displays 10 colors from The Color API. We ask that you use Typescript, Redux with Redux Sagas for state management, and Tailwind CSS for styling to complete this assessment. The file structure is up to you.

## Instructions

1. Create a new React app with the react-boilerplate-cra-template using the following command.
   `yarn create react-app --template cra-template-rb carerev-take-home`
2. Copy the Tailwind CSS CDN script into the head tag of the public > index.html file.
   [Tailwind CDN Docs](https://tailwindcss.com/docs/installation/play-cdn)
3. On page load, make an API call to The Color API.

- Documentation - [Colors API Documentation](https://www.thecolorapi.com/docs)
- Use the "scheme" endpoint in the docs based on a **random** seed color using "RGB" and in the mode "monochrome". **HINT**: The RGB parameter is in the format X,X,X where each X is any whole number 0 - 255.

4. The colors:

- Display 10 colors on the page, one color per card. Refer to the screenshots in the mocks folder on how to design each card.
- Display each card with the color’s hex value first. When the button “Show RGB” is clicked, the RGB value text is shown and the button text changes to “Show Hex”. If a user clicks the button again, the hex value is shown again and the button text switches back to “Show RGB”.
- Display the color represented in the card as a square picture to the right of the color code text. Refer to the screenshots.
- At the top of the card, display the color’s name next to the CareRev logo. **NOTE**: Don't worry if a couple of the cards come out with the same name.

5. Refresh the colors

- Build a button at the top of the page (refer to the screenshots) that when clicked will dump the previous colors and get 10 new random colors without reloading the app.
- The new colors should be displayed with the color’s hex value first and the button text as “Show RGB” like when the page first loads.

6. Style your application according to the provided screenshots and design notes. Be sure your application is mobile responsive and follows the design of the attached screenshots for mobile screen sizes.
7. When you’re finished with the assessment, please save your project in a zip folder and submit it per the instructions you received from our recruiter.
