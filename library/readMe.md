__***[ list.json 형식 강좌 ]***__

```js
/**
 * 기본 data 는 {}
 * 스크립트 추가는 key 를 늘려서 추가
 */
{
    "scriptName": { // scriptName 이 소스코드 이름
        "version": [
            0,
            0,
            1
        ], // 0.0.1 이 버전
        "available": false, // 현재 다운로드 가능한가?
        "download": null, // 다운로드 링크
        "patchnote": [
            {
                "version": [
                    0,
                    0,
                    1
                ], // 0.0.1 버전의 패치노트
                "title": "테스트용 소스코드", // 패치노트 제목
                "desc": "나는 밥오\n테스트용 설명" // 패치노트 내용
            }
        ] // 패치노트 - Array 가장 마지막이 최신 버전
    }
}
```

__** 끝 **__