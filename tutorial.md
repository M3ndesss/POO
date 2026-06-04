# Atividade Prática: Domínio de Git e GitHub

Este documento comprova a realização da atividade prática de Programação Orientada a Objetos (POO), demonstrando os conceitos de criação, clonagem, edição e gerenciamento de ramificações (branches) no Git.

---

## 1. Criação e Clonagem do Repositório

O repositório público chamado **`POO`** foi criado com sucesso no meu namespace. Em seguida, utilizei o terminal para clonar o repositório para a minha máquina local.

**Comando utilizado para clonagem:**

git clone https://github.com/M3ndesss/POO
![Descrição da imagem](exemplo.png)  

## 2. Edição de Conteúdo
Após clonar o repositório, foi criado/editado o conteúdo inicial do projeto. Foi adicionado este arquivo Markdown para estruturar a documentação. Os arquivos foram buildados para a área de preparação (staging area) e depois commitados.

Comandos utilizados:

Bash
git add .
git commit -m "Initial commit: Adicionando estrutura da atividade"
git push origin main
![Descrição da imagem](exemplo2.png)

## 3. Criação e Alteração de um Ramo (Branch)
Para demonstrar o fluxo de trabalho com ramificações, criei um novo ramo chamado feature-documentacao, mudei para ele, fiz alterações e enviei a nova branch para o servidor remoto.

Comandos utilizados:

Bash
# Criando e alternando para a nova branch
git checkout -b feature-documentacao

# (Após fazer alterações no texto) Enviando a nova branch para o GitHub
git add .
git commit -m "Docs: Atualizando documentação na branch feature-documentacao"
git push origin feature-documentacao
![Descrição da imagem](exemplo3.png)