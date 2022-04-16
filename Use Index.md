-- 인덱스 조회<br>
show index from 테이블명<br>
-- 인덱스 생성(둘 중 하나 사용)<br>
create index 인덱스명 on 테이블명(컬럼명)<br>
alter table 테이블명 add index 인덱스명(컬럼명)<br>
-- 인덱스 삭제<br>
alter table 테이블명 drop index 인덱스명;<br>
-- 인덱스 타는지 확인하는법<br>
EXPLAIN (type이 all, possible Key 가 null 일 경우에는 안탐  type이 ref일때 possible_key를 보자)<br>
select * from tb_1
