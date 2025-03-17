## User Stories

# Task 1

**[1.1] As a user, I want to see a concise average rating with a clear distribution of individual star ratings, so that I can quickly understand the overall sentiment at a glance.**

**Acceptance Criteria**  
1. The system displays the overall average rating (e.g., “4.6”) alongside the total number of reviews.  
2. A visual star component (or similar graphic) reflects the exact average rating.  
3. A simple chart (e.g., horizontal bars) shows how many 1-star, 2-star, 3-star, 4-star, and 5-star reviews are in the total.  
4. The average rating and distribution chart update in real time when new reviews are added or existing reviews are modified.  
5. The display remains readable and consistent in both light and dark modes.

![Average rating with distribution of ratings](https://github.com/user-attachments/assets/87908168-8f5e-4a82-a188-38fc0b450657)

# Task 2 - Option to sort reviews by latest, oldest, highest, lowest and most liked and filter them by rating

**Sorting Reviews**

![Sample Layout for Sorting Reviews](https://github.com/user-attachments/assets/60d47a3d-e819-460b-b02b-90efa84b2fc6)

[2.1] As a user, I want to sort reviews by the most recent or oldest first, So that I can read the newest or the oldest reviews based on my preference.

Acceptance criteria:
- The system provides sorting options: "Lastest", "Oldest"
- Selecting "Latest" displays reviews in descending order by date (newest first).
- Selecting "Oldest" displays reviews in ascending order by date (oldest first).
- The selected sorting option updates the displayed reviews instantly.
- Sorting selection persists within the session unless manually changed.    

[2.2] As a user, I want to sort reviews by rating from highest to lowest or vice versa, So that I can quickly see the most favorable or the most critical reviews.

Acceptance criteria:
- The system provides sorting options: "Highest Rating" and "Lowest Rating."
- Selecting "Highest Rating" sorts reviews in descending order by rating (5-star first).
- Selecting "Lowest Rating" sorts reviews in ascending order by rating (1-star first).
- The selected sorting option updates the displayed reviews instantly.
- Sorting selection persists within the session unless manually changed.

[2.3] As a user, I wnat to sort reviews by the number of likes, so that I can see the most helpful or apprieciated reviews first.

Acceptance criteria:
- The system provides a sorting option: "Most Liked"
- Selecting "Most Liked" sorts reviews in descending order by the number of likes.
- The selected sorting option updates the displayed reviews instantly.
- Sorting selection persists within the session unless manually changed.

**Filtering Reviews**

[2.4] As a user, I want to filter reviews by specific rating values, So that I can see only reviews that match my preferred rating level.

![Sample Filter by Rating](https://github.com/user-attachments/assets/10cdbcc3-12ea-485a-8451-0aabf8a99eb6)

Acceptance criteria:
- The system provides filter options for individual rating values (e.g., 1-star, 2-star, 3-star, 4-star, 5-star).
- Users can select one or multiple rating filters at a time.
- Only reviews matching the selected rating filters are displayed.
- If no filters are selected, all reviews are displayed.
- Users can reset filters to see all reviews again.
- Filtering selection persists within the session unless manually reset.

# Task 3 - Replace description for universities, courses and programs with a link to official website

[3.1] As a user, I want to see a direct link to the official university website instead of a text description, So that I can access the most accurate and up-to-date information.

Acceptance Criteria:
- The system replaces the university description with a "Visit Official Website" link.
- Clicking the link opens the official university website in a new tab.
- The link is displayed prominently in place of the previous text description.
- If no official website URL is available, a placeholder message is shown (e.g., "Official website not available").

[3.2] As a user, I want to see a direct link to the official course webpage instead of a text description, So that I can get detailed and updated course information.

Acceptance Criteria:
- The system replaces the course description with a "View Course Details" link.
- Clicking the link opens the official course webpage in a new tab.
- The link is clearly visible and easily accessible.
- If no official course webpage is available, a placeholder message is shown (e.g., "Course details unavailable").

[3.3] As a user, I want to see a direct link to the official program webpage instead of a text description, So that I can explore the program details on the university's website.

Acceptance Criteria:
- The system replaces the program description with a "View Program Details" link.
- Clicking the link opens the official program webpage in a new tab.
- The link is displayed in a user-friendly manner.
- If no official program webpage is available, a placeholder message is displayed (e.g., "Program details not available").

# Task 4 - Light background for logos in dark mode

[4.1] As a user, I want university logos to be displayed on a light background (white or light grey) even in dark mode, So that I can clearly see all logos regardless of their color scheme.

Acceptance Criteria:

- The rectangles containing university logos maintain a white or light grey background in both light and dark modes.
- Logo containers on university, program, and subject webpages all follow this consistent light background approach.
- Logos with lighter colors (such as UC logo) remain clearly visible against the background in dark mode.
- The contrast between the logo and its background meets accessibility standards.
- The light background for logos appears as a distinct element within the overall dark mode interface.
- This light background implementation applies uniformly across all university, program, and subject listing pages.

# Task 5 - Options for uni listings to switch between with and without logo or background pictures
As a prospective university student, I want a streamlined way to view university listings on the website so that I can easily scan through the information without being overwhelmed by large logos and background images. Currently, when I search for universities, the visual elements take up a lot of space on my screen, which makes it harder to focus on the essential details like university names and key facts. By having an option to toggle between a detailed visual layout and a minimalist text-only view, I can tailor the interface to my preference—whether I want a quick overview without distractions or a more immersive experience with graphics—ultimately enhancing my overall browsing experience.

Acceptance Criteria

- Toggle Option Availability: A clearly visible toggle switch or button is available on the university listing page, allowing users to switch between "With Images" and "Text-Only" views.  

- Default View: The default view includes university logos and background images.  

- Text-Only View Behavior: When the user selects the "Text-Only" view, university logos and background images are hidden while preserving essential details such as university names, locations, and descriptions.  

- Persistence of User Preference: The selected view preference is retained while navigating through search results until the user refreshes the page or manually switches back.  

- Responsive Design: The layout should adjust appropriately on different screen sizes (desktop, tablet, mobile) to ensure a user-friendly experience in both views.  

- Performance Considerations: The removal of images should improve page load time and scrolling performance, especially on slower internet connections.  

- Accessibility Compliance: The toggle feature should be accessible via keyboard navigation and screen readers to accommodate all users.  

# Task6
Tab for helpful links for all listings with option to bookmark#6
As a prospective or current student, I want to have access to a dedicated tab displaying helpful links related to each university, program, or subject listing.So that I can conveniently explore additional authoritative resources and bookmark important links for future reference during my university selection process.

Acceptance Criteria:
A new tab titled "Helpful Links" is clearly visible within each university, program, or subject listing page.
Each helpful link includes:
A clear and concise title indicating its content.
Users can bookmark any helpful link by clicking on a bookmark icon next to it.
Once bookmarked, the icon clearly changes state to indicate the item has been saved.
Users can view and manage all their bookmarked helpful links within their personal user profile page.
Users can remove bookmarks directly from either the original listing or from the bookmarked links section.

Example Scenario:
Lucy is considering the Master of Computer Science program at ANU. She views the listing on the Student Choice website and navigates to the "Helpful Links" tab.
She finds multiple helpful resources including official program details, subject information and career outcomes.
Lucy bookmarks the program information and subject information link by clicking the bookmark icon next to each link.
Later, she revisits her personal profile page, quickly finds her bookmarked resources, and efficiently accesses the links she previously saved.

