# Corrige_Vbox_Error

Script para Corrigir Virtual Box em derivados do Debian

Criei esse script para automatizar a correção do VirtualBox.

Quando algumas distribuições atualizam, geralmente esse erro aparece quando abre uma Máquina no Seu VirtualBox

Os Comandos que o script executa são esses. Mas de forma automática
#/bin/sh

sudo apt install linux-headers-$(uname -r)

sudo /sbin/vboxconfig

_________________________________________________________________________

Para executar o script abra o terminal e digite:

Feche totalmente seu Virtual Box

Vá até o Local do script baixado

sudo chmod +x CorrigeVBox.sh

sudo ./CorrigeVBox.sh

Aguarde o processo terminar e abra novamente seu Virtual Box e execute sua máquina virtual.


Lembrando que os comandos acima podem ser digitados manualmente no terminal. Apenas fiz o script para que possa "automatizar" a correção.



Abraços!!
