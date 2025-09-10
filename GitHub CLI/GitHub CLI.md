# gh
- Open source command line tool.
- Install gh at Debian
	
		sudo apt install gh
- Authenticate in GitHub account.

		gh auth login
		>GitHuh.com
		>SSH
		
- Generate a new SSH key to add to your GitHub account? (Y/n)
- Upload you SSH public key to GitHub account? (Y/n)
- Title for your SSH key:
- How would you like to authenticate GitHub CLI? 
		
		Login with a web browser
		gh repo clone Eridhonson/professor
# Author identity unknown

*** Please tell me who you are.

Run:

		git config --global user.email "you@example.com"
		git config --global user.name "Your Name"

### [Adicionar um arquivo a um repositório usando a linha de comando](https://docs.github.com/pt/repositories/working-with-files/managing-files/adding-a-file-to-a-repository#adding-a-file-to-a-repository-using-the-command-line)
1. Abra Terminal.
    
2. Mude o diretório de trabalho atual para o seu repositório local.
    
3. Prepare a arquivo para commit em seu repositório local.

		git add .
		git status
```shell
# Adds the file to your local repository and stages it for commit. Para cancelar o preparo de um arquivo, use 'git reset HEAD ARQUIVO'.
```
4. Faça commit do arquivo que você preparou no repositório local.
    
		$ git commit -m "Add existing file"
    ```shell
    # Commits the tracked changes and prepares them to be pushed to a remote repository. Para remover esse commit e modificar o arquivo, use "git reset --soft HEAD~1", faça o commit e adicione o arquivo novamente.
    ```
5 . [Efetue push das alterações](https://docs.github.com/pt/get-started/using-git/pushing-commits-to-a-remote-repository) no repositório local para o GitHub.com.

	Listando as branchs:
	git branch
	
    $ git push origin branch_name
```shell
    # Pushes the changes in your local repository up to the remote repository you specified as the origin
    ```