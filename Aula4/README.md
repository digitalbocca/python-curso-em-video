# PYTHON 3 - CURSO EM VÍDEO #

Dedicado aos desafios do curso de Python 3 do canal Curso em Vídeo.

#### DICA ####

- Para uma melhor experiência visual execute o arquivo principal do desafio.
- Para uma leitura melhor do código abra o arquivo resumido do desafio.
- Dúvidas e Sugestões no meu email: gabriel@estudiodigitalbocca.com.br.
- Dá um Watch no projeto pra receber as atualizações.

### Desafio 1 ###

#### DESAFIO ####

- Crie um script Python que leia o nome de uma pessoa e mostre uma mensagem de boas vindas de acordo com o valor digitado.

#### CÓDIGO ####

```python
# Recebe o Nome
nome = input('Atenção Humano. Identifique-se -> ')

# Mensagem de Boas Vindas
print('Bem Vindo Mestre', nome)
```

### Desafio 2###

#### DESAFIO ####

- Crie um script Python que leia o dia, o mês e o ano do nascimento de uma pessoa e mostre uma mensagem com a data formatada.

#### CÓDIGO ####

```python
# Recebe o dia do nascimento
dia = input('Dia do seu nascimento: ')

# Recebe o mês do nascimento
mes = input('Mês do seu nascimento: ')

# Recebe o ano do nascimento
ano = input('Ano do seu nascimento: ')

# Mostra uma mensagem bonitinha
print('Você nasceu em', dia + ' de ' + mes + ' de ' + ano + '.', 'Nunca é tarde para aprender a programar !!!')
```

### Desafio 3 ###

#### DESAFIO ####

- Crie um script Python que leia o nome de uma pessoa e mostre uma mensagem de boas vindas de acordo com o valor digitado.

#### CÓDIGO ####

- Solução 1 - Converter para inteiro na hora da soma.

```python
# Recebe um valor inteiro
numero1 = input('Inserir Primeiro Numero: ')

# Recebe um valor inteiro
numero2 = input('Inserir Segundo Numero: ')

# Realiza a soma dos valores recebidos
somaTotal = int(numero1) + int(numero2)

# Imprime o resultado na tela
print('O resultado da Soma é:', somaTotal)
```
- Solução 2 - Aceitar somente inteiros na entrada.

```python
# Recebe um valor inteiro
numero1 = int(input('Inserir Primeiro Numero: '))

# Recebe um valor inteiro
numero2 = int(input('Inserir Segundo Numero: '))

# Realiza a soma dos valores recebidos
somaTotal = numero1 + numero2

# Imprime o resultado na tela
print('O resultado da Soma é:', somaTotal)
```
>(c)2017 - Gabriel Bertola Bocca - **gabriel at estudiodigitalbocca.com.br**