# MOBILE APP TESTING

* An experienced tester must have an eye for this type of detail and must be able to catch these issues immediately. 


* things which should be taken care while using the mobile apps
1. Speed of the app
2. Internet Dependence of app
3. App performance offline and online and on slow Internet
4. Battery consumption of the app
5. Internet consumption of app

Feature Classification:
    Feature classification is a complex task various member from the teams should be involved inside this. Every feature of the product should be classified in at least of 3 sets.
    A. regularly used features: Eg. The main usecase/s or the app, around which business drives. Such cases should be tested exhaustively. Such as, buy a product in a e-com website etc.
    B. occasionally used feature: Eg. Change Password/Forget Password/ some details section etc
    C. one time used features : Eg. Login/Signup
    

## Different type of testings
1. Unit Testing: Unit testing is normally done by developer, but sometime QC engineer also do write unit test case. Its more toward testing each functional unit of the code.

2. Functional Testing
    Notes:
        a. Can naive user can complete the task?
        b. Can onetime educated user can complete the task?
        c. Does specific feature works?

3. Component Testing
    Notes:
        a. Does feature is accessible easily?
        b. Does feature is visible on the app?
        c. Does design is cluttered?
        d. Does icon or the text or color communicate about the action/task?
        e. Does developed product matches the designer outline?
        f. Overall color scheme/theme of the apps.
        g. Style, alignment, and color of icons.
        h. Font family and font size.
        i. Progress indicators when pages are loading.
        j. Menus. How they are invoked and typical items they contain.
        k. Spell check and naming conventions.
        l. Overall responsiveness of applications on the device.
        m. Proper keyboard: Input text should have text keyboard and input number should have Number keyboard
        n. Does the keyboard automatically appear if the user’s main action is to enter some text?
        o. Does the first layer of the keyboard include shortcut “@” and “.com” keys if the highlighted field is for entering email addresses?
        p. Can the keyboard be dismissed and redisplayed easily?
        q. Do keyboard characters entered in password fields only show up as ****? 

4. Performance Testing
    Notes:
        a. Network usage
        b. Battery usage
        c. speed and responsiveness of every feature/usecase
        d. Making sure, if something should work offline network should not be used inside that action
        e. App Load time should be less the 2 mins

5. Regression testing
    Note:
        Making sure, If some small change came, other feature/usecase should not break.

6. User Acceptance Testing
    After everything is fit and fine from the developers end. S/He should involve real app user and take his usage feedback on class A feature of the APP.

7. Mobile Screen testing: Mobile phone have lot of various in screen size, 3.5" to 7"+ . Checking the fonts, icons and other component placement is correct over different screen size of the mobile is important. Atleast of lowest medium and highest becomes very important. If you are aware of the kind of user phone, story changes little bit, but normally this is not the case.

8. Mobile Phone class testing: Pricing of smart phone varies acrols a big range from 4k INR - 60K INR. Different phones have different quility and quinity of sensor and other components. So, test over a specific kind class become important. For india it can be divide into 3 major classes such as . 4k-10k class A, 11k-20k class B and 21K+ in class C. Atleast of 1 from each case should be used for phyiscal mobile phone testing.

9. OS version testing

10. Network Testing
    a. Only Wi-Fi connection
    b. Only 2G/3G/4G connection
    c. Only LTE connection
    d. No connection
    e. With no SIM card in the device
    f. Intermittent connection scenarios that a user might encounter in the real world:
        • Walk out of Wi-Fi range so the connection automatically switches to 3G/LTE
        • Ride in an elevator or on a train where the network connection may go up and down
    g. Bluetooth connection or disruption scenarios depending on the range of Bluetooth (~100m)
    

11. Intreption Testing
    Be sure to test the following scenarios to see how your application reacts before, during and after a phone call:
    a. Your application is interrupted by an incoming call, originator hangs up the call
    b. Your application is interrupted by an incoming call, terminator hangs up the call
    c. Your application is interrupted by placing an outgoing call, originator hangs up the call
    d.Your application is interrupted by placing an outgoing call, terminator hangs up the call 
    
    Also take into consideration such interruptions as:
    a. Text messages
    b. Voicemail notifications
    c. Calendar events
    d. Social media notifications (Facebook, Twitter, etc.)
    f. Alarm clocks
    g. Low battery notifications
    h. Forced updates
    Any of the above could have an impact on the functionality or overall responsiveness of your application. 

12. Security Testing

        a. App data should not be accessible by other app and the users.
        b. Most mobile devices assume one user; however, some devices may support multiple user accounts therefore the following should be considered: user switching, multiple profiles, and permissions based on user level.
        c. If your application deals with the device’s Contacts or Email functions, testing should include the case of having multiple email addresses configured per device.
        d. It is up to the user whether or not they configure a password/ unlock pattern for their device at all.
        e. If the device does not support hardware encryption then all necessary encryption needs to occur at the application level.
        f. Outside communication of any sensitive data should be done over SSL/TLS because it can’t be assumed that the user will configure their Wi-Fi to be secure.
        g. Permission which are taking by the app are used or not.

13. Message Display Testing: Messages displayed at verious stage should the communicable and understandable. Default message should not inside a app. Such as, "No Data", "Data not found"  "empty" or "any wrong message". Message should be written in a way uses emotions, privacy and awareness is taken care.

# Mobile APP Testing Matrixs

1. Test cases pass on different screens
2. Test case pass on different Class of mobile
3. Power and network usage over different mobile class for CLASS A test cases 




## Tester Assets:
https://drive.google.com/drive/folders/1qkjOAxeHc7j_g41mobcFzpS_qiq8hm-e?usp=sharing
1. Page vise Usecases :
2. Flow vise Usecases :
3. Test Case based on every usecase : 

* Page Feature vise testing

A page consists of different features or function or actions etc. Each feature on the page should working as per as the use case

* Flow vise testing
Every app is made to get user actions in different senarios, such senarios should be document properly and tested accordingly.