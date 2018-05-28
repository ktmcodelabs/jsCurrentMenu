# jsCurrentMenu
Highlights current page in navigation menu (adds class 'active' to current page menu)

## How to
Include [jQuery](https://code.jquery.com/) library

Include **jsCurrentMenu.js**

Initiate *jsCurrentMenu* to required menu element
```
<script type="text/javascript">
    $('#sidebarMenu').activeMenu({
        current: "{{CURRENT_URL}}"
    });
</script>
```
