> Write test cases which test the following actions/checks:
> - [x] Opening an URL
> - [x] Checking visibility
> - [ ] Checking presence
> - [x] Checking text content
> - [x] Clicking on element
> - [ ] Checking browser title
> - [x] Checking browser URL
> - [x] Checking input text
> - [x] Checking input placeholder
> - [x] Typing into input
> - [ ] Checking checkbox state
> - [ ] Clicking on checkbox
> - [ ] Checking radio button state
> - [ ] Clicking on radio button
> - [ ] Checking whether button is enabled
> - [ ] Checking attribute of element
> - [ ] Checking number of elements
> - [ ] Selecting element by its text
> - [ ] Any more action/check necessary...

# Test cases

## `TC-1` Checking landing pages elements

1. **Given** https://angular.io URL is opened
1. **Then** Angular logo in the top navbar should be visible
1. **And** Angular logo in the hero section should be visible
1. **And** text in hero section should be "One framework. Mobile & desktop."
1. **And** Get started button should be visible in the hero section
1. **When** Get started button is clicked in the hero section
1. **Then** the URL should be https://angular.io/start
1. **And** the title on the content should be "Getting Started with Angular: Your First App"

## `TC-2` Checking search field on landing page

1. **Given** https://angular.io URL is opened
1. **Then** Search input in the top navbar should be visible
1. **And** it should be empty
1. **And** it should be "Search" as placeholder
1. **When** it is clicked in
1. **And** "directive" is typed in it
1. **Then** clear icon should be visible in it
1. **And** "Directive" should be listed in the "API" section
1. **When** "Directive" is clicked in the "API" section
1. **Then** the URL should be https://angular.io/api/core/Directive
1. **And** the title on the content should be "Directive"