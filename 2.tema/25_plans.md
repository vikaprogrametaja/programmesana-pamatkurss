## Ievade <br>   
1. speletaja_vards = int(input("kā tevi sauc?: ")) <br>
2. jautajums2 = int(input("cik bieži dodies uz treniņiem nedēļā?: ")) <br>
3. jautajums3 = int(input("cik daudz min pavadi ceļā uz treniņu?: ")) <br>
## Apstrāde <br>
4. rezultats = (jautajums2 * jautajums3) /60 <br>
## Izvade <br>
5. print(f"{speletaja_vards}  iznākums ir: {rezultats}")      

| mainīgā vārds | datu tips | ko glabā |
| speletaja_vards  | str |  vārdu |
|  jautajums2 | int |  reizes nedēļā |
| jautajums3 | int | minutes |
| rezultats | float | minutes nedēļā pavadītas ceļā uz treniņu |

jautajums2 = int(input("cik bieži dodies uz treniņiem?"))
jautajums3 = int(input("cik daudz min pavadi ceļā uz treniņu?: "))
rezultats = (jautajums2 * jautajums3)
print(f"{speletaja_vards}  iznākums ir: {rezultats} stundas") 
formulu vērts pārbaudīt pirms visas programmas rakstīšanas, 