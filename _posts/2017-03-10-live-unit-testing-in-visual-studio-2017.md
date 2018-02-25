---
layout: post
title: Live Unit Testing in Visual Studio 2017
date: 2017-03-10 18:13:30.000000000 -06:00
type: post
parent_id: '0'
published: true
password: ''
status: publish
categories:
- software
tags:
- testing
- visual studio
meta:
  _wpcom_is_markdown: '1'
  _rest_api_published: '1'
  _rest_api_client_id: "-1"
  _publicize_job_id: '2723480454'
author:
  login: tmeinershagen
  email: todd@meinershagen.net
  display_name: Todd Meinershagen
  first_name: ''
  last_name: ''
---
<p>I am a big proponent of unit testing my code because of the many benefits it provides:</p>
<ul>
<li>Helps me to catch potential bugs early</li>
<li>Helps me to clarify the behavior of my units (classes) from a client perspective</li>
<li>Leaves a documentation trail for those that come behind me to understand my intentions</li>
</ul>
<p>The only irritation/friction I have found in the past is the fact that running unit tests has required me to manually run them on a periodic basis. Having keyboard shortcuts has helped to make that fairly painless, but it would have been nice to have the tests automatically run as I am working on the code. That way I am continually receiving feedback and don't have to explicitly do anything to receive it.</p>
<p>While there have been custom add-on options in the past (<a href="https://github.com/amirrajan/SpecWatchr">SpecWatchr</a> and <a href="http://www.ncrunch.net/">nCrunch</a>), Microsoft has finally seen fit to add this functionality right into the Visual Studio 2017 Enterprise version.</p>
<p>Find out more about it <a href="https://blogs.msdn.microsoft.com/visualstudio/2017/03/09/live-unit-testing-in-visual-studio-2017-enterprise/">here</a> on Microsoft's Visual Studio Blog.</p>
<p><img src="{{ site.baseurl }}/assets/e6a6a618-0589-11e7-851e-8a96c230c9ec.png" alt="Live Unit Test Screenshot" /></p>
