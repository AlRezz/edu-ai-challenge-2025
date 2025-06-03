Title:
Logout Button Unresponsive on Safari

Description:
QA has identified an issue where the Logout button does not function in the Safari browser. When users attempt to log out, clicking the button yields no response—no session termination, no redirection, and no visible error message. This behavior appears to be limited to Safari, as the logout functionality works as expected in other browsers such as Chrome and Firefox.

Steps to Reproduce:

Open the application in the Safari browser.

Log in using valid credentials.

Navigate to any screen where the Logout button is available.

Click the Logout button.

Observe the behavior.

Expected vs Actual Behavior:

Expected Behavior:
Clicking the Logout button should terminate the user's session and redirect them to the login screen or homepage. Optionally, a visual confirmation or message should appear.

Actual Behavior:
Clicking the Logout button has no effect. The user remains logged in, and there is no feedback, redirection, or error.

Environment (if known):

Browser: Safari (confirmed on versions 14.x and 15.x)

Operating System: macOS Big Sur, macOS Monterey

Other Browsers Tested: Chrome and Firefox (Logout works as expected)

Severity or Impact:
High – A critical function (logout) is not working in Safari. This may lead to security risks, session persistence issues, and poor user experience for Safari users.

