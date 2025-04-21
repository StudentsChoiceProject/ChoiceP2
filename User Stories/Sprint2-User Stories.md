## Sprint 2 User Stories

### Milestone 1: Secondary Menu and Listing Layouts

#### Story 1.1: Add Secondary Hover Menu for New Categories

**User Story:** 

As a student, I want a secondary hover menu on the homepage, so that I can quickly access the new listing categories.

**Acceptance Criteria:**

- Hovering over the icon triggers the secondary menu
- Hovering out hides the menu unless it's pinned
- Pin icon toggles fixed state
- Contains links to all new category listings
- Menu is responsive and works on mobile devices

#### Story 1.2: Add Sorting to All Listing Pages

**User Story:**

As a student, I want to sort listings by name or rating, so that I can view them in the order that suits me best.

**Acceptance Criteria:**

- Sorting options: A-Z, Z-A, Rating High → Low, Rating Low → High
- Default sorting can be alphabetical
- Affects visible entries in list/grid views
- Sorting preference persists within session

#### Story 1.3: Add Grid/List View Toggle for Listings

**User Story:** 

As a student, I want to toggle between list and grid views, so that I can choose the layout that's easier for me to read.

**Acceptance Criteria:**

- Toggle buttons or icons switch between views
- State persists on navigation within the category
- Both layouts show title, type, location, and rating
- Layouts are responsive and work on different screen sizes

#### Story 1.4: Implement Listing Template for Standard Categories

**User Story:** 

As a developer, I want a reusable listing component, so that I can build consistent pages across all categories more efficiently.

**Acceptance Criteria:**

- Standard format includes: Title, Type, Location, Rating, Bookmark Icon
- Integrates with sorting and view toggle logic
- Applies to: Accommodation, Health, Fitness, Eateries, Culture & Religion, Clubs & Societies
- Component is flexible enough to handle different content types
- Includes error handling for missing data

#### Story 1.5: Add University Filter to All Listing Pages

**User Story:** 

As a student, I want to filter listings by university, so that I can focus on options relevant to my institution.

**Acceptance Criteria:**

- Filter options show all universities in the system
- "All universities" option is available
- Can be combined with sorting functionality
- Filter state persists within session

#### Story 1.6: Destination Listing Page with Landscape Visuals

**User Story:** 

As a student, I want destination listings to include large background visuals, so that I can get a better feel for each study location.

**Acceptance Criteria:**

- Each card includes: Landscape image, Title, Rating
- Supports bookmarking, sorting, view toggle
- Same bookmark logic as other categories
- Visuals optimize loading time (lazy loading)
- Fallback display if images fail to load

### Milestone 2: Bookmarking Extension

#### Story 2.1: Enable Bookmarking on All Listing Entries

**User Story:** 

As a student, I want to bookmark any listing entry, so that I can revisit it later from the Bookmark Hub.

**Acceptance Criteria:**

- Bookmark icon is shown on each listing entry
- Clicking toggles bookmark state (saved/unsaved)
- Bookmarked items appear in Bookmark Hub with correct label and link
- Works for all 7 listing types, including Destinations

#### Story 2.2: Modify Bookmark Hub to Support New Listing Types

**User Story:** 

As a student, I want the Bookmark Hub to include all new listings, so that I can access bookmarked content from all areas of the platform.

**Acceptance Criteria:**

- Items from all 7 categories appear correctly
- Redirect links and category labels are shown
- Consistent formatting across all listing types
- Pagination or scrolling support for many bookmarks