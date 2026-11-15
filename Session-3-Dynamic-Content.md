# Session 3: Dynamic Content Testing

**Website:** https://the-internet.herokuapp.com/dynamic_content

## Testing Charter

Explore the dynamic content page across multiple refreshes to discover consistency of content and image loading.

## Test Activities and Results

| S/N | Test Scenario | Actual Result | Status |
|---|---|---|---|
| 1 | Open the Dynamic Content page. | Text and images were displayed on the page. | PASS |
| 2 | Refresh the browser. | The text and all three pictures changed. | PASS |
| 3 | Refresh the browser again. | The text and pictures changed again. | PASS |
| 4 | Click the "click here" link. | Only the third picture and its text changed. | PASS |
| 5 | Click the link repeatedly. | Only the third section continued changing. | PASS |
| 6 | Click the displayed pictures. | No visible action occurred. | OBSERVATION |
| 7 | Check whether all three pictures load correctly. | All three pictures displayed without appearing broken or missing. | PASS |

## Summary of Findings

- The page displayed text and pictures successfully.
- Refreshing the browser changed the displayed text and pictures.
- Clicking the page link changed only the third content section.
- Repeated clicks continued changing the third section.
- Clicking the pictures produced no visible action.

## Conclusion

The dynamic content page behaved consistently during the checks performed. Clicking the pictures produced no visible action, but this was recorded as an observation rather than a confirmed defect.

**Total test checks:** 7  
**Passed:** 6  
**Observations:** 1  
**Failed:** 0

No confirmed defects were identified.
