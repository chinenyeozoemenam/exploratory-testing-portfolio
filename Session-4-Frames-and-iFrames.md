# Session 4: Frames and iFrames Testing

**Website:** https://the-internet.herokuapp.com/nested_frames

## Testing Charter

Explore the nested frames and iFrame content using keyboard navigation, direct URL access and page refresh to discover accessibility and content-loading behaviour.

## Test Activities and Results

| S/N | Test Scenario | Actual Result | Status |
|---|---|---|---|
| 1 | Check the LEFT frame. | The word LEFT was displayed correctly. | PASS |
| 2 | Check the MIDDLE frame. | The word MIDDLE was displayed correctly. | PASS |
| 3 | Check the RIGHT frame. | The word RIGHT was displayed correctly. | PASS |
| 4 | Check the BOTTOM frame. | The word BOTTOM was displayed correctly. | PASS |
| 5 | Test keyboard navigation using Tab. | No visible change occurred after pressing Tab inside the LEFT frame. | OBSERVATION |
| 6 | Open the LEFT frame using its direct URL. | The page displayed only the word LEFT. | PASS |
| 7 | Open the RIGHT frame using its direct URL. | The page displayed only the word RIGHT. | PASS |
| 8 | Open the BOTTOM frame using its direct URL. | The page displayed only the word BOTTOM. | PASS |
| 9 | Open the MIDDLE frame using its direct URL. | The page displayed only the word MIDDLE. | PASS |
| 10 | Refresh the nested frames page. | LEFT, MIDDLE, RIGHT and BOTTOM were still displayed. | PASS |

## Summary of Findings

- All four visible frame sections displayed their correct content.
- Each frame could be accessed independently using its direct URL.
- All four frame sections remained visible after refreshing the page.
- Pressing Tab inside the LEFT frame produced no visible change.

## Conclusion

The tested frame sections behaved as expected during the checks performed. The keyboard navigation observation requires further investigation to determine whether there is an accessibility issue.

**Total test checks:** 10  
**Passed:** 9  
**Observations:** 1  
**Failed:** 0

No confirmed defects were identified.
