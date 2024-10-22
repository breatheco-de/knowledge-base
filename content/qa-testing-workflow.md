The QA team will ensure that all the new features or bugs solved meet a high-quality standard, preventing bugs from being passed to the production environment.

Each QA member should look daily for the issues from the SCRUM table, specifically, you’ll be working with the issues in the QA and Tested columns.

- If an issue is in the Tested column and you haven't tested it yet, it means that another teammate already tested it and didn’t find any bugs. 
- If there are no issues in the QA column (Meaning you should always prioritize testing those in QA) and you didn’t test that issue yet, you should test it and make sure it’s working fine, most of the time, you will find bugs or UX improvements when your teammates don't.
- If you find a bug do the same you should’ve done with the issue if it was in the QA column.
- Once an issue is in the QA column, you should read the full instructions of what the developer should do, to make sure you understand the context and reason for these new features, allowing you to give feedback not only about whether it’s working or not, but also about how to improve the experience with this feature. 
- Following the developer’s instructions, you’ll find a Tests section, here you’ll find the main tests that ensure it’s working fine. If other bugs or UX improvements besides the main tests are found, you should report them as well. The tests section will look like this:
- 
![Screenshot 2024-10-22 143847](https://github.com/user-attachments/assets/b89cec2e-3a9a-401d-bf3f-a66d87b63d61)

You’ll have to copy the tests and add them in a new comment, then in the development server (dev.4geeks.com), you should follow the test instructions. Remember, each flow should be tested in:
- Light mode - Desktop view.
- Dark mode - Desktop view.
- Light mode - Mobile view.
- Dark mode - Mobile view.
- Language Spanish - Desktop view (Any of light/dark mode)
Language Spanish - Mobile view (Any of light/dark mode)
- Language English - Desktop view (Any of light/dark mode)
- Language English - Mobile view (Any of light/dark mode)

If a bug is found, include a comment that doesn't show the tests that were working fine, but only show a comment with the bugs found (You should report all the bugs here to avoid further iterations), including a video. Then move the card to the in progress column.

If no bugs are found, then you should move the issue to the tested column.
