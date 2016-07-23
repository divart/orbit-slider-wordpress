# Orbit Slider plugin for WordPress.

Adds Orbit Slider support to WordPress themes based on Foundation 6.


## Usage

```
OrbitSlider($orbitparam = null, $orbitsize = null, $orbitaria = null, $motionui = null)
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
Default value: null

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

## Download

Clone the git repo `https://github.com/thewirelessguy/orbit-slider-wordpress.git` or [download the archive](https://github.com/thewirelessguy/orbit-slider-wordpress/archive/master.zip).

## Authors

**ZURB**

Orbit Slider was made by [ZURB](http://foundation.zurb.com/), a product design company in Campbell, California. Their Github repository can be found at https://github.com/zurb/foundation-sites

**Stephen Mullen**

This plugin was developed by Stephen Mullen, a web designer and Android app developer based in Preston, UK
+ [Twitter @wirelessguyuk](http://twitter.com/wirelessguyuk)
+ [Website](https://www.thewirelessguy.co.uk)