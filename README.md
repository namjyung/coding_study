## 깃 튜토리얼

소스코드 블록은 다음과 같음

```cpp
#include <iostream>
using namespace std;

int main()
{
    string s;
    cin>>s;
    int cnt=0;
    for(int i=0; i<s.length()/2; i++){
        if(s[i]==s[s.length()-i-1]){
            cnt++;
        }
    }
    if(cnt==s.length()/2) cout<<1;
    else cout<<0;
}



```

링크는 다음과 같다

[블로그 주소](url)


순서없는 목록은 다음과 같다
* 깃 튜토리얼
  *깃 Clone
  *깃 Pull
  *깃 Commit
    *깃 Commit 1)

인용 구문
> ㅎㅇ


테이블 다음과 같음
이름|영어|정보|수학
---|---|---|---|
A|B|C|D|

강조는 다음과 같음
**치킨** ~~으아아아~~
