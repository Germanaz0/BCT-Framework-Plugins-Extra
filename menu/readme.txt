
@file
Basic menu tool.

This tool provides a way to define and display a navigation menu, use CSS to skin accordingly.

The tool makes no attempt to define a standard set of menus, it just provides a way of doing so
should you want to - however calling the view on its own will use 'default' so this may be a good
main menu :)

@section Example:
\code
$CONFIG->menus['menu'] = array('context' => 'url');
\endcode

Labels are: menu:label:$menu:$context

@package menu
@license The MIT License (see LICENCE.txt), other licenses available.
@author Marcus Povey <marcus@marcus-povey.co.uk>
@copyright Marcus Povey 2009-2012
@link http://www.marcus-povey.co.uk

