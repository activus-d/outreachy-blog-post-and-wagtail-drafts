# Manage redirects

## About redirects
In the course of publishing and unpublishing pages, you eventually need to make redirects. A redirect helps send visitors and search engines to a new page if your webpage becomes unavailable (404). This way, visitors won’t end up on a broken journey that results in a "page not found."

Wagtail considers two kinds of configurations for a redirect, depending on whether Permanent remains checked or not:
* Permanent redirect (checked by default)
* Temporary redirect

For both redirect configurations, the visitor won’t notice a difference when visiting a page, but search engines react to these two configurations of redirect differently. In the case of a temporary redirect, a search engine keeps track of your old page and indexes the redirected page. However, with a permanent redirect, a search engine marks the old page as obsolete and considers the new page as a replacement.

```Note
As a best practice, Wagtail checks redirects as permanent by default. This is to prevent the undermining of your search engine ranking.
```

## Configure redirects
To configure redirects, go to **Settings > Redirects** from the Wagtail **Sidebar**. You can create a new redirect and edit or search for an existing one from the Redirects interface.

### Add redirects
You can create a new redirect by clicking **Add redirect** in the top-right of the Redirect interface. Then set **Redirect from** to the URL pattern that's no longer available on your site. If your Wagtail is multisite, set the **From site** to the site that has the unavailable URL pattern. By default, Wagtail sets a redirect to a _permanent redirect_. To configure your redirect as a temporary one, uncheck the Permanent checkbox.

While _Redirect to a page_ allows you to redirect visitors and search engines to a new page within Wagtail, the _Redirect to any URL_ field allows you to  redirect to a different domain outside of Wagtail.

### Edit and search redirects
Edit the details of an existing redirect by clicking the URL path of the redirect you want to configure on the Redirect interface. Search for existing redirects by entering your search term in the search bar. The results automatically update as you type.

```Note
Keep in mind that a redirect only be initiates if the page is not found. It doesn't apply to existing pages (200), which resolves on your site.
```

> Discuss with mentors on what exactly the search term for a redirect is. Are users searching with the _Redirect from_ pattern or otherwise? Make sure to discuss with the mentors on how to maintain consistency when using the terms _interface_ and _screens_.
