# Session 6: Checkboxes Testing

**Website:** https://the-internet.herokuapp.com/checkboxes

## Testing Charter

Explore the checkbox feature by selecting and unselecting checkboxes, checking whether both can be selected together, and observing their behaviour after refreshing the page.

## Test Activities and Results

| S/N | Test Scenario | Actual Result | Status |
|---|---|---|---|
| 1 | Check the initial state of both checkboxes. | First checkbox was unchecked; second checkbox was checked. | PASS |
| 2 | Select the first checkbox. | The first checkbox became checked. | PASS |
| 3 | Unselect the second checkbox. | The second checkbox became unchecked. | PASS |
| 4 | Select both checkboxes. | Both checkboxes were checked successfully. | PASS |
| 5 | Unselect both checkboxes. | Both checkboxes became unchecked. | PASS |
| 6 | Refresh the page and check the initial states. | First checkbox returned to unchecked; second returned to checked. | PASS |
| 7 | Select the first checkbox independently. | First checkbox became checked while the second remained checked. | PASS |

## Summary of Findings

- Both checkboxes could be selected and unselected successfully.
- Both checkboxes could be checked at the same time.
- Selecting one checkbox did not prevent the other from remaining selected.
- Refreshing the page restored the original checkbox states.

## Conclusion

The checkbox feature behaved as expected during all the checks performed. No defects were identified.

**Total test checks:** 7  
**Passed:** 7  
**Failed:** 0

**Overall Result:** Successful testing with no confirmed defects.
