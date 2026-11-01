# sibal-anim — 교재 QR용 움직이는 그림

교재(시발키트 · 족발보쌈키트)의 그림 연재 QR이 여는 페이지를 모아 두는 곳. 공개 주소: https://woosukhs-123.github.io/sibal-anim/

## 폴더 규칙
- **과목마다 폴더 하나.** 폴더 이름은 `subjects.json`에 적힌 것만 쓴다. 이미 있는 폴더 이름은 바꾸지 않는다(찍힌 QR이 깨짐).
- 주소 = `https://woosukhs-123.github.io/sibal-anim/<과목 폴더>/<단원-주제>.html` (예: `pharmacol2/22-6-flu.html`).
- 파일 이름은 영문 소문자 · 숫자 · 하이픈만. 같은 폴더 안에서 같은 이름 = 같은 주제의 업데이트(덮어쓰기).
- 각 html의 `<head>`에 `<meta name="anim-subject">` · `anim-unit` · `anim-topic`을 적는다. 같은 이름인데 이 값이 다르면 덮어쓰지 말고 이름 끝에 `-2`를 붙인다.
- `index.html`은 저장소 파일 목록을 스스로 읽어 과목별로 보여 준다. 키트가 따로 만들거나 덮어쓸 필요 없다.

## 테스트용 (지우지 말 것)
- 맨 위의 `flu.html` 과 `test/flu.html` 은 **테스트용**(v3.5 → v3.6 견본, 약리학 II 22-6 flumazenil). 이미 찍힌 QR이 있을 수 있어 그대로 둔다.
