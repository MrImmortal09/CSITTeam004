## Sequence Diagram

@startuml
actor User

User -> AuthenticationService: Sign Up / Log In
AuthenticationService -> Database: Verify Credentials / Store User Data
<br>
User -> ProfileService: Update Profile
ProfileService -> Database: Save Profile Data
<br>
User -> PhotoService: Upload Photo
PhotoService -> Database: Store Photo
<br>
User -> FeedService: View Feed
FeedService -> Database: Fetch Posts from Followed Users
<br>
User -> LikeService: Like Post
LikeService -> Database: Update Like Count
<br>
User -> CommentService: Comment on Post
CommentService -> Database: Store Comment
@enduml
<br>

@startuml
actor User

usecase "Sign Up / Log In" as UC1
usecase "Update Profile" as UC2
usecase "Upload Photo" as UC3
usecase "Like Post" as UC4
usecase "Comment on Post" as UC5
usecase "Follow/Unfollow User" as UC6
usecase "View Feed" as UC7
usecase "Search for Users" as UC8
usecase "Receive Notifications" as UC9
<br>
User --> UC1
User --> UC2
User --> UC3
User --> UC4
User --> UC5
User --> UC6
User --> UC7
User --> UC8
User --> UC9
@enduml
<br>
