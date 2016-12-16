# Orbit Slider plugin for WordPress.

Adds Orbit Slider support to WordPress themes based on Foundation 6.


## Usage

```
OrbitSlider($orbitparam = null, $orbitsize = null, $orbitaria = null, $motionui = null, $bullets = null, $post_type = null, $posts_per_page = null, $hide_title = null)
```

### Parameters

**$orbitparam**  
(String) (Optional) Orbit data-options  
Default value: null

**$orbitsize**  
(String) (Optional) Image size to use (eg thumbnail, medium, large, custom)  
Default value: null

**$orbitaria**  
(String) (Optional) Aria label text  
Default value: null

**$motionui**  
(Boolean) (Optional) Use MotionUI  
Default value: false

**$bullets**  
(Boolean) (Optional) Use Bullets  
Default value: false

**$post_type**  
Default value: 'orbit'

**$posts_per_page**  
(String) (Optional) Number of post to display  
Default value: '-1'

$hide_title
(Boolean) (Optional) Hide title  
Default value: false

### Examples

```
OrbitSlider(); // Simple
```
```
OrbitSlider(null, "orbit", null, true);  // Orbit Slider with custom image size and uses MotionUI
```
```
OrbitSlider("animInFromLeft:fade-in; animInFromRight:fade-in; animOutToLeft:fade-out; animOutToRight:fade-out;", "large", "Orbit Slider", true);  // Orbit Slider with custom transitions, large image size and uses MotionUI. ARIA label set as 'Orbit Slider'
```

## Added support for other WordPress plugins

**[WP Rocket](https://wp-rocket.me) and [Rocket Lazy Load](https://wordpress.org/plugins-wp/rocket-lazy-load/)**

The plugin deactivates Lazy Load on Orbit Slider images so you can safely enable Lazy Load on your website without it breaking the slider.


## Download

Clone the git repo `https://github.com/thewirelessguy/orbit-slider-wordpress.git` or [download the archive](https://github.com/thewirelessguy/orbit-slider-wordpress/archive/master.zip).

## Authors

**ZURB**

Orbit Slider was made by [ZURB](http://foundation.zurb.com/), a product design company in Campbell, California. Their Github repository can be found at https://github.com/zurb/foundation-sites

**Stephen Mullen**

This plugin was developed by Stephen Mullen, a web designer and Android app developer based in Preston, UK
+ [Twitter @wirelessguyuk](http://twitter.com/wirelessguyuk)
+ [Website](https://www.thewirelessguy.co.uk)