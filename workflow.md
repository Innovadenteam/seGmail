## Workflow
This will contain the details of the application development workflow.
This will help have uniformity in our work and everyone can know exactly what is going on!

seGmail is a webapp.

### A webapp because:

1. We can reach a greater audience across platforms

2. We have people who are good at it

3. We want to make the web safer so there never was a better place to start.

### Tech Stack:

- Front End:  Angular4

- Back End:   Django

- Encryption: Yet to be decided

## Architecture: 

![img_20171028_181408](https://user-images.githubusercontent.com/33156557/32155861-19d59b50-bd60-11e7-8631-a80f5a64004a.jpg)





During the signup to seGmail we collect the email address and their public key. 

Sender writes a mail to receiver.

Now the sender needs to validate the receivers email id to see if they have registered to our website. 

After clicking encrypt option the website would verify the reciever's email account and fetch the public key form seGmail database. The message would be encrypted on the client side and would be sent to the receiver.

The receiver would then enter his private key to decrypt it on client side.


### Join the discussions on Telegram: 
[seGmail](t.me/seGmail)

