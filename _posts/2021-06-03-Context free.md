---
layout: post
title: "Context free"
categories: incomplete thoughts
##author:
#- Your name here
#- yours too
meta: "Meta"
---

### Context free design program
v.2021-03-06 19:35:00 +7

<html lang="en">
   <head>
	 <script src="https://cdnjs.cloudflare.com/ajax/libs/mermaid/8.0.0/mermaid.min.js"></script>
    </head>
	 
<body>

<div class="mermaid">graph LR
A--&gt;B
</div>
	
</body>
<script>
var config = {
    startOnLoad:true,
    theme: 'forest',
    flowchart:{
            useMaxWidth:false,
            htmlLabels:true
        }
};
mermaid.initialize(config);
window.mermaid.init(undefined, document.querySelectorAll('.language-mermaid'));
</script>

</html>

### Context free design program
v.2021-03-06 19:35:00 +7

```mermaid
graph TD

S --> NP
	NP --> D
		D --> The
	NP --> N
		N --> designer
	
S --> VP
	VP --> V
		V --> Aux
			Aux --> will
		V --> v
			v --> design
	VP --> NP'


NP' --> D'
	D' --> the 
NP' --> N'
	N' --> design.

```


