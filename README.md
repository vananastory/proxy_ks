# proxy_ks
proxy kiwoom securities on windows.

키움증권 OpenAPI 를 Windows 가 아닌 UNIX 계열에서 사용하기 위해 Proxy 역할을 해주는 Gateway.
키움증권에 직접 연결해서 UNIX 시스템에서 요구하는 작업을 OpenAPI를 호출해서 수행하고, 그 결과를 UNIX 시스템에 Text로 전달.
