# bananapkg :banana: :package: 🇧🇷 [![Bash4.4.18-shield]](http://tldp.org/LDP/abs/html/bashver4.html#AEN21220) [![LICENSE](https://img.shields.io/badge/Licen%C3%A7a-MIT-brightgreen.svg)](https://github.com/slackjeff/bananapkg/blob/master/LICENSE) [![Doe-shield]](https://slackjeff.com.br/doacao/)

> Gerenciador de Pacotes de baixo nível, escrito em Shell Bash.
 
![Banner]

### Para uma melhor Documentação consulte
* [Site Oficial](https://bananapkg.github.io/)

### DESENVOLVEDORES: leiam o Code-Style :ledger:
* [Code Style](https://bananapkg.github.io/code-style.html)

### Requisitos/Requirements :star:
* **Bash** >= 4.4.18 <br/>
* **GNU Sed** >= 4.2.2<br/>
* **GNU Tar** >= 1.30<br/>
* **AWK** >= 4.2.1<br/>
* **xz** >= 5.2.2<br/>
* **GPG** >= 2.2.9<br/>

### Distribuições que usam o Banana como principal gerenciador :heart:
* [MazonOS](http://mazonos.com/pt)

----

### Instalação Direta :computer:
**Clone o Repositório**<br/>
git clone https://github.com/slackjeff/bananapkg<br/>
<br/>
**Como ROOT, crie os diretórios**<br/>
mkdir -vp /var/lib/banana/{list,desc,remove}<br/>
mkdir -v /etc/banana<br/>
mkdir -v /usr/libexec/banana<br/>
<br/>

**Copie os arquivos**<br/>
cp -v banana /sbin/<br/>
cp -v banana.conf /etc/banana<br/>
cp -v {core,help}.sh /usr/libexec/banana<br/>
cp -v banana.8 /usr/share/man/pt_BR/man8/<br/>
*Enjoy ;)*

## Instalação Automática :computer:
**Conceda permissões e execute o script**<br>
chmod +x install.sh<br>
bash install.sh

[Banner]: https://raw.githubusercontent.com/slackjeff/bananapkg/master/imgs/banners/bananabanner.png
[Bash4.4.18-shield]: https://img.shields.io/badge/Bash-4.4.18%2B-brightgreen.svg "Bash 4.4.18 Ou superior"
[Doe-shield]: https://img.shields.io/badge/Doe-Pagseguro-red.svg
