7. body and info that you want to post to the social site 

8. object data

9. https://practiceapi.devmountain.com/api/posts?id=555

10. Returns an array of filtered posts
Request query is missing required text property.

11. https://practiceapi.devmountain.com/api/posts

{
"text": "Nate"
}

12. https://practiceapi.devmountain.com/api/posts

{
"text": "blue"
}

13. https://practiceapi.devmountain.com/api/posts/filter?text=blue

14.  content-type: application/json; charset=utf-8 

15. Request was missing req.query.id or req.body.text

16.  The only response is too send all the posts. No way to filter 