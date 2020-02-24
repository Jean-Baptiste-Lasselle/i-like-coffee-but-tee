# i-like-coffee-but-tee

_All I (love) know about tee_

This is a little cheatsheet dedicated  to the `tee` software, present for decades in `*nix` distributions across the world. 

And I started it with this little magic to understand what tee is capable of :

```bash
echo "I'm gonna understand tee" | tee -p warn -a voila.txt | echo "ah  ouii" | tee -p warn -a voila.txt | echo "$1 [] mdr c super"| tee -a voila.txt
cat voila.txt
```
