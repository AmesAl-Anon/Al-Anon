---
layout: meeting.njk
title: Ames Iowa Al-Anon Meetings
tags: ['Monday', 'Beginner', 'Tuesday', 'Wednesday', 'Thursday', 'Adult-Child', 'Saturday', 'Ames Iowa']
featuredImage: /_images/AmesIowaAl-AnonMeetings-textIntoImages-com.png
order: 80
date: Last Modified  # page.date resolves to last modified date, otherwise to created date if date: left out
description: 'Ames Iowa Al-Anon meetings in one list'
details: ""

eleventyExcludeFromCollections: true
pagination:
  data: collections.sortedPosts
  size: 6
  alias: items
  addAllPagesToCollections: true
---

{% for pageitem in pagination.items %}
    <h3>{{ pageitem.data.title }}</h3>
    <p>{{ pageitem.data.details | markdownify | safe }}</p>
{% endfor %}

### [How can Al-Anon Help Me?](https://al-anon.org/newcomers/)

<br>

