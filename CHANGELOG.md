# Change Log - refer to http://keepachangelog.com/

## [Unreleased][unreleased]

### Changed
- Archive Featured Images are now controlled by the Genesis Theme Settings page
/wp-admin/admin.php?page=genesis.  Previously, archive featured images were
always on.  To turn the featured image on, go to the Content Archives
section, check "Include the Featured Image?", choose the Image Size
"bsg-featured-image (1170 x 630)", and Image Alignment "None".
- Add new Sass variables $commentBgColor and $galleryCaptionColor
- Change all images to resize responsively by default
- Add .clearfix behavior to .widget
- Remove erronous extra closing div in nav markup
- Remove Bootstrap Markup from all nav instances other than
primary and secondary theme locations. This change was introduced to stop
the Bootstrap markup from being applied to the WP_Widget_Links widget
- Apply max-width: 100% to form elements anywhere on the page, previously only
widget form elements were targetted. Fixes bug with Comment textarea
overflowing browser window on mobile devices
- remove redundant nav tag
- change secondary menu default styles to nav inverse
- add class .navbar-static-top to both primary and secondary nav


## [0.6.0] - 2015-02-13

### Changed
- Change Bootstrap version from 2.3.2 to 3.3.2