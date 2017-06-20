gtk2dir=$(datadir)/themes/Adwaita-blue/gtk-2.0
gtk2_DATA = \
	gtkrc \
	apps.rc \
	hacks.rc \
	main.rc

gtk2assetsdir=$(datadir)/themes/Adwaita-blue/gtk-2.0/assets
gtk2assets_DATA = \
	assets/*

EXTRA_DIST = \
	assets/* \
	apps.rc \
	gtkrc \
	hacks.rc \
	main.rc

uninstall-hook:
	-rmdir $(datadir)/themes/Adwaita-blue/gtk-2.0/assets
	-rmdir $(datadir)/themes/Adwaita-blue/gtk-2.0
	-rmdir $(datadir)/themes/Adwaita-blue
