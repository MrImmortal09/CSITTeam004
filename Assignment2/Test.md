<div align="center">

# Testing Documentation

This test documentation outlines the testing approach and strategy for ***Instagram Competitor***, a social media platform designed to compete with Instagram. 

The purpose of this documentation is to ensure that ***Instagram Competitor*** meets the required functionality, performance, and security standards, providing a seamless and 
engaging user experience. This documentation will guide the testing process, covering various aspects of the application, including user registration, login, 
posting, commenting, liking, and sharing, as well as security and performance features.

</div>

<br/>

---

<br/>

# Content

1. [Test Plan: User account management](https://github.com/IIITLucknowSWEngg/CSITTeam004/new/main/Assignment2#test-plan-user-account-management)<br/>
   1.1 [User Registration](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#1-user-registration)<br/>
   1.2 [Login](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#2-user-login)<br/>
   1.3 [Password Recovery](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#3-password-recovery)<br/>
   1.4 [Account Deletion](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#4-account-deletion)<br/>
   1.5 [Profile Management](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#4-account-deletion)<br/>
2. [Test Plan: Posting and Sharing](https://github.com/IIITLucknowSWEngg/CSITTeam004/new/main/Assignment2#test-plan-posting-and-sharing)<br/>
   2.1 [Image/Video Posting](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#1-imagevideo-posting)<br/>
   2.2 [Caption Editing](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#2-caption-editing)<br/>
   2.3 [Tagging Users](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#3-tagging-users)<br/>
   2.4 [Location Tagging](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#4-location-tagging)<br/>
   2.5 [Sharing Posts](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#5-sharing-posting)<br/>
3. [Test Plan: Feed and Discovery](https://github.com/IIITLucknowSWEngg/CSITTeam004/new/main/Assignment2#test-plan-feed-and-discovery)<br/>
   3.1 [Feed Loading](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#1-feed-loading)<br/>
   3.2 [Post Rendering](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#2-post-rendering)<br/>
   3.3 [Hashtag Search](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#3-hashtag-search)<br/>
   3.4 [User Search](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#4-user-search)<br/>
   3.5 [Discovery Page](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#5-discovery-page)<br/>
4. [Test Plan: Interactions and Notification](https://github.com/IIITLucknowSWEngg/CSITTeam004/new/main/Assignment2#test-plan-feed-and-discovery)<br/>
   4.1 [Liking Posts](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#1-liking-posts)<br/>
   4.2 [Commenting](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#2-commenting-on-posts)<br/>
   4.3 [Replying to Comments](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#3-replying-on-comments)<br/>
   4.4 [Notification](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#4-notifications)<br/>
   4.5 [Follow](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#5-follow-an-user)<br/>
   4.6 [Unfollow](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#6-unfollow)<br/>
6. [Additional Features](https://github.com/IIITLucknowSWEngg/CSITTeam004/new/main/Assignment2#test-plan-feed-and-discovery)<br/>
   6.1 [Stories](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#1-stories)<br/>
   6.2 [Reels](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#2-reels)<br/>
   6.3 [Direct Messaging](https://github.com/IIITLucknowSWEngg/CSITTeam004/edit/main/Assignment2/Test.md#3-direct-messaging)<br/>

<br/>

---

<br/>


## Test Plan: User account management

### **1. User registration**

**Test Plan Identifier**

TP-REG-001

**Test Plan Introduction**

This test plan outlines of the testing approach and strategy for the registration feature of the Instagram clone project. The purpose of this test plan is to ensure 
that the registration feature meets the required functionality, performance, and security standards.

**Test Items**

- Registration form
- Registration API
- User database

**Test Objectives**

- To verify that a user can successfully register with complete and valid information.
- To verify that the registration form validates user input correctly.
- To verify that the registration API integrates correctly with the user database.

**Test Scope**

This test plan covers the testing of the registration feature, including the registration form, registration API, and user database. The following scenarios are in scope:

- Valid registration with complete information
- Invalid registration with missing or invalid information
- Registration with existing email address or username

The following scenarios are out of scope:

- Testing of other features, such as login or password recovery
- Testing of the application's performance or security

**Test Approach**

The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the registration form and API, while automated 
testing will be used to test the integration with the user database.

*signup.test.js*
```js
describe('Registration API', () => {
  it('should register a new user with valid information', async () => {
    const response = await axios.post('http://localhost:8000/register', {
      username: 'testuser',
      email: 'testuser@example.com',
      password: 'P@ssw0rd',
      confirm_password: 'P@ssw0rd'
    });

    expect(response.status).toBe(201);
    expect(response.data.username).toBe('testuser');
    expect(response.data.email).toBe('testuser@example.com');
  });

  it('should return an error for invalid email', async () => {
    const response = await axios.post('http://localhost:8000/register', {
      username: 'testuser',
      email: 'invalid_email',
      password: 'P@ssw0rd',
      confirm_password: 'P@ssw0rd'
    });

    expect(response.status).toBe(400);
    expect(response.data.error).toBe('Invalid email address');
  });

  it('should return an error for password mismatch', async () => {
    const response = await axios.post('http://localhost:8000/register', {
      username: 'testuser',
      email: 'testuser@example.com',
      password: 'P@ssw0rd',
      confirm_password: 'InvalidPassword'
    });

    expect(response.status).toBe(400);
    expect(response.data.error).toBe('Passwords do not match');
  });
});
```

**Test Environment**

The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**

- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **2. User login**

**Test Plan Identifier**
TP-LOG-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the user login feature of the Instagram clone project. The purpose of this test plan is to ensure that the user login feature meets the required functionality, performance, and security standards.

**Test Items**
- Login form
- Login API
- User database

**Test Objectives**
- To verify that a user can successfully log in with valid credentials.
- To verify that the login form validates user input correctly.
- To verify that the login API integrates correctly with the user database.

**Test Scope**
This test plan covers the testing of the user login feature, including the login form, login API, and user database. The following scenarios are in scope:
- Valid login with correct username and password
- Invalid login with incorrect username or password
- Login with existing account
The following scenarios are out of scope:
- Testing of other features, such as registration or password recovery
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the login form and API, while automated testing will be used to test the integration with the user database.

*login.test.js*
```js
describe('Login API', () => {
  it('should login a user with valid credentials', async () => {
    const response = await axios.post('http://localhost:8000/login', {
      username: 'testuser',
      password: 'P@ssw0rd'
    });
    expect(response.status).toBe(200);
    expect(response.data.username).toBe('testuser');
  });

  it('should return an error for invalid username or password', async () => {
    const response = await axios.post('http://localhost:8000/login', {
      username: 'invalid_username',
      password: 'P@ssw0rd'
    });
    expect(response.status).toBe(401);
    expect(response.data.error).toBe('Invalid username or password');
  });

  it('should return an error for existing account', async () => {
    const response = await axios.post('http://localhost:8000/login', {
      username: 'testuser',
      password: 'P@ssw0rd'
    });
    expect(response.status).toBe(200);
    expect(response.data.username).toBe('testuser');
  });
});
```

**Test Environment**
The testing environment will consist of:
- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **3. Password recovery**

**Test Plan Identifier**
TP-PWD-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the password recovery feature of the Instagram clone project. The purpose of this test plan is to ensure that the password recovery feature meets the required functionality, performance, and security standards.

**Test Items**
- Password recovery form
- Password recovery API
- User database

**Test Objectives**
- To verify that a user can successfully recover their password using a valid email address.
- To verify that the password recovery form validates user input correctly.
- To verify that the password recovery API integrates correctly with the user database.

**Test Scope**
This test plan covers the testing of the password recovery feature, including the password recovery form, password recovery API, and user database. The following scenarios are in scope:

- Valid password recovery with correct email address
- Invalid password recovery with incorrect email address
- Password recovery with existing account
The following scenarios are out of scope:

- Testing of other features, such as login or registration
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the password recovery form and API, while automated testing will be used to test the integration with the user database.

*password_recovery.test.js*
```js
describe('Password Recovery API', () => {
  it('should recover password with valid email address', async () => {
    const response = await axios.post('http://localhost:8000/password-recovery', {
      email: 'testuser@example.com'
    });
    expect(response.status).toBe(200);
    expect(response.data.message).toBe('Password recovery email sent successfully');
  });

  it('should return an error for invalid email address', async () => {
    const response = await axios.post('http://localhost:8000/password-recovery', {
      email: 'invalid_email'
    });
    expect(response.status).toBe(400);
    expect(response.data.error).toBe('Invalid email address');
  });

  it('should return an error for existing account', async () => {
    const response = await axios.post('http://localhost:8000/password-recovery', {
      email: 'testuser@example.com'
    });
    expect(response.status).toBe(200);
    expect(response.data.message).toBe('Password recovery email sent successfully');
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **4. Account deletion**

**Test Plan Identifier**
TP-DEL-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the account deletion feature of the Instagram clone project. The purpose of this test plan is to ensure that the account deletion feature meets the required functionality, performance, and security standards.

**Test Items**
- Account deletion form
- Account deletion API
- User database

**Test Objectives**
- To verify that a user can successfully delete their account.
- To verify that the account deletion form validates user input correctly.
- To verify that the account deletion API integrates correctly with the user database.

**Test Scope**
This test plan covers the testing of the account deletion feature, including the account deletion form, account deletion API, and user database. The following scenarios are in scope:

- Valid account deletion with correct credentials
- Invalid account deletion with incorrect credentials
- Account deletion with existing account
The following scenarios are out of scope:

- Testing of other features, such as login or registration
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the account deletion form and API, while automated testing will be used to test the integration with the user database.

*account_deletion.test.js*
```js
describe('Account Deletion API', () => {
  it('should delete account with valid credentials', async () => {
    const response = await axios.delete('http://localhost:8000/account', {
      headers: {
        'Authorization': 'Bearer valid_token'
      }
    });
    expect(response.status).toBe(204);
    expect(response.data).toBeNull();
  });

  it('should return an error for invalid credentials', async () => {
    const response = await axios.delete('http://localhost:8000/account', {
      headers: {
        'Authorization': 'Bearer invalid_token'
      }
    });
    expect(response.status).toBe(401);
    expect(response.data.error).toBe('Invalid credentials');
  });

  it('should return an error for existing account', async () => {
    const response = await axios.delete('http://localhost:8000/account', {
      headers: {
        'Authorization': 'Bearer valid_token'
      }
    });
    expect(response.status).toBe(204);
    expect(response.data).toBeNull();
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **5. Profile Management**

**Test Plan Identifier**
TP-PRO-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the profile management feature of the Instagram clone project. The purpose of this test plan is to ensure that the profile management feature meets the required functionality, performance, and security standards.

**Test Items**
- Profile page
- Profile editing form
- Profile API
- User database

**Test Objectives**
- To verify that a user can successfully view and edit their profile information.
- To verify that the profile editing form validates user input correctly.
- To verify that the profile API integrates correctly with the user database.

**Test Scope**
This test plan covers the testing of the profile management feature, including the profile page, profile editing form, profile API, and user database. The following scenarios are in scope:

- Viewing profile information
- Editing profile information with valid input
- Editing profile information with invalid input
- Saving profile changes
The following scenarios are out of scope:

- Testing of other features, such as login or registration
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the profile page and profile editing form, while automated testing will be used to test the profile API and integration with the user database.

*profile_management.test.js*
```js
describe('Profile Management API', () => {
  it('should view profile information', async () => {
    const response = await axios.get('http://localhost:8000/profile');
    expect(response.status).toBe(200);
    expect(response.data.username).toBe('testuser');
  });

  it('should edit profile information with valid input', async () => {
    const response = await axios.patch('http://localhost:8000/profile', {
      username: 'new_username',
      email: 'new_email@example.com'
    });
    expect(response.status).toBe(200);
    expect(response.data.username).toBe('new_username');
  });

  it('should return an error for invalid input', async () => {
    const response = await axios.patch('http://localhost:8000/profile', {
      username: 'invalid_username',
      email: 'invalid_email'
    });
    expect(response.status).toBe(400);
    expect(response.data.error).toBe('Invalid input');
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>
<br/>

## Test Plan: Posting and Sharing

### **1. Image/video posting**

**Test Plan Identifier**
TP-IMG-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the image/video posting feature of the Instagram clone project. The purpose of this test plan is to ensure that the image/video posting feature meets the required functionality, performance, and security standards.

**Test Items**
- Image/video upload form
- Image/video processing API
- Media database

**Test Objectives**
- To verify that a user can successfully upload and post images and videos.
- To verify that the image/video upload form validates user input correctly.
- To verify that the image/video processing API integrates correctly with the media database.

**Test Scope**
This test plan covers the testing of the image/video posting feature, including the image/video upload form, image/video processing API, and media database. The following scenarios are in scope:

- Uploading images with valid format and size
- Uploading videos with valid format and size
- Posting images and videos with valid captions
- Posting images and videos with invalid captions
The following scenarios are out of scope:

- Testing of other features, such as login or registration
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the image/video upload form and posting functionality, while automated testing will be used to test the image/video processing API and integration with the media database.

*image_video_posting.test.js*
```js
describe('Image/Video Posting API', () => {
  it('should upload and post an image with valid format and size', async () => {
    const response = await axios.post('http://localhost:8000/posts', {
      image: 'image.jpg',
      caption: 'Test caption'
    });
    expect(response.status).toBe(201);
    expect(response.data.post_id).toBeGreaterThan(0);
  });

  it('should upload and post a video with valid format and size', async () => {
    const response = await axios.post('http://localhost:8000/posts', {
      video: 'video.mp4',
      caption: 'Test caption'
    });
    expect(response.status).toBe(201);
    expect(response.data.post_id).toBeGreaterThan(0);
  });

  it('should return an error for invalid image/video format', async () => {
    const response = await axios.post('http://localhost:8000/posts', {
      image: 'invalid_image.txt',
      caption: 'Test caption'
    });
    expect(response.status).toBe(400);
    expect(response.data.error).toBe('Invalid image/video format');
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **2. Caption editing**

**Test Plan Identifier**
TP-CAP-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the caption editing feature of the Instagram clone project. The purpose of this test plan is to ensure that the caption editing feature meets the required functionality, performance, and security standards.

**Test Items**
- Caption editing form
- Caption editing API
- Post database

**Test Objectives**
- To verify that a user can successfully edit the caption of a post.
- To verify that the caption editing form validates user input correctly.
- To verify that the caption editing API integrates correctly with the post database.

**Test Scope**
This test plan covers the testing of the caption editing feature, including the caption editing form, caption editing API, and post database. The following scenarios are in scope:

- Editing caption with valid text
- Editing caption with invalid text (e.g. too long, contains profanity)
- Saving edited caption
- Canceling edited caption

The following scenarios are out of scope:

- Testing of other features, such as posting or commenting
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the caption editing form and functionality, while automated testing will be used to test the caption editing API and integration with the post database.

*caption_editing.test.js*
```js
describe('Caption Editing API', () => {
  it('should edit caption with valid text', async () => {
    const response = await axios.patch('http://localhost:8000/posts/1', {
      caption: 'New caption'
    });
    expect(response.status).toBe(200);
    expect(response.data.caption).toBe('New caption');
  });

  it('should return an error for invalid caption text', async () => {
    const response = await axios.patch('http://localhost:8000/posts/1', {
      caption: 'Invalid caption text'
    });
    expect(response.status).toBe(400);
    expect(response.data.error).toBe('Invalid caption text');
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **3. Tagging users**

**Test Plan Identifier**
TP-TAG-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the tagging users feature of the Instagram clone project. The purpose of this test plan is to ensure that the tagging users feature meets the required functionality, performance, and security standards.

**Test Items**
- Tagging form
- Tagging API
- User database

**Test Objectives**
- To verify that a user can successfully tag other users in a post.
- To verify that the tagging form validates user input correctly.
- To verify that the tagging API integrates correctly with the user database.

**Test Scope**
This test plan covers the testing of the tagging users feature, including the tagging form, tagging API, and user database. The following scenarios are in scope:

- Tagging a single user
- Tagging multiple users
- Tagging a user who is not following the poster
- Tagging a user who is already tagged
The following scenarios are out of scope:

- Testing of other features, such as posting or commenting
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the tagging form and functionality, while automated testing will be used to test the tagging API and integration with the user database.

*tagging_users.test.js*
```js
describe('Tagging Users API', () => {
  it('should tag a single user', async () => {
    const response = await axios.post('http://localhost:8000/posts/1/tags', {
      user_id: 2
    });
    expect(response.status).toBe(201);
    expect(response.data.tag_id).toBeGreaterThan(0);
  });

  it('should tag multiple users', async () => {
    const response = await axios.post('http://localhost:8000/posts/1/tags', {
      user_ids: [2, 3]
    });
    expect(response.status).toBe(201);
    expect(response.data.tag_ids).toHaveLength(2);
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **4. Location tagging**

**Test Plan Identifier**
TP-LOC-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the location tagging feature of the Instagram clone project. The purpose of this test plan is to ensure that the location tagging feature meets the required functionality, performance, and security standards.

**Test Items**
- Location tagging form
- Location tagging API
- Location database

**Test Objectives**
- To verify that a user can successfully tag a location in a post.
- To verify that the location tagging form validates user input correctly.
- To verify that the location tagging API integrates correctly with the location database.

**Test Scope**
This test plan covers the testing of the location tagging feature, including the location tagging form, location tagging API, and location database. The following scenarios are in scope:

- Tagging a location by searching for a location name
- Tagging a location by selecting a location from a list of suggested locations
- Tagging a location with valid coordinates (latitude and longitude)
- Tagging a location with invalid coordinates (latitude and longitude)

The following scenarios are out of scope:

- Testing of other features, such as posting or commenting
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the location tagging form and functionality, while automated testing will be used to test the location tagging API and integration with the location database.

*location_tagging.test.js*
```js
describe('Location Tagging API', () => {
  it('should tag a location by searching for a location name', async () => {
    const response = await axios.post('http://localhost:8000/posts/1/locations', {
      location_name: 'New York'
    });
    expect(response.status).toBe(201);
    expect(response.data.location_id).toBeGreaterThan(0);
  });

  it('should tag a location by selecting a location from a list of suggested locations', async () => {
    const response = await axios.post('http://localhost:8000/posts/1/locations', {
      location_id: 1
    });
    expect(response.status).toBe(201);
    expect(response.data.location_id).toBe(1);
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **5. Sharing posting**

**Test Plan Identifier**
TP-SHR-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the sharing posts feature of the Instagram clone project. The purpose of this test plan is to ensure that the sharing posts feature meets the required functionality, performance, and security standards.

**Test Items**
- Sharing post form
- Sharing post API
- Post database

**Test Objectives**
- To verify that a user can successfully share a post.
- To verify that the sharing post form validates user input correctly.
- To verify that the sharing post API integrates correctly with the post database.

**Test Scope**
This test plan covers the testing of the sharing posts feature, including the sharing post form, sharing post API, and post database. The following scenarios are in scope:

- Sharing a post with a valid caption
- Sharing a post without a caption
- Sharing a post with a caption that exceeds the maximum allowed length
- Sharing a post with a caption that contains invalid characters
- Sharing a post to a valid user
- Sharing a post to an invalid user

The following scenarios are out of scope:

- Testing of other features, such as posting or commenting
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the sharing post form and functionality, while automated testing will be used to test the sharing post API and integration with the post database.

*sharing_posts.test.js*
```js
describe('Sharing Posts API', () => {
  it('should share a post with a valid caption', async () => {
    const response = await axios.post('http://localhost:8000/posts/1/share', {
      caption: 'Test caption'
    });
    expect(response.status).toBe(201);
    expect(response.data.post_id).toBeGreaterThan(0);
  });

  it('should share a post without a caption', async () => {
    const response = await axios.post('http://localhost:8000/posts/1/share', {});
    expect(response.status).toBe(201);
    expect(response.data.post_id).toBeGreaterThan(0);
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>
<br/>

## Test Plan: Feed and Discovery

### **1. Feed loading**

**Test Plan Identifier**
TP-FEED-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the feed loading feature of the Instagram clone project. The purpose of this test plan is to ensure that the feed loading feature meets the required functionality, performance, and security standards.

**Test Items**
- Feed loading mechanism
- Feed API
- Post database

**Test Objectives**
- To verify that the feed loads correctly and displays the most recent posts.
- To verify that the feed loading mechanism handles pagination correctly.
- To verify that the feed API integrates correctly with the post database.

**Test Scope**
This test plan covers the testing of the feed loading feature, including the feed loading mechanism, feed API, and post database. The following scenarios are in scope:

- Loading the feed with a small number of posts
- Loading the feed with a large number of posts
- Loading the feed with pagination
- Loading the feed with filtering (e.g. by hashtag or location)
- Loading the feed with a slow internet connection

The following scenarios are out of scope:

- Testing of other features, such as posting or commenting
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the feed loading mechanism and functionality, while automated testing will be used to test the feed API and integration with the post database.

*feed_loading.test.js*
```js
describe('Feed Loading API', () => {
  it('should load the feed with a small number of posts', async () => {
    const response = await axios.get('http://localhost:8000/feed');
    expect(response.status).toBe(200);
    expect(response.data.posts).toHaveLength(10);
  });

  it('should load the feed with pagination', async () => {
    const response = await axios.get('http://localhost:8000/feed?page=2');
    expect(response.status).toBe(200);
    expect(response.data.posts).toHaveLength(10);
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **2. Post rendering**

**Test Plan Identifier**
TP-POST-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the post rendering feature of the Instagram clone project. The purpose of this test plan is to ensure that the post rendering feature meets the required functionality, performance, and security standards.

**Test Items**
- Post rendering mechanism
- Post API
- Post database

**Test Objectives**
- To verify that posts are rendered correctly and display the correct information.
- To verify that the post rendering mechanism handles different types of posts (e.g. images, videos, text-only posts).
- To verify that the post API integrates correctly with the post database.

**Test Scope**
This test plan covers the testing of the post rendering feature, including the post rendering mechanism, post API, and post database. The following scenarios are in scope:

- Rendering a post with an image
- Rendering a post with a video
- Rendering a post with text only
- Rendering a post with multiple images
- Rendering a post with multiple videos
- Rendering a post with a combination of images and videos

The following scenarios are out of scope:

- Testing of other features, such as commenting or liking
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the post rendering mechanism and functionality, while automated testing will be used to test the post API and integration with the post database.

*post_rendering.test.js*
```js
describe('Post Rendering API', () => {
  it('should render a post with an image', async () => {
    const response = await axios.get('http://localhost:8000/posts/1');
    expect(response.status).toBe(200);
    expect(response.data.post.type).toBe('image');
  });

  it('should render a post with a video', async () => {
    const response = await axios.get('http://localhost:8000/posts/2');
    expect(response.status).toBe(200);
    expect(response.data.post.type).toBe('video');
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **3. hashtag search**

**Test Plan Identifier**
TP-HASH-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the hashtag searching feature of the Instagram clone project. The purpose of this test plan is to ensure that the hashtag searching feature meets the required functionality, performance, and security standards.

**Test Items**
- Hashtag search form
- Hashtag search API
- Post database

**Test Objectives**
- To verify that the hashtag search feature returns relevant results.
- To verify that the hashtag search form validates user input correctly.
- To verify that the hashtag search API integrates correctly with the post database.

**Test Scope**
This test plan covers the testing of the hashtag searching feature, including the hashtag search form, hashtag search API, and post database. The following scenarios are in scope:

- Searching for a hashtag with a single word
- Searching for a hashtag with multiple words
- Searching for a hashtag with special characters
- Searching for a hashtag that does not exist
- Searching for a hashtag with a large number of results

The following scenarios are out of scope:

- Testing of other features, such as posting or commenting
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the hashtag search form and functionality, while automated testing will be used to test the hashtag search API and integration with the post database.

*hashtag_searching.test.js*
```js
describe('Hashtag Searching API', () => {
  it('should return relevant results for a single-word hashtag', async () => {
    const response = await axios.get('http://localhost:8000/hashtag/search', {
      params: {
        hashtag: '#test'
      }
    });
    expect(response.status).toBe(200);
    expect(response.data.posts).toHaveLength(10);
  });

  it('should return relevant results for a multi-word hashtag', async () => {
    const response = await axios.get('http://localhost:8000/hashtag/search', {
      params: {
        hashtag: '#test hashtag'
      }
    });
    expect(response.status).toBe(200);
    expect(response.data.posts).toHaveLength(10);
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **4. User search**

**Test Plan Identifier**
TP-USR-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the user search feature of the Instagram clone project. The purpose of this test plan is to ensure that the user search feature meets the required functionality, performance, and security standards.

**Test Items**
- User search form
- User search API
- User database

**Test Objectives**
- To verify that the user search feature returns relevant results.
- To verify that the user search form validates user input correctly.
- To verify that the user search API integrates correctly with the user database.

**Test Scope**
This test plan covers the testing of the user search feature, including the user search form, user search API, and user database. The following scenarios are in scope:

- Searching for a user by username
- Searching for a user by full name
- Searching for a user by email address
- Searching for a user who does not exist
- Searching for a user with a large number of results

The following scenarios are out of scope:

- Testing of other features, such as posting or commenting
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the user search form and functionality, while automated testing will be used to test the user search API and integration with the user database.

*user_search.test.js*
```js
describe('User Search API', () => {
  it('should return relevant results for a username search', async () => {
    const response = await axios.get('http://localhost:8000/users/search', {
      params: {
        username: 'testuser'
      }
    });
    expect(response.status).toBe(200);
    expect(response.data.users).toHaveLength(1);
  });

  it('should return relevant results for a full name search', async () => {
    const response = await axios.get('http://localhost:8000/users/search', {
      params: {
        full_name: 'Test User'
      }
    });
    expect(response.status).toBe(200);
    expect(response.data.users).toHaveLength(1);
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **5. Discovery page**

**Test Plan Identifier**
TP-DIS-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the discovery page feature of the Instagram clone project. The purpose of this test plan is to ensure that the discovery page feature meets the required functionality, performance, and security standards.

**Test Items**
- Discovery page layout
- Post rendering on discovery page
- Hashtag rendering on discovery page
- Location rendering on discovery page
- Infinite scrolling on discovery page

**Test Objectives**
- To verify that the discovery page layout is correct and consistent.
- To verify that posts are rendered correctly on the discovery page.
- To verify that hashtags are rendered correctly on the discovery page.
- To verify that locations are rendered correctly on the discovery page.
- To verify that infinite scrolling works correctly on the discovery page.

**Test Scope**
This test plan covers the testing of the discovery page feature, including the discovery page layout, post rendering, hashtag rendering, location rendering, and infinite scrolling. The following scenarios are in scope:

- Viewing the discovery page as a logged-in user
- Viewing the discovery page as a logged-out user
- Viewing a post on the discovery page
- Viewing a hashtag on the discovery page
- Viewing a location on the discovery page
- Scrolling through the discovery page using infinite scrolling

The following scenarios are out of scope:

- Testing of other features, such as posting or commenting
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the discovery page layout and functionality, while automated testing will be used to test the post rendering, hashtag rendering, location rendering, and infinite scrolling.

*discovery_page.test.js*
```js
describe('Discovery Page', () => {
  it('should render the discovery page layout correctly', async () => {
    const response = await axios.get('http://localhost:8000/discovery');
    expect(response.status).toBe(200);
    expect(response.data.layout).toBe('correct');
  });

  it('should render posts correctly on the discovery page', async () => {
    const response = await axios.get('http://localhost:8000/discovery/posts');
    expect(response.status).toBe(200);
    expect(response.data.posts).toHaveLength(10);
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>
<br/>

## Test Plan: Interactions and Notification

### **1. Liking posts**

**Test Plan Identifier**
TP-LIKE-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the liking post feature of the Instagram clone project. The purpose of this test plan is to ensure that the liking post feature meets the required functionality, performance, and security standards.

**Test Items**
- Liking post button
- Liking post API
- Post database

**Test Objectives**
- To verify that a user can successfully like a post.
- To verify that the liking post button validates user input correctly.
- To verify that the liking post API integrates correctly with the post database.

**Test Scope**
This test plan covers the testing of the liking post feature, including the liking post button, liking post API, and post database. The following scenarios are in scope:

- Liking a post as a logged-in user
- Liking a post as a logged-out user
- Liking a post that has already been liked
- Liking a post that does not exist
- Liking multiple posts in a row

The following scenarios are out of scope:

- Testing of other features, such as commenting or sharing
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the liking post button and functionality, while automated testing will be used to test the liking post API and integration with the post database.

*liking_post.test.js*
```js
describe('Liking Post API', () => {
  it('should like a post as a logged-in user', async () => {
    const response = await axios.post('http://localhost:8000/posts/1/like');
    expect(response.status).toBe(200);
    expect(response.data.post_id).toBe(1);
  });

  it('should not like a post as a logged-out user', async () => {
    const response = await axios.post('http://localhost:8000/posts/1/like');
    expect(response.status).toBe(401);
    expect(response.data.error).toBe('Unauthorized');
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **2. Commenting on posts**

**Test Plan Identifier**
TP-COMM-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the commenting feature of the Instagram clone project. The purpose of this test plan is to ensure that the commenting feature meets the required functionality, performance, and security standards.

**Test Items**
- Commenting form
- Commenting API
- Post database
- Comment database

**Test Objectives**
- To verify that a user can successfully comment on a post.
- To verify that the commenting form validates user input correctly.
- To verify that the commenting API integrates correctly with the post database and comment database.

**Test Scope**
This test plan covers the testing of the commenting feature, including the commenting form, commenting API, post database, and comment database. The following scenarios are in scope:

- Commenting on a post as a logged-in user
- Commenting on a post as a logged-out user
- Commenting on a post with a valid comment
- Commenting on a post with an invalid comment (e.g. too long, contains profanity)
- Commenting on a post that does not exist
- Commenting on a post that has been deleted

The following scenarios are out of scope:

- Testing of other features, such as liking or sharing
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the commenting form and functionality, while automated testing will be used to test the commenting API and integration with the post database and comment database.

*commenting.test.js*
```js
describe('Commenting API', () => {
  it('should comment on a post as a logged-in user', async () => {
    const response = await axios.post('http://localhost:8000/posts/1/comments', {
      comment: 'Test comment'
    });
    expect(response.status).toBe(201);
    expect(response.data.comment_id).toBeGreaterThan(0);
  });

  it('should not comment on a post as a logged-out user', async () => {
    const response = await axios.post('http://localhost:8000/posts/1/comments', {
      comment: 'Test comment'
    });
    expect(response.status).toBe(401);
    expect(response.data.error).toBe('Unauthorized');
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **3. Replying on comments**

**Test Plan Identifier**
TP-REPLY-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the replying on comments feature of the Instagram clone project. The purpose of this test plan is to ensure that the replying on comments feature meets the required functionality, performance, and security standards.

**Test Items**
- Reply form
- Reply API
- Comment database
- Post database

**Test Objectives**
- To verify that a user can successfully reply to a comment.
- To verify that the reply form validates user input correctly.
- To verify that the reply API integrates correctly with the comment database and post database.

**Test Scope**
This test plan covers the testing of the replying on comments feature, including the reply form, reply API, comment database, and post database. The following scenarios are in scope:

- Replying to a comment as a logged-in user
- Replying to a comment as a logged-out user
- Replying to a comment with a valid reply
- Replying to a comment with an invalid reply (e.g. too long, contains profanity)
- Replying to a comment that does not exist
- Replying to a comment that has been deleted

The following scenarios are out of scope:

- Testing of other features, such as liking or sharing
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the reply form and functionality, while automated testing will be used to test the reply API and integration with the comment database and post database.

*replying_on_comments.test.js*
```js
describe('Replying on Comments API', () => {
  it('should reply to a comment as a logged-in user', async () => {
    const response = await axios.post('http://localhost:8000/comments/1/replies', {
      reply: 'Test reply'
    });
    expect(response.status).toBe(201);
    expect(response.data.reply_id).toBeGreaterThan(0);
  });

  it('should not reply to a comment as a logged-out user', async () => {
    const response = await axios.post('http://localhost:8000/comments/1/replies', {
      reply: 'Test reply'
    });
    expect(response.status).toBe(401);
    expect(response.data.error).toBe('Unauthorized');
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **4. Notifications**

**Test Plan Identifier**
TP-NOTIF-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the notifications feature of the Instagram clone project. The purpose of this test plan is to ensure that the notifications feature meets the required functionality, performance, and security standards.

**Test Items**
- Notification system
- Notification API
- User database
- Post database
- Comment database

**Test Objectives**
- To verify that notifications are generated correctly for various events (e.g. likes, comments, follows).
- To verify that notifications are displayed correctly to users.
- To verify that users can manage their notification preferences.

**Test Scope**
This test plan covers the testing of the notifications feature, including the notification system, notification API, user database, post database, and comment database. The following scenarios are in scope:

- Receiving notifications for likes on a post
- Receiving notifications for comments on a post
- Receiving notifications for follows
- Receiving notifications for mentions
- Managing notification preferences
- Disabling notifications for a specific post or user

The following scenarios are out of scope:

- Testing of other features, such as posting or sharing
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the notification system and functionality, while automated testing will be used to test the notification API and integration with the user database, post database, and comment database.

*notifications.test.js*
```js
describe('Notifications API', () => {
  it('should generate notifications for likes on a post', async () => {
    const response = await axios.post('http://localhost:8000/posts/1/like');
    expect(response.status).toBe(200);
    expect(response.data.notification).toBe('Like notification sent');
  });

  it('should generate notifications for comments on a post', async () => {
    const response = await axios.post('http://localhost:8000/posts/1/comments', {
      comment: 'Test comment'
    });
    expect(response.status).toBe(201);
    expect(response.data.notification).toBe('Comment notification sent');
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **5. Follow an user**

**Test Plan Identifier**
TP-FOLLOW-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the "Follow" feature of the Instagram clone project. The purpose of this test plan is to ensure that the "Follow" feature meets the required functionality, performance, and security standards.

**Test Items**
- Follow button
- Follow API
- User database
- Follower database

**Test Objectives**
- To verify that a user can successfully follow another user.
- To verify that the follow button updates correctly after a follow action.
- To verify that the follower count updates correctly after a follow action.
- To verify that the user receives a notification when someone follows them.

**Test Scope**
This test plan covers the testing of the "Follow" feature, including the follow button, follow API, user database, and follower database. The following scenarios are in scope:

- Following a user as a logged-in user
- Following a user who does not exist
- Following a user who has blocked the current user
- Following a user who has disabled follow requests

The following scenarios are out of scope:

- Testing of other features, such as posting or commenting
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the follow button and functionality, while automated testing will be used to test the follow API and integration with the user database and follower database.

*follow.test.js*
```js
describe('Follow API', () => {
  it('should follow a user as a logged-in user', async () => {
    const response = await axios.post('http://localhost:8000/users/1/follow');
    expect(response.status).toBe(200);
    expect(response.data.following).toBe(true);
  });

  it('should not follow a user who does not exist', async () => {
    const response = await axios.post('http://localhost:8000/users/999/follow');
    expect(response.status).toBe(404);
    expect(response.data.error).toBe('User not found');
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **6. Unfollow**

**Test Plan Identifier**
TP-UNFOLLOW-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the "Unfollow" feature of the Instagram clone project. The purpose of this test plan is to ensure that the "Unfollow" feature meets the required functionality, performance, and security standards.

**Test Items**
- Unfollow button
- Unfollow API
- User database
- Follower database

**Test Objectives**
- To verify that a user can successfully unfollow another user.
- To verify that the unfollow button updates correctly after an unfollow action.
- To verify that the follower count updates correctly after an unfollow action.

**Test Scope**
This test plan covers the testing of the "Unfollow" feature, including the unfollow button, unfollow API, user database, and follower database. The following scenarios are in scope:

- Unfollowing a user as a logged-in user
- Unfollowing a user who the current user is not following
- Unfollowing a user who has blocked the current user
- Unfollowing a user who has disabled follow requests

The following scenarios are out of scope:

- Testing of other features, such as posting or commenting
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the unfollow button and functionality, while automated testing will be used to test the unfollow API and integration with the user database and follower database.

*unfollow.test.js*
```js
describe('Unfollow API', () => {
  it('should unfollow a user as a logged-in user', async () => {
    const response = await axios.post('http://localhost:8000/users/1/unfollow');
    expect(response.status).toBe(200);
    expect(response.data.following).toBe(false);
  });

  it('should not unfollow a user who the current user is not following', async () => {
    const response = await axios.post('http://localhost:8000/users/2/unfollow');
    expect(response.status).toBe(404);
    expect(response.data.error).toBe('Not following user');
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>
<br/>

## Additional Features

### **1. Stories**

**Test Plan Identifier**
TP-STORIES-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the "Stories" feature of the Instagram clone project. The purpose of this test plan is to ensure that the "Stories" feature meets the required functionality, performance, and security standards.

**Test Items**
- Story posting form
- Story posting API
- Story database
- Story display functionality

**Test Objectives**
- To verify that a user can successfully post a story.
- To verify that the story posting form validates user input correctly.
- To verify that the story posting API integrates correctly with the story database.
- To verify that stories are displayed correctly to users.

**Test Scope**
This test plan covers the testing of the "Stories" feature, including the story posting form, story posting API, story database, and story display functionality. The following scenarios are in scope:

- Posting a story as a logged-in user
- Posting a story with a photo
- Posting a story with a video
- Posting a story with text only
- Viewing a story as a logged-in user
- Viewing a story as a logged-out user

The following scenarios are out of scope:

- Testing of other features, such as posting or commenting
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the story posting form and functionality, while automated testing will be used to test the story posting API and integration with the story database.

*stories.test.js*
```
describe('Stories API', () => {
  it('should post a story as a logged-in user', async () => {
    const response = await axios.post('http://localhost:8000/stories', {
      photo: 'test-photo.jpg'
    });
    expect(response.status).toBe(201);
    expect(response.data.story_id).toBeGreaterThan(0);
  });

  it('should view a story as a logged-in user', async () => {
    const response = await axios.get('http://localhost:8000/stories/1');
    expect(response.status).toBe(200);
    expect(response.data.story).toBeDefined();
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **2. Reels**

**Test Plan Identifier**
TP-REELS-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the "Reels" feature of the Instagram clone project. The purpose of this test plan is to ensure that the "Reels" feature meets the required functionality, performance, and security standards.

**Test Items**
- Reel posting form
- Reel posting API
- Reel database
- Reel display functionality
- Reel editing functionality
- Reel deletion functionality

**Test Objectives**
- To verify that a user can successfully post a reel.
- To verify that the reel posting form validates user input correctly.
- To verify that the reel posting API integrates correctly with the reel database.
- To verify that reels are displayed correctly to users.
- To verify that reels can be edited and deleted successfully.

**Test Scope**
This test plan covers the testing of the "Reels" feature, including the reel posting form, reel posting API, reel database, reel display functionality, reel editing functionality, and reel deletion functionality. The following scenarios are in scope:

- Posting a reel as a logged-in user
- Posting a reel with a video
- Posting a reel with audio
- Posting a reel with text overlay
- Viewing a reel as a logged-in user
- Viewing a reel as a logged-out user
- Editing a reel as a logged-in user
- Deleting a reel as a logged-in user

The following scenarios are out of scope:

- Testing of other features, such as posting or commenting
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the reel posting form and functionality, while automated testing will be used to test the reel posting API and integration with the reel database.

*reels.test.js*
```js
describe('Reels API', () => {
  it('should post a reel as a logged-in user', async () => {
    const response = await axios.post('http://localhost:8000/reels', {
      video: 'test-video.mp4'
    });
    expect(response.status).toBe(201);
    expect(response.data.reel_id).toBeGreaterThan(0);
  });

  it('should view a reel as a logged-in user', async () => {
    const response = await axios.get('http://localhost:8000/reels/1');
    expect(response.status).toBe(200);
    expect(response.data.reel).toBeDefined();
  });
});
````

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>

### **3. Direct messaging**

**Test Plan Identifier**
TP-DM-001

**Test Plan Introduction**
This test plan outlines the testing approach and strategy for the "Direct Messages" feature of the Instagram clone project. The purpose of this test plan is to ensure that the DMs feature meets the required functionality, performance, and security standards.

**Test Items**
- DM sending form
- DM sending API
- DM database
- DM display functionality
- DM threading functionality

**Test Objectives**
- To verify that a user can successfully send a DM to another user.
- To verify that the DM sending form validates user input correctly.
- To verify that the DM sending API integrates correctly with the DM database.
- To verify that DMs are displayed correctly to users.
- To verify that DMs are threaded correctly.

**Test Scope**
This test plan covers the testing of the DMs feature, including the DM sending form, DM sending API, DM database, DM display functionality, and DM threading functionality. The following scenarios are in scope:

- Sending a DM to a single user
- Sending a DM to multiple users
- Sending a DM with text only
- Sending a DM with media (e.g. photo, video)
- Viewing a DM as the sender
- Viewing a DM as the recipient
- Threading DMs with multiple messages

The following scenarios are out of scope:

- Testing of other features, such as posting or commenting
- Testing of the application's performance or security

**Test Approach**
The testing approach will include a combination of manual testing and automated testing. Manual testing will be used to test the DM sending form and functionality, while automated testing will be used to test the DM sending API and integration with the DM database.

*dms.test.js*
```js
describe('DMs API', () => {
  it('should send a DM to a single user', async () => {
    const response = await axios.post('http://localhost:8000/dms', {
      recipient_id: 1,
      text: 'Test DM'
    });
    expect(response.status).toBe(201);
    expect(response.data.dm_id).toBeGreaterThan(0);
  });

  it('should send a DM to multiple users', async () => {
    const response = await axios.post('http://localhost:8000/dms', {
      recipient_ids: [1, 2, 3],
      text: 'Test DM'
    });
    expect(response.status).toBe(201);
    expect(response.data.dm_id).toBeGreaterThan(0);
  });
});
```

**Test Environment**
The testing environment will consist of:

- Operating System: Windows 10
- Browser: Google Chrome
- Database: MySQL
- API: RESTful API

**Test Schedule**
- Test planning: 1 day
- Test execution: 3 days
- Test reporting: 1 day

<br/>
<br/>

<div align="center">
Instagram Competitor Testing, <br/>
IEEE-829-2008, Clause 5
</div>
