# Photos 탭 사진 추가 방법

## 1. 사진 파일 업로드

GitHub 저장소의 `images/photos/` 폴더에 사진 파일을 업로드합니다.

- 권장 형식: JPG, JPEG, PNG 또는 WebP
- 파일명에는 영문, 숫자, 하이픈을 사용하면 경로 오류를 줄일 수 있습니다.
- GitHub에서 이 폴더를 연 뒤 **Add file → Upload files**를 선택하고 파일을 올려 커밋합니다.

## 2. 홈페이지의 사진 목록에 등록

저장소의 `index.html`을 열고 `site-data`를 검색합니다. 그 안의 `photos` 배열에 사진 정보를 한 항목 추가합니다.

```json
{
  "src": "images/photos/2026-lab-seminar.jpg",
  "caption": "연구실 세미나",
  "date": "2026.10",
  "year": "2026"
}
```

- `src`: 1단계에서 올린 파일 경로
- `caption`: Photos 탭에 보일 사진 설명
- `date`: 사진 날짜
- `year`: 연도별 필터에 사용할 연도

배열 안의 다른 항목과 쉼표를 확인하고, 실제 사진에는 `"demo": true`를 넣지 마세요. `index.html`을 커밋하면 GitHub Pages가 자동으로 업데이트됩니다.

Photos 탭에도 이 안내로 연결되는 링크가 있습니다.
