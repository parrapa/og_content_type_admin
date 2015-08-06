# og_content_type_admin

Drupal 7.x module.
Enhance OG functionality https://www.drupal.org/project/og
Allows restriction of content type use based on group.

Since the permission system only lets the admin allow/disallow
creation of content types and can't specify WHERE they can be used,
this module solves that problem. This module allows the
admin to limit content types available site-wide and by group. 
Group owners can then choose which types to use within their group. 
Group owners can use ALL content types ALLOWED to that group, even 
if that owner only ACTIVATES a subset of those types for use by 
his members. All regular permissions and roles are still valid and 
this module will not override your settings there. So, given that 
a user has permission to create a content type SOMEWHERE, this 
module will limit where exactly they can do that. You can limit 
or even forbid creation of content at the site level, at the overall 
group level, or at individual groups.
