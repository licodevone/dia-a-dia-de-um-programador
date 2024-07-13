# Como criar uma máquina virtual com o Hyper-V Windows

É possível criar a máquina virtual e o disco juntos, mais abaixo irei criar uma um disco e posteriormente a VM.

> Diretório padrão das VM

> C:\ProgramData\Microsoft\Windows\Virtual Hard Disks

## Criar um disco virtual

> Apertar trecla do Windows e procurar por "Ativar ou desativar recursos do Windows"

![alt text](../img/imagens_3/image-5.png)

![alt text](../img/imagens_3/image-6.png)

![alt text](../img/imagens_3/image-7.png)

![alt text](../img/imagens_3/image-8.png)

> Após a reiniciar o Windows procurar por Hyper-V

![alt text](../img/imagens_3/image-9.png)

![alt text](../img/imagens_3/image-10.png)

![alt text](../img/imagens_3/image-11.png)

![alt text](../img/imagens_3/image-12.png)

![alt text](../img/imagens_3/image-13.png)

![alt text](../img/imagens_3/image-14.png)

![alt text](../img/imagens_3/image-15.png)

![alt text](../img/imagens_3/image-16.png)

![alt text](../img/imagens_3/image-17.png)

![alt text](../img/imagens_3/image-18.png)

![alt text](../img/imagens_3/image-19.png)

![alt text](../img/imagens_3/image-20.png)

# Criar a máquina Virtual com Hyper-V

![alt text](../img/imagens_3/image-22.png)

![alt text](../img/imagens_3/image-21.png)

![alt text](../img/imagens_3/image-23.png)

![alt text](../img/imagens_3/image-24.png)

> Neste caso irei alocar memória dinâmica, pois meu computador tem 32GB

![alt text](../img/imagens_3/image-25.png)

> No Windows 11 é melhor deixar conectado na próxima opção, pois deve precisare da internet.

![alt text](../img/imagens_3/image-26.png)

![alt text](../img/imagens_3/image-27.png)

> Como já existe um disco criado utilizar a opção usar disco rígido e procurar onde ele foi criado.

![alt text](../img/imagens_3/image-28.png)

![alt text](../img/imagens_3/image-29.png)

![alt text](../img/imagens_3/image-30.png)

![alt text](../img/imagens_3/image-31.png)

> Acessar configurações


![alt text](../img/imagens_3/image-32.png)

![alt text](../img/imagens_3/image-33.png)

> Alterar a quantidade de núcleos desejados, por padrão foi utilizado 4 núcleos

![alt text](../img/imagens_3/image-34.png)

> Alterar em Segurança e desabilitar Secure boot

https://www.youtube.com/watch?v=3XMn8JssNxU

Tempo 5:00

![alt text](../img/imagens_3/image-65.png)

> Clicar em Iniciar

![alt text](../img/imagens_3/image-35.png)

> Clicar em conectar

![alt text](../img/imagens_3/image-36.png)

> Erro na inicialização

![alt text](../img/imagens_3/image-37.png)

![alt text](../img/imagens_3/image-38.png)

![alt text](../img/imagens_3/image-39.png)

> Deletar a VM criada possível que a HD não seja da segunda geração

![alt text](../img/imagens_3/image-40.png)

> Instalação sem internet

> desabilitar a placa de rede
com o comando

ncpa.cpl  (tecle enter)   

desabilitar a rede local e depois digitar

oobe\bypassnro (tecle enter)

https://www.youtube.com/watch?v=1rDNMY-dlkc

![alt text](../img/imagens_3/image-66.png)

habilitar a placa de rede ethernet novamente

![alt text](../img/imagens_3/image-67.png)

![alt text](../img/imagens_3/image-68.png)

## <mark>Hyper-V Quick Create/mark>

A melhor maneira de criar uma uma VM com Hyper-V

![alt text](../img/imagens_3/image-41.png)

![alt text](../img/imagens_3/image-42.png)

### VM Ubuntu utilizando a imagem 22.04 padrão fornecida pelo sistema.

![alt text](../img/imagens_3/image-43.png)


![alt text](../img/imagens_3/image-44.png)

![alt text](../img/imagens_3/image-45.png)

> <mark>Não esquecer de modificar o Firmware para o Disco rígido, sendo que ele esta utilizando uma unidade de DVD virtual para rodar a ISO.</mark>

Tempo 15:40 no vídeo abaixo
https://www.youtube.com/watch?v=p6RoEe0CO_Q


![alt text](../img/imagens_3/image-46.png)

## Criando uma instalação do Windows 11 através de Imagem ISO

> No momento que a tela mostrar o botão iniciar é preciso segurar uma tecla porexemplo a espaço, depois clicar no botão iniciar até começar a instalação.

> Eliminando os requisitos para a instalação do Windows 11

> Clicar em shift + F10 para iniciar o cmd e depois digitar regedit para alterar os registros do Hardware, conforme imagem abaixo.

![alt text](../img/imagens_3/image-60.png)

> acessar os registros do windows e criar algumas 

![alt text](../img/imagens_3/image-59.png)

> fecha a janela de registro do Windows e clica em voltar 

![alt text](../img/imagens_3/image-61.png)

![alt text](../img/imagens_3/image-62.png)

Vemos que agora ele pérmite a continuação da formatação.

![alt text](../img/imagens_3/image-63.png)

> Aceitar os termos

![alt text](../img/imagens_3/image-64.png)

### VM Windows utilizando a imagem Ambiente de desen... padrão fornecida pelo sistema.

![alt text](../img/imagens_3/image-47.png)

> Editar Configurações

![alt text](../img/imagens_3/image-48.png)

![alt text](../img/imagens_3/image-49.png)

![alt text](../img/imagens_3/image-50.png)

> Para não inicializar com o Windows do sistema

![alt text](../img/imagens_3/image-51.png)

> Caso tenha problema de boot segura a tecla barra de espaço e deixar precionada até colicar em iniciar.

![alt text](../img/imagens_3/image-52.png)

![alt text](../img/imagens_3/image-53.png)

![alt text](../img/imagens_3/image-54.png)

![alt text](../img/imagens_3/image-55.png)

![alt text](../img/imagens_3/image-56.png)

![alt text](../img/imagens_3/image-57.png)

![alt text](../img/imagens_3/image-58.png)

# Compartilhamento entre maquina Host e Guest

https://www.youtube.com/watch?v=cbwQKR78OMs

![alt text](../img/imagens_3/image-88.png)

![alt text](../img/imagens_3/image-89.png)

![alt text](../img/imagens_3/image-90.png)

![alt text](../img/imagens_3/image-91.png)

![alt text](../img/imagens_3/image-92.png)

![alt text](../img/imagens_3/image-93.png)

![alt text](../img/imagens_3/image-94.png)

![alt text](../img/imagens_3/image-95.png)

![alt text](../img/imagens_3/image-96.png)

![alt text](../img/imagens_3/image-97.png)

![alt text](../img/imagens_3/image-98.png)

![alt text](../img/imagens_3/image-99.png)











