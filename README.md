### Spring Boot를 이용한 쇼핑몰 프로젝트

![img](C:/Users/dabee/OneDrive/%EB%B0%94%ED%83%95%20%ED%99%94%EB%A9%B4/img.png)

> 쇼핑몰 기능

- 회원가입
- 로그인 / 로그아웃
- 상품 등록 / 상품 목록 / 상품 수정
- 장바구니 / 주문

> 활용

- Spring Boot
- SQL Developer
- mybatis
- tiles

> 작동 구조

`Request`  -	-	-	-	 `Controller` -	-	-	-  `Model(mybatis -> sql)`

​	  |									     |					

​	  |									     |			

​	  |									     |   **Tiles**

​	  |									     |

​	  |									     |

​		 	-	-	-	-		 `View Page`	

​			   **submit**

