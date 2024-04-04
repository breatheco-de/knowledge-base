## Watch these Videos:
- [Understanding Stale Issues in GitHub](https://www.loom.com/share/video1)
- [Daily Task: Checking Unassigned Issues](https://www.loom.com/share/video2)

## Procedure:

1. **Enter GitHub:**
   - Navigate to the GitHub repository and search for stale bug reports or unassigned issues.
   - You can find them using [this link](https://github.com/breatheco-de/breatheco-de/issues?q=is%3Aissue+label%3Astale+is%3Aopen+no%3Aasignee) or by applying the filters: `is:issue label:stale no:assignee is:open`.
   
2. **Read and Understand:**
   - Read the bug reports to understand the type of bug and where it is occurring.
   
3. **Replicate or Confirm:**
   - Try to replicate the error mentioned in the report.
   - Visit the website mentioned in the report to confirm if the bug is still present.

4. **Action Based on Confirmation:**
   - If the bug is still present:
     - Remove the stale label.
     - Add one or more of the following labels:
       - `Confirm`: If it was confirmed that the bug is still occurring.
       - `BUG`: If it is indeed a mistake.
       - `Front end`: If the bug is a frontend bug.
       - `Back end`: If the bug is a backend bug.
   - If you can't confirm the bug:
     - Add the label `✋ waiting-for-feedback`.
     - Review it in the standup meeting.
   - If the bug is not happening:
     - Close the issue by adding a comment.


Following this procedure will help streamline the bug reporting and management process, ensuring that issues are properly identified, confirmed, and addressed in a timely manner.
