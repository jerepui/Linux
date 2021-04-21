1

d) ![kuvaD](https://i.gyazo.com/a3b060a9ead2853d4b8de2ebaa183132.png)

e) ![KuvaE](https://i.gyazo.com/bcd13d426ff625dff00780764a5b347f.png)

f) grep -n -i -v -E 'elämä|ei|kuolema' pg14152.txt
   ![kuvaF](https://i.gyazo.com/ea4e1f1b2b1700b0da9cbc2594ba47d6.png)
   

3

a) sed -1 's\lääkäri\puoskari\' pg14152.txt
b) sed '\maailma\d' pg14152.txt
c) sed 's/ab/bc/g;s/bc/ab/g' pg14152.txt
d) sed 's/\b Enfield \b/"Enfield"/' -i filename

4

a) paste file1 file2 file3
b) ![kuva4B](https://i.gyazo.com/f807b0cdf8731962fea8505731d838c4.png)


