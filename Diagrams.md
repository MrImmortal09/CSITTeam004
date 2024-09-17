## Sequence Diagram

@startuml<br>
actor User <br>

User -> AuthenticationService: Sign Up / Log In
<br>
AuthenticationService -> Database: Verify Credentials / Store User Data
<br>
User -> ProfileService: Update Profile
<br>
ProfileService -> Database: Save Profile Data
<br>
User -> PhotoService: Upload Photo
<br>
PhotoService -> Database: Store Photo
<br>
User -> FeedService: View Feed
<br>
FeedService -> Database: Fetch Posts from Followed Users
<br>
User -> LikeService: Like Post
<br>
LikeService -> Database: Update Like Count
<br>
User -> CommentService: Comment on Post
<br>
CommentService -> Database: Store Comment
<br>
@enduml
<br>

## Use Case Diagram

@startuml<br>
actor User<br>

usecase "Sign Up / Log In" as UC1 <br>
usecase "Update Profile" as UC2 <br>
usecase "Upload Photo" as UC3 <br>
usecase "Like Post" as UC4 <br>
usecase "Comment on Post" as UC5 <br>
usecase "Follow/Unfollow User" as UC6 <br>
usecase "View Feed" as UC7 <br>
usecase "Search for Users" as UC8 <br>
usecase "Receive Notifications" as UC9 <br>
<br>
User --> UC1 <br>
User --> UC2 <br>
User --> UC3 <br>
User --> UC4 <br>
User --> UC5 <br>
User --> UC6 <br>
User --> UC7 <br>
User --> UC8 <br>
User --> UC9 <br>
@enduml <br>
<br>


###Class Diagram

@startuml
class User {
  +String username
  +String email
  +String password
  +Profile profile
  +signUp()
  +logIn()
  +logOut()
}

class Profile {
  +String bio
  +String profilePicture
  +updateProfile()
}

class Photo {
  +String photoId
  +String caption
  +uploadPhoto()
}

class Post {
  +Photo photo
  +List<Comment> comments
  +List<Like> likes
  +addComment()
  +addLike()
}

class Comment {
  +String text
  +User author
  +commentOnPost()
}

class Like {
  +User user
  +likePost()
}

class Follow {
  +User follower
  +User followed
  +followUser()
  +unfollowUser()
}

User "1" --> "1" Profile
User "1" --> "0..*" Post
User "1" --> "0..*" Comment
User "1" --> "0..*" Like
User "1" --> "0..*" Follow
Post "1" --> "1" Photo
Post "0..*" --> "0..*" Comment
Post "0..*" --> "0..*" Like
@enduml


