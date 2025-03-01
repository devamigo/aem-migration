# aem-migration - JMH Website

## Templates (static) used Count: 8
-------------------------------------
* /apps/jmh/templates/content
* /apps/jmh/templates/fragment
* /apps/jmh/templates/generic
* /apps/jmh/templates/page-article
* /apps/jmh/templates/page-campaign
* /apps/jmh/templates/page-content
* /apps/jmh/templates/page-event
* /apps/jmh/templates/page-home


### Total pages  : 2647

# PRC Website

## Templates (static) used Count: 6
-------------------------------------
* /apps/prc/templates/contactus
* /apps/prc/templates/content
* /apps/prc/templates/contentdetails
* /apps/prc/templates/homepage
* /apps/prc/templates/public
* /apps/prc/templates/resources

### Total Pages: 665

# Tried Modernization tool.

Note: for Tool setup used
aem-modernize-tools.all-2.2.0-aem65.zip, 238 KB, Jun 6, 2024 (when using aem-modernize-tools.all-2.2.0.zip it gave budle dep error for caom.day.cq.search)
(Not sure exactly what made it work, may enabling the components ?)


1. Created a new site (aemoprem) using latest archetype(v51) and then tried to use import tool to migrate /content/jmh/en/home to /content/jmh/us
	* It just copied, but couldnt identify 
		* Structure Rules	
		* Policies	
		* Policy Rules	
		* Components	
		* Component Rules

		Why?
