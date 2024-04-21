TCP 신뢰성, UDP 비신뢰성으로 볼 수 있다.
TCP는 A라는 메시지를 보냈다면 보내졌다는 것을 믿을 수 있다.
UDP의 경우 보내지지 않을 수도 있다.

## TCP

TCP는 핸드셰이킹을 통해 매번 확인한다. 연결해도돼? 메시지 갔어? 연결 끊을게

이렇게 확인을 통해 제대로 전송되지 않았다면 다시 메시지를 재요청한다.

## UDP

최소한의 프로토몰 매커니즘만을 갖추었다. 데이터 무결성을 위해 checksum 및 데이터그램의 소스 및 대상에서 다양한 기능을 처리하기 위한 포트 번호를 제공한다.
UDP의 경우 비신뢰성으로 한번 요청하고 중간에 데이터가 유실되거나하는 문제가 있을 수 있지만 확인하지 않는다.

# 참고자료

- [TCP | MDN](https://developer.mozilla.org/ko/docs/Glossary/TCP)
- [UDP | MDN](https://developer.mozilla.org/ko/docs/Glossary/UDP)
