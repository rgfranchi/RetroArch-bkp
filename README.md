# RetroArch-bkp

Repositório criado para manter as configurações do RetroArch

## Incluir nas configurações "Directory" o caminho para pastas do Repositório
- playlist 
- database 

## O que foi observado ? (Carregar Playlist pelo Retroarch)
	- Banco de dados é baixado da internet (OnLine Updater) - **CUIDADO substitui os arquivo locais**.
	- A busca pela ROM no banco de dados é pela coluna pelo CRC (codigo gerado "único" pelo arquivo), com o 7z é possível visualizar.
		- Para abrir os arquivos da pasta "database" utilizar o RDBEd (https://github.com/schellingb/RDBEd/releases).
	- Algumas colunas no banco de dados podem ser utilizadas para filtro (Name, Gener, Users, Publisher, etc... ).
	- Com o nome informado no banco de dados é possivel atualizar as Capas do jogo (OnLine Updater)   
### Arquivos não carregados na Playlist correta, testado com o MAME
	- *Problema:* Ao tentar buscar lista de jogos do MAME não localizou a grande a maioria dos jogos.
	- *Teste:* Separado o arquivo **database\MAME.rdb** a maioria dos jogos foi localizada porem com Core de outros MAMES e EMULADORE (Final Burn).
		* Repositório contem as informações corrigidas.
	- Os arquivos '.rdb' foram renomeados e ajustado de acordo com as necessidades.