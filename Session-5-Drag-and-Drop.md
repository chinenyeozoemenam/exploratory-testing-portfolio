# Session 5: Drag and Drop Testing

**Website:** https://the-internet.herokuapp.com/drag_and_drop

## Testing Charter

Explore the drag-and-drop interaction using different actions to discover whether the feature works correctly and consistently.

## Test Activities and Results

| S/N | Test Scenario | Actual Result | Status |
|---|---|---|---|
| 1 | Drag box A over box B using the mouse. | Both boxes changed positions successfully. | PASS |
| 2 | Repeat the drag-and-drop action. | Both boxes changed positions again. | PASS |
| 3 | Drag box B over box A. | The boxes moved and exchanged positions. | PASS |
| 4 | Drag a box to the blank area outside the boxes. | The box would not stay in the blank area. | OBSERVATION |
| 5 | Test keyboard navigation using Tab. | Focus moved to an element outside the boxes. | OBSERVATION |
| 6 | Refresh the page after moving the boxes. | Both boxes returned to their original positions. | PASS |
| 7 | Test drag-and-drop again after refreshing. | The boxes changed positions successfully. | PASS |
| 8 | Check whether the boxes exchange positions correctly. | Box A moved right while box B moved left. | PASS |

## Summary of Findings

- Drag-and-drop worked successfully using the mouse.
- Both boxes exchanged positions correctly.
- The feature continued working after refreshing the page.
- A box would not remain in the blank area outside the two boxes.
- Keyboard focus moved outside the boxes when Tab was pressed.

## Conclusion

The drag-and-drop feature worked as expected during the mouse interaction tests. Two observations were recorded for further investigation: dropping outside the boxes and keyboard accessibility.

**Total test checks:** 8  
**Passed:** 6  
**Observations:** 2  
**Failed:** 0

No confirmed defects were identified.
