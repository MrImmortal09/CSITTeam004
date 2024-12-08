# Pixello Architecture
## 1. System Context Diagram

![initial](https://github.com/user-attachments/assets/10f289e7-4cf9-4175-af6b-eae8944b4657)


```
@startuml
' External Actors
actor "User" as User
actor "Notification Service" as NotificationService

' System Boundary: Pixello App
package "Pixello App" {

    ' Subsystems
    rectangle "User Authentication \nand Profile Management" as AuthSystem
    rectangle "Photo and Video Upload \nand Sharing" as MediaSystem
    rectangle "Feed Generation \nand Social Interactions" as FeedSystem
    rectangle "Direct Messaging" as ChatSystem
    rectangle "Analytics \nand Insights" as AnalyticsSystem
}

' Relationships between actors and system components
User --> AuthSystem : Sign Up/Login
User --> MediaSystem : Upload Photos/Videos
User --> FeedSystem : View/Interact with Feed
User --> ChatSystem : Send/Receive Messages
User --> AnalyticsSystem : View Engagement Insights

MediaSystem --> NotificationService : Notify Followers
@enduml


```
---
## 2. Container Diagram 
The container diagram breaks down the system into high-level containers and their interactions.

![cotainer](https://github.com/user-attachments/assets/6c7d0c86-6d5c-4054-a641-3d63a7b10aa1)


```
@startuml
title Container Diagram - Pixello

' Add primary containers
rectangle "Mobile/Web App" as App <<User Interface>> #lightblue
rectangle "API Gateway" as APIGateway <<API Gateway>> #lightgreen
rectangle "Media Service" as MediaService <<Service>> #lightyellow
rectangle "Feed Service" as FeedService <<Service>> #lightyellow
rectangle "Chat Service" as ChatService <<Service>> #lightyellow
rectangle "Analytics Service" as AnalyticsService <<Service>> #lightyellow

' Database containers
database "User Database" as UserDB <<Database>> #lightpink
database "Media Database" as MediaDB <<Database>> #lightpink
database "Feed Database" as FeedDB <<Database>> #lightpink

' External services
rectangle "Notification Service" as NotificationService <<External Service>> #lightgray

' Relationships between containers
App --> APIGateway : API Requests
APIGateway --> MediaService : Upload Media
APIGateway --> FeedService : Generate Feed
APIGateway --> ChatService : Send/Receive Messages
APIGateway --> AnalyticsService : Engagement Insights
APIGateway --> NotificationService : Send Notifications

MediaService --> MediaDB : Store Media
FeedService --> FeedDB : Manage Feed Data
AnalyticsService --> UserDB : Analyze User Data
@enduml

```
---
## 3. Component Diagrams
### 3.1 Component Diagram for Users
This diagram shows the system components and interactions from the user's perspective.

![componentuser](https://github.com/user-attachments/assets/e824ea26-c840-4872-86ae-6896fc413914)


```
@startuml
' External Actor
actor "User" as User

' System Boundary: Pixello App
package "Pixello App" {

    ' Subsystems for User
    rectangle "Authentication \nand Profile Management" as AuthSystem
    rectangle "Photo and Video Upload \nand Sharing" as MediaSystem
    rectangle "Feed Generation \nand Social Interactions" as FeedSystem
    rectangle "Direct Messaging" as ChatSystem
    rectangle "Analytics \nand Insights" as AnalyticsSystem
}

' Relationships between User and system components
User --> AuthSystem : Sign Up/Login
User --> MediaSystem : Upload Photos/Videos
User --> FeedSystem : View/Interact with Feed
User --> ChatSystem : Send/Receive Messages
User --> AnalyticsSystem : View Engagement Insights
@enduml

```
### 3.2 Component Diagram for Admins
This diagram shows the system components and interactions from the admin's perspective.

![componentadmin](https://github.com/user-attachments/assets/825ddf81-50ee-4427-8b51-345bf7e5e055)


```
@startuml
' External Actor
actor "Admin" as Admin

' System Boundary: Pixello Admin Panel
package "Admin Panel" {

    ' Subsystems for Admin
    rectangle "User Management" as UserManagement
    rectangle "Content Moderation" as ContentModeration
    rectangle "Analytics Management" as AnalyticsManagement
    rectangle "Notification Management" as NotificationManagement
}

' Relationships between Admin and system components
Admin --> UserManagement : Manage Users
Admin --> ContentModeration : Moderate Content
Admin --> AnalyticsManagement : Analyze Metrics
Admin --> NotificationManagement : Manage Notifications
@enduml

```
---
# 4. Deployment Diagram
This diagram outlines the physical deployment of the system across servers, databases, and external services.

![image](https://github.com/user-attachments/assets/1c445bfa-e925-4b93-a3f5-9d2e148f1992)


```
@startuml
title Deployment Diagram - Pixello

node "User's Device" {
    [Mobile/Web App] <<User Interface>>
}

node "Server" {
    [API Gateway] <<API Gateway>>
    [Media Service] <<Service>>
    [Feed Service] <<Service>>
    [Chat Service] <<Service>>
    [Analytics Service] <<Service>>
}

node "Database Server" {
    database "User Database" as UserDB
    database "Media Database" as MediaDB
    database "Feed Database" as FeedDB
}

cloud "External Services" {
    [Notification Service] <<External Service>>
}

' Connections
[Mobile/Web App] --> [API Gateway] : API Calls
[API Gateway] --> [Media Service] : Handle Media
[API Gateway] --> [Feed Service] : Generate Feed
[API Gateway] --> [Chat Service] : Manage Messages
[API Gateway] --> [Analytics Service] : Analyze Engagement
[Media Service] --> MediaDB : Store Media
[Feed Service] --> FeedDB : Feed Data
[Analytics Service] --> UserDB : User Data
@enduml

```
---
