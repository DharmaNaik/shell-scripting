
**Delete old Credencials**

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

