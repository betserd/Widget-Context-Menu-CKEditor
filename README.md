# Widget-Context-Menu-CKEditor
A CKEditor plugin which makes it possible to edit, copy and remove widgets using the right click context menu. This overcomes the problems of some widgets that are difficult to select. The name of the widget in the context menu is the title of the outer element, if that does not exist it shows the name of the widget.

Configuration

By default no configuration is required. To disable commands use any of the following config settings:

config.widgetcontextmenu_edit = false;
config.widgetcontextmenu_copy = false;
config.widgetcontextmenu_remove = false;

Dependencies:

Context Menu Plugin (http://ckeditor.com/addon/contextmenu)
Widget Plugin (http://ckeditor.com/addon/widget)
Installation:

Add the widget to your CKEditor build 
OR
Extract the downloaded file into the CKEditor’s plugins folder.
Enable the plugin by changing or adding the extraPlugins line in your configuration (config.js): config.extraPlugins = 'widgetcontextmenu'; 
