FM-AJAXPOST
===========
Using Javascript to handle our request allows us to control setting the HTTP header as well
as submitting the content in other formats, such as JSON or XML, instead of the commonly 
used key/value pairs that get submitted as text.

Furthermore, this method does not use any plugins, so will also work in FileMaker Go. It may 
also work in WebDirect, however the method we use for returning information via a FMP url 
will not work in WebDirect, but could use some custom web publishing to get similar functionality.

In the example file, we use some rather straightforward Javascript (no jquery or other 
dependencies) to create our request and return whatever response we get as a result, and log 
that in our database. By substituting in our values into the HTML used to perform the request, 
we can easily reuse this code for lots of different purposes.

Read more here:
http://www.soliantconsulting.com/blog/2014/11/filemaker-and-javascript-ajax-post

Video walk through:
http://youtu.be/B_pArX3W61U
