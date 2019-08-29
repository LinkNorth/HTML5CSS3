# Introduktion till `git`

## Övning 1

### a)

Ladda ner och installera `git` om du inte redan har det installerat på din maskin.

Du kan hitta en version för ditt operativsystem på den här sidan:

* [https://git-scm.com/downloads](https://git-scm.com/downloads)

När du har det installerat bör du kunna skriva `git --version` i en kommandotolk:

```
$ git --version  
git version 2.17.1
```

### b)

Konfigurera `git` med ert namn och emailadress.

```
$ git config --global user.name "Mitt Namn"  
$ git config --global user.email "min@mail.com"
```

### c)

Registrera ett konto om du inte redan har ett på GitHub.

### d)

Skapa och ladda upp SSH-nycklar till ditt konto. Hur man gör beror på vilket operativsystem du använder så följ den här guiden:

[https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/)

## Övning 2

### a)

Skapa ett tomt repo på GitHub (ge det ett namn som är lätt att komma ihåg, t ex `mitt-forsta-repo`).

### b)

Klona repot till din maskin mha `git clone`.

## Övning 3

### a)

Skapa en ny textfil i det nya katalogen och spara den.

Om ditt repo heter `mitt-forsta-repo` kommer det ha skapats en katalog med samma namn när du klonade repot.

### b)

Navigera till katalogen och lägg till filen med `git add`.

Du kan se om den blivit tillagd genom att skriva `git status`.

### c)

Gör en commit genom att skriva `git commit -m "Min första commit"`.

### d)

Skicka ändringarna till GitHub med `git push`.

Du kan kontrollera att din commit har skickats genom att ladda om repots sida på GitHub.

## Övning 4

### a)

Gör en ändring i din fil och spara den.

Du kan se alla ändringar med `git diff`.

### b)

Lägg till filen och gör en commit.

### c)

Gör en till commit där du tar bort filen.

### d)

Visa en lista på dina commit:ade ändringar med `git log`.

### e)

Skicka ändringarna till GitHub.

## Övning 5

### a)

Klona ditt repo igen till en ny katalog.

### b)

Gör en commit i den nya katalogen och skicka den till GitHub med `git push`.

### c)

Hämta ändringen i den första katalogen med `git pull`.

## Övning 6

Gör en commit och ångra den mha `git revert`.
