# Uninitialized Variable in COBOL PERFORM Loop

This repository demonstrates a common error in COBOL programs involving uninitialized variables within PERFORM loops. The provided COBOL code adds 1 to WS-TOTAL repeatedly, but if WS-TOTAL is not initialized before the loop, it will start with an unpredictable value, leading to incorrect results.  The solution demonstrates proper variable initialization before the loop.