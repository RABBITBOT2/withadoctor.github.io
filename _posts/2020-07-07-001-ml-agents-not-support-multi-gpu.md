---
title:  "ml-agents는 훈련할 때, 멀티 GPU를 사용하지 않는다."
excerpt: "ml-agents는 훈련할 때, 멀티 GPU를 사용하지 않는다."

# toc: true
# toc_sticky: true
# toc_label: "페이지 주요 목차"

categories:
  - idletalk
tags:
  - 잡담
  - idletalk
last_modified_at: 2020-07-07T23:04:00+09:00
---


## ml-agents
오늘 일하다가 깨달은 사실인데..  
세상에 멀티 GPU를 지원하지 않는다.  

## gym-unity
다른 방법을 찾기위해서 gym-unity를 사용해보려고도 하였으나.  
웬걸 gym-unity는 하나의 에이전트만 훈련시킬 수 있다.  

테니스 예제나 축구 예제는 gym-unity로 훈련시킬 수 없다는 것이다..

## 다시 ml-agents
결론은 다시 ml-agents로..  
지금은 공부 중이라서 상관없을 것 같지만.  

실제로 개발할 때에는 치명적일 것같다.  

뭐 쓰레드리퍼 가져와서 훈련시켜야하는건가 ㄷㄷ