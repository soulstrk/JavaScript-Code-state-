# JavaScript-Code-state-
자바스크립트 공부한거 기록
# 12월 넷째주

---

## BOM (브라우저에 대한 정보를 가지고 있는 객체들)

- navigator
    - 브라우저나 운영체제에 대한 정보
    - navigator.language; "ko"
    - navagator.vendor; // "Google Inc"
- screen
    - 화면에 대한 정보를 알려주는 객체
- location

    ## 주소에 대한 정보를 알려주는 객체

    - location.host
    - location.hostname
    - location.protocol
    - location.href
    - location.pathname
- history
    - history.pushState — html5에서 추가됨
    - history.forward(), history.back()

## DOM (Document Object Model)

- tag.children // tag.childNodes
- tag.firstChild, tag.lastChild
- tag.parentNode
- tag.previousSibling, tag.nextSibling

- prototype
    - prototype은 생성자 함수에 정의한 모든 객체가 공유할 원형

- 생성자와 this

    ![](Untitled-422b73b4-f6d4-4b51-86dd-1a6aca80ab10.png)

    - 아래 두 문장의 this는 서로다른 객체를 가르킨다. ㅇㄷ?

        위는 window객체를 가르키고, 아래는 Person 객체를 가르킨다.
