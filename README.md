# Lab-1_202001275

## Name: Ayush Jain
## Student ID: 202001275

## Library Interface System
## Q1: Functional and Non-Functional Requirements of LIS:

### Functional Requirements:
#### 1. Registration of new user into the LIS:
A user should have the ability to register themselves as a member of the LIS. log into the LIS using a unique username and password hence verifying that they are a member of the LIS.

#### 2. Login facility of registered users:
A user should have the ability to log into the LIS using a unique username and password hence verifying that they are a member of the LIS.

#### 3. Browsing/searching the required book:
A user should be able to search/browser the book they desire in the LIS book directory and check out the contents of it regardless of their membership status of the LIS.

#### 4. Issuing the desired book:
A registered user should be able to issue (borrow) their desired book with ease.

#### 5. Returning the desired book:
A registered user should be able to return their issued book with ease.

#### 6. Extending the returning date by **reissuing** the desired book:
A registered user should be able to extend their book returning date (reissuing) if there are no current requests of that book.

#### 7. Request a book:
A registered user should be able to request their desired book if it is not currently present in the catalog to issue.

#### 8. Checking/Verifying user status:
The system should be able to check/verify whether the user is a registered member before allowing them to request a book or issue one.

#### 9. Admin Privileges:
The interface should provide the administrator privileges to only the lab staff and librarian for day to day book transactions like issuing, returning and reissuing the book.

#### 10. Complete Control:
The interface should allow the librarian with complete control over the system including the database of books and users and the ability to add new books requested and otherwise for all users.

#### 11. Accessible only within institute LAN:
The system should only be accessible within the institute LAN.


### Non-Functional Requirements:
#### 1. Security: 
The system should have some security/validation checks to protect against attacks and an encryption protocol to ensure that no confidential information is stored in plaintext and hence protect againt leaks.

#### 2. Performance:
The system should be optimized so that users don't face any problems during issuing and the administrators don't face any problems managing the records.

#### 3. Speed:
The system should use AI and ML technologies so that the speed at which the day to day transactions are performed is not limited at any time.

#### 4. Ease of Use:
The system should be easy to use for each kind of users and also have some special mechanisms for users with disabilities.

#### 5. Reliability:
The system should be reliable, i.e. it should let the user perform an action based on the current issuing status of the book. It should work accurately by synchronizing the database and the application at regular intervals.

#### 6. Privileges:
The system should have ways to assign different roles and privileges to different users since every user is different and so is their role.


## Q2: Scope, Features and Non-Functional Aspects of the hearing aid application (AI):
### Scope:
The application can prove very helpful to people with hearing disabilities, disabling hearing loss or partial.
### Features:
1. The application should be able to sense various sounds that are important for living a sound life like traffic, car honking, crying, shouting etc and record them into the app's database.
2. The application should alert the user about the recorded sounds and the events pertaining to them.
3. The application should allow the users to stop the alert at will.
4. The application should allow the synchronization of alerts to the user's guardians
5. The application should allow various kinds of alerts mapped to the various sound events for example flash for traffic, vibration for someone crying/loud noise etc.
### Non-Functional Aspects:

#### Ease of use: 
The application should be easy to use and have a very clean, clear and simple UI so that even people with severe disabilities find it easy to work with.

#### Efficient: 
The application should not drain system resources and be very efficient with the battery usage.

#### Accuracy:
 To more effectively prevent false positives, the application should have an accurate sensing and recording mechanism.
 
#### Performance: 
The system should aim to minimize latency between the recording of the sound event and the event of alerting the user with an appropriate alert.

#### Optimization: 
The application should have minimum system requrements and should be optimized enough to run on every phone even with very low specifications.
