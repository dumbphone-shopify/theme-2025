# theme-2025
*Editing the theme of Dawn.*
## LINK TO OFFICIAL DOCS HERE:
### Overall docs relevant to us: [Shopify's overall theme architecture](https://shopify.dev/docs/storefronts/themes/architecture/)
This explains the general structure and features of Shopify and the themes components.

### [Sections and blocks:](https://help.shopify.com/en/manual/online-store/themes/theme-structure/sections-and-blocks)
This gives a good deep dive about how we can work with sections and blocks. We will probably want to refer to this quite a bit at the start.
### [Input settings:](https://shopify.dev/docs/storefronts/themes/architecture/settings/input-settings)
This is where to find out about which *customisable settings* we want to add to our modules, such as ***sections*** and ***blocks.*** 

## Good to knows:
- Schema is the part of the code that will be visible in the theme-editor.
- The `"name"` inside `{% schema %}` sets the name that will be present in the sections-list in the theme-editor. (web-ui)
- `"settings:"[]` is where you write the input settings that the user will be able to interact with and customise in the theme-editor. 
- "tag" is the name of the wrapping element around the section. Can be either of these: 
	* `article`
	- `aside`
	- `div`
	- `footer`
	- `header`
	- `section`
- Blocks are like sections within sections - repeatable content within the main section.
