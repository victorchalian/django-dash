===============================================
TODOs
===============================================
Based on the MoSCoW principle. Must haves and should haves are planned to be worked on.

Must haves
===============================================
Core and contrib
-----------------------------------------------
+ Layouts:
    + Android layout (styled).
    + Windows 8 layout (styled).
+ Documentation.
+ Group widgets.
+ Plugins:
    + Memo plugin.
    + URL plugin.
    + RSS feed plugin.
    + Weather plugin.
    + Simple news plugin.
    + Video plugin.
+ Unify the CSS usage, so that colours for font-awesome icons do get the same colour from layout.
+ Apply CSS unifications to News plugin.
+ Public dashboard (visible to everyone).
+ CRUD operations for models ``DashboardSettings``, ``DashboardWorkspace``, ``DashboardEntry`` based
  on Django permissions.
+ Template tags for permissions (edit dashboard, add workspace, etc) and templates properly adjusted.
+ Add extensive logging.
+ Make sure no strange things happen logged in with no administartive privelleges.
+ Fix Internet Explorer bug (layout not centered).
+ When running on Python 3, b'string' like values appear in the front end. Get rid of that!
+ Add authentication templates to the example application.
+ Stand alone templates top menu on click style fix.
+ Basic Django tests.
+ Demo app (installer), which would create records.
+ Log out link.
- List all (or most important) overridable settings.
+ Add news app to the demo app installer. Create a new workspace on which news app would be shown. Use
  Delusional Insanity images as image factory. Take those images from a bitbucket repository.
+ Add licenses.
+ In the example app, make use of bulk-save.

Should haves
===============================================
Core and contrib
-----------------------------------------------
- Dragging of widgets (within the Placeholder).
- Reset dashboards triggers/hoocks.
- Pre-defined template system for workspaces (with plugins in).
- Think of a convention on naming the plugins and widgets.
- Strange problems with hover in IE (all versions).
+ Make installation instructions for all plugins, especially advanced ones (that require to be added
  to ``urls`` module).
- Fix Google Chrome bug, when dash widget controls (edit/delete) being hidden under Youtube video.
- Contact form plugin.
- Blog plugin.
- When blog engine is ready, add notes about using a public site with blogs.

Example app
-----------------------------------------------
- Basic example app with a layout and couple of plugins defined.
- Implemented triggers for resetting the dashboard.

Could haves
===============================================
Core and contrib
-----------------------------------------------
- Blog application, based on public dashboard concept.
- Copy/paste widgets between workspaces.
- Google agenda/calendar plugin.
- Google docs plugin.
- Twitter feed plugin.
- Ubuntu 12.04 layout.
- Mac layout.
- In-line editing.

Would haves
===============================================
Core and contrib
-----------------------------------------------

Example app
-----------------------------------------------