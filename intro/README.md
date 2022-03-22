#Como realizar a criação de uma VM (Máquina Virtual) no Hyoer-V:

##Será preciso habilitar o *Hyper-V* no SO (Sistema operacional):

1. Verificar se o SO (Windows 2008 Enterprise) esta atualizado. 
2. Inicie o Server Manager e instale o **Hyper-V**
   1. Inicie.
   2. Clique em Roles e adcione um novo Roles (Add Roles).
   3. Clique em próximo (Next).
   4. Tique a opção *Hyper-V*
      * Clique em próximo (Next).
   5. Ecolha a placa de rede que será usada.
      * Clique em próximo (Next).
   6. Installe o sistema (Install).
      * Será necessário reiniciar a máquina.
   7. Ocorrendo tudo bem, esta instalado, é só fechar (Close).
3. Criar a VM
   1. Abra o gerenciado do *Hyper-V*.
   2. Selecione:
      * Action >> New >> Virtual Machine >> Wizard
   3. Com a janela aberta:
      * Defina o nome da VM.
      * O tamanho da memoria que será diponibilizado.
      * Escolha um disco que existe localmente.
      * Escolha o adaptador de rede.
      * Aponte um disco para boot.
      * Escolha um disco Virtual.
      * E, escolha um real.
      
   4. Configure o sistema operacional:
      * Na VM criada, clique com o botão direito do mouse >> Settings;
      * Escolha a a IDE Controller 1 e uma imagem do Sistema Operacional.
      * Conecte a VM
      * Start a mesma.
      * E, instalar o sistema opecional.
   
#Sobre o seu tipo?

## Este é uma VM do hypervisor tipo 2, já que usara um sistema operacional, no caso o Windows Server, como base para execultar seus serviços.

#Atualizacação do servidor

| Componentes         | Atual                   | Atualizado              |
|---------------------|-------------------------|-------------------------|
| Memória Ram         | 8GB                     | 32GB                    |
| Processador         | 2.4GHz                  | 5GHZ                    |
| Disco Rigido        | 500GB                   | 6TB                     |

