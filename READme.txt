A Social Website - "Image bookmarking website"

features:
- Custom Login, Logout, Password change, Password Reset using url on email, SignUp
- Image upload for profile (profile pic)
- Message Notification
- Custom Email Authentication
- Social Authentication (Login using fb/twitter/google)

- Many to Many relationship between User and Images
- Saving images using Jquery Bookmarklet
- Displaying saved image using sorl-thumbnail
- Like-Unlike feature for every Image using AJAX
- Displaying all User's profile pic who likes the Image
- Displaying list of all images using AJAX and Django's Paginator
- Follow existing Users
- Displaying User Actions (News Feed)
    (generic activity stream using select_related() and prefetch_related())
- Displaying images by popularity (likes count)
    (using 'm2mchanged' signal for denormalizing counts)