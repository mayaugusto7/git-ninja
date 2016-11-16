git config --global user.name                                                                                                                                       
MayconRibeiro                                                                                                                                                                 
git config --global user.email                                                                                                                                      
maycon_ribeiro@hotmail.com                                                                                                                                                    
bash-3.2$ git config --global color.ui  

#criando um projeto git
mkdir projeto
cd projeto
git init 

#primeiro commit
git status
git add my_file.txt myfile2.txt myfile3.txt
git add .
git status
git commit -m "First Commit"

#comprometer-se mais com o git
git diff // mostra possiveis alteracoes do arquivo
git diff my_file.txt // sempre colocar a extensao do arquivo
git add my_file.txt myfile2.txt // substitui o conteudo do arquivo por outro

#guardando a history
git log
#mostrando a history
git show 2df83

# .gitignore ignorar arquivos desnecessarios
create .gitignore pelo vi 
git status
arquivo .exe ignorado pelo commit

#Repositorio remoto
git remote add origin https://github.com/mayribeiro/git_ninja.git
git push -u origin master