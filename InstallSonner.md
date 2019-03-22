### Instalação de Sistema Sonner: Cliente Prefeitura de Suzano.
    Por: Marcos Gimenez - version 2.0 - by Cristian Reges.

#### Faça logoff na máquina do usuário e entre como Administrador.

*   Usuario: sonner@pmsuzano
*   Senha: Tapprovedt2016

Abra o Executar do windows (Windows + R) e digite: \\10.26.0.3
Dê enter e acesse a pasta "INSTALL".

#### 1° Execute como Administrador o arquivo "InstalaClient.bat".

#### 2° Verifique se o sistema utilizado é 32 bits ou 64 bits (Meu computador -> Botão direito -> Propriedades) e escolha o arquivo "InstalaSonnerSuzano" na versão compativel.

#### 3° Execute como Administrador o Aqruvio "InstalaSonnerSuzano.XX Bits (32 ou 64)".

#### 4° Adicione permissão total à pasta DBCLIENT que se encontra na raiz (C:)
Clique com o botão direito sobre a pasta - Propriedades - Segurança.

#### 5° Acesse o "Regedit" para permitir o sistema para o usuário.
Abra o Executar do windows (Windows + R) e digite: REGEDIT
Acesse o caminho: HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\GRP -> InstalledApplications.
Adiciona os sistemas no campo como no exemplo:
- "CBP;CGA;CGC;CGF;LIC"
Clique em "OK"

#### 5° Reinicie a máquina e entre com o login do usuário.
