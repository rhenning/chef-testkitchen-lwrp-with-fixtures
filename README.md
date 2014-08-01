chef-testkitchen-lwrp-with-fixtures
===================================
This is a simple cookbook called "junk" that defines a LWRP and no recipes.  It contains a TestKitchen "fake" cookbook that uses the LWRP.  Note that we do not include_recipe or explicity put "junk" into any run_lists.  We simply declare in fake's metadata.rb a dependency on the "junk" cookbook and the LWRP is available in fake's recipes.
