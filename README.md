FontAwesome 2 to 3 migration script
===================================
Simple script to automatically upgrade (known) FontAwesome glyphs from version 2 to version 3.

Usage:

	cd /where/ever/your/project/is
	find -print0 | xargs -0 /where/this/script/is/fa-upgrade
