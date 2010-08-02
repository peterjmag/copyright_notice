Copyright Notice
----------------

Copyright Notice is a very simple module that exposes a block called "Copyright notice". By default, the block has no title, and its content looks something like this:

©2010 Your Site's Name

It might not make sense in every site's context to use the site_name variable, so future versions of this module might allow further configuration.

The purpose of this module is merely to avoid creating a custom block and using the PHP input filter (which is usually a bad idea).

Installation
============

Simply enable the module in Site building >> Modules (admin/build/modules) and visit the Blocks config page at Site building >> Blocks (admin/build/block). A block titled "Copyright notice" should appear in the list of disabled blocks. Move it into your preferred region (e.g. your site's footer) and save.