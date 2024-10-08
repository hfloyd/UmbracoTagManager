# Umbraco.Community.TagManager

Tag utilities for Umbraco ≥ 10. 

Based on code from https://github.com/usome/UmbracoTagManager and https://github.com/huwred/Tag-Lister

This package installs a custom section within the administration area and a new DataType.

## TagManager
Creates a tree view of all tags that have been created by the Umbraco Tag Datatype. 

The tree is split into separate branches for each tag group created - useful if you run multiple blogs on your site, or have multiple tag groups defined in a site.

Functionality includes:

1. Ability to edit tag data
2. Ability to delete tags
3. Tags on nodes / media updated with edited tag
4. Indication of how many times the tag is currently being used (number in brackets).
5. Ability to move all tagged nodes to another tag - useful in cases of spelling mistakes, cleaning up tags, etc.
6. Links to content and media where tag is used.

## Tag List
A new DataType for multiselecting from a list of common Tags.
