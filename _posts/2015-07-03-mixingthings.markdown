---
layout: post
title:  "Mixing Things Up"
date:   2015-03-07 19:29:00
categories: jekyll update
---

Today I learned more about mixins and actually made and implemented one.I created a mixin for default links.The code is below.
<pre>
	<code>@mixin linkStyle{
	color:$lightBlue-color;
    &:visited{
        color:$lightBlue-color;
    }
    &:hover{
        color:$lightOrange-color;
        text-decoration:none;
    }
}
}</code>
</pre>
