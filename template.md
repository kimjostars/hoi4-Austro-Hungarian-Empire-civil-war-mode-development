name: "[버그사항]"
description: 버그발견하셨습니까?
title: "[버그]"
labels: "bug"
body:
  - type: markdown
    attributes:
      value: |
        버그사항 접수해주셔서 감사합니다.!
  - type: dropdown
    attributes:
      label: 버그유형 선택
      description: 버그유에 해당하면 선택해주세요.
      options:
      -'국가중점'
      -'이벤트'
      -'디시전'
      -'오탈자'
      -'그외'
