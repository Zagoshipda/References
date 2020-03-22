C++ Study
==========


 <br/><br/>


### References
- [Standard C++](https://isocpp.org/)
    - [___C++ Core Guidelines___](http://isocpp.github.io/CppCoreGuidelines/)
- [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
- [C++ Standard Library Reference | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/standard-library/cpp-standard-library-reference?view=vs-2019)
- [cppreference.com](https://en.cppreference.com/w/)
- [cplusplus.com - The C++ Resources Network](http://www.cplusplus.com/)
- [C++ Team Blog](https://devblogs.microsoft.com/cppblog/)
- [씹어먹는 C++ 강좌 계획](https://modoocode.com/135)
- [Learn C++](https://www.learncpp.com/)
- [Learn C and C++ Programming - Cprogramming.com](https://www.cprogramming.com/) (C/C++ Graphics Game Algorithms)  <br/><br/>
- [스터디메이크 :: C++ 강의 글 목록 (목차)](https://studymake.tistory.com/8)
- [나는 개발자다](https://studyc.tistory.com/) (C 언어 강좌 + youtube 강의)
- [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page) (C++ template library for linear algebra)


 <br/><br/>


### General
- [Open Sourcing MSVC's STL | C++ Team Blog](https://devblogs.microsoft.com/cppblog/open-sourcing-msvcs-stl/)
- [Power Function in C/C++ - GeeksforGeeks](https://www.geeksforgeeks.org/power-function-cc/) (add 0.5 to the result and then typecast to int)
- [floating point - C: i got different results with pow(10,2) and pow(10,j), j=2; - Stack Overflow](https://stackoverflow.com/questions/19126809/c-i-got-different-results-with-pow10-2-and-pow10-j-j-2)
- [[C++] 함수 앞에 쓰이는 const 키워드는 어떤 의미인가요? | KLDP](https://kldp.org/node/71134) (리턴값은 r-value이기 때문에 수정이 불가능)
    - [[C++ 강좌] 029 - 함수에서 const의 사용 (2) - const가 붙은 멤버 함수 : 네이버블로그](https://blog.naver.com/kks227/60205418298) (___const로 선언된 object에서의 호출을 가능하게 함___ -> 전체 코드의 안정성을 높임)
- [C++ Rvalue References Explained](http://thbecker.net/articles/rvalue_references/section_01.html) (Thomas Becker)
- [C++ named requirements: LegacyRandomAccessIterator - cppreference.com](https://en.cppreference.com/w/cpp/named_req/RandomAccessIterator)
    - [Iterators in C++ STL - GeeksforGeeks](https://www.geeksforgeeks.org/iterators-c-stl/)
- [소년코딩 - C++ 07.20 - 이중 포인터와 동적 다차원 배열 (Pointers to pointers and dynamic multidimensional arrays)](https://boycoding.tistory.com/212)
    - [[오늘, 행복하자!] [C++] 2차원 배열 동적 할당, 해제하기](https://felixblog.tistory.com/72)
    - [How do I declare a 2d array in C++ using new? - Stack Overflow](https://stackoverflow.com/questions/936687/how-do-i-declare-a-2d-array-in-c-using-new)  <br/><br/>
- [c - Correct format specifier for double in printf - Stack Overflow](https://stackoverflow.com/questions/4264127/correct-format-specifier-for-double-in-printf)
- [___c - Is an array name a pointer? - Stack Overflow___](https://stackoverflow.com/questions/1641957/is-an-array-name-a-pointer)
    - [씹어먹는 C 언어 - <12 - 2. 포인터는 영희이다! (포인터)>](https://modoocode.com/24) (___배열은 배열이고 포인터는 포인터다___, 배열 이름은 포인터가 아니다)
    - [씹어먹는 C 언어 - <12 - 3. 포인터는 영희이다! (포인터)>](https://modoocode.com/25) (___배열 이름의 주소값, 배열과 포인터의 관계___, 1차원 배열에서 배열의 이름은 첫 번째 원소를 가리키는 포인터로 타입 변환, 2차원 배열에서 배열의 이름은 첫 번째 행(이 역시나 배열)을 가리키는 포인터로 타입 변환)
- [std::qsort - cppreference.com](https://en.cppreference.com/w/cpp/algorithm/qsort)
    - [___C qsort() vs C++ sort()___ - GeeksforGeeks](https://www.geeksforgeeks.org/c-qsort-vs-c-sort/)
    - [C qsort 함수 vs C++ sort 함수 (작성중)](https://adaid.tistory.com/64)
    - [gshscs :: [C++ STL] Header <algorithm> – 1. Sort 파헤치기 (1)](https://gshscs.tistory.com/11)
- [Difference between Header file and Library - GeeksforGeeks](https://www.geeksforgeeks.org/difference-header-file-library/)
    - [[C++] C++ 헤더파일의 명명 – Qaupot's blog](http://www.qaupot.com/wordpress/?p=2206)  <br/><br/>
- [___Array of Vectors___ in C++ STL - GeeksforGeeks](https://www.geeksforgeeks.org/array-of-vectors-in-c-stl/) (___vector <data_type> V[size]___)
- [우주의 중심 :: [C++] String과 char 배열 비교](https://mk28.tistory.com/entry/C-String%EA%B3%BC-char-%EB%B0%B0%EC%97%B4-%EB%B9%84%EA%B5%90)
- [MultiThread Life - C++ 객체생성 두가지 방법과 의문점(___new를 이용한 동적할당객체___)](https://multithread.tistory.com/entry/C-%EA%B0%9D%EC%B2%B4%EC%83%9D%EC%84%B1-%EB%91%90%EA%B0%80%EC%A7%80-%EB%B0%A9%EB%B2%95%EA%B3%BC-%EC%9D%98%EB%AC%B8%EC%A0%90new%EB%A5%BC-%EC%9D%B4%EC%9A%A9%ED%95%9C-%EB%8F%99%EC%A0%81%ED%95%A0%EB%8B%B9%EA%B0%9D%EC%B2%B4)


 <br/><br/>


## Standard Template Library (STL)
- [[C++] STL 이란. :: 개발자 지망생](https://blockdmask.tistory.com/67)
- [개발이 하고 싶어요 :: [STL] 역방향 반복자 (reverse_iterator)](https://hyeonstorage.tistory.com/322)
- [[C++11] cbegin()과 cend(), crbegin()과 crend()](https://psychoria.tistory.com/70)
- [c++ - What is the difference between cbegin and begin for vector? - Stack Overflow](https://stackoverflow.com/questions/31208640/what-is-the-difference-between-cbegin-and-begin-for-vector)
- [씹어먹는 C++ - <10 - 1. C++ STL - 벡터(std::vector), 리스트(list), 데크(deque)>](https://modoocode.com/223)


 <br/><br/>
 

### pair, tuple
- [pair::pair - C++ Reference](http://www.cplusplus.com/reference/utility/pair/pair/)
- [[C++/STL]pair, vector](https://sarah950716.tistory.com/4)

 <br/><br/>


### list, deque 
- [[C++] list container 정리 및 사용법 :: 개발자 지망생](https://blockdmask.tistory.com/76)
- [개발이 하고 싶어요 :: [STL] list 정리 및 예제](https://hyeonstorage.tistory.com/326)


 <br/><br/>
 

### vector
- [C++ - Initializing a std::vector | c++ Tutorial](https://riptutorial.com/en/cplusplus/example/1676/std----vector-%EC%B4%88%EA%B8%B0%ED%99%94%ED%95%98%EA%B8%B0)
- [In what scenarios should I use emplace_back, instead of push_back, in C++? - Quora](https://www.quora.com/In-what-scenarios-should-I-use-emplace_back-instead-of-push_back-in-C++)
- [[C++ STL] std::vector - emplace_back](https://shaeod.tistory.com/630)
- [std::vector embrace_back 과 push_back의 차이 (The difference between emplace_back and push_back in a std::vector container)](https://blog.naver.com/sorkelf/220825930008)
- [나만의 연습장 :: emplace_back 과 push_back 의 차이](https://openmynotepad.tistory.com/10)
- [[C++] vector container 정리 및 사용법 :: 개발자 지망생](https://blockdmask.tistory.com/70)
- [DEV & PS :: C++ STL 1. vector(벡터)](https://canna90.tistory.com/41)
- [오늘은 맑음 :: C++ 이차원 벡터 사용](https://wh00300.tistory.com/116)
- [[C++ STL] 동적 2차원 배열 사용법(vector)](https://sunnyholic.com/93)


 <br/><br/>


### map, unordered map, multimap
- [[C++] map container 정리 및 사용법 :: 개발자 지망생](https://blockdmask.tistory.com/87)
- [개발이 하고 싶어요 :: [STL] multimap 정리 및 예제](https://hyeonstorage.tistory.com/330)
- [set::insert map::insert에 관한 고찰...](https://blog.naver.com/sorkelf/40148176100) (map.insert(pair<>) 와 map[a]=b의 차이점)
- [[C++/STL]map, set](https://sarah950716.tistory.com/6)
- [dictionary - How can I print out C++ map values? - Stack Overflow](https://stackoverflow.com/questions/14070940/how-can-i-print-out-c-map-values)
- [About STL : C++ STL 프로그래밍(7)-맵(Map) - 한빛출판네트워크](http://www.hanbit.co.kr/channel/category/category_view.html?cms_code=CMS9990721111)


 <br/><br/>


### set, unordered set, multiset 
- [[C++] set container 정리 및 사용법 :: 개발자 지망생](https://blockdmask.tistory.com/79)
- [개발이 하고 싶어요 :: [STL] set 정리 및 예제](https://hyeonstorage.tistory.com/327)


 <br/><br/>


