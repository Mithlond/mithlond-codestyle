# About mithlond-codestyle-war-parent

The WAR parent should be used as the parent POM of all WAR artifact projects, implying both presentation
projects and restful WARs for backend usage.

In addition to providing all facilities included in the mithlond-codestyle-api-parent, the 
mithlond-codestyle-war-parent sets up required facilities to simplify running restful unit tests. 
For this purpose, the Undertow web server is used.