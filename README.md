# Magento Commerce QoL Demo Improvements

A bunch of simple changes to Magento OS and Commerce that help me out.

## List of improvements/adjustments made
* Content Staging Preview
    * Responsive using window resize or Chrome device preview
    * Adjusted Logo, Calendar & Scope controls
    * Adjusted Calendar and Scope dropdowns

![Content Staging w/ Viewport](image_staging_viewport.gif "Content Staging w/ Viewport")

* Frontend CSS changes
    * Category Page Full Width
        * Hide Header
        * Hide Breadcrumbs
    * Full Page Width CMS
        * Minimize navigation spacing
    * PB Product Grid -> Mobile Slider
        * For mobile, make product grids in PB a horizontal slider instead of stacked
* Performance Improvements
    * Reduced reindexing batch sizes to improve index performance on smaller platforms
* Added whitelist for Adobe Target

## Boring stuff

This code is provided "as is" and not intended for production use. It is created to improve my own personal workflow and is not endoresed or supported by myself, my employer or anyone else associated with the code. If you use this, you do so at your own risk, and with full knowledge of what you're doing.