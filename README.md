# Serie-de-Fibonacci
É uma sequência, que a natureza segue, por exemplo: as ramificações das árvores, árvores genealógica do zangão, a forma de nossa galáxia, o código binário, etc.

Code:

import time

var1 = 0
var2 = 1
res = var1 + var2
print(1)
print()
print(res)

time.sleep(2.5)
while True:
  var1 = var2
  var2 = res
  res = var1 + var2
  print()
  print(res)
  time.sleep(2.5)
