# Python_Dic
Dict Comprehensio
d={'stephen.marquard@uct.ac.za': '333', 'louis@media.berkeley.edu': '222', 'zqian@umich.edu': '212', 'rjlowe@iupui.edu': '32323', 'cwen@iupui.edu': '2212', 'gsilver@umich.edu': '5656'}

names=["Stephen","Louis","Zqian","Rjlowe","Cwen","Gsilver"]
d2={}
#DICT COMPREHENSION
d2={name:{k:v}for k,v in d.items()for name in #names}

Output i want is this:
{'Stephen': {'stephen.marquard@uct.ac.za': '333'}, 'Louis': { 'louis@media.berkeley.edu': '222'}, 'Zqian': { 'zqian@umich.edu': '212'}, 'Rjlowe': {'rjlowe@iupui.edu': '32323'}, 'Cwen': {'cwen@iupui.edu': '2212'}, 'Gsilver': {'gsilver@umich.edu': '5656'}}

But i am getting this:
{'Stephen': {'gsilver@umich.edu': '5656'}, 'Louis': {'gsilver@umich.edu': '5656'}, 'Zqian': {'gsilver@umich.edu': '5656'}, 'Rjlowe': {'gsilver@umich.edu': '5656'}, 'Cwen': {'gsilver@umich.edu': '5656'}, 'Gsilver': {'gsilver@umich.edu': '5656'}}

can somebody explain me and show me the right code
