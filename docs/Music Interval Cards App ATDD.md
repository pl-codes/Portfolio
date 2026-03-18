## Registration Form
### Acceptance Test-Driven Development (ATDD)

As a User I want to:

1.  Be shown/directed to the registration page  
2.  Fill out the form (email & password)  
3.  Submit the info to be registered  
4.  Receive confirmation

### Given-When-Then
1.  **Given** the user is on the home page<br>
    **When** they choose to register (e.g. by clicking on sign up)<br>
    **Then** they are directed to the registration page

2.  **Given** the user is on the registration page <br>
    **When** the user correctly fills out the form<br>
    **Then** the form accepts the input information

3.   **Given** the user has correctly filled out the form <br>
    **When** the user submits the form<br>
    **Then** the form is submitted successfully and account it created

4.  **Given** the user has submitted the form<br>
    **When** the account is created<br>
    **Then** the user receives a confirmation
## Card Application
### Acceptance Test-Driven Development (ATDD)
As a User I want to:
- View the first card's key
- Think of the correct interval up or down from that key, and then be able to flip the card to see the answer
- Then repeat with the next card in the same manner until all the intervals have been tested

### Given-When-Then
**Given** the user is on the "Flip Cards Play" page<br>
**When** they can see the key on the front of the card and choose to click/hover to see the back of the card<br>
**Then** the card flips to show the corresponding key on the back of the card