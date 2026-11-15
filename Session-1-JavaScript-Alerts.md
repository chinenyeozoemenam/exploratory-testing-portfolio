# Session 1: JavaScript Alerts Testing

**Website:** https://the-internet.herokuapp.com/javascript_alerts

## Testing Charter

Explore the JavaScript alert, confirm, and prompt dialogs using different inputs and actions to discover errors or unexpected behaviour.

## Test Activities and Results

| S/N | Test Scenario | Actual Result | Status |
|---|---|---|---|
| 1 | Click the JavaScript Alert button. | Alert appeared and displayed the expected message. Clicking OK showed a success message. | PASS |
| 2 | Click the JavaScript Confirm button and select OK. | The page displayed "You clicked: Ok". | PASS |
| 3 | Click the JavaScript Confirm button and select Cancel. | The page displayed "You clicked: Cancel". | PASS |
| 4 | Enter text into the JavaScript Prompt. | The page displayed the entered text correctly. | PASS |
| 5 | Leave the JavaScript Prompt empty and select OK. | The page displayed an empty response. | PASS |
| 6 | Open the JavaScript Prompt and select Cancel. | The page displayed "You entered: null". | PASS |

## Summary of Findings

- JavaScript Alert displayed correctly.
- JavaScript Confirm handled both OK and Cancel actions.
- JavaScript Prompt accepted text input.
- Empty input and Cancel produced different results.

## Conclusion

All six test scenarios behaved as observed and no confirmed defects were identified.

**Total test checks:** 6  
**Passed:** 6  
**Failed:** 0
