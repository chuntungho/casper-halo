# Casper for Halo

[Casper](https://github.com/TryGhost/Casper) theme in [Thymeleaf](https://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html) for [Halo](https://github.com/halo-dev/halo).

It requires following static variables:
- `Map : options` - System config
- `Map : settings` - Current theme config
- `List<MenuDTO> : menus` - Navigation list
- `User : user` - Blog owner

For i18n, use `#themes.code(messageKey)` to get localed message defined in i18n/i18n_xx.properties.

![screenshot](screenshot.jpg)