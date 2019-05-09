**Disconnected: No supported authentication methods available (server sent: publickey,gssapi-keyex,gssapi-with-mic)**


I got this error when i did an ssh to EC2 instance on my Windows system. Really broke my head for more than an hour because this is the exact same error i was encountering no matter which platform I used... WSL/ GitBash/ MobaXterm


Finally figured out a solution. It is lame but thought posting it could help thousands of others who get the same error [Internet couldnt help me :( ]

1. Copy the content in the .pem file
2. Paste it to another file and save it with .pem extn.

It will work...

How on earth will this kind of lame thing fix that error... No idea but it worked
