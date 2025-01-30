user-service/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/userservice/
│   │   │       ├── core/
│   │   │       │   ├── domain/
│   │   │       │   │   ├── entity/
│   │   │       │   │   │   ├── User.java
│   │   │       │   │   │   ├── Badge.java
│   │   │       │   │   │   └── UserChannelRelation.java
│   │   │       │   │   └── valueobject/
│   │   │       │   │       ├── user/
│   │   │       │   │       │   ├── UserId.java
│   │   │       │   │       │   └── UserRole.java
│   │   │       │   │       ├── badge/
│   │   │       │   │       │   ├── BadgeId.java
│   │   │       │   │       │   └── BadgeTitle.java
│   │   │       │   │       └── userchannelrelation/
│   │   │       │   │           ├── RelationId.java
│   │   │       │   │           └── RelationType.java
│   │   │       │   ├── ports/
│   │   │       │   │   ├── UserRepository.java
│   │   │       │   │   ├── UserAuthenticationService.java
│   │   │       │   │   ├── BadgeRepository.java
│   │   │       │   │   └── UserChannelRelationRepository.java
│   │   │       │   └── services/
│   │   │       │       ├── UserService.java
│   │   │       │       ├── AuthenticationService.java
│   │   │       │       ├── BadgeService.java
│   │   │       │       └── RelationService.java
│   │   │       ├── adapters/
│   │   │       │   ├── persistence/
│   │   │       │   │   ├── jpa/
│   │   │       │   │   │   ├── UserRepositoryJpaImpl.java
│   │   │       │   │   │   ├── UserJpaEntity.java
│   │   │       │   │   │   ├── BadgeRepositoryJpaImpl.java
│   │   │       │   │   │   ├── BadgeJpaEntity.java
│   │   │       │   │   │   ├── UserChannelRelationJpaImpl.java
│   │   │       │   │   │   └── UserChannelRelationJpaEntity.java
│   │   │       │   │   ├── querydsl/
│   │   │       │   │   │   └── ...
│   │   │       │   │   ├── mongo/
│   │   │       │   │   │   ├── UserRepositoryMongoImpl.java
│   │   │       │   │   │   ├── UserMongoEntity.java
│   │   │       │   │   │   ├── BadgeRepositoryMongoImpl.java
│   │   │       │   │   │   ├── BadgeMongoEntity.java
│   │   │       │   │   │   ├── UserChannelRelationMongoImpl.java
│   │   │       │   │   │   └── UserChannelRelationMongoEntity.java
│   │   │       │   │   └── common/
│   │   │       │   │       ├── UserMapper.java
│   │   │       │   │       ├── BadgeMapper.java
│   │   │       │   │       └── UserChannelRelationMapper.java
│   │   │       │   ├── api/
│   │   │       │   │   ├── UserController.java
│   │   │       │   │   ├── AuthenticationController.java
│   │   │       │   │   └── RelationController.java
│   │   │       │   ├── security/
│   │   │       │   │   ├── JwtTokenProvider.java
│   │   │       │   │   ├── CustomUserDetailsService.java
│   │   │       │   │   └── SecurityConfig.java
│   │   │       │   └── client/
│   │   │       │       └── ChannelServiceClient.java
│   │   │       ├── config/
│   │   │       │    └── AppConfig.java
│   │   │       └── ...
│   │   └── resources/
│   │       ├── application.yml
│   │       └── ...
│   └── test/
│       └── java/
│           └── com/example/userservice/
│               └── ...
├── pom.xml
└── ...