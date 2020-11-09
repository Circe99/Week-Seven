# Raise the Dead I

## Option A:
  
  I tired to set up the virus-spread-chance and recovery-chance to a % that would allow a never ending cycle  ![Image](Netlogo(3).png)
  
  And then again with this setting ![Image](Netlogo(7).png) 
  
  The first version did last a long time, but because there was a resistance chance it evetually ended. But with the second set I was able to get a (I hope) neverending loop of people getting the virus and people recovering from it at almost the same rate with no chance of resistance. 
  
  Next I tried the setting with number-of-nodes at 300 and inital-outbreak-size at 1. If you compare the default settings and the new setting you can see that the end result is the almost the same. I think this shows that there is not a huge significance in how many nodes there are and how many of them start with the outbreak. It did admitidly take longer to end the outbreak with the larger outbreak number, but other than that the graphs look very similar and the end result is almost the same.
  ![Image](Netlogo(1).png)
  ![Image](Netlogo(2).png)
  
  The next part of this activity is a bit more difficult for me in terms of just wrapping my head around each step. I am taking it very slowly.
  
  When I went in to add a row in the link.txt file I did get this error message. ![Image](Netlogo(4).png) Luckily cocochantel and DR. Graham have sent suggestions on how to solve that. I will try Dr. Graham's method first. 
  Ok so the steps I did (for future Teddy) were: 
  
  1. I made a new file called links_2.txt where I added the line 4 1 0.8 to create the link between 1 and 4 both ways. 
  
  2. I saved it in my Documents because I wasn't able to save it in the same place at links.txt
  
  3. I changed the code to say file-open "link_2.txt" as seen in the image below
  ![Image](Netlogo(6).png)
  
  4. I moved the file from Documents to Code Examples (not sure why that worked but saving it directly didn't, but I will not question my luck)
  
  Now I have access to the new version I made (though the change is very subtle) *note the double ended arrow between 1 and 4*
  ![Image](Netlogo(5).png)
  
  I'm still not finished the activity, and it has taken me a long time to get to this point, but it is not because I am stuck at some annoying error message. Instead it's because I am working with something comepletely new to me so I want to take my time to better understand what it is I'm doing and why it is important. 
  
