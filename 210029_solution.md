# Details

Rename this file in the format `yourRollNumber_solution.md` (example, `210000_solution.md`)

## Your zeroth approach below

Reasoning - Simply executed the program after removing the compilation error occuring due to 'int ved[]' being assigned a character string. On execution, it printed "The answer of this challenge is output of "man" when run on the terminal, copy the exact output". So I ran the command on the Ubuntu 20.04 LTS terminal.

```md
What manual page do you want?
For example, try 'man man'.
```

---

## Your first approach below

Reasoning - the " #define clue_of_1 "not rot13 try all" " in zeroth.c and the README.md file indicated that alphabets may be rotated by a certain no. Thus with the help of [https://rot13.com/](https://rot13.com/) by applying different permutations I got that the alphabets were rotated by 8 positions.

```md
noicee you did crack a rotation encryption on your own. The following is a clue for the next puzzle: CLASS of that INPUT %%%
```

---

## Your second approach below

Reasoning - The README.md file instructed to look for the input class of the "Google Search" button. So I opened www.google.com and 'inspect'ed the page and found :

```html
<input class="gNO89b" value="Google Search" aria-label="Google Search" name="btnK" role="button" tabindex="0" type="submit" data-ved="0ahUKEwjEjrKKr_D3AhVwp1YBHeBxC2QQ4dUDCA0">
```

Thus i got the class as "gNO89b". Then as intructed in the README.md I ran "python second.py gNO89b" in my terminal%%%

```md
Gotcha! Here's your answer: fMN78alst
```

---

## Your third approach below

Reasoning - First I used "unzip 'Downloads/hackit_challenge_1.zip' -d Desktop" to extract the files and move it to desktop(Note that the name of zip file is changed to "hackit_challenge_1.zip" from "hackit_challenge.zip" and the extracted files are moved to desktop because the zip file got downloaded twice. Hence these measures were to avoid confusion.). Then via "cd desktop" followed by "cd question_mark" I entered the directory containing "third.zip". README.md implied that the problems are independent and the password of this file is an obvious one. Thus i tried "password" which indeed worked. Then using "grep -r hack" I found the required string.

```md
hackIT{y0ur3_4w350m3_4nd_1n}
```

- Name : Abhinav Garg
- Roll : 210029

## Do not tamper below this line

---

Q29yZSB0ZWFtIGtvIGZha2UgZG8=
