# SQL 튜닝 수업 노트


<img src="https://github.com/oracleyu01/test20/blob/main/001.png" width="600" height="400">

&nbsp;

## 수업 자료( ☀️ 2024년 6월 26일 updated)


- **튜닝예제1.  select 문의 실행과정 3단계를 먼저 아셔야해요**:  📄[노트](https://www.notion.so/164f3dfd7d3e45198ce868bafede3c6c?v=0e23b77813244ef8b44de4d43a3d7fda&p=f25b447bd9034bf0bbdcb5ba5a1ca76b&pm=s)
  &nbsp;
  
- **튜닝예제2.  옵티마이져가 뭔지 알아야해요 !**: 📄 [노트](https://www.notion.so/2-cd5fdc33e988487eb45bf22e61fc1faa?pvs=21)
  
- **튜닝예제3. 실행계획의 종류 2가지를 알아야합니다 !**: 📄[노트](https://www.notion.so/3-2-2b3e4e2f2ada4f92a9125a83d5bbc9d0?pvs=21)

- **튜닝예제4.  where 절에 인덱스 컬럼을 가공하지 마세요 !**: 📄[노트](https://www.notion.so/4-where-e2dfa73bb4624af38ce516a5515a1cc0?pvs=21)

- **튜닝예제5. having 절에 일반 검색조건을 쓰지 마세요 !**: 📄[노트](https://www.notion.so/5-having-7d2424d0ea294f04a775abe7e9d9301a?pvs=21)

- **튜닝예제6. where 에 인덱스 컬럼 가공이 불가피하다면 함수 기반 인덱스 생성하세요 !**: 📄[노트](https://www.notion.so/6-where-1804500b8c2f4fceae5f3ddef1060e76?pvs=21)

- **튜닝예제7. 암시적 형변환에 주의하세요 !**: 📄[노트](https://www.notion.so/7-d6e2275726074067bdb463cb267ed606?pvs=21)

- **튜닝예제8. Order by 를 통한 과도한 정렬작업을 피하세요 !**: 📄[노트](https://www.notion.so/8-order-by-e9a9e9f53fa04483872311ba3506026e?pvs=21)

- **튜닝예제9. 그룹함수 대신에 인덱스를 사용해서 SQL을 튜닝하세요**: 📄[노트](https://www.notion.so/9-SQL-6b9419c7c2394c04972235a08eaeb0c7?pvs=21)

- **튜닝예제10. 인덱스를 엑세스 하지 못하는 검색조건을 알아야해요**: 📄[노트](https://www.notion.so/10-0b7aeab9d4f34bf1a653ddd15962d767?pvs=21)

- **튜닝예제11. full table scan 을 할 수 밖에 없다면 full table scan 이 빠르게 되도록 튜닝하세요**: 📄[노트](https://www.notion.so/11-full-table-scan-full-table-scan-0e882e6809494200815ae2d9cd8e5631?pvs=21)

- **튜닝예제12. 인덱스를 탈 수 있도록 힌트를 사용하세요.**: 📄[노트](https://www.notion.so/12-37d404634fb94be8a7f77f73c281d3db?pvs=21)

- **튜닝예제13. 훌륭한 인덱스 2개를 같이 사용하여 시너지 효과를 볼 수 있어요**: 📄[노트](https://www.notion.so/13-2-975414b5bd7346da8f668616c3bb5952?pvs=21)

- **튜닝예제14. 테이블 랜덤 엑세스를 줄이기 위해 결합 컬럼 인덱스를 사용하세요**: 📄[노트](https://www.notion.so/14-22f3337f29734c2a964f946c76d753b8?pvs=21)

- **튜닝예제15. 결합 컬럼 인덱스 구성시 컬럼순서가 중요합니다**: 📄[노트](https://www.notion.so/15-0e9f7cf7e37846179026b65f70f9121a?pvs=21)

- **튜닝예제16. index skip scan 을 사용하세요 !**: 📄[노트](https://www.notion.so/16-index-skip-scan-7758f4a2d76d4ce8b23ee7344af08fda?pvs=21)

- **튜닝예제17. index full scan 을 사용하세요 !**: 📄[노트](https://www.notion.so/17-index-full-scan-1f553ee2a219489aac5192ce2a0cc3cb?pvs=21)

- **튜닝예제18. index fast full scan 을 사용하세요 !**: 📄[노트](https://www.notion.so/18-index-fast-full-scan-61d5491c7a634d13838f1772869c893b?pvs=21)

- **튜닝예제19. index bitmap merge scan 을 사용하세요 !**: 📄[노트](https://www.notion.so/19-index-bitmap-merge-scan-91efba813044479e8304c4993d5748a3?pvs=21)

- **튜닝예제20. index unique scan을 사용하세요 !**: 📄[노트](https://www.notion.so/20-index-unique-scan-038cca597517471fb1a83fb85c2f390a?pvs=21)

- **튜닝예제21. 조인문장을 튜닝할 때 조인 순서 튜닝이 중요합니다.**: 📄[노트](https://www.notion.so/21-c37e3b477bbd4218b701e123fc2ce435?pvs=21)

- **튜닝예제22. 검색조건에 따라 조인 순서를 잘 정해줘야합니다.**: 📄[노트](https://www.notion.so/22-a4396b6346fd46ffba5119ae0633e0fb?pvs=21)

- **튜닝예제23. 조인되는 데이터의 양이 작을 때는 nested loop조인으로 조인하세요 !**: 📄[노트](https://www.notion.so/23-nested-loop-0af79f5881924ae28532db19e48f973e?pvs=21)

- **튜닝예제24. 3개 이상의 테이블을 nested loop조인으로 조인할 때 힌트 사용법을 알아야 해요 !**: 📄[노트](https://www.notion.so/24-3-nested-loop-993ca9b270be41aaafd1d83c70fa8dad?pvs=21)

- **튜닝예제25. 대량의 데이터를 조인할 때는 해쉬조인을 사용하세요 !**: 📄[노트](https://www.notion.so/25-2fa4d0ad4e374c1fbc73355fd2335b6e?pvs=21)

- **튜닝예제26. 3개의 테이블을 해쉬 조인 할때 해쉬 테이블을 선택할 수 있어요 !**: 📄[노트](https://www.notion.so/26-3-101dcd13aa4341d091caa3fb61271e0e?pvs=21)

- **튜닝예제27. 해쉬조인이 안되는 연산자가 있어요 !**: 📄[노트](https://www.notion.so/27-8163788d251e4c309bf2d9a09b25c079?pvs=21)

- **튜닝예제28. 대량의 테이블을 조인하는데 해쉬조인을 할 수 없다면 sort merge join 을 하세요 !**: 📄[노트](https://www.notion.so/28-sort-merge-join-33c503a778764ae68cee9fcb2d67168c?pvs=21)

- **튜닝예제29. 아우터 조인은 이렇게 튜닝해야합니다 !**: 📄[노트](https://www.notion.so/29-e3d5d87f673f475192c01fdc5a8256d2?pvs=21)

- **튜닝예제30. 3개 이상의 테이블을 조인할 때 조인 방법을 다양하게 조절할 줄 알아야해요**: 📄[노트](https://www.notion.so/30-3-dec843ed59b544d49ee1884b3ad2b129?pvs=21)

- **튜닝예제31.선택적 조인을 하면서 조인의 성능을 높일 수 있어요 !**: 📄[노트](https://www.notion.so/31-90a7240118c241569171115b405ec5ee?pvs=21)

- **튜닝예제32. 인라인 뷰와 조인할 때는 인라인 뷰가 해체 되지 않게 하세요!**: 📄[노트](https://www.notion.so/32-e38994dac8c84d89ac3374a967f35c89?pvs=21)

- **튜닝예제33. 뷰와 조인을 할 때 조인 순서를 조정할 수 있어요 !**: 📄[노트](https://www.notion.so/33-13e563d9dbb04b0ebd2e4cf8c936c03e?pvs=21)

- **튜닝예제34. 조인의 성능을 높이고 싶다면 MVIEW 생성을 고려하세요 !**: 📄[노트](https://www.notion.so/34-MVIEW-1a39b84aa12c4bc795e0cce84180c03a?pvs=21)

- **튜닝예제35. 서브쿼리문에서 서브쿼리의 데이터가 작으면 서브쿼리부터 수행되게 해야해요 !**: 📄[노트](https://www.notion.so/35-5754c868303c41e183f2503bae19f3f1?pvs=21)

- **튜닝예제36. push_subq 와 no_push_subq 와의 짝꿍힌트를 알아야 해요 !**: 📄[노트](https://www.notion.so/36-push_subq-no_push_subq-738e044298d94578849211aeeb3c0911?pvs=21)

- **튜닝예제37. 서브쿼리를 세미조인으로 변경해서 수행되게 하세요 !!**: 📄[노트](https://www.notion.so/37-96ece50d2e2f43398c8ca8231b28948d?pvs=21)

- **튜닝예제38. 해쉬 세미 조인도 서브쿼리 부터 수행되게 할 수 있어요 !**: 📄[노트](https://www.notion.so/38-11e257c26e96430bac9cf25ed19895f2?pvs=21)

- **튜닝예제39. not in 연산자를 사용한 서브쿼리문을 튜닝할 줄 알아야해요 !**: 📄[노트](https://www.notion.so/39-not-in-47b5b88f1d634559a46d28d24a0267bf?pvs=21)

- **튜닝예제40. in 연산자를  exists 로 변경해서 튜닝할 줄 알아야해요 !**: 📄[노트](https://www.notion.so/40-in-exists-a1046425164d41d79ce471f888f327a1?pvs=21)

- **튜닝예제41. minus 를 not exists 문으로 변경해서 튜닝하세요 !**: 📄[노트](https://www.notion.so/41-minus-not-exists-5814b59e1e5c43f6adc1427fbedea224?pvs=21)

- **튜닝예제42. 데이터 분석함수를 이용해서 SQL을 재작성할 줄 알아야해요. 첫번째 !!**: 📄[노트](https://www.notion.so/42-SQL-df72e228b3974512b0f6bee7594a764b?pvs=21)

- **튜닝예제43. 데이터 분석함수를 이용해서 SQL을 재작성할 줄 알아야해요. 두번째 !**: 📄[노트](https://www.notion.so/43-SQL-bb8d842dcdc14d6690759bb508ced2fb?pvs=21)

 - **튜닝예제44. 데이터 분석함수를 이용해서 SQL을 재작성할 줄 알아야해요. 세번째 !**: 📄[노트](https://www.notion.so/44-SQL-b7bf656d680b461ab0ee37d1427aefec?pvs=21)

- **튜닝예제45. 데이터 분석함수를 이용해서 SQL을 재작성할 줄 알아야해요. 네번째 !**: 📄[노트](https://www.notion.so/45-SQL-baafa96fea694f74acdec3f437bd3c23?pvs=21)

- **튜닝예제46. 데이터 분석함수를 이용해서 SQL을 재작성할 줄 알아야해요. 다섯번째 !**: 📄[노트](https://www.notion.so/46-SQL-9952caa00f124deb8e21ea8e07d55cae?pvs=21)

- **튜닝예제47. update 문의 튜닝방법을 잘 알아야해요 !**: 📄[노트](https://www.notion.so/47-update-5606ffa3b7224dce94e2e959876c7257?pvs=21)

- **튜닝예제48. 파티션 테이블이 뭔지 알아야해요 !**: 📄[노트](https://www.notion.so/48-36da11d44fb84a709b7545c661e66e4b?pvs=21)

- **튜닝예제49. 리스트 파티션이 뭔지 알아야해요 !**: 📄[노트](https://www.notion.so/49-02660b2b4e734626b1d07f3dc459df56?pvs=21)

- **튜닝예제50. 해쉬 파티션이 뭔지 알아야해요 !**: 📄[노트](https://www.notion.so/50-255e010c9c0840beb65f25750807f171?pvs=21)
