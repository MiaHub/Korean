---
layout: page
title: Conjugation
---

Word conjugation paste tense / 2. and 3. politeness level

<pre class="mermaid">
classDiagram
    Conjucation <|-- 았 아요 아
    Conjucation <|-- 었 어요 어
    Conjucation <|-- 였 여요 여
    class 았 아요 아{
      ㅏ ㅗ
      ㅏ->ㅡ ㅗ->ㅡ
    }
    class 었 어요 어{
      ㅓ ㅜ ㅕcons ㅣcons 
      ㅟ ㅚ ㅢ ㅐ ㅔ  
      ㅡ
    }
    class 였 여요 여{
      ㅕx ㅣx 하*
    }
</pre>    