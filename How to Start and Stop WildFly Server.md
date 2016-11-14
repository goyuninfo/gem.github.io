---
layout: page
title: How to Start and Stop WildFly Server
permalink: /How to Start and Stop WildFly Server/
---

Change to the bin directory
<div style="color: #333333; font-family: Helvetica, arial, freesans, clean, sans-serif; font-size: 15px; line-height: 25px; margin-bottom: 15px; margin-top: 15px;">
<pre class="prettyprint " style="background: rgb(239, 239, 239); border-radius: 3px; border: none; font-family: Menlo, 'Bitstream Vera Sans Mono', 'DejaVu Sans Mono', Monaco, Consolas, monospace; font-size: 12px; line-height: 1.5; padding: 10px; white-space: pre-wrap;"><span class="pln" style="color: black;">$ cd wildfly</span><span class="pun" style="color: #666600;">-[</span><span class="pln" style="color: black;">version</span><span class="pun" style="color: #666600;">]/</span><span class="pln" style="color: black;">bin</span></pre>
Start the server in domain mode</div>
<div style="color: #333333; font-family: Helvetica, arial, freesans, clean, sans-serif; font-size: 15px; line-height: 25px; margin-bottom: 15px; margin-top: 15px;">
<pre class="prettyprint " style="background: rgb(239, 239, 239); border-radius: 3px; border: none; font-family: Menlo, 'Bitstream Vera Sans Mono', 'DejaVu Sans Mono', Monaco, Consolas, monospace; font-size: 12px; line-height: 1.5; padding: 10px; white-space: pre-wrap;"><span class="pln" style="color: black;">$ </span><span class="pun" style="color: #666600;">./</span><span class="pln" style="color: black;">domain</span><span class="pun" style="color: #666600;">.</span><span class="pln" style="color: black;">sh</span></pre>
Start the server in standalone mode</div>
<div style="color: #333333; font-family: Helvetica, arial, freesans, clean, sans-serif; font-size: 15px; line-height: 25px; margin-bottom: 15px; margin-top: 15px;">
<pre class="prettyprint " style="background: rgb(239, 239, 239); border-radius: 3px; border: none; font-family: Menlo, 'Bitstream Vera Sans Mono', 'DejaVu Sans Mono', Monaco, Consolas, monospace; font-size: 12px; line-height: 1.5; padding: 10px; white-space: pre-wrap;"><span class="pln" style="color: black;">$ </span><span class="pun" style="color: #666600;">./</span><span class="pln" style="color: black;">standalone</span><span class="pun" style="color: #666600;">.</span><span class="pln" style="color: black;">sh</span></pre>
To stop the server, press Ctrl + C, or use the admin console</div>
<pre class="prettyprint " style="background: rgb(239, 239, 239); border-radius: 3px; border: none; color: #333333; font-family: Menlo, 'Bitstream Vera Sans Mono', 'DejaVu Sans Mono', Monaco, Consolas, monospace; font-size: 12px; line-height: 1.5; padding: 10px; white-space: pre-wrap;"><span class="pln" style="color: black;">$ </span><span class="pun" style="color: #666600;">./</span><span class="pln" style="color: black;">jboss</span><span class="pun" style="color: #666600;">-</span><span class="pln" style="color: black;">cli</span><span class="pun" style="color: #666600;">.</span><span class="pln" style="color: black;">sh </span><span class="pun" style="color: #666600;">--</span><span class="pln" style="color: black;">connect command</span><span class="pun" style="color: #666600;">=:</span><span class="pln" style="color: black;">shutdown</span></pre>
See also:
<a href="http://it.i88.ca/2013/11/why-cant-i-connect-to-wildfly-server.html" target="_blank">&nbsp;How to connect to wildfly server remotely?</a>
