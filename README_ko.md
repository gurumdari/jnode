Jnode Framework
======
Node 기반의 Front-end 개발 프레임워크이다. HTML element node와 JavaScript hierarchical object node 단위로 개발을 할 수 있다. 구조화하여 Template (HTML 포함)을 개발하는 경우, Template 소스를 기능별로 분리하여 개발하기도 하지만, Back-end의 Web Application Engine에서 제공하는 Include 기능을 통해 전체 Template 파일로 구성하기 때문에 실제 Client로부터 요청될 때는 분리되었던 소스들이 결국에는 단순히 합쳐져서 전체 Template 파일이 네트워크를 통해 전달되는 비효율적인 방식이 된다. 그러나, Jnode Framework는 실제로 필요로 하는 Node만 요청하고, 해당 Node를 위한 Template 파일과 JavaScript 파일, CSS 파일들만 Front-end로 전달되어 렌더링에 사용된다.

![Alt Jnode Framework architecutre](images/jnode_architecture.png?raw=true "Jnode Framework architecutre")

> 비대해진 프레임워크(Heavy framework)로 인해 피로도가 높아진 개발자들을 위해 가벼운 프레임워크(Thin framework)을 제공한다.

> 무늬뿐인 HTML5을 따르는 개발 환경이 아니라, 진정한 HTML5 권고안에 충실한 개발 환경을 구축해 준다.

> 다양한 Template engine들을 플러그인처럼 add-on할 수 있다.

> Template 파일로부터 JavaScript 파일, CSS 파일들을 분리하기 위한 최적화된 방법을 제시해 준다.

> HTML Controller, JavaScript Module 등 편리 라이브러리들을 제공하여 보다 쉽게 개발을 할 수 있다.

> +back-end 추가 패키지를 통해 JEE 혹은 PHP 환경의 data를 binding하여 Front-end에서 사용할 수 있다.

### 사용 가이드
Jnode Framework의 자세한 사용법은 아래의 Jnode Framework 공식 사이트를 참조하기 바란다.

[https://ko.jnodeframework.com](https://ko.jnodeframework.com/)

### 지원 환경
Jnode Framework는 HTML5를 지원하는 Web Application을 개발하기 위한 Front-end 개발 프레임워크이므로, HTML5를 지원하는 Client Web Browser (Safari, Chrome, Opera, Firefox, Edge, Internet Explorer 9 이상)에서 실행되는 애플리케이션 개발을 지원한다. Front-end 개발 Framework이지만, Back-end 개발 환경으로 가장 많이 사용하는 JEE와 PHP를 위해 추가 모듈을 제공한다. 이를 통해 Front-end의 템플릿 파일들을 Back-end에서 관리하고, Back-end의 Data를 Front-end로 바인딩할 수 있는 기능을 제공한다. 단, JEE Servlet 3.0 이상, PHP 7.0 이상을 공식으로 지원한다. 그 이하의 환경에서 사용하고자 한다면 직접 구현(implement)하도록 소스까지 제공하고 있다.

### 기부 Donate
Jnode Framework는 100% 무료 소프트웨어이다! 만약 Jnode Framework을 사용하면서 유용하다고 생각했다면, 자발적인 기부를 부탁드린다. 금액에 상관없이 참여한 기부금에 대해 보다 나은 Jnode Framework 개발로 보답하겠다. 아울러 우리 나라에서도 공개 소프트웨어가 활성화되고, 기부문화도 활성화되는 계기가 되었으면 한다.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6YYMTECUZXM9S)

### 다른 언어로 읽기
[영어 (English)](https://github.com/gurumdari/jnode)
