Part 1

 week7-2[Week5_6_P2_arriaga.py for MPG code.pdf](https://github.com/Arriaga8022/week7-2/files/8612959/Week5_6_P2_arriaga.py.for.MPG.code.pdf)

Part 2
while True:
      #user input
      milesDriven = int(input("Enter the number of miles driven: "))
      gasUsed = int(input("Enter the amount of gas used: "))
      #finding the mile per gallon
      MPG = milesDriven / gasUsed
      #printing the result
      print("Miles Driven:", milesDriven)
      print("Gas used:", gasUsed)
      print("Miles per gallon:",MPG)

Input: two float values
Output: three float value
1.	Insert milesdriven
2.	Instert gasused
3.	Calculate mpg:milesdriven/gasused
4.	Print mpg
5.	Ask user if they wish to perform another calculation
a.	Y, go back to step 1
b.	N, exit the program
o.    if the user didn’t input y/n, we will ask the user, until we receive a y/n answer
#input to stop script from closing: bad
name=input('ford')
name=input('chevy')
name=input('tesla')
name=input('hyaundi')
name=input('honda')
name=input('volkswagon')
name=input('error')
name=('ford [11] is [16]')
name=('chevy [12] is [15]')
name=('tesla [13] is [20]')
name=('hyaundi [14] is [18]')
name=('honda [15] is [22]')
name=('volkswagon [16] is [22]')

#Code

#create loop
#without loop list

user = input("input to stop script from closing: ")

a = ("ford","chevy","tesla","hyaundi","honda”,”volkswagon")
b=[3,]
c=["1,750","2,450","2,000","450","1,000”,”700",]
    
for i in a:
    print(i)
    if i == user:
      break
else:
    print("error")

    print("ford", b[0]+1, "is", c[0])
    print("chevy", b[0]+2, "is", c[1])
    print("tesla", b[0]+3, "is", c[2])
    print("hyaundi", b[0]+4, "is", c[3])
    print("honda", b[0]+5, "is", c[4])
    print("volkswagon", b[0]+5, "is", c[5])
