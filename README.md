# inviastory-landing

Inviastory(인비아스토리)의 랜딩 페이지입니다.
Inviastory는 두 사람의 이야기를 AI가 문장으로 옮겨, 세상에 하나뿐인 모바일 청첩장을 만들어 드리는 서비스입니다.

## 구조

빌드 과정 없이 `index.html` 한 장으로 구성된 정적 페이지입니다.

```
index.html   # 랜딩 페이지 (HTML + CSS)
```

## 로컬에서 보기

```
python3 -m http.server 8000
```

실행 후 http://localhost:8000 에서 확인할 수 있습니다.

## 배포

Vercel에 연결되어 있으며, `main` 브랜치에 푸시하면 자동으로 배포됩니다.

## 도메인

| 주소 | 용도 |
| --- | --- |
| https://www.inviastory.com | 랜딩 페이지 (이 저장소) |
| https://sample.inviastory.com | 샘플 청첩장 |
