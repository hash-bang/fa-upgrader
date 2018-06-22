FontAwesome migration script
============================
Simple script to automatically upgrade (known) FontAwesome glyphs.

* `fa-upgrade-3` - Upgrade from FontAwesome 3 to 4
* `fa-upgrade-4` - Upgrade from FontAwesome 4-5

Usage:

	cd /where/ever/your/project/is
	find -print0 | xargs -0 /where/this/script/is/fa-upgrade-4
