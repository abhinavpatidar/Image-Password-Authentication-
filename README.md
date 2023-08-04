# Image Password Authentincation

## Introduction
A Image Password Authentication system is an authentication system that uses some combination of graphical images replacing the regular passwords. Graphical passwords may offer better security than text-based passwords because most of the people use regular, popular passwords everywhere and are prone to social engineering attacks. So graphical passwords can put stop to many attacks of this kind.

<br>

## Resistance to Popular Attacks
### Bruteforce
After reaching max tries, the user will be notified via message through email. And the further authentication through the generic URL/website is disabled for that user account, instead, they have to use the link that will be sent by the company in the notification email. This also lets the legitimate user know about the adversary. 

### Shoulder Surfing
Shoulder surfing is a type of social engineering technique used to obtain information such as personal identification numbers (PINs), passwords and other confidential data by looking over the victim's shoulder. The system we adopt is similar to the Phone pattern system. The pattern is invisible on the screen when the users draw it. This makes it incredibly tough for the adversary to see the images on the grid that the user clicks.

### Spyware
Graphical password systems resist spyware more easily than regular passwords. Key-loggers secretly capture keystrokes and transfer, but if the spyware wants to track the mouse movements, it can be tracked, but the adversary wouldn’t know which part of the mouse event is actually the graphical password. The timeline vs mouse-event graph is too difficult to get the pattern

### Hidden Camera
There will be a camera in front of the user which identifies a face while authentication i.e., the number of pixels the face occupies should be 80-90% of the total pixels in the current frame and if this condition is not satisfied then the screen does not show the graphical password. It alerts the user to cover the screen with a proper posture. But this will be a costly operation. 

### Phishing
Since the adversary is made to believe that the password is a set of images, it’s not possible to make a fake page, since the adversary thinks he doesn’t know the images. Moreover, we restrict the user to one attempt and suggest the user to give a fake password every time so that he triggers the server to send and URL in email so that he can log in through the legitimate login page, and the adversary cannot send the URL to users from a legitimate server. However, when the adversary knows the technique this attack might be still possible. 

<br>

## Screenshots
![pass](https://github.com/abhinavpatidar/Image-Password-Authentication-/assets/78012583/30962394-b975-4487-9ccb-64172f5665e5)
![pass1 (2)](https://github.com/abhinavpatidar/Image-Password-Authentication-/assets/78012583/cd88efc6-7f24-4252-b84f-447e97d156a8)
![pass](https://github.com/abhinavpatidar/Image-Password-Authentication-/assets/78012583/ba65ffae-3dfe-4663-8b7e-45a00b9a433c)
![pass1 (9)](https://github.com/abhinavpatidar/Image-Password-Authentication-/assets/78012583/13c075f9-0715-4459-aa46-cb57d1b9b5c2)

![pass1 (3)](https://github.com/abhinavpatidar/Image-Password-Authentication-/assets/78012583/da838049-63a7-4296-8dcd-abf13d7dbb7a)
![pass1 (4)](https://github.com/abhinavpatidar/Image-Password-Authentication-/assets/78012583/9333cb57-4ddd-47cf-910c-6eb43f59d8ed)
![pass1 (8)](https://github.com/abhinavpatidar/Image-Password-Authentication-/assets/78012583/f754e531-9c7f-4901-bb69-8b33da5c11a8)
![pass1 (7)](https://github.com/abhinavpatidar/Image-Password-Authentication-/assets/78012583/26372769-a422-41d8-8736-6b2988cbad0e)

#### Thank you

