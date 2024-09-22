# Estudos de Sistemas operacionais

`Atenção!!!: Esse conteúdo é só algumas anotações do meu caderno repassada para o github com foco de facilitar os estudos.`

O sistema operacional, gerência os recursos do sistema

- Elo entre harware e software
- Em todos sistemas operacionais tem vários serviços sendo executados em segundo plano

## Componentes do Pc/computador

> Processador: Cálculo e operação

> Memória Ram (principal): Permite abrir vários programas ao mesmo tempo, não salva arquivos
>
> Rápida, abrir programas

> Hd ou SSD (secundária): Arquivo são salvos na memória secundária
>
> Lenta, salvar programas

- memória virtual é usar o hd ou ssd como memória ram

## Evolução dos Computadores (gerações)

Os sistemas operacionais evoluiram em cunjunto como a evolução dos computadores

> Guerra fria:
>
> foi uma disputa tecnológica entre grandes potências

> A.R.P.A.N.E.T:
>
> Criação da A.R.P.A.N.E.T em 1969 nos Estados Unidos e foi a primeira rede de computadores operacional, foi desenvolvida para interligar laboratórios de pesquisa e departamentos militares

> Internet:
>
> Deixaram a rede publica

- **1º Geração**: Válvulas
- **2º Geração**: Transistores (Assembly, Fortram) - IBM
- **3º Geração**: Circuitos integrados (Multiprogramação)
- **4º Geração**: Computadores pessoais (MS - DOS) - Gráfica
- **5º Geração**: Redes de comunicação

> Internet of things (IOT):
>
> Conectar tudo á internet, ex:

- > vestíveis (werables)
- > casas

## Unidades de Medidas do computador

Essa é a unidade de medida para armazenar arquivos

- > Binários: menor unidade de medida
- > 1 bit: Binary digit
- > 1 Yotabyte: maior unidade de medida

| 8 bits         |  =  |     1 Byte |
| :------------- | :-: | ---------: |
| 1024 Bytes     |  =  |    1 KByte |
| 1024 KBytes    |  =  | 1 MegaByte |
| 1024 MegaBytes |  =  | 1 GigaByte |
| 1024 GigaByte  |  =  | 1 TeraByte |
| 1024 TeraByte  |  =  | 1 PetaByte |
| 1024 PetaByte  |  =  |  1 ExaByte |
| 1024 ExaByte   |  =  | 1 ZetaByte |
| 1024 ZetaByte  |  =  | 1 YotaByte |

## Servidor

Servidor é um computador com muito poder de:

> Processamento
>
> Armazenamento

## Interfaces

> Interface gráfica (GUI)
>
> tipo de interface que permite a interação por meio de elementos gráficos como ícones e outros indicadores visuais

> Interface de comandos (CLI):
>
> modo de comando é mais eficiente para menos consumo de memória

## Virtualização

A virtualização é pegar os recursos de uma máquina e dividir/compartilhar por uma questão de custo benefício

- **Nome Técnico:** Hypervisor

> **3 plataformas em alta**
>
> - Clod da Google.
> - AWS da Amazom.
> - Azule da Microsoft.
>
> Eles vendem um serviço que no caso seria pegar algo fisico e vender virtualmente

- Virtual Box e Vmware são os principais programas de máquinas virtuais

## Windows

- Principal que as pessoas usam para resolver problemas do dia a dia

> Cmd (Prompt de Comando):
>
> O cmd antes do windows era chamado de DOS.

> Power shell:
>
> - permiti que administradores de sistema automatizem ações e configurações.
> - tem o código aberto.
> - é uma atualização do cmd

- Power Shell e Cmd: Ambos são linhas de comandos.

### Comandos

```cmd
dir -> abre/exibe uma pasta/diretório
ls -> abre/exibe uma pasta/diretório (power shell)

cd -> change directory, entrando/acessando um diretório

cls -> limpar tela

mkdir -> make a derectory/criar uma pasta

rmdir -> remove a derectory/remover uma pasta

ipconfig -> serve para exibir as configurrações de ip do computador

ipconfigall -> detalha as configs do computador

ping -> verifica a conexão da máquina à um servidor

tracert -> exibe a rota da máquina a um servidor serve para rastrear o pacote de uma rede

ping e tracert -> comando para rede

sisteminfo -> exibe as informações do seu sistema
```

## Linux

- Foi criado para guardar/armazenar dados.
- É sempre gratuito
- LPI: Linux Professional Institute.
- Para trabalhar com linux é necessário certificado.
- Linux Escensials: programa com certificado.

> Código aberto:
>
> é um software com código-fonte que qualquer pessoa pode inspecionar, modificar e aprimorar e distribua o código-fonte de forma gratuita.

> Interface gráfica(GUI):
>
> Antigamente tinha uma interface gráfica ruim pois não foi projetado para isso

> Interface de comandos(CLI):
>
> Mais utilizado pois é mais eficiente para menos consumo de memória

> Distros:
>
> São como são chamados as versões do linux
>
> - Ubunto (Iniciante)
> - Linux Mint (Iniciante)
> - Debian (Estavel)
> - CentOS (Servidores)
> - Kali Linux (Pentest)

### Comandos Linux

```linux-config
$ -> usuário comum do sistemas não tem os privilégios do administrador

sudo su -> comando para poder acessar o admim do sistema

exit -> Admim: volta para o usuário padrão, Usuário comum: fecha o terminal

apt -> Advanced Powered Tools, Exibe todos os comando disponíveis com apt

apt update -> verifica se tem atualização

apt upgrade -> atualização do linux, não precisa reiniciar a máquina

apt insttal -> instala alguma coisa

pwd -> Mostra o caminho do diretório atual

clear / ctrl L(Teclas do teclado) -> limpa a tela

history -> Exibe os ultimos comandos já utilizou

⬆(seta para cima tecla do teclado) -> mostra o ultimo comando

if config -> exibe as configurações de ip do computador

ls -> Verifica o que tem dentro do diretório atual
    Azul -> Diretório ou pasta
    Vermelha -> Arquivo zipado ou compactado ouu comprimido

TAB(Tecla do teclado) -> Autocompletar

mkdir -> Criando um diretório/pasta

rmdir -> Deleta um diretório/pasta

cd -> Entrando / acessando uma pasta

df -> Exibe todo espaço disponível no hd ou ssd

ctrl c(teclas do teclado) -> Para a execução de qualquer coisa

ping -> verifica a conexão com algu, servidor a sua máquina, em ms
```
