## Disclaimer: ##
This module has been made to ease the activities of custom styling for user-facing content forms.
This module was built with heavy code guidance from references_id_trim.module and some help from the #drupal-support irc.
I have not yet tested this module on field collections or other newer/obscure entities.

# Installation: #
1. Drop module package into module folder
2. Enable on module page
3. Go to a field settings page, [site]/admin/structure/types/manage/[type]/fields/[field] and scroll to the bottom.
4. Enter a comma separated list of css classes in the 'Add These Classes...' field 
5. Enter some css styling for those classes in your style sheets
6. Marvel at how you did not have to write a list of 18 field ids into your theme styles to cherry-pick which ones get which style
7. Enter the drupal irc and type: developerweeks++     ( for great karma! )

# Intented Use: #
  My company is building several sites with field-intensive, user-facing content forms.  These forms are often required to stylistically match an arbitrary standard.  Finding the right combinations of fieldsets and descriptors for css was taking too much time.
  I had found modules that do this for displays already, field_formatter_class and field_formatter_css_class, but I did not find one for the form side of things.  This module is intended to mend that shortfall.
