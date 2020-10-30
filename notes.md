Associations:

<!-- User
    -has many posts -->
<!-- Post
    - belongs_to user
    - has many tags through post_tag -->
<!-- Post_tag
    - belongs to post
    - belongs to tag -->
<!-- Tag
    - has many post_tag
    - has many posts through post_tag -->



<!-- 1. include content:text in posts table -->
<!-- 2. rails g model for User and Tag
    - --no-test-framework -->
<!-- 3. create user and tag controllers -->
<!-- 4. create join table user_tag -->
<!-- 5. build out associations in models -->
<!-- 6. create routes with resources -->
<!-- 7. migrate, and seed it -->

<!-- 8. validations for post
    - presence of name and content -->
<!-- 9. validations for user
    - uniqueness of name -->
<!-- 10. validations for tag
    - uniqueness of name  -->

11. create a form on post form page that lists all tags as checkboxes
    - collection_check_boxes