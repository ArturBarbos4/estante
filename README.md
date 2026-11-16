# Estante de Leitura no GitHub Pages

Os arquivos desta pasta já estão prontos para publicar:

- index.html: o app
- sw.js: faz o app abrir sem internet depois da primeira visita
- manifest.webmanifest e icon-*.png: nome e ícone na Tela de Início do iPad
- LEIA-ME.md: este guia (não precisa enviar)

## 1. Criar o repositório

1. Entre em https://github.com (crie uma conta grátis se ainda não tiver).
2. Clique em "+" (canto superior direito) > "New repository".
3. Nome: estante (ou outro nome qualquer).
4. Marque "Public". No plano grátis, o GitHub Pages só funciona com repositório público.
   Isso deixa só o código do app público. Os seus livros nunca vão para o GitHub.
5. Clique em "Create repository".

## 2. Enviar os arquivos

1. No repositório novo, clique no link "uploading an existing file".
2. Arraste para a página estes 6 arquivos da pasta:
   index.html, sw.js, manifest.webmanifest, icon-180.png, icon-192.png, icon-512.png
3. Clique em "Commit changes".

## 3. Ligar o GitHub Pages

1. No repositório, vá em Settings > Pages (menu da esquerda).
2. Em "Build and deployment" > Source, escolha "Deploy from a branch".
3. Branch: "main", pasta: "/ (root)". Clique em Save.
4. Espere de 1 a 2 minutos e recarregue a página. O endereço aparece no topo:
   https://SEU-USUARIO.github.io/estante/

## 4. Instalar no iPad

1. Abra o endereço no Safari do iPad.
2. Toque em Compartilhar (quadrado com seta) > "Adicionar à Tela de Início".
3. Abra a Estante pelo ícone na Tela de Início. Ela abre em tela cheia, como um app.

Use sempre pelo ícone. Os livros ficam guardados nesse "app" instalado,
separados do Safari normal. Pelo ícone, o iPad também não apaga os
dados por falta de uso, ao contrário do que pode acontecer no Safari comum.

## Sem internet

Depois de abrir o app uma vez com internet, ele passa a abrir offline,
com os livros já adicionados.

## Para atualizar o app

Envie o novo index.html para o repositório do mesmo jeito (Add file > Upload files).
Na próxima vez que abrir o app com internet, a versão nova é carregada.

## Outras pessoas

Qualquer pessoa pode usar o mesmo endereço, sem conta do Claude nem do GitHub.
Cada iPad tem a sua própria estante. Ninguém vê os livros de outra pessoa.
