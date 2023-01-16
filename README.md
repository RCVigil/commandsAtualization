# Comandos para atualização em geral por Terminal

<br
/>

## Clique na seta para abrir os comandos

<details
>
  <summary
  ><strong
  >
    Ubuntu & pacotes de sistemas</strong></summary>

  <br
  />

## Atualizar os pacotes do sistema

  > <p
  > >sudo apt-get update && sudo apt-get dist-upgrade</p>

  <br
  />

## Comando abaixo vai reinicializar sua máquina
  
  > <p
  > >sudo reboot</p>

  <br
  />

## Comando abaixo vai instalar na sua máquina o update-manager-core
  
  > <p
  > >sudo apt-get install update-manager-core</p>

  <br
  />

## Comando abaixo vai editar o arquivo /etc/update-manager/release-upgrades

#### Faça uma cópia de segurança antes!
  
  > <p
  > >sudo apt-get install update-manager-core</p>

  <br
  />

## Visualize o arquivo /etc/update-manager/release-upgrades, antes de editá-lo;
  
  > <p
  > >cat /etc/update-manager/release-upgrades</p>

    Se aparecer [Prompt=never] na ultima linha quer dizer que ele nunca vai atualizar sozinho, se quiser que atualize utilize o comando abaixo.

  <br
  />
  
## Comando abaixo vai atualizar seu prompt

##### Normal
  
  > <p
  > >sudo sed -i 's/Prompt=normal/Prompt=lts/g' /etc/update-manager/release-upgrades</p>

  <br
  />

##### Never
  
  > <p
  > >sudo sed -i 's/Prompt=normal/Prompt=lts/g' /etc/update-manager/release-upgrades</p>

  <br
  />

## Iniciar o processo de atualização
  
  > <p
  > >sudo do-release-upgrade -d</p>

  <br
  />

## Verificar a versão do Ubuntu
  
  > <p
  > >lsb_release -a</p>

  <br
  />

</details>

#