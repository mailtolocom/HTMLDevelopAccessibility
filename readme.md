# HTMLDevelopAccessibility
A web javascript to help blind developpers to inspect html web pages

## A. Purpose

When imported into grease monkey or tamper monkey, on simply called by a web page, this script add shortcuts to the web browser that a blind developper with its screen reader can use to explore the html page dom.

With grease monkey or tamper monkey, the blind user could use it on any web site he visits.

Especifically, the script create a virtual field on the current page where a treeview is simulated, and where the user can basically move in the dom with arrow keys.

While moving or using other shortcuts, informations on each important nodes are then given by saying:

* the type, name, id and class;
* position (left and top)
* dimensions (width and height)
* colors (background and text) by their code and approximate name
* font family
* margin
* inner text
* and so on

## B. Shortcuts

These are the main keyboard shortcuts added to the web browser:

* F2 = say informations on the element under the cursor in the pweb page. When pressed quickly several times, give instead information for a parent of that focussed element;
* Ctrl+F2 = move the focus to the virtual dom explorer
* arro keys = move in the treeview of the dom in the virtual dom explorer
* b = say the borders of the current selected node
* c = say the colors (background and text) of the current selected node
* d = say the dimensions (width and height) of the current selected node
* f = say the font family in the current selected node;
* shift+f = open e search dialog to find a node by its tag name
* f3 = search the next node with the criteria given in the search dialog;
* m = say the margins in the current selected node
* n = say the type, name, and class of the current selected node
* p = say the absolute positions (left and top) of the current selected node
* t = say the inner text in the current selected node
* Ctrl+home = go to the first node  of the treeview
* home = go to the first cibling
* end = go to the last cibling
* enter = show the current node description in a prompt dialog in order to be selected and copied

## C. How to install HTMLDevelopAccessibility

They are two ways of using this javascript file:

1. by simply calling it in the html of the web page you are developping.
Example:

<script type="text/javascript" src="HTMLDevelopAccessibility.user.js"></script>

2. By including it in grease monkey or tamper monkey by your favorit web browser.
In order to simplify this task, I have created the file "install.html" that you can open in your web browser, and click on the link "instal this script" to eventually add it in grease monkey or tamper monkey if you have them installed.

## D. The autor

Yannick Daniel Youale
mailtoloco2011@gmail.com
Cameroon, central Africa
