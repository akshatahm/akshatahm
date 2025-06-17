
----------------------------------------------------------------
1. try.. catch :
----------------------------------------------------------------
try:
    .
    .
except Exception as e:
    .
    
----------------------------------------------------------------  
2. Data types:
----------------------------------------------------------------
base datatypes:
    string
    float
    complex
    bool
    list []
    tuple ()
    set {}
    frozenset
    dict {}
    bytearray

----------------------------------------------------------------
3. Increment and substr (str & list):
----------------------------------------------------------------
inp_str ="good morning"

# 3a string related increment, substr, find:
# 3a.1 increment
    for i in range(0, len(inp_str), 2):
        print("[str]incremented:"+inp_str[i])

# 3a.2 copy
    inp_str1 = inp_str[::]
    print("[str]copied:"+inp_str1)

# 3a.3 substr
    for i in inp_str[::2]:
        print("[str]substr:"+i)

# 3a.4 find
    if inp_str.find("m")!=-1:
        print("found m!")


print("------------------------------")
inp_list = ["a","b","c","d","e","f"]

# 3b list related increment and substr:
# 3b.1 increment
    for i in inp_list[::2]:
        print("[lst]incremented:"+i)

# 3b.2 copy
    inp_list1 = inp_list[::]
    print("[lst]copied:"+str(inp_list1))

# 3b.3 substr
    temp = inp_list1[::2]
    print("[lst]substr:"+str(temp))

----------------------------------------------------------------
4. add a string to a list
----------------------------------------------------------------
"hello" + str(list)

----------------------------------------------------------------
5. 
----------------------------------------------------------------
