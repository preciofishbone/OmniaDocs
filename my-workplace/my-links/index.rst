My Links
===========================

The My Links control makes it possible for the logged on user to have quick access to resources that are often used. The control will display links that are mandatory, links that the user have selected from the Common Links list, and personal links the user has created.

The My Links control is part of the Cross Site Header and is shown across all SharePoint sites in Omnia. My links can also be added separately to any legacy page as a web part or to a Quick Page as a block, to for example display the users last visited links. 

Here's an example of My Links in the Cross Sites Header:

![My Links - No links added yet](../../Images/my-links-example.png)

- **Filter links...**: The list can be filtered by typing in the top field.
- **Show all links**: Select to show all centrally handled links. 
- **Show categories**: Select to show category headings for the links. If not selected the list of links is shown in alphabetical order. If selected the list is shown, sorted on the category headings, in alphabetical order.

## Working with personal links
En users can add and remove centrally handled links that are not mandatory, from the list. End users can also add personal links.

### Selecting centrally handled links
To add a link to the personal list from the centrally managed common links, click on "Show all links".

Links that are not added to the personal list will be shown in light gray color. Add a link by hover over it and then click the plus icon (+) next to the link.

![My Links - Add common link](../../Images/my-links-add-common-link.png)

To remove a link from the list, hover the link and click the remove icon  (-) next to the link. If the link is a personally added link.

![My Links - Edit/Remove link](../../Images/my-lniks-remove.png)

### Adding personal links
To add a personal link, click on the plus icon (+) next to the "Filter links..." text box. An add link form will then be displayed.

![My Links - Add personal link](../../Images/my-links-add.png)

+ **Title**: The title for the link, shown in the list.
+ **Url**: The link url.
+ **Category**: Type a ctaegory. Links that share the same category will be grouped together when "Show categories" is selected.
+ **Information**: It is optional to add information about the link.
+ **Open in New Window**: Defines whether to open the link in a new window or not.
+ **Icon**: The user can select from built-in icons based on [Font Awesome](https://fortawesome.github.io/Font-Awesome) or any image uploaded to a document library in SharePoint.
+ **Icon background color**: Here you can set the background color for the icon, if needed.

A personal link can be deleted the same way as described above (but for e personal link, the linke is actually deleted, not just removed).

To edit a personal link, hover over the link and click the pen:

![My Links - Edit personal link](../../Images/my-links-edit.png)

## My Links Mobile Navigation

The My links control will not be shown when the screen is below a certain width. When the my links control is hidden, the mobile navigation will be shown. The mobile navigation includes the list of my links, but the user cannot add/remove links from the list.

![My Links Mobile Navigation](../../Images/myy-links-mobile-view.png)

## My Links Web Part and block
My links can also be added to any legacy page as a web part and to any Quick Page as a block. Mandatory links, links the user have selected and personal links will be displayed. The links list can not be altered through the web part/block. The my links web part/block settings are web part scoped.

Here's an example where My Links is used as a block:

![My Links](../../Images/my-links-block.png)

## The settings
To change the settings for the web part/block, active the edit switch and click  the settings gear.

This will open the settings dialog.

![My Links Web Part and block Settings](../../Images/my-links-block-settings.png)

### General
On the General tab you can set the following:

+ **Title**: Add the title to be displayed for the web part/block.
+ **Sorted by**: Choose to sort the list alphabetically or in order by last visited.
+ **View Template**: Select how to display the links, as a simple list or as app icons. (See below for some examples app icons.)
+ **Item Limit**: The maximum number of items to display before a "Show more" link appears.

Here's some examples of app icons:

![App Icons](../../Images/MyLinksBlockAppIcons.png)

### Custom Colors
You should primarily set colors through Theme colors in Omnia Admin (System/Settings/Default colors). If you still would like custom colors for the control, you can set them using this tab.

![Custom colors](../../Images/my-links-colors.png)
