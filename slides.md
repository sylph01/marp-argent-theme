---
title: Sample
paginate: true
marp: true
theme: argent
---

<!-- _class: titlepage -->

# Sample Slide
## sylph01, 2022/10/03

---

<!-- _class: titlepage -->

# Sample Slide
## sylph01, 2022/10/03
### This is h3 に日本語混ぜたもの
#### And This is H4


---

# This is not titlepage

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel consequat diam. Pellentesque cursus sem et interdum faucibus. Aenean rutrum nulla nec cursus maximus. Pellentesque vel finibus orci. Proin velit purus, accumsan ac sodales in, consequat sed ligula. Mauris sapien sapien, dictum vitae nisl vitae, laoreet tincidunt ante. Nunc tempor tellus nisl, lacinia sodales magna posuere eu.

----

# Test 日本語 mix

吾輩はcatである。Nameはまだ無い。どこで生れたかとんと見当がつかぬ。何でも薄暗いじめじめした所で*meow meow*泣いていた事だけは*記憶*している。吾輩は**ここで始めてhumanというもの**を見た。しかもあとで聞くとそれ

----

```js
function deleteNode(node) {
  let currentNode = node;
  let nextNode    = node.next;
  while(currentNode !== null) {
    if (nextNode !== null) {
      currentNode.value = nextNode.value
      if (nextNode.next == null) {
        currentNode.next = null
      }
      currentNode = currentNode.next
      nextNode = nextNode.next
    } else {
      currentNode = null
    }
  }
}
```
