## Libraries
This project uses the following third-party libraries:

- DOMPurify: Licensed under the Apache License Version 2.0 or the Mozilla Public License Version 2.0. See js/libs/purify_license.txt for details.
- Turndown: Licensed under the MIT License. See js/libs/turndown_license.txt for details.
- Showdown: Licensed under the MIT License. See js/libs/showdown_license.txt for details.

## Roadmap
### Features:
- [ ] Citation numbers next to the source links
- [ ] Code type specified in codeblocks
    => When Phind will make it correct
- [ ] ~~Export to different file types? (PDF, Word, etc.)~~
- [ ] Make a Firefox extension (multi-browser development approach?)
- [ ] Reduce file title length and move the next as the subtitle
```md
# My title...
### ... is too long
```
- [x] Include AI response quotes after the response
- [x] Export source links
- [x] Link to the Phind original search on the file top
- [x] Export conversation to markdown


### Bugs:
- [ ] Make extension icon with transparent background
- [ ] Special characters in title are not correctly formatted (e.g. "\n" should be "\\n")
- [ ] Long user question are cut off in the middle so are not entirely exported
    => temporary solution: drop the question by using "v" button before exporting.
- [x] Fix broken quotes links
- [x] Fix bug not exporting correctly (AI begins with backtite?, citations so the HTML structure is different?)
  https://www.phind.com/search?cache=3dc3a9e2-6841-4ca0-9110-8ee9b11c327b
- [x] Icons instead of sources
- [x] Code is not correctly formatted when converting Html to md 
- [x] Not longer exporting AI answers and source links
     => stronger CSS selectors (try not to use styling classes)
- [x] Inconsistent spaces between questions and answers
- [x] Fix bug "AI Answer" with user question
- [x] File title is the last followup question (= tab title)
     => title taken from search bar

### Security and maintenance:
- [ ] Comment code
- [ ] Remove unused libraries
- [x] Sanitize HTML code

