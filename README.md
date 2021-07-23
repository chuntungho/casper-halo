# Casper for Halo

[Casper](https://github.com/TryGhost/Casper) theme in [Thymeleaf](https://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html) for [Halo](https://github.com/halo-dev/halo).

It requires following static variables:
- `Map : options` - System config
- `Map : settings` - Current theme config
- `List<MenuDTO> : menus` - Navigation list
- `User : user` - Blog owner

Also based on 2 Thymeleaf custom functions:
- `themeUtil.url` - Append theme prefix to url for static resources
- `themeUtil.imgUrl` - Join image size to url for responsive image