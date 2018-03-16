# 2018-03-Wiki
Let's a build a simple wiki

# Challenge for March

Let's create a simple wiki software.

This wiki will be very simple, not users auth, just the ability to display pages and create/edit new pages.

The wiki should have the following methods:

GET /page/{{$category/..}}/{{$page}}.md
If the page does not exist, it should redirect to edit page.
GET /edit/{{$category/..}}/{{$page}}.md
Will be used to both edit or create a new page.
POST /etc/{{$category/..}}/{{$page}}.me
Will change the page.
DELETE /etc/{{$category/..}}/{{$page}}.md
Will delete the page.

You are free to choose how to want to implement this.
Once you have the basic implemented; see if you can add some meta data to the page.
What about versioning of each page.
Storing images and other types of media.

