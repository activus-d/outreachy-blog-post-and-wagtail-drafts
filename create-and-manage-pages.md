## Create new pages
To create a new page, click **`...`** Actions and select the Add child page option. This creates a child page of the section you are currently in. In this case a child page of the 'Breads' page.

## Edit existing pages
You can access an existing page's edit screen in three ways. First by clicking **Actions** and then selecting the Edit option from the dropdown. Second, by clicking the page's title if you are accessing the page from its parent's Explorer page or in search results. Last, if you are accessing the page from the Explorer page of its parent, you can hover over the page and then click Edit.

On the edit screen, you can find the title of the page you are editing at the top of the page. If the page is already published, then you can find a link to the live version of the page at the top right of the page. To change the title of the page, click the title field and enter a new title. 

While on the edit screen, you can perform several actions, such as copying, moving, or deleting a page. To perform any of these actions, click **Actions** at the top of the edit screen and select the applicable option from the dropdown.

## Create and edit comments
To toggle on commenting mode, click **Comments** at the top of the edit screen page. Once commenting mode is on, you can create a new comment or reply to a comment by hovering over any commentable field to reveal the add comment icon.

If there is no pre-existing comment in the field, click the add comment icon to create a new comment. However, if there is an existing comment, clicking either the field button or the comment brings the comment thread into focus. This allows you to add new replies.

To comment on the text within the rich text field, highlight the text and then click the add comment icon to add an inline comment.

Alternatively, you can perform all of these actions using the comment shortcut, Ctrl + Alt + M / ⌘ + Alt + M.

To edit, delete, or resolve a comment, click the three vertical dots in the top right of an existing comment and select the applicable option. Saving the page after leaving a comment or replying to a comment saves the comment or reply.

> Open an issue for adding a tooltip for the `add comment` action on the edit screen. Once this is done, modify `Edit existing page` by replacing `clicking the add comment icon` with `clicking the add comment`. [UI elements and interaction](https://developers.google.com/style/ui-elements).

## Copy pages
Sometimes, you don't need to create a new page from scratch. For example, you may have several pages that are similar in terms of structure but differ in content. In that case, you can copy an existing page and only change the required parts.

To copy an existing page, hover over a page in an Explorer page, then click **More** and select **Copy**. Selecting **Copy** from the dropdown takes you to a form where you can enter the title and slug of the copy and also choose its parent page. You then get the option to publish the copy right away and an option to mark the copy as an alias of the original page. Once you have completed the form, click Copy this page. Congratulations, you just copied a page. You can now find your copied page in the Explorer page.

## Alias pages
When copying a page, you have the option to mark it as an alias. The content of an aliased page always stays in sync with the original. This is useful when you want a page to be available in multiple places. For example, if you have a page about Brioche as a child page of Breads, and you want to make the Brioche page available in the Pastries section. One way to do this is to create a copy of the Brioche page and change the parent page to the Pastries page. However, you now need to remember to update this copy each time you modify the original page. If you mark a copy as an alias, Wagtail automatically makes changes to the copy each time you modify and publish the original page.

Creating an alias for an existing page is similar to creating a copy. Hover over a page in the Explorer page, click **More**, and then select **Copy**. Selecting **Copy** takes you to the copy page form. On the copy page form, choose another page as the parent page by clicking Choose another page. Then, click the **Alias** checkbox and click **Copy this page** to complete the aliasing. Congratulations, you just aliased a page. You can now find your aliased page in the Explorer page of the parent page.

If you try to edit the aliased page, you get a notification that it's an alias of another page. To edit an aliased page, you have two options: 
* Edit the original page. This option changes both the original page and the aliased page.
* Convert the alias page to an ordinary page, which is a copy of the original. If you choose this option, you must make manual changes to the alias page in order for it to be in sync with the original page.