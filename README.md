This self-contained HTML and JavaScript app is created so anyone can write, encrypt and decrypt formatted text. Even without Internet access. With software they already have at hand. You could encrypt anything: a note, a message even a love letter if you think it is romantic to send an encrypted letter for a loved one (nope). The point is: all you need is this file. I made this because I wanted to learn encryption in JavaScript, needed a project for it, and I had this idea of self-contained files that open themselves with a password. From there I realized I can make a self-contained file that generates such encrypted documents.

# Why?
Because I had this idea, wanted to learn encryption in JavaScript anyway, so I built this around it. I had no other goal with this. While making it I realized a lot of things about the nature of this idea, and it took this form. And why szamizd.at? Because of the text editor it could be used like that too. I do not tell you to use it for that. But it came out that way.

# How to use it?
All you need is a modern Internet browser (like Chrome, Firefox, Edge etc.). If you are reading this you are most likely good to go. You can write your own content, then produce an encrypted file with a password from it. You share the encrypted file and the password with people. Only those with the password can read it. Best part: it works offline too! You can encrypt and dectrypt text without the need of internet connection.

If you wrote a file you can share it with others. The file will try to decrypt itself, prompting for a password. It would be silly to send the password with the file. Tell them in person. Send it in a letter. You get my point. Also the idea of not using Internet for this means you can pass the files around on a USB stick. Imagination is your friend here.

This file saves nothing on the server, doesn nothing in there. Everything happens on your machine so you can use it offline. You can save this file by pressing CTRL+S on PC or CMD+S on Mac, pull the internet cable so you can be sure it does not communicate to anywhere, you do not have to trust me.

# Is this really safe?
It is as safe as the code I use for it. I consider it safe, but you should decide it for yourself. Encryption is hard, all encryption algorithms are under incredible pressure all the time, so even if this version of the file uses encryption that considered strong, it might break next day. The point is you have to accept the risk coming with this kind of communication.

It is open source, if you understand code you can decide for yourself, even change the encryption in it. I just put this out as a concept. I do not even looking it up if others done this before (I am sure I am not the first to do this).

The nature of this app is not that safe anyway. This sounds bad, but hear me out: You encrypt a text, share the text and the password with someone you trust so they read it. So now two people knows the password. They share it to a third person... etc. You get the point. Eventually people you want to hide the contents from will know the password. It all depends on the trust you put in others. This thing is retro in a way: World War II level communication (but with modern encryption). Still it is not hard to imagine cases when you might want to share the file offline and tell the password in person to someone.

# Use cases
I will not give you real life examples and use cases for this app (other than its name). I do not abet anything you should do with it. But in general terms an exchange could happen like this: Person A gives a USB stick with the encrypted data to Person B. Then Person A tells the password to Person B. Person B couldn't read the data until Person A gives them the password so Person A can decide when to trust Person B with the information, for when they need them to know it fast (so they have the data encrypted but no password until it needed). Even if someone stumbles upon it couldn't read it without the password.

# Vulnerabilities
I mentioned what I think about encryption above. But you have to consider your password too. As the produced file is self-contained, it is pretty easy to hook up a brute force attack on it. Also the encryption algorithm is there, so an attacker knows what algorithm they are trying to break. So even if the encryption is strong in itself it is still as strong as your password. I do not limit how long and strong password you are using, but I provide a strong password generator in this version.

# Ok but WinRar, BitLocker, VeraCrypt etc. can do this too
Yes. And no. Encrypting information and sharing it offline is not new. My goal with this: its easy to use for anyone. Everyone owns a browser already on their machine and phone and those will open the file. Users without higher tech skills could open it with the password without the need of downloading and installing anything else. It is small, fast and easy this way. A layperson can use this, and that is the point.
