# Guira: instaladores

O Guira é um facilitador do Jira: sprint, board, backlog, urgências, impedimentos e a daily da equipe num só lugar. Este repositório só guarda as **Releases** com os instaladores; o código fica em repositório privado.

**Baixe o instalador na [última Release](https://github.com/guglieelmor/guira-releases/releases/latest):**

| Sistema | Arquivo | Como instalar |
| --- | --- | --- |
| Windows 10/11 | `guira-X.Y.Z-setup.exe` | Dois cliques. Se o Windows avisar, "Mais informações › Executar assim mesmo". |
| Ubuntu, Debian, Mint | `guira_X.Y.Z_all.deb` | Dois cliques, ou `sudo apt install ./guira_X.Y.Z_all.deb` |
| Fedora, openSUSE | `guira-X.Y.Z-1.noarch.rpm` | Dois cliques, ou `sudo dnf install ./guira-X.Y.Z-1.noarch.rpm` |
| Outro Linux | `guira-X.Y.Z.zip` | Descompacte e rode `bash guira/instalar.sh` |

Na primeira abertura o Guira pede o e-mail do Jira e um [token](https://id.atlassian.com/manage-profile/security/api-tokens). Depois ele se atualiza sozinho: quando sai uma Release nova, aparece o painel "Nova versão disponível" com o botão **Atualizar versão**.
