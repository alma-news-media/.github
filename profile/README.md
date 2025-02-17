# alma-news-media

Organization for Alma News Media software development.

## Creating new repositories

Repository-settings github app has been installed to this organization. That means that virtually all repository settings can be administered through pull-requests by 
changing file .github/settings.yml in repository.

Because of this, all new repositories should be created using default-template repository template or your own team's template that is derived from default template. The template 
ensures that the settings file is installed to new repository with sensible default settings such as repository admin group and CODEOWNERS that protects the repository settings from 
changes without review.

New repositories should be created internal. The settings from template enforce this and for a good reason this can be overridden afterwards through the settings file.

## Owners group

Organization owners that are allowed to change all organization settings:
- Markus Heikkilä
- Tomi Vainio
- Valon Ruka
- Onni Valkeapää

## Admins group

Admin group can approve PRs to default template and .github repositories:
- Markus Heikkilä
- Joni Väyrynen
- Ukko Sarekoski
- Janne Saraste
- Pentti Oinonen

## Developers group

All users invited to organization should be added to Developers group. By default this group is set as admin to all repositories excluding .github repository of the organization.

## Other user groups

Other groups can be created as needed by organization owners. One example use case is group for specific team that can then be used to request reviews. All groups should have Developers as parent group.
