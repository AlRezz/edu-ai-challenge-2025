## Title  
Logout button doesn’t work on Safari

## Description  
The QA team reported that the **Logout** button does not respond when clicked in the **Safari** browser.  
Users remain logged in with no feedback or redirection.  
This issue is specific to Safari; logout works normally in Chrome and Firefox.

## Steps to Reproduce  
1. Open the application in the **Safari** browser  
2. Log in using valid credentials  
3. Navigate to any page where the **Logout** button is visible  
4. Click the **Logout** button  
5. Observe the behavior

## Expected vs Actual Behavior

**Expected Behavior:**  
- Clicking **Logout** should end the user session  
- The user should be redirected to the login or homepage  
- Optional visual confirmation should appear

**Actual Behavior:**  
- Clicking **Logout** does nothing  
- User remains logged in  
- No feedback or redirect

## Environment (if known)  
- Browser: Safari (versions 14.x, 15.x)  
- Operating System: macOS Big Sur, Monterey  
- Other browsers tested: Chrome, Firefox (working as expected)  
- Application version: _[Insert version/build]_

## Severity or Impact  
**High** — Logout is a critical security and UX function.  
Failure to log out on Safari risks session persistence and user frustration.
