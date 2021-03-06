  * [수학 관련 정보](%EC%88%98%ED%95%99%20%EA%B4%80%EB%A0%A8%20%EC%A0%95%EB%B3%B4.md), [소프트웨어/목록](%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4/%EB%AA%A9%EB%A1%9D.md)  

![http://his.cuahsi.org/images/matlablogo.jpg](http://his.cuahsi.org/images/ma
tlablogo.jpg)

[[JPG external image]](http://his.cuahsi.org/images/matlablogo.jpg)

  
로고

![http://www.sph.emory.edu/about/information_technology/images/matlabdesktop_l
g.jpg](http://www.sph.emory.edu/about/information_technology/images/matlabdesk
top_lg.jpg)

[[JPG external image]](http://www.sph.emory.edu/about/information_technology/i
mages/matlabdesktop_lg.jpg)

  
일반적인 개발환경

이 항목은 [매트랩](%EB%A7%A4%ED%8A%B8%EB%9E%A9.md),
[매틀랩](%EB%A7%A4%ED%8B%80%EB%9E%A9.md)으로도 들어올 수 있다.

  

## Contents

    

1. 개요 
2. 역사 
3. 특징 
    

3.1. 장점

3.2. 단점

4. 기타 

[[edit](http://rigvedawiki.net/r1/wiki.php/MATLAB?action=edit&section=1)]

# 1. 개요 ¶

  

Mathworks사에서 개발하고 있는 [공학](%EA%B3%B5%ED%95%99.md)용 프로그램 및 [프로그래밍 언어](%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%96%B8%EC%96%B4.md)이다.
[2015년](2015%EB%85%84.md) [4월](4%EC%9B%94.md) 현재 R2015b가 최신버전이며, 이름의
MAT는 Mathematics가 아니라 [Matrix](%ED%96%89%EB%A0%AC.md)다.

  

대부분의 [미국](%EB%AF%B8%EA%B5%AD.md)공대에서 처음으로 프로그래밍에 입문하는 학생들이 제일 먼저 배우는
프로그램이다. 프로그래밍 언어라고 볼수도 있고, 어플리케이션으로도 볼 수 있으나, 쓰는 사람의 목적에 따라 두가지 성격이 모두 나타난다.
현재 쓰이는 프로그래밍 언어 중 19위 정도로 사용자의 층이 꽤 큰편이다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/MATLAB?action=edit&section=2)]

# 2. 역사 ¶

  

1970년대에 뉴 멕시코 대학의 컴퓨터 공학과의 학장인 클리브 몰러의 주도아래 개발이 시작되었으며, 1984년 본격적으로
Mathworks사를 세우고 개발하여 2000년대에 처음으로 일반 사용자에게 판매되기 시작하였다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/MATLAB?action=edit&section=3)]

# 3. 특징 ¶

  

보통 일반적인 프로그래밍 언어에서 행렬은 그저 각 차원으로 이루어진 방식으로, 현실의 행렬계산 방식과는 거리가 좀 있으며, 그에 따라 각
행렬에 대한 값을 구하려면 그 부분 역시 유저들이 직접 알고리즘을 짜서 계산해야한다. 그러나 문제는 대부분의 공학이 행렬계산 위에 성립된
학문이기 때문에 행렬계산이 불편한 일반적인 프로그래밍 언어는 공학계열에서 사용하기 힘들었다.

  

또한 C/C++나, 이후 개발된 Java도, 애시당초 다목적 용도를 가지고 개발되었기 때문에 공학용으로 디자인된 수식을 계산하기 위해선
공학도들이 알고리즘에 숙달될 필요가 있었다. 하지만 각 공학과의 현실상 그러한 것을 가르치기도 힘들었고, 가르칠 커리큘럼도 만들어져있지
않았다. 또한 컴퓨팅 파워 역시 1990년 이전에는 부족한 편이었으므로, 공학계산과 시뮬레이션에 있어 컴퓨터가 절대적으로 필요했으나 그
유용방식이 한정되어 있었다. 또한 Fortran등의 단순 계산에 적합한 언어들의 경우 그 나름의 장점이 있었으나 병렬계산에 적합하지 못했다.

  

그러나 매트랩은 공학과 시뮬레이션에 특화된 언어라는 목적을 가지고 개발되었으며, 그에 따라 시간과 (자금적)리소스를 크게 사용하지 않으면서도
목적을 달성하기 위해 기존 언어와 다른 개념을 들고 개발이 되는데, 그건 바로 쓰일만한 명령어셋이란 명령어셋은 죄다 컴파일러에
쳐박는(...) 비효율적이나 사용자 입장에선 쉬운 방법을 택한것이다. 또한 기존 언어와의 차이점으로, 모든 정의한 변수는 행렬취급이 된다.
이는 공학계에서 수 많은 변수들을 간편화 하기 위해 행렬을 사용하기에 이러한 방법을 택한것이다.

  

매트랩이 처음 사용자용으로 발표된 2000에는 컴퓨팅 파워의 한계와 여전히 컴퓨터 보급의 난항으로 이 느린 매트랩이 주목받지 못했으나, 얼마
안되어 컴퓨터의 급격한 보급으로 인해 매트랩은 그 사용하기와 가르치기에 간편함에 주목받아 공학도들이라면 한번씩 만져본 프로그래밍 언어가
되었다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/MATLAB?action=edit&section=4)]

## 3.1. 장점 ¶

  

  * [C언어](C%EC%96%B8%EC%96%B4.md) 만큼의 효율성을 보여주지는 못 하나 [문법](%EB%AC%B8%EB%B2%95.md)이 쉽기 때문에 작은 규모의 계산이나 [알고리즘](%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98.md)을 테스트할때 쓴다. 컴퓨팅 리소스는 많이 먹지만 컴파일러에 워낙 박혀있는 명령어셋이 많아 개발할때 시간과 비용을 절약할 수 있으므로, 테스트는 매트랩으로, 실제 개발은 C나 Java로 하는 경우도 상당히 많다.   

  * 일부 공학대에서는 쉬운 문법에 주목해서 프로그램의 개념을 익히기 위한 입문용으로도 자주 쓰인다. <del>근데 이 용도로는 [Python](Python.md)이 낫다. 공짜!!! 우리 모두 [오픈소스](%EC%98%A4%ED%94%88%EC%86%8C%EC%8A%A4.md)를 애용합시다!!</del>  

  * 공대 학부생의 프로젝트에서는 프로그램을 짜는 것이 목적이 아니라 간단한 시뮬레이션의 결과를 내는 것이 목적이기 때문에 매트랩를 쓰는게 시간절약에는 더 나은 경우도 보인다. [매스매티카](mathematica.md)는 정확한 결과를 내지만, 대부분의 공학관련문제는 이산수학등의 순수 [수학](%EC%88%98%ED%95%99.md)에서 요구하는 정확도가 필요 없다.  

  * 애플리케이션으로의 특징은, 매트랩 용으로 개발된 여러가지 패키지(프로그램 모음)을 이용하여 그래프 작업이나 [미분방정식](%EB%AF%B8%EB%B6%84%EB%B0%A9%EC%A0%95%EC%8B%9D.md) 계산, 또는 신호 처리 같은 계산을 수행할 수 있다. 이런 작업들은 자신이 직접 프로그램 언어로 구현 하려면 매우 어려운 작업들이다.  

  * 지들도 한계를 알고 있어서, CMEX, FMEX등의 함수로 C나 Fortran으로 짜인 함수의 결과값을 불러올 수 있다. <del>[돚거](%EB%8F%84%EC%A0%81.md)</del>  

  * 모든 연산을 행렬연산으로 프로그래밍 할 수 있다면, MATLAB만큼 강력한 것이 없다.  

[[edit](http://rigvedawiki.net/r1/wiki.php/MATLAB?action=edit&section=5)]

## 3.2. 단점 ¶

  * 위의 이야기에서도 보이듯, 무지막지한 명령어셋을 가지고 있는 **인터프리터 언어**이기 때문에 더럽게 무겁다. 따라서 아무리 효율적으로 짜도 C는 커녕 **가상머신위에서 돌아가는 JAVA보다 느리다.** 그렇다고 기능 자체로 보면 빠른편 아니냐고 할텐데, 천만의 말씀. **매스매티카가 매트랩보다 더 정확하고 더 빠르다.** 단지 기능이 적을뿐.   

  * 명령어셋이 그냥 무식하게 때려박혀있는 구조이기 때문에 필요한 헤더만 선언하여 최적화를 할 수가 없다. 위의 단점과 더불어 매트랩이 본격적인 언어로 쓰이지 않는 이유이다.  

  * 모든 연산이 벡터로 처리되므로 코드가 너무 쉽게 **스파게티 코드가 된다**.   

  * 컴공과라면 이 언어를 절대 손대지 말아야 할 이유가 또 있는데, **[디버깅](%EB%94%94%EB%B2%84%EA%B9%85.md) 하기가 무지 나쁘다.**   
  

  * 2012a 버전 부터는 좀 많이 덜하지만, 그 이전 버전은 [윈도우](%EC%9C%88%EB%8F%84%EC%9A%B0.md)유저 입장에서는 **악성코드**라고 불릴 정도로 느리고 짜증났다. 한번 설치하면 삭제가 제대로 안될 정도였으니(...). 그에 반해 [OS X](OS%20X.md)에서는 비교적 잘 돌아갔다.   

  * 라이센스 비용이 좀 지나치게 비싸다. 보통 학생용은 기능을 제한하는 대신 싸게 파는게 보통인데, 매트랩은 한화로 15만원씩 한다. <del>[GNU](GNU.md):옥타브 쓰세요 옥타브</del>  

  * 간단한 행렬연산을 for, if, while문으로 써서 만든다면, 무지막지하게 시간이 걸린다. 그래서 매트랩 입문자들에게는 튜토리얼때 가능한 한 Vectorization이라는 테크닉을 사용하도록 가르치는 것이 보통. 이름은 거창해보이지만, 단순히 for, if, while 대신 매트랩에서 자체 지원하는 함수들을 사용하는 것이라고 생각하면 편하다. for이나 while loop은 그 구조 상 순차적(sequential)으로 처리할 수 밖에 없지만, 매트랩의 행렬 관련 operation들은 병렬(parallel) 연산을 지원하기 때문. 효율이 몇십~몇백배 이상 증가한다.  

[[edit](http://rigvedawiki.net/r1/wiki.php/MATLAB?action=edit&section=6)]

# 4. 기타 ¶

비슷한 프로그램으로 [매스매티카](mathematica.md)(mathematica)와
[메이플](%EB%A9%94%EC%9D%B4%ED%94%8C#s-2.md)(maple), 그리고 SciLab이 있다. 매트랩과
매스매티카는 각각 차이가 있는데, 매트랩은 내부 알고리즘이 주로 수치로 돌아가기 때문에 계산도 느린 주제에 정확성도 떨어지고, 매스매티카는
다항식을 그대로 쓰기 때문에 정확성은 매우 높다. 단지 매스매티카가 지원하지 않는 기능들을 매트랩이 지원하는 경우가 많기에 공대생은 주로
매트랩을 쓰는편이고, 이산수학을 연구하는 수학자들은 매스매티카를 주로 사용한다.`[1]`

  

참고로 그냥 단순히 MATLAB을 배우는 대학생들은 한문제 푸는데 명령창을 500줄을 넘기는 경우는 거의 없을 것이다. 그런데 대학원
석사.박사 논문 쓰는순간 1000줄의 영역을 쳐다보게 될것이고, 정말 끝을 보는 사람들은 5000줄의 경지에 도달한다. 참고로 MATLAB
명령창 30~40줄이 A4 한장을 차지한다는걸 감안하면 이미 천줄만 넘어가도 멘탈붕괴 시작이고, 천 줄 가량 짰는데 오타 한글자 때문에 결과
에러 뜨면 그 순간 <del>멘탈붕괴</del>. <del>그러니 비 전산 공학인들은 무식함을 버리고 프로그래밍 방법론을 배워서 코드를
분할하자.</del> <del>그리고 메뉴얼을 한 번 더 읽어보면 10줄로 짰던 게 1줄로 끝나는 기능도 많이 구현되어 있다. 선배가 1달
걸려 짜둔 기능을 1주일만에 백지부터 다시 짜보는 것도 재미있다.</del>

  

실 MATLAB 자체의 계산 엔진도 나날이 발전을 거듭하는 중이어서, 코드만 효율적으로 짠다면 (사실 MATLAB은 어떻게 코드를 효율적으로
바꿀수 있는지도 가이드 해주는 기능이 있다..), 아~주 답답하지 않을정도로 최적화는 가능하다. <del>그래도
[자바](%EC%9E%90%EB%B0%94.md)보다 느린건 어쩔건데(...)</del>

`\----`

  * `[1]` 물론 매스매티카가 다중 적분식으로 가면 느려지긴 하는데, 그건 매트랩이 정확도를 크게 요구하지 않다 보니 항을 100분할정도 해서 그냥 사다리꼴등으로 계산해버리는 편법을 써서 그렇다. 그런식으로 정확도를 희생해서 속도를 높일 수 있는 경우가 아닌 일반적인 계산은 매트랩이 매스매티카보다 느리다.

