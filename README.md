# Exercicio_17

#calculating ''sen'' ''cos'' ''tan'' of a triagule

import math
angu = float (input ('digite um angulo que voce deseja: '))
sen = math.sin (math.radians (angu))
cos = math.cos (math.radians (angu))
tan = math.tan (math.radians (angu))
print ('o angulo {} tem um seno de {:.2f}' .format (angu , sen))
print ('o angulo {} tem um cosseno de {:.2f}' .format (angu , cos))
print ('o angulo {} tem uma tangente de {:.2f}' .format (angu , tan))
