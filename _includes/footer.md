Beth Ashley
<script type="text/javascript" language="javascript">
<!--
// Email obfuscator script 2.1 by Tim Williams, University of Arizona
// Random encryption key feature by Andrew Moulden, Site Engineering Ltd
// This code is freeware provided these four comment lines remain intact
// A wizard to generate this code is at http://www.jottings.com/obfuscator/
{ coded = "7slZ@C857EH8s.oXp"
  key = "K9aiVX3yNnxZItU5CdSGHvb0qP4gJzlfAcr1WLu7RFemjOYE8Do2QMkBh6Tspw"
  shift=coded.length
  link=""
  for (i=0; i<coded.length; i++) {
    if (key.indexOf(coded.charAt(i))==-1) {
      ltr = coded.charAt(i)
      link += (ltr)
    }
    else {     
      ltr = (key.indexOf(coded.charAt(i))-shift+key.length) % key.length
      link += (key.charAt(ltr))
    }
  }
document.write("<a href='mailto:"+link+"'>"+link+"</a>")
}
//-->
</script><noscript>Sorry, you need Javascript on to email me.</noscript>

Background graphic [CC BY-SA 2.0](http://creativecommons.org/licenses/by-sa/2.0/) by [David Boyle](http://www.flickr.com/photos/beglendc/)
