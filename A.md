# 📱 Introdução ao Termux (Guia para Iniciantes)

## ❓ O que é o Termux?

O **Termux** é um aplicativo para Android que funciona como um
**terminal Linux**.\
Com ele, você pode executar comandos, scripts e até programar direto
pelo celular.

Pense nele como um **CMD do Windows / Terminal do Linux**, só que no
Android.

------------------------------------------------------------------------

## 🧠 Conceito básico

No Termux, tudo funciona através de **comandos** digitados no terminal.\
Cada comando tem uma função específica, como entrar em pastas, listar
arquivos ou instalar programas.

------------------------------------------------------------------------

## 📂 Onde você está (Prompt)

Quando você abre o Termux, verá algo parecido com isso:

``` bash
~ $
```

-   `~` → pasta inicial\
-   `$` → pronto para receber comandos

------------------------------------------------------------------------

## 📁 Arquivos e Pastas

-   **Pastas** são como caixas\
-   **Arquivos** ficam dentro das pastas

Exemplo:

``` text
downloads/    ← pasta
musica.mp3   ← arquivo
```

------------------------------------------------------------------------

## 📌 Comandos básicos

### 🔹 `cd` --- Entrar em pastas

O comando `cd` é usado para **entrar em uma pasta**.

``` bash
cd download
```

Para voltar uma pasta:

``` bash
cd ..
```

------------------------------------------------------------------------

### 🔹 `ls` --- Listar arquivos

Lista todos os arquivos e pastas do diretório atual.

``` bash
ls
```

------------------------------------------------------------------------

### 🔹 `pwd` --- Mostrar localização atual

Mostra em qual pasta você está.

``` bash
pwd
```

------------------------------------------------------------------------

### 🔹 `clear` --- Limpar a tela

Limpa o terminal.

``` bash
clear
```

------------------------------------------------------------------------

## 🔐 Permissão de acesso ao armazenamento

Para acessar arquivos do celular, execute:

``` bash
termux-setup-storage
```

Depois disso, você poderá acessar:

``` bash
/storage/emulated/0
```

------------------------------------------------------------------------

## 📦 Gerenciador de pacotes (`pkg`)

### 🔄 Atualizar o Termux

``` bash
pkg update
pkg upgrade
```

### 📥 Instalar programas

``` bash
pkg install python
pkg install nodejs
pkg install git
```

------------------------------------------------------------------------

## 📁 Criar pastas

``` bash
mkdir projetos
```

------------------------------------------------------------------------

## 🗑️ Remover arquivos

⚠️ **Atenção:** este comando apaga permanentemente.

``` bash
rm arquivo.txt
```

------------------------------------------------------------------------

## 💡 Dicas úteis

-   Use `tab` para completar comandos\
-   Use as setas ↑ ↓ para comandos anteriores\
-   Linux diferencia maiúsculas de minúsculas

------------------------------------------------------------------------

## ❗ Erros comuns

-   `command not found`
-   `permission denied`
-   Pasta não existe

------------------------------------------------------------------------

## 🚀 Conclusão

Agora você já sabe o básico do Termux e pode avançar para programação,
scripts e automações.
