---
layout  : wikiindex
title   : wiki
toc     : true
public  : true
comment : false
resource: 06/227923-8E1A-42ED-BD8B-7B8C4E1E70EE
updated : 2025-05-30 17:00:29 +0900
regenerate: true
---
* TOC
{:toc}

## [[/blog]]
- [[/blog/2025-05-05-teddynotelab]]
- [[/blog/2025-05-12-catastrophic_forgetting]]

## [[/article]]
- [[/article/react_with_langchain]]
- [[/article/docling]]

## [[/books]]
- [[/books/understanding_deep_learning]]

## [[/study]]

### [[/study/understanding_deep_learning]]
- [[/study/understanding_deep_learning/ch1_introduction]]
- [[/study/understanding_deep_learning/ch2_supervised_learning]]
- [[/study/understanding_deep_learning/ch3_shallow_neural_networks]]
- [[/study/understanding_deep_learning/ch4_deep_neural_networks]]

## [[/dsa]]
- [[/dsa/arrays_and_strings]]


## [[/how]]
- [[/how/my-first-wiki]]


## 미분류
- [[pipreqs]]
- [[pandas_interpolation]]

---

## blog posts
<div>
    <ul>
{% for post in site.posts %}
    {% if post.public == true %}
        <li>
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
                {{ post.title }}
            </a>
        </li>
    {% endif %}
{% endfor %}
    </ul>
</div>

