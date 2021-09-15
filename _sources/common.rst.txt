**2-1. 서체 및 초기화**
============================

- 서체 및 초기화 세팅 방법입니다.

서체 다운
-------------

- Digico 서체 / KT 서체 중 1 가지 택하여 사용
- `font 다운 <https://github.com/eugenekk/template/tree/master/fonts>`_



서체설정 및 css 초기화
--------------------------------

- 폰트 설정 및 html 요소의 기본 스타일을 브라우저간 일관성을 유지하도록 돕는 파일입니다.
- 모든 HTML 파일에서 우선순위 최하로 설정하여 사용합니다.

- 폰트 사용 예시

.. code-block:: css

   div1 {
    font-family: 'DigicoM', sans-serif;
    }

- `common.css 소스보기 <https://github.com/eugenekk/template/blob/master/css/common.css>`_


색상 코드
-------------

- 5가지 메인컬러의 alias 입니다.

========= ========= 
색상 코드 alias
-------------------
alias     hex code
========= ========= 
--white   #fafdff
--gray    #5f6264
--navy    #0d1e2b
--yellow  #030303;
--mint    #33cccc;
========= ========= 

- 색상 alias 사용 예시

.. code-block:: css

   div2 {
    background-color: var(--mint);
    }