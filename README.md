# aspnet-mvc-sidebar
ASP.NET MVC layout with sidebar (sidebar.less, _Layout.cshtml)

## Integration with your application
* Include sidebar.less into your project
* Setup sidebar.less parameters
* Inclue sidebar.css in bundle ~/Content/css
* In _Layout.cshtml apply sidebar-navbar-inverse (see source for an example)
* Apply sidebar-navbar-container
* Add divs sidebar-layout, sidebar-aside-content
* Move body-content inside sidebar-layout and apply sidebar-body-content
* Insert content of sidebar into div sidebar-aside-content