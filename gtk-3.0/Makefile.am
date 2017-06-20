gtk.css: adwaita-blue.scss
	sassc adwaita-blue.scss gtk.css

gtk-dark.css: adwaita-blue-dark.scss
	sassc adwaita-blue-dark.scss gtk-dark.css

gtk3dir=$(datadir)/themes/Adwaita-blue/gtk-3.0
gtk3_DATA = \
	gtk.css \
	gtk-dark.css

gtk3assetsdir=$(datadir)/themes/Adwaita-blue/gtk-3.0/assets
gtk3assets_DATA = \
	assets/*

EXTRA_DIST = \
	assets/* \
	_common.scss \
	_colors-public.scss \
	_colors.scss \
	_drawing.scss \
	adwaita-blue.scss \
	adwaita-blue-dark.scss

uninstall-hook:
	-rmdir $(datadir)/themes/Adwaita-blue/gtk-3.0/assets
	-rmdir $(datadir)/themes/Adwaita-blue/gtk-3.0
	-rmdir $(datadir)/themes/Adwaita-blue
