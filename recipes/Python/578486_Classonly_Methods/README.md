## Class-only Methods 
Originally published: 2013-03-07 19:55:04 
Last updated: 2013-03-08 17:00:53 
Author: Eric Snow 
 
We use the classmethod builtin to tie methods to the class rather than the instance.  This is really useful for a variety of things, like alternate contructors.  However, sometimes you don't want to expose the method on the instances, just on the class.