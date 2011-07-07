#CodeIgniter Multiple Upload Library
Just an extension to the existing Upload class to take advantage of multiple uploads in one form field

##v.0.1: July 7, 2011

__Description__
This version is a quick and dirty first pass for a project I'm currently working on. I haven't worked on the error reporting piece yet, so feel free to send in that contribution if you're so inclined.

__Installation__
Copy the MY_Upload to your application/libraries directory.
If you are using a prefix other than MY_ for your classes and/or alternative file paths, adjust accordingly.

__Usage__
Load the Upload class as usual, in your controller call the function do_multi_upload(). If you are uploading a single file, it'll default to the regular do_upload() method.


