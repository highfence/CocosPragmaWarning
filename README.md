# CocosPragmaWarning
Github only for PragmaWarning for cocos2d-x

엔진 내부에서 발생하는 워닝을 무시해주기 위하여 인클루드 부분에 pragma warning처리를 한 코드입니다.

```
pragma warning(push)
pragma warning(pop)
```

이 두 라인 사이에 내가 무시하고 싶은 번호의 pragma warning과 인클루드 코드를 넣어주면 됩니다.