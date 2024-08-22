# When using TextInput with secureTextEntry={true} on iOS, pressing the back button erases the entire text instead of just the last character
Issue: When using TextInput with secureTextEntry={true} on iOS, pressing the back button erases the entire text instead of just the last character

Steps to Reproduce:

1. Enter text in a TextInput with secureTextEntry={true}.
2. Focus out of the input (e.g., move to the next input field).
3. Refocus on the TextInput.
4. Press the back button to erase text.

Expected Behavior:
The back button should erase only the last character of the input in the TextInput.

Current Behavior:
The entire text is erased when pressing the back button once. 
