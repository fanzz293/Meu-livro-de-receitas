Comandos básicos

Listar diretório das pastas
Windows - DIR; Unix - LS

Navegar entre pastas 
Windows/Unix -  CD/ ou CD.. -> Retorna 
		CD [NomePasta] -> Acessa a pasta

Limpar tela 
Windows - CLS; Unix - Clear (ou pressione CTRL + L)

"Atalhar" nome de pasta em comando CD[NomePasta]
Windows - CD [Letra inicial da pasta a ser acessada]. 
Ex.: CD W (Windows). Não pode ser qualquer letra pois
depende do contexto de disponibilidade de pasta a 
ser acessada. 
Unix - Não disponível

[Síntaxe] Criar/editar arquivo em TXT
Windows - echo hello > hello.txt, sendo que o comendo echo
imprime a palavra "hello". O ">" insere (redireciona fluxo)
da palavra imprimida ao arquivo criado chamado "hello.txt". 

Deletar arquivos

Windows - Del [Nome da pasta]
Unix - rm -rf  

Deletar pasta

Windows - rmdir [Nome da pasta] /S /Q
/S e /Q são comandos flags, que são formas de passar 
opções para comandos executados. 
Unix - rm -rf.  

Criar pasta 

mkdir [nome da pasta]

