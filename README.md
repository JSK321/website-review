# website-review

## HTML Semantics
Changed all <div></div> tags to detailed HTML semantics. The <div></div> tags were correct in its coding language, but was difficult to decipher when glancing at the code. With the updated HTML semantics, it is much easier to read the code and find the corresponding element.

## Navigation not working
When using the navigation bar, the "Search Engine Optimization" was not working. The 'id="search-engine-optimization"' was missing and is now included in the code.

## Redundent CSS
In the style.css the classes .benefit-lead, .benefit-brand, and .benefit-cost along with its img classes and h2 classes were redundent and combined into one css. Same with the classes for .search-engine-optimization, .online-reputation-management, and .social-media-marketing along with its img classes and h2 classes. Also commented out the redundent code.

".header nav ul {
    list-style-type: none;
}"

The css above is not needed as the list is an unordered list and therefore redundent to include.