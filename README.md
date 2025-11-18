# Colors-in-Notebook
Código para incrementar seu print em python com texto em cores

Este código está disponivel no Kaggle em: https://www.kaggle.com/discussions/general/273188
O mesmo conteúdo por ser encontrado lá:

Exemplo, com retorno em verde claro:

\033[ Código de escape, este é sempre o mesmo
1 = Estilo, 1 para normal
32 = Cor do texto, 32 para verde brilhante
40m = Cor de fundo, 40 para preto

A tabela abaixo apresenta os vários formatos;

<img width="811" height="627" alt="image" src="https://github.com/user-attachments/assets/96f0e551-b085-4f17-b5df-b035529c697e" />

Aqui está o código usado para colorir o texto:

print("\033[0;37;40m Normal text\n")

print("\033[2;37;40m Underlined text\033[0;37;40m \n")

print("\033[1;37;40m Bright Colour\033[0;37;40m \n")

print("\033[3;37;40m Negative Colour\033[0;37;40m \n")

print("\033[5;37;40m Negative Colour\033[0;37;40m\n")

print("\033[1;37;40m \033[2;37:40m TextColour BlackBackground TextColour GreyBackground WhiteText ColouredBackground\033[0;37;40m\n")

print("\033[1;30;40m Dark Gray \033[0m 1;30;40m \033[0;30;47m Black \033[0m 0;30;47m \033[0;37;41m Black \033[0m 0;37;41m")

print("\033[1;31;40m Bright Red \033[0m 1;31;40m \033[0;31;47m Red \033[0m 0;31;47m \033[0;37;42m Black \033[0m 0;37;42m")

print("\033[1;32;40m Bright Green \033[0m 1;32;40m \033[0;32;47m Green \033[0m 0;32;47m \033[0;37;43m Black \033[0m 0;37;43m")

print("\033[1;33;40m Yellow \033[0m 1;33;40m \033[0;33;47m Brown \033[0m 0;33;47m \033[0;37;44m Black \033[0m 0;37;44m")

print("\033[1;34;40m Bright Blue \033[0m 1;34;40m \033[0;34;47m Blue \033[0m 0;34;47m \033[0;37;45m Black \033[0m 0;37;45m")

print("\033[1;35;40m Bright Magenta \033[0m 1;35;40m \033[0;35;47m Magenta \033[0m 0;35;47m \033[0;37;46m Black \033[0m 0;37;46m")

print("\033[1;36;40m Bright Cyan \033[0m 1;36;40m \033[0;36;47m Cyan \033[0m 0;36;47m \033[0;37;47m Black \033[0m 0;37;47m")

print("\033[1;37;40m White \033[0m 1;37;40m \033[0;37;40m Light Grey \033[0m 0;37;40m \033[0;37;48m Black \033[0m 0;37;48m")


veja o resultado do código:
<img width="901" height="356" alt="image" src="https://github.com/user-attachments/assets/1282b69b-03fe-4823-94fd-68044076b4b8" />





