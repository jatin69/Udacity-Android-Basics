# Lesson 2 : Building Layouts - Part 1

> Learn how to place layouts on a page to create images, buttons, and text on a phone screen.

## Lesson Overview

- Views
	+ TextView
	+ ImageView
	+ ButtonView
- XML
	+ element : tags with attributes form a element
	+ tags | Self-Closing tags : `TextView`
	+ attributes : `android:layout_width`
- TextView
	+ layout_height | layout_Width : dp (density independent pixels)
		* `fixed`
		* `wrap_content`
		* `match_parent`
	+ textSize : sp (scale independent pixels)
		* `24sp`
		* `?android:textAppearanceSmall` | `?android:textAppearanceMedium` | `?android:textAppearanceLarge` 
	+ textColor : color of text written inside TextView
	+ background : to specify the background color of the TextView
		* `@android:color/blue`
		* `#2196F3`
- ImageView
	+ src : `@drawable/<filename>`
	+ scaleType 
		* center - Places at center wrt to screen size
		* centerCrop - Places at center wrt to specified pixel density

## Resouces

- [Common Android Views Cheat Sheet](./Common Android Views Cheat Sheet.pdf)
- [Android Vocab by Google](https://developers.google.com/android/for-all/vocab-words) - quick lookup for commonly used terms in android
- [XML Visualiser](http://labs.udacity.com/android-visualizer/#/android/linear-layout-weight) - to practice XML 
- [Material Design Guidelines](https://material.io/guidelines/#) - for consistency and uniformity of fonts and sizes across views and activities


## Notes

- XML tags follow `PascalCase`
- XML attributes follow `snake_case`
- Java follows `camelCase`
- views / objects - dp (density independent pixels) 
- text / fonts - sp (scale independent pixels)
- When to use dp / sp for text ?
	+ In a nutshell: would increasing the text-size by around 5sp result in the text being unreadable or mangle your UI? If so use density-independent pixels. If not, use scale-independent pixels. However you should generally aim to use scale-independent pixels wherever possible, which means designing a UI that can accommodate different text sizes.
- [`textAppearanceMedium`](https://plus.google.com/+AndroidDevelopers/posts/gQuBtnuk6iG) - Remove hardcoded values and use these for consistency



