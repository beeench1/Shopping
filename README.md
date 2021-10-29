### Spring Boot를 이용한 쇼핑몰 프로젝트

![img](https://www.google.com/url?sa=i&url=https%3A%2F%2Fspring.io%2Fprojects%2Fspring-boot&psig=AOvVaw379DR9NPtbyT8i-LR7rKLp&ust=1635572164601000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCPDs8aLz7vMCFQAAAAAdAAAAABAu)

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

