# Liberty MediaWiki Skin


[English](README.en.md)

[리브레 위키](https://librewiki.net)의 기본 스킨입니다. 위키엔진 '리버티'의 기본 레이아웃이 될 예정입니다.

## 개발

원본 소스는 [GitLab.com](https://gitlab.com/librewiki/Liberty-MW-Skin)에서 이루어지고 있으며, 버그 리포팅은 [Phabricator](https://issue.librewiki.net/)에서, 패치는 GitLab.com 에서만 받고 있습니다. 이 외의 호스팅에서 발견되는 코드는 모두 미러링이며, 코드의 최신성을 보증하지 않습니다.

## 설정

| 이름                 	| 설명                                  	| 예시 값                                                                                                              	| 기본 값      	|
|----------------------	|---------------------------------------	|----------------------------------------------------------------------------------------------------------------------	|--------------	|
| `$wgLibertyMainColor`  	| `theme-color` 메타 설정                 	| `#4188F1`                                                                                                              	| `#4188F1`      	|
| `$wgTwitterAccount`    	| 트위터 카드 언어 설정                 	| `librewiki`                                                                                                            	| (없음)       	|
| `$wgLibertyOGLogo`     	| 오픈그래프 태그에 사용 될 이미지 설정 	| `https://librewiki.net/images/6/6a/Libre_favicon.png`                                                                  	| `$wgLogo`의 값 	|
| `$wgNaverVerification` 	| 네이버 사이트 도구 인증 코드          	| (네이버에서 제공된 값)                                                                             	| (없음)       	|
| `$wgLibertyAdSetting`  	| 구글 애드센스 설정                             	| `array( "client" => "(Google Adsense에서 제공한 값)", "header" => "3627980722", "right" => "6581447128" )` 	| (없음)       	|
| `$wgLibertyMaxRecent`  	| 사이드바 최근 변경에 등장하는 편집의 최대 개수          	| `10`                                                                                                                   	| `10`           	|

## 상단바
위키 내부의 `미디어위키:Liberty-Navbar` 문서를 수정해주세요. 예시는 [리브레 위키](https://librewiki.net/wiki/MediaWiki:Liberty-Navbar)에 있습니다.
