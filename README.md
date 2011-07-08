Overview
========

From time to time I have to look at JSON formated configuration files. 
Doing this hurts my eyes!  To make my life slighlty easier I can convert
them to the YAML layout instead. 

What is in here
===============

  * json2pretty 
     Takes a  hard to read optimized one line of JSON and makes it pretty.
  * json2yaml
     Takes a JSON file and outputs it to STDOUT in YAML format
  * yaml2json
     Takes a YAML file and outputs it to STDOUT in JSON format
  * yaml2json-ugly
     Takes a YAML file and outputs it to STDOUT in that hard to read  but 
     optimized crap

Goal 
====
Take two JSON files and compare them to see what there differences are.
If you were to diff the example files you would find see they are different.
Different internal layout but they contain the same information. (I just 
copied different blocks around).

I want to diff either the JSON or the YAML and find the section or sections 
that have changed or have been added.

Why
---

> * Opscode chef-server stores data bags in json format.

> * You can edit a chef-server data bags file in a local editor. The import that 
   with the knife command into the chef-server. You have a physical file.

> * You can edit the chef-server data bags directlry with knife in you favorite
>   editor. When you save the tempory file it is imported into the chef-server.

> * What if Admin Bob edits the chef-server data bag directly with knife and 
>   Admin Jill edits the same data bag locally and pushes it to the server.

> ** I need to be learning Ruby. (Python, C, C++, Perl, JavaScript, etc...)



### Yazz D. Atlas © 2011

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
