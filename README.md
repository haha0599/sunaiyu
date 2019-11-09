#evensum.py
def func_sum(a_list):
    s=0
    for i in range(0,len(a_list)):
        if a_list[i]%2==0:
            s=s+a_list[i]
    return s
