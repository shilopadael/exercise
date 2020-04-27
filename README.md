# exercise
exercise 1
# ava 
def sum_q(string):
    sum_all=0
    sum_1=0
    for chr in string:
        if chr == "q":
            sum_all = sum_1/(len(string)-1)
            return sum_all
            
        else:
            chr = int(chr)
            sum_1 = sum_1 + chr
            
           
       
    return sum_all    
        
string= "1234567q"  
print(sum_q(string))
