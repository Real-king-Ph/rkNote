---
layout: post
title: test
mermaid: true
mathjax: true
nav_order: 3
---

test

$\LaTeX$


```cpp
#include <iostream>

using namespace std;

int main() {
   for (int i = 0 ; i <= 100 ; i++ ) {
      map[{1 * i + i ,2 * i}]= i;
   }
   return 0;
}
```

~~~mermaid
%%{init: { 'logLevel': 'debug', 'theme': 'base' } }%%
      gitGraph
        commit
        branch hotfix
        checkout hotfix
        commit
        branch develop
        checkout develop
        commit id:"ash" tag:"abc"
        branch featureB
        checkout featureB
        commit type:HIGHLIGHT
        checkout main
        checkout hotfix
        commit type:NORMAL
        checkout develop
        commit type:REVERSE
        checkout featureB
        commit
        checkout main
        merge hotfix
        checkout featureB
        commit
        checkout develop
        branch featureA
        commit
        checkout develop
        merge hotfix
        checkout featureA
        commit
        checkout featureB
        commit
        checkout develop
        merge featureA
        branch release
        checkout release
        commit
        checkout main
        commit
        checkout release
        merge main
        checkout develop
        merge release
~~~

δΈ­ζζη΄’ 

[<i class="fa-solid fa-bowl-rice"></i>](#)


π