---
title: API
layout: rancher-default-v1.0
version: v1.0
lang: zh
---

## register



### Resource Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
accessKey | string | - | - | - | 
description | string | Optional | Yes | - | 
id | int | - | - | - | The unique identifier for the register
key | string | Yes | - | - | 
name | string | Optional | Yes | - | 
secretKey | string | - | - | - | 


Please read more about the [common resource fields]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/common/). 
These fields are read only and applicable to almost every resource. We have segregated them from the list above.


### Operations
{::options parse_block_html="true" /}



<div class="action">
<span class="header">
Create
<span class="headerright">POST:  <code>/v1/register</code></span></span>
<div class="action-contents">
{% highlight json %} 
{

	"description": "string",

	"key": "string",

	"name": "string"

} 
{% endhighlight %}
</div>
</div>











### Actions

<div class="action">
<span class="header">
activate
<span class="headerright">POST:  <code>${actions.activate}</code></span></span>
<div class="action-contents">
To activate the register
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/genericObject/">genericObject</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
deactivate
<span class="headerright">POST:  <code>${actions.deactivate}</code></span></span>
<div class="action-contents">
To deactivate the register
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/genericObject/">genericObject</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
purge
<span class="headerright">POST:  <code>${actions.purge}</code></span></span>
<div class="action-contents">
To purge the register
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/genericObject/">genericObject</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
remove
<span class="headerright">POST:  <code>${actions.remove}</code></span></span>
<div class="action-contents">
To remove the register
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/genericObject/">genericObject</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
restore
<span class="headerright">POST:  <code>${actions.restore}</code></span></span>
<div class="action-contents">
To restore the register
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/genericObject/">genericObject</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
stop
<span class="headerright">POST:  <code>${actions.stop}</code></span></span>
<div class="action-contents">
To stop the register
<br>

<span class="input">
<strong>Input:</strong> instanceStop
</span>

Field | Type | Required | Default | Notes
---|---|---|---|---
remove | boolean | No |  | 
timeout | int | No |  | 


<br>
{% highlight json %}{

	"remove": true,

	"timeout": 0

}{% endhighlight %}

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/instance/">instance</a> resource</span>
</div>
</div>

