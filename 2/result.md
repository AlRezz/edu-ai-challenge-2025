## Title
Logout button doesn’t work on Safari

## Description
The QA team reported that the **Logout** button does not respond when clicked in the **Safari** browser.  
Users remain logged in with no feedback, no session termination, and no redirection.  
This issue seems specific to Safari, while logout works correctly on other browsers such as Chrome and Firefox.

## Steps to Reproduce
1. Open the application in the **Safari** browser  
2. Log in using valid credentials  
3. Navigate to a page where the **Logout** button is visible  
4. Click the **Logout** button  
5. Observe the behavior

## Expected vs Actual Behavior

**Expected Behavior:**  
- Clicking **Logout** should terminate the user session  
- The user should be redirected to the login page or homepage  
- Optional: A logout confirmation or visual feedback should appear

**Actual Behavior:**  
- Clicking **Logout** does nothing  
- The user remains logged in  
- No feedback, redirect, or error message appears

## Environment (if known)
- Browser: Safari (versions 14.x, 15.x)  
- Operating System: macOS Big Sur, macOS Monterey  
- Other Browsers Tested: Chrome, Firefox (working as expected)  
- Application Version: _[Insert version/build number]_

## Severity or Impact
**High** – Logout is a critical security and user experience function.  
Failure to log out on Safari poses security risks and negatively impacts user experience.
