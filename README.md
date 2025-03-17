# aem-migration - JMH Website

## Templates (static) used Count: 8
-------------------------------------
| Template | Count | Eg: Pages |
| -------- | ----- | --------- |
|   /apps/jmh/templates/content       |  200     | /content/jmh/en/shared      |
|                                     |          | /content/jmh/en/home/about-john-muir-health/newsletters |
|                                     |          | /content/jmh/en/home/find-doctor |
|/apps/jmh/templates/fragment         |   8       |/content/jmh/en/shared/footer |
|                                     |          |/content/jmh/en/shared/top-navigation |
|                                     |          |/content/jmh/en/shared/top-navigation/patients |
|                                     |          |/content/jmh/en/shared/top-navigation/services |
|                                     |          |/content/jmh/en/shared/top-navigation/health-education |
|                                     |          |/content/jmh/en/shared/top-navigation/for-physicians |
|                                     |          |/content/jmh/en/shared/top-navigation/giving |
|                                     |          |/content/jmh/en/shared/top-navigation/about |
|  /apps/jmh/templates/generic        |   1      |/content/jmh/en/home/patients-and-visitors/payment-and-insurance/paying-for-services/online-bill-pay |
| /apps/jmh/templates/page-article    |  318     | /content/jmh/en/home/about-john-muir-health/press-room * |
| /apps/jmh/templates/page-campaign   |  4       |/content/jmh/en/home/services/cancer-services/* |
| /apps/jmh/templates/page-content    | 1627     | /content/jmh |
|                                     |          |/content/jmh/en |
|                                     |          |/content/jmh/en/home/about-john-muir-health |
| /apps/jmh/templates/page-home       |  1       |  /content/jmh/en/home |


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
