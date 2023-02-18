# Page
You can use Wagtail Pages to organize the content of your Wagtail websites. It's common for a typical website to have multiple web pages, and the web pages themselves can have several sections. The same is true for Wagtail pages. Wagtail pages can have child pages within them. In turn, these child pages can have child pages of their own.

Although rare, it's also possible for a single Wagtail page to serve the content of an entire website. 

## Wagtail page structure
The structure of a Wagtail website is like a tree. At the top of this tree-like structure is a Root page which branches off to several child pages. For instance, in the bakery demo website, the Welcome to  the Wagtail Bakery page is the Root page, while the Breads, Blog, About, Locations, Gallery, and Contact us pages are immediately below it on the tree.

## Nature of the relationship between Wagtail pages
When a website takes its content from multiple Wagtail pages, it indicates that there is a parent-child relationship between the pages. A Wagtail parent page has within it one or more child pages. For instance, in the Admin interface of the Bakery demo, if you click Pages from the Sidebar, the Sidebar extends to show you the Welcome to the Wagtail Bakery page. The Welcome to the Wagtail Bakery page is a parent page. Clicking it takes you to its Explorer page, where you can see all the child pages within it.
Page types
You can have different page types available for you to use in the Admin interface. Developers usually configure Wagtail page types during the development stage. 
Having multiple page types in your Admin interface allows you to choose the structure you want your page to adopt. You can choose a page type for your pages when you are creating them.
The page type of a parent page may differ from that of the child pages within it. For instance, in the Admin interface of the Bakery demo, the page type of the Welcome to the Wagtail Bakery page is Home Page. Its child page Breads has the Breads index page type, while Blog, another child page has the Blog index page type.



