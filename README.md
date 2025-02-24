# numero = 0

# while numero + 1
# print (numero)
# if numero = int (n/3)
#     continue
# if
#     numero = 15
# break

# numero = 0
# while True:
#     numero += 1
#     print(numero)
#     if numero % 3 == 0:
#         continue
#     if numero == 15:
#         break
    
    
numero = 0
while True:
    numero += 1

    if numero == 15:
        break
    
    if numero % 3 == 0:
        # Skip additional processing for numbers divisible by 3
        continue
    print(numero)
