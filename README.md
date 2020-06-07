# React
### React has no strong opinion on a recommended way to structure React projects; but there are two suggestions:

**Grouping by features or routes**: This approach locates CSS, JS, and tests together inside folders grouped by feature or route.

    common/
    Avatar.js
    Avatar.css
    APIUtils.js
    APIUtils.test.js
    feed/
    index.js
    Feed.js
    Feed.css
    FeedStory.js
    FeedStory.test.js
    FeedAPI.js
    profile/
    index.js
    Profile.js
    ProfileHeader.js
    ProfileHeader.css
    ProfileAPI.js

Read more in [React Doc](https://reactjs.org/docs/faq-structure.html)
