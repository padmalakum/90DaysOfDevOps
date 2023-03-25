create a text file newfile1.txt and gave ls -ltr
![image](https://user-images.githubusercontent.com/92623347/227663997-056f32a2-8bcf-46c6-bdee-100c7da69c89.png)
tochange owner permissions we have to use chown command 
chown  username filename
![image](https://user-images.githubusercontent.com/92623347/227664095-fd389fe5-7416-4332-8493-55fb87c6485a.png)

to change grp permissions we have to use chgrp command
chgrp groupname filename
![image](https://user-images.githubusercontent.com/92623347/227664226-790ff8fd-ee0b-4dfe-94b2-7d31ebe1bfff.png)

to change other(users ) we have to use chmod command
chmod o=rw filename if we want to give write and read permissions for that file.

![image](https://user-images.githubusercontent.com/92623347/227665602-915d6569-5576-4b02-8783-be9cf5869241.png)

ACL are access control lists which gives access or specific  permissions for other users, and groups .

getfacl filename
![image](https://user-images.githubusercontent.com/92623347/227669781-9decc35c-7b3b-4d66-9c76-c14f1794ebf7.png)

and we can set specific permissions  to a different user (other than owner) and to different users in a different grp



