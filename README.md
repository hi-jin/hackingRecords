# hackingRecords
things to consider to find the entry point
------------------------------------------

### Webhacking
1. 서버에서 어떤 쿠키값을 얻었고, 그 쿠키값이 어떤 변화를 일으키는지 관찰하기. (cookie-based sql injection ...)

### SystemHacking
1. 함수에 입력된 인자들을 분석할 떄, 함수의 본 의도대로 인자들을 제대로 사용했는지 확인하기.
  (ex. scanf(%d, var1) || scanf(%d, &var1)      -from pwnable.kr passcode)
