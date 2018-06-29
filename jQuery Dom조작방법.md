# jQuery DOM조작방법

1. $('선택자')

   1. $('#선택자') : id를 검색 ex) ('#pw') => pw가 id 인 tag를 찾아서 가져와줌

   2. ('.선택자')  : class를 검색 ex)$('.email') => email을 클래스로 가진 모든 tag를 가져와줌

   3. $('[]') : attribute를 검색

      1. ex)$('[href]') : href특성을 가진 모든 태그를 가져와줌,

         $('[href="www.naver.com"]') :href가 네이버인 태이블을 모두 가져와줌