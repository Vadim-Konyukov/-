# Задание №1 
def fnuc(str_list: list):
  str_list = [x for x in str_list if x != ' ' and x != '']
  return str_list
  
# задание №2
_____

# Задание №3 как найти строку в которую входит подстрока

def func(n: str, symbol):
    s = []
    start = -1
    while True:
        start = n.find(symbol, start+1)
        if start == -1:
            break
        s.append(start)
    return s

    # Задание №10
    a = 1
b = 5
x = [_ for _ in range(a, b + 1)]
c = 4
d = 9
y = [_ for _ in range(c, d + 1)]

e = set(x) & set(y)
print(e)
