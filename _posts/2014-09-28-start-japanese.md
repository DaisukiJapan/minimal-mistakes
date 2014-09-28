---
layout: post
title: "อยากเรียนภาษาญี่ปุ่น ต้องเริ่มจากอะไร"
author: Mim
modified:
excerpt: "A post to test author overrides using a data file."
tags: []
---

"อยากเรียนภาษาญี่ปุ่น ต้องเริ่มจากอะไร"

เป็นคำถามที่หลายๆคนถามตัวเอง เมื่อต้องการเริ่มต้นเรียนภาษาญี่ปุ่นด้วยตัวเอง สิ่งสำคัญเลยก็คือ **ความตั้งใจ** ไม่ว่าเราจะเริ่มทำอะไรนั้น ความตั้งใจนั้นเป็นสิ่งที่สำคัญค่ะ ยิ่งเป็นการศึกษาด้วยตัวเองแล้ว ต้องยิ่งตั้งใจมากยิ่งขึ้นกว่าเดิม

มิ้มเองก็เป็นคนหนึ่งที่เรียนภาษาญี่ปุ่นตัวเองค่ะ ด้วยการที่ตัวเองมีความชอบเกี่ยวกับญี่ปุ่นเป็นทุนเดิมอยู่แล้ว ความรู้ภาษาญี่ปุ่นที่ได้มาส่วนใหญ่ไม่ได้มาจากการอ่านหนังสือเพียงอย่างเดียว 


For those of you who may have content written by multiple authors on your site you can now assign different authors to each post if desired.

Previously the theme used a global author for the entire site and those attributes would be used in all bylines, social networking links, Twitter Card attribution, and Google Authorship. These `owner` variables were defined in `config.yml`

Start by modifying or creating a new `authors.yml` file in the `_data` folder and add your authors using the following format.






{% highlight yaml %}
# Authors

billy_rick:
  name: Billy Rick
  web: http://thewhip.com
  email: billy@rick.com
  bio: "What do you want, jewels? I am a very extravagant man."
  avatar: bio-photo-2.jpg
  twitter: extravagantman
  google:
    plus: BillyRick

cornelius_fiddlebone:
  name: Cornelius Fiddlebone
  email: cornelius@thewhip.com
  bio: "I ordered what?"
  avatar: bio-photo.jpg
  twitter: rhymeswithsackit
  google:
    plus: CorneliusFiddlebone
{% endhighlight %}

To assign Billy Rick as an author for our post. You'd add the following YAML front matter to a post:

{% highlight yaml %}
author: billy_rick
{% endhighlight %}