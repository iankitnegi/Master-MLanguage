# Master M Language of Power Query

### How to create LIST {}:
List: ={1,2,3,4,5}  
List 1 to 100: ={1..50}

### How to create RECORD []:
= [A=1, B=2, C=3, D=4]

### How to create TABLE ():
= #table(
        {"Column1", "Column2", "Column3"},
        {
            {1, "A", true},
            {2, "B", false},
            {3, "C", true}
        }
    )

### How to create Invoked Funn => :
= (x,y) => x+y/2
