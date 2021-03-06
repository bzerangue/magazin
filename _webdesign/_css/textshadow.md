---
published: false
layout: page
subheadline: "CSS"
title: "text-shadow: Aufbau und Beispiele für CSS-Textshatten"
teaser: "Diese Anleitung erklärt das CSS-Element <code>text-shadow</code> und zeigt Standardanwendungen und außergewöhnliche Beispiele."
tags:
    - css
---

{% highlight css %}
div { text-shadow: 3px 3px 4px #777 }
      ^            ^   ^   ^   ^  
      |            |   |   |   |  
      |            |   |   |   |
      |            |   |   |   +- Schattenfarbe
      |            |   |   |
      |            |   |   +- Verlaufs-Radius des Schattens
      |            |   |
      |            |   +- Vertikaler Versatz
      |            |
      |            +- Horizontaler Versatz
      | 
      +- CSS3-Eigenschaft text-shadow 
{% endhighlight %}



<p style="padding: 10px; background: #d4007a; color: #fff;font: bold 5em/1 'Inconsolata', monospace; font-size: 5em;text-shadow: 0 1px 0 #ccc, 0 2px 0 #c9c9c9, 0 3px 0 #bbb, 0 4px 0 #b9b9b9, 0 5px 0 #aaa, 0 6px 1px rgba(0,0,0,0.1), 0 0 5px rgba(0,0,0,0.1), 0 1px 3px rgba(0,0,0,0.3), 0 3px 5px rgba(0,0,0,0.2), 0 5px 10px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.2), 0 20px 20px rgba(0,0,0,0.15);">Inconsolata</p>

<p style="padding: 10px; background: #d4007a; color: #fff;font: bold 5em/1 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 5em;text-shadow: 0 1px 0 #ccc, 0 2px 0 #c9c9c9, 0 3px 0 #bbb, 0 4px 0 #b9b9b9, 0 5px 0 #aaa, 0 6px 1px rgba(0,0,0,0.1), 0 0 5px rgba(0,0,0,0.1), 0 1px 3px rgba(0,0,0,0.3), 0 3px 5px rgba(0,0,0,0.2), 0 5px 10px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.2), 0 20px 20px rgba(0,0,0,0.15);
">Neue Helvetica</p>

<p style="padding: 10px; background: #d4007a; color: #fff;font-family: 'Droid'; font-size: 5em;text-shadow: 0 1px 0 #ccc, 0 2px 0 #c9c9c9, 0 3px 0 #bbb, 0 4px 0 #b9b9b9, 0 5px 0 #aaa, 0 6px 1px rgba(0,0,0,0.1), 0 0 5px rgba(0,0,0,0.1), 0 1px 3px rgba(0,0,0,0.3), 0 3px 5px rgba(0,0,0,0.2), 0 5px 10px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.2), 0 20px 20px rgba(0,0,0,0.15);
">Droid Schrift</p>
