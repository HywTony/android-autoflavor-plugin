auto-product-flavor-plugin
==========================

When applied to an Android application or library, this plugin will detect product flavors, based on the folder structure and create them automatically. Any product flavors declared in the actual build.gradle file will override those created "automatically" by this plugin. In other words, simple flavors can be auto-generated in a consistent way while still leaving room for more complicated flavors (that don't fit the typical pattern) to be created, normally.
