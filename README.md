A Bluesky hashtag stream web application, in the manner of the defunct twitterfall

Requirements (draft):
1. Dark mode styling: The entire app should have a dark color scheme for better readability and modern aesthetics.
2. Login functionality: A separate login screen for users to enter their Bluesky handle and app password.
3. Hashtag streaming: Ability to search for posts containing specific hashtags, with a configurable refresh rate.
4. Hyperlinked web links: Any URLs in post content should be automatically converted to clickable links that open in new tabs.
5. Display of media content: Images attached to posts should be displayed within the post content.
6. Error handling and logging: Implement error handling throughout the app and log errors to the console for debugging.
7. Logout functionality: Allow users to log out, clearing their session and returning to the login screen.
8. Avatar display: Show the avatar of each post's author.
9. Indented post content: Align post content under the author's handle, indented from the avatar.
10. Toggle control for 'all' vs 'any' hashtags: Allow users to switch between searching for posts containing all specified hashtags or any of the specified hashtags.
11. Toggle switch design: Implement the toggle as "Any ( ) All" for clear user understanding.
12. Layout improvements: Place the Any/All toggle on the same line as the search box, reduce the width of the refresh rate input, and rename the 'Start Stream' button to 'GO'.
13. Correct hashtag search functionality: Ensure the search looks specifically for hashtags, not just any text in posts.
14. Handle hash symbol in search: Allow users to enter hashtags with or without the '#' symbol.
15. Display Bluesky handle: Show the user's Bluesky handle (@username) in addition to their display name.
16. Date and time display: Show the date and time of each post in a standard social post format.
17. Exclude deleted posts: Do not display posts that have been deleted.
18. Display alt text: Show alternative text for images when available.
19. Responsive design: Ensure the app looks good and functions well on various screen sizes.
20. Minimum refresh rate: Enforce a minimum refresh rate of 5 seconds to prevent excessive API calls.
