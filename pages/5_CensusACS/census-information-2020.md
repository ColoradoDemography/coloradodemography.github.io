---
# This layout is used to redirect pages, if you moved them.
# Use the following settings in front matter:
# 
layout: redirect
sitemap: false
permalink: /census-acs/2020-census-information/
redirect_to:  /census_2020/
# 
# Idea and Code by: http://codingtips.kanishkkunal.in/about/
---
<!DOCTYPE html>
<html>
<head>
<link rel="canonical" href="{{ page.redirect_to }}"/>
<meta http-equiv="content-type" content="text/html; charset=utf-8" />
<meta http-equiv="refresh" content="0;url={{ page.redirect_to }}" />
</head>
<body>
    <h1>Redirecting...</h1>
      {{ site.data.language.if_you_are_not_redirected_automatically }} <a href="{{ page.redirect_to }}">{{ site.data.language.click_here }}</a>.
      <script>location='{{ page.redirect_to }}';</script>
</body>
</html>
