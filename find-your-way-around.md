# Find your way around
This section describes the different pages that you are going to see as you navigate around the Wagtail **Admin interface**.
## The Dashboard
The **dashboard** is the main hub of the Wagtail website. From the dashboard, you can access all of the content you create in Wagtail as well as reports, settings, and other content management features.

If you access a new version of Wagtail for the first time, your **Dashboard** shows a banner notifying you of the changes to Wagtail. The banner has a link to the Editor guide where you can learn more about these changes.

The following is a quick overview of the dashboard's different panels and tools:

```Note
What you see in your **Dashboard** depends on your user role. Common user roles include editors, moderators, and administrators.

Wagtail is highly customizable, so your **Dashboard** may look different from the one in this demonstration. This Editor guide uses the Wagtail Bakery for demonstration purposes. If you have trouble locating a panel or feature, you may want to ask your webmaster or developer if they added any customizations.
```

### How to reach the Dashboard
Logging into Wagtail automatically takes you to the **Dashboard**. If you navigate away from the dashboard, you can return to it at any time by clicking on the Wagtail logo in the top-left section of your screen.

### The Dashboard panels
The dashboard panels provide you with an overview of the various states of your Wagtail pages. The different panels on your dashboard are as follows:

#### Your pages in a workflow
The _Your pages in a workflow_ panel shows you any pages in moderation that you own or have submitted for moderation yourself. It also shows the moderation tasks that are pending and how long the tasks have been open. 

#### Awaiting your review
If your webmaster or web developer gives you permission to perform moderation actions, your Wagtail dashboard displays the _Awaiting your review_ panel. This panel shows content that's ready for you to review.

From the panel, you can perform the following actions:
* Click the name of a page to edit that page.
* Use the buttons to move the page to the next stage in your workflow by requesting changes to a page, approving the page, or approve the page with a comment.
* Get a quick view of the page status by hovering over the indicator circles to get more information about the pending task. The indicator circles show a tick for a completed task or an empty circle for an incomplete one.
* See how long a page has been waiting for review.

#### Your most recent edits
The _Your most recent edits_ panel displays the five pages you last edited. The panel also shows the date that you last edited the pages as well as the current status of the pages.

#### Your locked pages
The _Your locked pages_ panel shows all of the pages you've locked so that only you can edit them. From this panel, you can quickly view the date you locked a page. To edit a locked page, click the name.

### The Sidebar
On the left-hand side of the dashboard and throughout Wagtail is a menu called the **Sidebar**. You can use the Sidebar to navigate to different parts of Wagtail.

The **Sidebar** helps you quickly access your content as well as Wagtail features and settings. The items on the **Sidebar** can vary depending on what your developer or webmaster decides to give you access to. A standard Wagtail installation has the main Wagtail features in the sidebar. These features include Search, Documents, Snippets, Forms, Reports, Settings, and Help.

```Note
If you want the **Sidebar** to take up less space, you can click the white arrow near the top of the **Sidebar** to switch it into slim mode and give yourself more space for writing.
```

### The Explorer page
The Explorer page allows you to view a page’s children and perform actions on them. In the Explorer page, you can publish and unpublish pages, move them to other sections, drill down into the content tree, or reorder child pages within a parent.

You can see the name of the page whose explorer page you are on at the top of the screen. If the page has child pages within it, then you can see a list displaying the child pages. Clicking the title of a child page takes you to the edit screen, from which you can edit that child page.

If you hover over a child page, you get an arrow on the right-hand side of that child page row. Clicking the arrow displays a further level of child pages.

Additionally, hovering over a child page displays a checkbox at the left-hand side of the child page row. Selecting one or more child pages by clicking their checkboxes gives you an action bar at the bottom of the Explorer page. Clicking on any of the options in the action bar takes you to a confirmation page from which you can confirm the action.

As you drill down through the site, the breadcrumb (the row of pages beginning with the home icon) displays the path you have taken. Clicking on the page titles in the breadcrumb takes you to the Explorer screen for that page.

Clicking on the **… Actions** dropdown shows a list of actions for the parent page, like Move, Copy, Delete, Unpublish, and History. Also, clicking the Sort menu order option from the dropdown takes you to the ordering page.

To view the parent page on the live website, click **Live** from the top-right side of the Explorer page.

### Search Wagtail
The search feature is the topmost feature in the Wagtail **Sidebar**. You can use the search feature to quickly search for content in Wagtail.

### Adjust Wagtail's settings
Click **Settings** from the Wagtail sidebar to access Wagtail settings. If you have the correct role, you'll be able to add users, add user groups, and perform other administrative tasks.

### Get help
Click **Help** from the Wagtail sidebar to access links to the user documentation and the new features of the latest version of Wagtail.


> I noticed that the document used the terms `tools` and `features` interchangeably. To bring about consistency in terms, I have decided to go with the term `features`. The reason for this is that I believe the term `features` can be used more broadly to cover both the wagtail tools and the other components that may not be strictly regarded as tools.
> I also think using the term `toolbar` is confusing since it basically the same as the `sidebar`. In this draft, I  substitute the term `toolbar` with `sidebar` to avoid confusing the user.
