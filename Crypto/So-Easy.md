## So Easy
### Crypto

- The Challenges Gives Me Some Base64 Encoded Strings To Solve So I Types ```echo "{ENCODED} | base64 -d"``` On The Terminal To Decode This String, After Doing That I Got Another Encoded String Here I Was Like ```tk is happining``` Then I Got AN Simple Idea To Put The Decoded String In A File Then Decode It Again And Again And Again.. , Then After Type ```echo "{ENCODED}" | base64 -d | tee Basefile ``` I Got Another Base Data There AND IDK WHY I DO THAT BUT I TYPED ```echo "" >> Basefile``` To Add New Line To The File, I Was About To Loop The Decode Proccess Using Bash **That What Happen Most Time In CTFs** Then I Got Data Contaning The Flag AT First Time.. , Solved.

- Data 
```
{"alg":"HS512"}{
  "author": "R0X4R",
  "flag": "3a5y_ch3ea5y"
```

- Flag 
```
cyberhack{3a5y_ch3ea5y}
```

## Tips

- Always Use ```-i``` With Base Decode From Terminal Even It Was Just A Simple One That Will Force The Proccess To Ignore UnBase Data And Continue Decode All Other Stuff

- Try Most Simple Stuff First To Save Your Time For Hard Challenges.

- Make Sure You Have Bash/Python For Automate Stuff In CTFs

## Online Stuff

- You Could Use ```https://www.base64decode.org/``` For Base64 Decode And Encode.

## Our Team

```
NAME = Roots
RANK = 16th
POINTS = 4230
```
