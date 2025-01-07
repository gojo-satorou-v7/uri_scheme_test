## This is another browser testing repo:

### 1. In full-screen.html we're trying to open a full screen window mode onclick and trying different things like opening a new tab or window to see the behaviour of the browser.
### Untill now no abnormality has been found.

### 2. This is a Content-security policy test to check their behaviour in view-source mode, an example scenario:
###       a. First let's say an attacker is able to load their payload through stored xss, however execution was prevented through csp, but now we want to check if the behaviour is the same in the view-source mode or not.
###       i.e, onclicking the payload does the xss still execute? [untill now it works perfect]


### 3. Checking if opening of a modal iframe blocks the security notification to escape full screen mode or not. [Works fine]

### 4. URI scheme test: to check if any of these schemes can be used to bypass view-source mode or not [pending test]
