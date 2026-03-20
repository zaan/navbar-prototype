
# The main left navigation bar:
* It allows switching between main product areas like modules, profile settings
* By default it is collapsed but can be expanded when clicked on the "hamburger" icon. 
It expands over the content on the right so width of other elements doesn't change.
This behavior is designed on images with name starting from collapsible_
* Starting from the top, it has links to following places:
	* Expand / collapse the sidebar
	* Analytics
	* Data Activation
	* Tag Manager
	* Administration
	* Help center (outlink to help.piwik.pro)
	* User Profile
	* Developer docs (outlink to developers.piwik.pro)
	* Dark mode / light mode
	* Logout
* When collapsed, each item has a tooltip
* Currently selected section has blue icon and background
* When switching between modules, the entire page is reloaded. It takes around 3 seconds


# Modules (Analytics, Tag Manager and other):
* Each module has its own navigation bar at the top. All of those elements should be interactive.
If you're missing the design of specific tab, the content should have only a header with the name
of the tab and the rest should be empty.
* When the specific tab is selected its colour is blue as on designs.

# Side selector
* At the top right corner there is a site selector. It is a dropdown with the ability
to select a different website. 
* Available sites: Piwik PRO, User docs, Developer docs
 