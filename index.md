
### List of articles 
1. this is coool
2. this really sucks 

[http://google.com](this is google link)

```common-lisp
(defun add (x y)
  (+ x y))
```
why not working 
{% for post in site.posts %}
  [{{ post.url }}]{{ post.title }}
  {{ post.excerpt }}
{% endfor %}
