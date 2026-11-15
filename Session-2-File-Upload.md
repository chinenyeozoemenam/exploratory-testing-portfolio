# Session 2: File Upload Testing

**Website:** https://the-internet.herokuapp.com/upload

## Testing Charter

Explore the file upload feature using different file types and filenames, including special characters, to discover validation behaviour.

## Test Activities and Results

| S/N | Test Scenario | Actual Result | Status |
|---|---|---|---|
| 1 | Upload a PDF file. | The PDF file uploaded successfully without an error. | PASS |
| 2 | Click Upload without selecting a file. | The website displayed an Internal Server Error message stating that no file was chosen. | OBSERVATION |
| 3 | Upload a Word document. | The website displayed File Uploaded successfully and showed the filename. | PASS |
| 4 | Upload a file with special characters in its name. | The file uploaded successfully and its filename was displayed. | PASS |
| 5 | Upload an empty text file. | The website displayed File Uploaded successfully. | PASS |
| 6 | Upload a JPG image. | The image uploaded successfully without an error. | PASS |

## Summary of Findings

- The website accepted PDF, Word and JPG files.
- A filename containing special characters was accepted.
- An empty text file was accepted.
- Attempting to upload without selecting a file produced an Internal Server Error message.

## Conclusion

The file upload feature successfully handled the file types tested. The no-file upload response was recorded as an observation requiring further investigation.

**Total test checks:** 6  
**Passed:** 5  
**Observations:** 1  
**Failed:** 0

No confirmed defects were identified.
