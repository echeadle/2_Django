1. Creating model managers page 33
2. Creating list and detail views page 34
3. Creating templates for your views page 38
4. Additional resources Page 43
   The following resources provide additional information related to the topics covered in this chapter:
5. Enhancing Your Blog with Advanced Features
   Chapter 2 Page 45
6. Using canonical URLs for models page 46
7. Creating SEO-friendly URLs for posts page 48
8. Adding pagination to the post list view page 52
9. Handling pagination errors
10. Building class-based views
11. Sending emails with Django page 61  
12. Using Django forms to share posts via email
13. Adding comments to posts using forms from models
14. Add then Filter posts by tags 
15. Retrieving posts by similarity
In order to retrieve similar posts for a specific post, you need to perform the following steps:
1.Retrieve all tags for the current post
2.Get all posts that are tagged with any of those tags
3.Exclude the current post from that list to avoid recommending the same post
4.Order the results by the number of tags shared with the current post
5.In the case of two or more posts with the same number of tags, recommend the most recent post
6.Limit the query to the number of posts you want to recommend
16. Creating custom template tags and filters page 106
17. Creating an inclusion template tag