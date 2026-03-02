# 🍀 IT in Dublin Portal

Bem-vindo ao repositório oficial do IT in Dublin Portal! Este é um projeto open-source dedicado a conectar a comunidade de TI em Dublin, oferecendo um espaço centralizado para notícias, eventos e networking.

---

## 🇧🇷 Português (Brasil)

### Objetivos do Projeto

O objetivo principal deste projeto é criar um portal robusto de eventos, notícias e postagens de TI em Dublin. Queremos garantir que profissionais e entusiastas encontrem um lugar para se engajar no mercado tecnológico local, participar de meetups e se manterem informados.

### Backlog de Desenvolvimento

* **Internacionalização:** Traduzir o projeto para Inglês e Espanhol utilizando *Loco Translate* e *Polylang*.
* **Eventos:** Adicionar eventos de TI de Dublin diretamente na página inicial.
* **Carreira:** Listar vagas de TI da Irlanda na homepage.
* **Conteúdo:** Criar posts oficiais com os tópicos mais populares da comunidade.
* **Comunidade:** * Página de créditos para os contribuidores.
* Galeria de fotos dos últimos eventos.
* Página sobre a dinâmica e história do evento.


* **Automação:** Desenvolver um plugin para automatizar a geração de eventos na home.
* **QA:** Validar o processo de setup local.

### Configuração Local

Para rodar o projeto em sua máquina, siga estes passos:

1. Opcional: Inicie uma nova instalação do **WordPress** do zero ou use Docker ([Docker README](README.docker.md)).
2. Instale o plugin **WPvivid Backup Plugin**.
3. Faça o upload do arquivo de backup `.wpress` ou `.zip` gerado pelas últimas *releases* deste projeto e restaure-o através do WPvivid.

**Como criar um backup/restauração com WPvivid:**

* Abra o painel do WordPress e vá em **WPvivid Backup > Backup**.
* Clique em **Backup Now** para gerar um arquivo de backup completo (banco de dados + arquivos).
* O arquivo será salvo na pasta `wp-content/wpvividbackups` ou poderá ser baixado.

*Para restaurar*: vá em **WPvivid Backup > Restore** e escolha o arquivo gerado anteriormente, então clique em **Restore Now**. Aguarde a conclusão e faça login novamente caso seja desconectado.

5. Usuário do painel administrativo, usuário: admin, senha: admin.

**Por que contribuir?**
Dublin é um dos maiores centros de tecnologia da Europa, mas as informações costumam estar dispersas. Ao contribuir com este projeto, você ajuda milhares de desenvolvedores, designers e profissionais de tecnologia a encontrarem seu caminho na Irlanda. Não importa se você está corrigindo um bug, traduzindo conteúdo ou melhorando a interface; sua ajuda é inestimável!

---

## 🇺🇸 English (US)

### Project Goals and Objectives

The main goal of this project is to build a comprehensive portal featuring IT events, news, and blog posts specifically for the Dublin tech scene. Our mission is to provide a central hub where anyone interested in IT can find opportunities to participate in the local market and grow their network.

### Local Setup

To get the project running on your machine, follow these steps:

1. Optional: start a fresh **WordPress** installation from scratch or use Docker ([Docker README](README.docker.md)).
2. Install the **WPvivid Backup Plugin**.
3. Upload the `.wpress` or `.zip` backup file from the [latest release](https://www.google.com/search?q=link-to-releases) and restore it using WPvivid.

**How to backup/restore with WPvivid:**

* Open the WordPress dashboard and go to **WPvivid Backup > Backup**.
* Click **Backup Now** to create a full backup (database and files).
* The file will be saved in `wp-content/wpvividbackups` or can be downloaded.

*To restore*: go to **WPvivid Backup > Restore**, select the previously generated file, then click **Restore Now**. Wait for completion and log in again if you are logged out.

5. Admin panel user: user `admin` password `admin`.

---

## 🚀 Contribuir / Contributing

---

## 🇧🇷 Português (Brasil)

**Por que contribuir?**
Dublin é um dos maiores centros de tecnologia da Europa, mas as informações costumam estar dispersas. Ao contribuir com este projeto, você ajuda milhares de desenvolvedores, designers e profissionais de tecnologia a encontrarem seu caminho na Irlanda. Não importa se você está corrigindo um bug, traduzindo conteúdo ou melhorando a interface; sua ajuda é inestimável!

**Como contribuir?**

1. Faça um **Fork** do projeto.
2. Crie uma **Branch** para sua funcionalidade (`git checkout -b feature/NovaFuncionalidade`).
3. Faça o **Commit** de suas alterações (`git commit -m 'Adicionando nova funcionalidade'`).
4. Envie para o **Repo Principal** (`git push origin feature/NovaFuncionalidade`).
5. Abra um **Pull Request**.

> "Se você quer ir rápido, vá sozinho. Se você quer ir longe, vá acompanhado." 🇮🇪

---

## 🇺🇸 English (US)

**Why contribute?**
Dublin is one of the biggest tech hubs in Europe, but the information is often scattered. By contributing to this project, you are helping thousands of developers, designers, and tech professionals find their footing in Ireland. Whether you are fixing a bug, translating content, or improving the UI, your help is invaluable!

**How to contribute?**

1. **Fork** the project.
2. Create a **Branch** for your feature (`git checkout -b feature/NewFeature`).
3. **Commit** your changes (`git commit -m 'Adding a new feature'`).
4. Push to the **Main Repo** (`git push origin feature/NewFeature`).
5. Open a **Pull Request**.

> "If you want to go fast, go alone. If you want to go far, go together." 🇮🇪
