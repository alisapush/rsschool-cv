# Alisa Pushnova

![alt text](photo.JPG "Alisa Pushnova")

* ### Contacts
  ***email: alisa.pushnova@gmail.com***   
  ***phone: +375(29)691-60-67***

* ### Summary
  I am a second-year Computer Science student looking for my calling in IT. 
  My favorite subjects at university are all the ones related with programming. 
  I also like to learn new technologies by experimenting with myself. For instance last month, I have created a cross-platform mobile app in Xamarin Forms (C#) because I was curious about how to change some settings in my favorite application. 
  The main reason I am passionate about programming in Swift is that I have the availability of necessary equipment: MacBook and iPhone =)

* ### Skills
	* Python
	* Git
	* C#
	* Algorithms and data structures  
	* Object oriented programming

* ### Code examples
  
  My latest lab in Python at university
   
  ```python
  import re
  import sys
  import argparse

  def word_count(str):
  	words = re.split("\W+", tmp.lower())
  	word_occurrences = dict([[x, words.count(x)] for x in words])
  	return word_occurrences

  def repeat_words(str):
  	word_occurrences = word_count(str)
  	top_10_words = sorted(word_occurrences.items(), key = lambda t: t[1], reverse = True)[:10]
  	return " ".join(list(map(lambda t: t[0], top_10_words)))

  parser = argparse.ArgumentParser()
  parser.add_argument("--file")
  parser.add_argument("--method")

  args = parser.parse_args()

  methods = {
  	"word_count": word_count,
  	"repeat_words": repeat_words
  }

  with open(args.file) as file:
  	lines = file.readlines();
  	tmp = ""
  	for line in lines:
  		tmp += line

  result = methods.get(args.method, lambda _: "Method not defined")(tmp)
  print(result)
  ```

  I prefer to keep my labs and projects [here](bitbucket.org/alisapushnova/labs) 

* ### Education
  * 2016-2018 Lyceum of BSU  
  Math and physics
  * 2018-2022 BSUIR  
  Faculty of computer systems and networks  
  Informatics and programming technologies

* ### English  
  Upper Intermediate (B2)  
  When I have an opportunity to travel around the world I try to practice my English. The rest of the time I am watching videos on TED talks or YouTube, reading social media websites including Twitter and Facebook. 
  It's generally known that English-language resources have more information in science and technology. So, this is the reason I'm trying to find useful information on educational websites/documentation in English. 




