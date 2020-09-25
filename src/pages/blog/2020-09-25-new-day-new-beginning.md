---
templateKey: blog-post
title: New day, new beginning!
date: 2020-09-25T11:00:19.175Z
description: I am so looking forward to this day, wooohooo!
featuredpost: true
featuredimage: /img/ian-stauffer-bh7kz0yazb0-unsplash.webp
tags:
  - Time to shine
  - work hard
  - get gold
---
## Because everyday is a new oppurtunity

* To grow
* To live
* To give

[Check this out](https://www.humanetech.com/)

```javascript
let time = `forever`

function carpeDiem(today) {
  fetch(`https//seize-api.app`, {
    method: 'POST',
    headers: {
      'Content-Type': 'application/json'
    },
    body: JSON.stringify({ whatDay: today }) // body data type must match "Content-Type" header
  })
  .then(res => res.json())
  .then(gold => {
    console.log(`Go get that ${gold}`)
  })
}

while(time) {
  carpeDiem(new Date())
}
```