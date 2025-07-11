
**Delete old Credencials of Git**

***Windows – Step-by-Step***
1.Open Windows Credential Manager:

`Press Windows Key, type Credential Manager, open it.`

Go to "Windows Credentials".

Find any credentials saved for `github.com`

`Remove/Delete` those GitHub credentials.

Now, next time you do:

```
git push origin main
```
Git will prompt you to log in — enter credentials or token.


.......................................................................................................................................

**SetUP in VsCode**

***These commands tell Git who you are — specifically, who is making the commits.***
```
git config --global user.email "dharmanaik1239@gmail.com"
```
```
git config --global user.name "DharmaNaik"
```

........................................................................................................................................

🔹 What is #!/bin/bash?
It is the first line in a shell script.

It tells the computer:
👉 “Run this script using the Bash shell.”

🔹 Why is it needed?
Without it, the system might use a different shell (like sh), which can cause errors.

With it, your script will always run the same way.

**How to Run**
```
sh 01-hello-world.sh
```

🔹 Think of it like this:
Just like a movie script needs a director to read it,
a shell script needs Bash to run it.
#!/bin/bash tells the computer,
"Hey, Bash! You're the director of this script."
