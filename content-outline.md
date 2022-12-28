# Content outline

# Content outline

## Getting started
* Overview
* Quick tutorial (review with mentors as to whether title is appropriate)

> There should be a discussion regarding the subsection `Quick tutorial`. The discussion will be on how I can create a `Bakerydemo` tutorial from the start to the end. This tutorial does not need to have as many pages as the `Bakerydemo`. However, it should be complete enough to convince a user new to Wagtail about the capabilities of the Wagtail admin interface. The tutorial should take into consideration the following details:
> * The tutorial should state what the end goal is from the beginning. This is to prepare the mind of the user that they're building towards a goal.
> * The tutorial should have clear and orderly steps that a beginner would have to take to get to a meaningful end.
> * The tutorial should state the effect of each step it directs the user to take.
> * Every step in the tutorial should be rewarding. This means that the user should be able to see the effect of each step they take.
> * The tutorial should disclose information progressively.
> * The aim of the tutorial isn't to teach the user about any feature of the Wagtail admin interface but to provide them with a picture of the capabilities of Wagtail’s admin interface.
> * The tutorial has to be complete. You should not be misunderstand this to mean that the tutorial should have all the features of the admin interface. It should be complete in the sense that it has a start that is meaningful to a beginner and a meaningful end.
> 
> ### Possible issue
> The users of the admin interface may not be programmers and the user may not be working on a deployed Wagtail. The instructions on how to work with the `Bakerydemo` within a development environment have to be simplified. One way to avoid complications by users who are not programmers is avoiding the use of a virtual environment and documenting how to work on the `Bakerydemo` with `Gitpod`.

## Concepts
* Admin interface
* Pages
* Streamfield
* Embeds
* Snippets
* Reports
  * Locked pages
  * Site history
  * Aging pages
* Page status definitions
  * Live
  * Draft
  * In Moderation
  * Scheduled
  * Expired
  * Live + Draft
  * Live + (another status)
* Users
* Locales
* Styleguide
* Multi sites
* ModelAdmin
* Table block
* Supercharged
* Server error

```Note
According to Storm, "ModelAdmin "is similar to "Snippets". The likely long time goal  
is to have the former replaced with the latter.  
If this is the case it may be a good idea to leave "ModelAdmin" out of the How-to  
guides so as to promote the use of "Snippets".  
Having it in the concept section might be great for users who may find it very important.
```

## How-to guides

* Find your way around
  * The wagtail dashboard
    * How to reach the dashboard (review as it is not parallel in structure with subsequent headings)
    * The Wagtail dashboard panels
    * The Wagtail explorer pages
    * The Wagtail sidebar
    * Search Wagtail
    * Adjust Wagtail's settings
    * Get help

```Note
I do not see any difference between "The wagtail sidebar" and "The sidebar" as used in the  
existing user guide document. My suggestion is to merge the content of both elements into one.

It appears to me that the commands, Search, Pages, Images, Documents, reports, Snippets, and  
Forms are not needed in this subsection. Our focus should be on documenting them in the light  
of their functionality and not as UI elements. I believe mentioning them in the content for  
Sidebar to aid in locating them and as a way to introduce them to the user may be a better  
idea. The best section to host these commands is the Explanation or Concepts section.

The item "Reordering pages" in the existing user guide document would find a better use and  
purpose an item in `Manage pages`. This means it should be on the same level as 
"Finding your way around".
```

* Manage pages
  * Create a new page
  * Edit an existing page (edit locked, edit promote tab, edit settings tab)
  * Manage revisions
  * Workflow
  * Create comments
  * Edit comments
  * Copy pages
  * Alias pages
  * Reorder pages
  * Publish and unpublish pages
  * Schedule publishing
  * Lock pages
  * Search pages
  * Delete pages
  * Typed table block (review as to whether it's placement is right)
  * Reorder pages
  * Preview pages
* Manage documents
  * Add documents
  * edit documents
  * Change documents
  * View documents
  * Search documemts
  * Make documents private
  * Delete documents
* Manage images
  * Add images
  * edit images
  * Change images
  * Focal area
  * View images
  * Search images
  * Generate image URL
  * delete images
* Manage snippets
  * Snippets menu
  * Add snippets
  * Edit snippets
  * Add images and documents to snippets
  * View snippets
  * Search snippets
  * Delete snippets
* Manage collections
  * Add a collection
  * Add images to a collection
  * Add documents to a collection
  * Make collections private
* Manage tags
  * Add images to tags (review as to whether it's possible)
  * Add documents to tags (review as to whether it's possible)
* Manage groups
  * Add group
  * Edit group
  * Group users
  * View group
  * Search groups
  * Delete groups
* Manage forms
  * View forms
  * Build forms
* Manage redirects
  * About redirects
  * Configure redirects
* Manage sites
  * Add sites
  * Edit sites
  * View sites
  * Multi sites (review as to whether it's placement is right)
  * Delete sites
* Manage users and roles
  * Editor
  * Moderator
  * Admistrator
* Configure and moderate workflows
  * Add workflow
  * Edit workflows
  * Create and edit workflow tasks
* Promote search results
* Translate Wagtail sites
* Reset password

## Reference
* Browser issues

## Releases
* New in Wagtail

## Contributing
```Note
It should be stated that the user guide website uses Wagtail CMS
```

## About