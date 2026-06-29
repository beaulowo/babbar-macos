# Babbar

UNIST 식단을 macOS 메뉴바에서 바로 확인하는 앱입니다.

## 요구 사항

- macOS 26 이상
- Apple Silicon Mac
- 인터넷 연결

## 설치

1. Releases에서 최신 `Babbar-*-macos26.dmg`를 다운로드합니다.
2. DMG를 엽니다.
3. `Babbar.app`을 `Applications` 폴더로 드래그합니다.
4. `Applications` 폴더에서 앱을 실행합니다.

개발자 ID로 notarize된 앱이 아니므로 첫 실행 시 macOS 보안 경고가 뜰 수 있습니다.
이 경우 Finder에서 앱을 Control-클릭한 뒤 `열기`를 선택합니다.

## 사용

- 메뉴바의 Babbar 아이콘을 누르면 현재 시각 기준 다음 식단이 표시됩니다.
- 식사 시간이 지나면 다음 식사로 자동 전환됩니다.
- 설정 버튼에서 로그인 시 자동 실행을 켤 수 있습니다.
- 설정 버튼에서 업데이트를 확인할 수 있습니다.

## 업데이트

앱은 Sparkle을 사용해 GitHub Releases의 업데이트를 확인합니다.
처음 설치는 DMG에서 Applications로 드래그해야 하지만, 이후 업데이트는 앱 안의 `업데이트 확인` 버튼으로 진행됩니다.

## 라이선스

이 배포판은 GPL-2.0 라이선스를 따릅니다. 대응 소스 코드는 배포자에게 요청할 수 있습니다.
