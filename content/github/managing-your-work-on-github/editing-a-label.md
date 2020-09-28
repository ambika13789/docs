---
title: Editing a label
intro: 'In repositories where you have write access, you can edit the name, color, and description of an existing label.'
redirect_from:
  - /articles/editing-a-label
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

{{ site.data.reusables.repositories.navigate-to-repo }}
{{ site.data.reusables.repositories.sidebar-issue-pr }}
{{ site.data.reusables.project-management.labels }}
{{ site.data.reusables.project-management.edit-label }}
{{ site.data.reusables.project-management.name-label }}
{{ site.data.reusables.project-management.label-description }}
{{ site.data.reusables.project-management.label-color-randomizer }}
{{ site.data.reusables.project-management.save-label }}

### Further reading

- "[About labels](/articles/about-labels)"
- "[Creating a label](/articles/creating-a-label)"
- "[Deleting a label](/articles/deleting-a-label)"
- "[Applying labels to issues and pull requests](/articles/applying-labels-to-issues-and-pull-requests)"
- "[Filtering issues and pull requests by labels](/articles/filtering-issues-and-pull-requests-by-labels)"{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.19" %}
- "[Managing default labels for repositories in your organization](/articles/managing-default-labels-for-repositories-in-your-organization)"
{% endif %}