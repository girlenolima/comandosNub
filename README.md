# COMANDOS PARA NAO ESQUECER GIT


**pwd**              								//  lista onde esta o diretorio
ls                	 							//  lista todos os diretorios
mkdir             	 							//  criar uma pasta
git init									//cria o repositorio local no projeto (criar a pasta git)
touch             	 							//  cria uma arquivo
la a              	 							//  exibi direotiro git
git log            								//  indetifica os commits
git log --oneline  								//  log simplificado
git log --graph   	 							//  log em grafico
git log --oneline --graph							//  versao simplificada grafico
git commit m - 									//  comita o arquivo ja adicionado ao conteiner
git add *                       						//  adiciona um todos os arquivos ao conteiner
git commit am- 	               		 					//  adiciona e comita ao mesmo tempo os arquivos
git branch                      	 					//  indentifica o ramo atual
git checkout (add o hash)       	 					//  volta o projeto para o commit escolhido
git checkout master  			 					//   retorna para ultima versao do projeto (na linha de tempo princiapal)
git diff  			  	 					//   mostras as foi alterado em um arquivo
git restore  ( mais nome do arquivo)     					//   volta o conteudo do arquivo para versao anterior (se foi adcionado ao conteiner nao funciona)
git restore --staged ( mais nome do arquivo)    				//   volta o conteudo do arquivo para versao anterior (mesmo dentro de um conteiner)
git reset --hard (mais hash)     						//   remove commit da linhna temporaval (principal master)
git checkout -b (mais algum nome) 						//   cria um novo ramo
git checkout master    								//   retonar  ao master
git log --oneline --graph --all  						//   visualiza toda a arvore
git merge (mais nome do ramo)  							//   funde o ramo a arvore princial
git remote								        //   verifica se tem repositorio remoto
git remote add origin https://github.com/girlenolima/praticaTerminal.gi 	//   monta um repositorio para ser enviado
git push -u origin master						 	//   Push para o servidor remoto
git remote rm origin //apargar vinculo antigo
git clone (mias link) // clona o repositorio
