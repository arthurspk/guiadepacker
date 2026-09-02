<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="./images/guia.png" alt="Guia Dev Brasil" width="160" height="160">
  </a>
  <h1 align="center">Guia de Packer</h1>
</p>

## :dart: O guia para alavancar a sua carreira

> Packer é a ferramenta da HashiCorp para criar imagens de máquina idênticas e reproduzíveis a partir de um único template declarativo (HCL): a mesma definição gera uma AMI na AWS, uma imagem no Azure, no Google Cloud, um container Docker ou uma imagem local em VirtualBox/QEMU, todas com o mesmo conjunto de pacotes e configurações. Este guia reúne roadmap, documentação oficial, cursos, canais, ferramentas do ecossistema (builders, provisioners e plugins), projetos práticos e comunidades sobre Packer, com prioridade para conteúdo gratuito e em português. Serve tanto para quem nunca criou uma "imagem golden" quanto para quem já usa Terraform e quer eliminar configuração manual de servidor, adotando infraestrutura verdadeiramente imutável. Todo link foi verificado na data da última revisão — guarde nos favoritos e volte sempre que precisar de uma trilha confiável.

<sub> <strong>Siga nas redes sociais para acompanhar mais conteúdos: </strong> <br>
[<img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">](https://github.com/arthurspk)
[<img src = "https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white">](https://www.facebook.com/seixasqlc/)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/arthurspk/)
[<img src = "https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white">](https://twitter.com/manotoquinho)
[![Discord Badge](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/NbMQUPjHz7)
[<img src = "https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/guiadevbrasil/)
[![Youtube Badge](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCzmXzz_VR0Li8-YOvWN_t3g)
</sub>

## ⚠️ Aviso importante

> Antes de tudo você pode me ajudar e colaborar, deu bastante trabalho fazer esse repositório e organizar para fazer seu estudo ou trabalho melhor, portanto você pode me ajudar das seguintes maneiras:

- Me siga no [Github](https://github.com/arthurspk)
- Acesse as redes sociais do [Guia Dev Brasil](https://linktr.ee/guiadevbrasil)
- Mande feedbacks no [LinkedIn](https://www.linkedin.com/in/arthurspk/)

## 💡 Nossa proposta

> A proposta deste guia é dar uma ideia sobre o atual panorama e guiá-lo se você estiver confuso sobre qual será o seu próximo aprendizado, sem influenciar você a seguir os 'hypes' e 'trends' do momento. Acreditamos que com um maior conhecimento das diferentes estruturas e soluções disponíveis poderá escolher a ferramenta que melhor se aplica às suas demandas. E lembre-se, 'hypes' e 'trends' nem sempre são as melhores opções.

## :beginner: Para quem está começando agora

> Não se assuste com a quantidade de conteúdo apresentado neste guia. Acredito que quem está começando pode usá-lo não como um objetivo, mas como um apoio para os estudos. <b>Neste momento, dê enfoque no que te dá produtividade e o restante marque como <i>Ver depois</i></b>. Ao passo que seu conhecimento se torna mais amplo, a tendência é este guia fazer mais sentido e ficar fácil de ser assimilado. Bons estudos e entre em contato sempre que quiser! :punch:

## 🚨 Colabore

- Abra Pull Requests com atualizações
- Discuta ideias em Issues
- Compartilhe o repositório com a sua comunidade

## 🌍 Tradução

> Se você deseja acompanhar esse repositório em outro idioma que não seja o Português Brasileiro, você pode optar pelas escolhas de idiomas abaixo, você também pode colaborar com a tradução para outros idiomas e a correções de possíveis erros ortográficos, a comunidade agradece.

<img src = "https://i.imgur.com/lpP9V2p.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>English — </b> [Click Here](https://github.com/arthurspk/guiadepacker)<br>
<img src = "https://i.imgur.com/GprSvJe.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Spanish — </b> [Click Here](https://github.com/arthurspk/guiadepacker)<br>
<img src = "https://i.imgur.com/4DX1q8l.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Chinese — </b> [Click Here](https://github.com/arthurspk/guiadepacker)<br>
<img src = "https://i.imgur.com/6MnAOMg.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Hindi — </b> [Click Here](https://github.com/arthurspk/guiadepacker)<br>
<img src = "https://i.imgur.com/8t4zBFd.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Arabic — </b> [Click Here](https://github.com/arthurspk/guiadepacker)<br>
<img src = "https://i.imgur.com/iOdzTmD.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>French — </b> [Click Here](https://github.com/arthurspk/guiadepacker)<br>
<img src = "https://i.imgur.com/PILSgAO.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Italian — </b> [Click Here](https://github.com/arthurspk/guiadepacker)<br>
<img src = "https://i.imgur.com/0lZOSiy.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Korean — </b> [Click Here](https://github.com/arthurspk/guiadepacker)<br>
<img src = "https://i.imgur.com/3S5pFlQ.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Russian — </b> [Click Here](https://github.com/arthurspk/guiadepacker)<br>
<img src = "https://i.imgur.com/i6DQjZa.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>German — </b> [Click Here](https://github.com/arthurspk/guiadepacker)<br>
<img src = "https://i.imgur.com/wWRZMNK.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Japanese — </b> [Click Here](https://github.com/arthurspk/guiadepacker)<br>

## 📚 ÍNDICE

[🗺️ Roadmap](#️-roadmap) <br>
[🚀 Por onde começar](#-por-onde-começar) <br>
[📖 Documentação oficial](#-documentação-oficial) <br>
[🔤 Sites e cursos para aprender Packer](#-sites-e-cursos-para-aprender-packer) <br>
[🎥 Canais no Youtube](#-canais-no-youtube) <br>
[📰 Sites, blogs e newsletters](#-sites-blogs-e-newsletters) <br>
[🛠️ Ferramentas](#️-ferramentas) <br>
[🧪 Projetos práticos e desafios](#-projetos-práticos-e-desafios) <br>
[🤖 IA na prática](#-ia-na-prática) <br>
[💼 Carreira e vagas](#-carreira-e-vagas) <br>
[👥 Comunidades](#-comunidades) <br>

## 🗺️ Roadmap
- [Introduction to Packer (oficial, HashiCorp)](https://developer.hashicorp.com/packer/docs/intro) — Página oficial de introdução: o que é Packer, o problema das "imagens douradas" que ele resolve e como se compara a scripts manuais de provisionamento.
- [HashiCorp Well-Architected Framework](https://developer.hashicorp.com/well-architected-framework) — Framework oficial de boas práticas de infraestrutura, incluindo o papel de imagens imutáveis construídas com Packer.
- [roadmap.sh — DevOps](https://roadmap.sh/devops) — Roadmap de DevOps da comunidade, que inclui Packer entre as ferramentas de automação de imagens e infraestrutura.

**Trilha resumida** (siga na ordem; cada etapa tem recursos nas seções abaixo):

1. **Fundamentos de imagens imutáveis** — por que "assar" uma imagem já provisionada é mais confiável do que configurar um servidor manualmente toda vez que ele sobe.
2. **Instalação e primeiro `packer build`** — instalar o CLI e gerar sua primeira imagem local (Docker ou VirtualBox), sem precisar de conta em nuvem.
3. **Linguagem HCL do Packer** — blocos `packer`, `source`, `build`, `variable` e a diferença para o antigo formato JSON.
4. **Provisioners** — instalar pacotes e configurar a imagem com shell, Ansible, PowerShell ou outros provisioners oficiais.
5. **Builders de nuvem** — gerar AMIs na AWS, imagens no Azure e no Google Cloud a partir do mesmo template.
6. **Post-processors e manifesto** — comprimir, taguear e registrar a saída do build para uso em pipelines de CI/CD.
7. **HCP Packer** — publicar, versionar e revogar "imagens golden" em um registro central, integrando com Terraform.
8. **Avançado** — múltiplas plataformas em paralelo, plugins próprios com o Packer Plugin SDK e integração completa em pipeline de CI/CD.

## 🚀 Por onde começar
1. **Instale o Packer** pelo [guia oficial de instalação](https://developer.hashicorp.com/packer/install) (Homebrew, apt ou binário direto) e confira com `packer version`.
2. **Instale a extensão oficial de HCL no VS Code** — [HashiCorp HCL (Marketplace)](https://marketplace.visualstudio.com/items?itemName=hashicorp.HCL) — para ter autocomplete e validação nos arquivos `.pkr.hcl`.
3. **Siga o tutorial oficial "Get Started: Docker"**, que não exige conta em nuvem: [instalar o CLI](https://developer.hashicorp.com/packer/tutorials/docker-get-started/get-started-install-cli), [construir sua primeira imagem](https://developer.hashicorp.com/packer/tutorials/docker-get-started/docker-get-started-build-image) e [provisioná-la com shell](https://developer.hashicorp.com/packer/tutorials/docker-get-started/docker-get-started-provision).
4. **Entenda a linguagem HCL do Packer** — [tutorial oficial sobre configuration language](https://developer.hashicorp.com/packer/tutorials/configuration-language) explica os blocos `source` e `build` com exemplos.
5. **Quando quiser ir para a nuvem**, siga o [tutorial oficial "Get Started: AWS"](https://developer.hashicorp.com/packer/tutorials/aws-get-started) e gere sua primeira AMI de verdade.
6. **Leia a referência de templates HCL** — [Documentação de templates](https://developer.hashicorp.com/packer/docs/templates/hcl_templates) cobre `source`, `variable`, `build` e funções built-in.
7. **Valide antes de rodar `build`:** use `packer validate` para pegar erros de sintaxe cedo, e `packer fmt` para manter o template formatado.
8. **Pratique em um repositório real:** o [learn-packer-getting-started (HashiCorp)](https://github.com/hashicorp-education/learn-packer-getting-started) ensina a estruturar um template do zero.

Seu primeiro projeto em 60 segundos:

```bash
packer version                     # confirme a instalação
mkdir ola-packer && cd ola-packer
```

```hcl
# ola.pkr.hcl
packer {
  required_plugins {
    docker = {
      source  = "github.com/hashicorp/docker"
      version = "~> 1"
    }
  }
}

source "docker" "ola" {
  image  = "alpine"
  commit = true
}

build {
  sources = ["source.docker.ola"]

  provisioner "shell" {
    inline = ["echo 'Olá, Guia Dev Brasil!' > /ola.txt"]
  }
}
```

```bash
packer init ola.pkr.hcl            # baixa o plugin declarado (docker)
packer validate ola.pkr.hcl        # confere erros de sintaxe, sem rodar nada
packer build ola.pkr.hcl           # gera a imagem de verdade
```

## 📖 Documentação oficial
- [Packer (página oficial)](https://developer.hashicorp.com/packer) — Ponto de entrada da documentação: intro, linguagem, CLI, integrações e HCP Packer.
- [Packer Docs (índice)](https://developer.hashicorp.com/packer/docs) — Índice completo de toda a documentação técnica do produto.
- [Templates HCL — referência](https://developer.hashicorp.com/packer/docs/templates/hcl_templates) — Referência completa da sintaxe de templates em HCL, o formato atual (substituto do antigo JSON).
- [Bloco `source`](https://developer.hashicorp.com/packer/docs/templates/hcl_templates/blocks/source) — Referência do bloco que define o builder e os parâmetros da imagem a construir.
- [Bloco `build`](https://developer.hashicorp.com/packer/docs/templates/hcl_templates/blocks/build) — Referência do bloco que orquestra provisioners e post-processors sobre um ou mais `source`.
- [Variáveis de entrada](https://developer.hashicorp.com/packer/docs/templates/hcl_templates/variables) — Como declarar, tipar e passar variáveis para um template.
- [Funções incorporadas](https://developer.hashicorp.com/packer/docs/templates/hcl_templates/functions) — Todas as funções built-in disponíveis no HCL do Packer.
- [Packer CLI — comandos](https://developer.hashicorp.com/packer/docs/commands) — Referência completa dos comandos: `build`, `init`, `validate`, `fmt`, `console`.
- [Comando `packer build`](https://developer.hashicorp.com/packer/docs/commands/build) — Referência do comando que executa a build a partir do template.
- [Comando `packer init`](https://developer.hashicorp.com/packer/docs/commands/init) — Referência do comando que baixa os plugins declarados no bloco `required_plugins`.
- [Comando `packer validate`](https://developer.hashicorp.com/packer/docs/commands/validate) — Referência do comando que valida a sintaxe do template sem executar a build.
- [Provisioners — índice](https://developer.hashicorp.com/packer/docs/provisioners) — Índice de todos os provisioners oficiais (shell, Ansible, PowerShell, file e outros).
- [Provisioner shell](https://developer.hashicorp.com/packer/docs/provisioners/shell) — Referência do provisioner mais usado para instalar pacotes e rodar comandos na imagem.
- [Provisioner file](https://developer.hashicorp.com/packer/docs/provisioners/file) — Referência do provisioner que copia arquivos do host para dentro da imagem em construção.
- [Provisioner PowerShell](https://developer.hashicorp.com/packer/docs/provisioners/powershell) — Referência do provisioner usado em imagens Windows.
- [Post-processors — índice](https://developer.hashicorp.com/packer/docs/post-processors) — Índice dos post-processors oficiais, que rodam depois da build (compactar, taguear, gerar manifesto).
- [Post-processor manifest](https://developer.hashicorp.com/packer/docs/post-processors/manifest) — Referência do post-processor que grava um JSON com o resultado da build, útil em pipelines de CI/CD.
- [Bloco `hcp_packer_registry`](https://developer.hashicorp.com/packer/docs/templates/hcl_templates/blocks/build/hcp_packer_registry) — Referência do bloco que publica metadados da imagem no registro HCP Packer.
- [HCP Packer — documentação](https://developer.hashicorp.com/hcp/docs/packer) — Documentação do registro gerenciado de imagens golden da HashiCorp: buckets, canais, versões.
- [HCP Packer — gerenciar o registro](https://developer.hashicorp.com/hcp/docs/packer/manage-registry) — Como organizar buckets, canais e versões de imagem no registro.
- [HCP Packer — revogar e restaurar versões](https://developer.hashicorp.com/hcp/docs/packer/manage/revoke-restore) — Documentação oficial sobre marcar uma versão de imagem como revogada (e restaurá-la, se preciso).
- [Integrações (plugins)](https://developer.hashicorp.com/packer/integrations) — Índice de todas as integrações oficiais e de parceiros do Packer: builders, provisioners e post-processors.
- [hashicorp/packer (código-fonte)](https://github.com/hashicorp/packer) — Repositório oficial do núcleo do Packer no GitHub, com changelog e issues.
- [packer.io](https://www.packer.io/) — Domínio curto oficial do produto (redireciona para a documentação).

## 🔤 Sites e cursos para aprender Packer

> Cursos para aprender Packer em Português

- [Toma que o filho é teu: reduzindo toil e mudando cultura com Packer](https://www.youtube.com/watch?v=TWhiTD_tDDU) — Palestra oficial da HashiCorp em português sobre adoção de Packer em produção e a cultura em torno de imagens imutáveis.
- [Packer — Automatizando a criação de imagens de máquina (Cloud Treinamentos)](https://www.youtube.com/watch?v=gt4rpH6y0PI) — Vídeo em português explicando o fluxo completo de criação de uma imagem com Packer.
- [Packer Tutorials (oficial, HashiCorp)](https://developer.hashicorp.com/packer/tutorials) — Trilha oficial e gratuita de tutoriais interativos, em inglês mas com editor embutido no navegador — não exige instalação local para acompanhar.

> Cursos para aprender Packer em Inglês

- [Get Started: Docker (oficial, HashiCorp)](https://developer.hashicorp.com/packer/tutorials/docker-get-started) — Tutorial oficial e gratuito, do primeiro `packer build` à publicação de imagens Docker.
- [Get Started: AWS (oficial, HashiCorp)](https://developer.hashicorp.com/packer/tutorials/aws-get-started) — Tutorial oficial e gratuito para criar e usar sua primeira AMI da AWS.
- [HashiCorp Packer Tutorial: Building Custom Images for AWS, Azure, and Docker (KodeKloud)](https://www.youtube.com/watch?v=OmQRpi3CSjU) — Curso introdutório gratuito em vídeo, cobrindo os três principais builders de nuvem.
- [HashiCorp Packer Crash Course: Master AWS AMI Creation in 30 Mins](https://www.youtube.com/watch?v=uNuXAXvSjAc) — Curso rápido e gratuito focado especificamente em gerar AMIs da AWS.

## 🎥 Canais no Youtube
### Em português
- [Cloud Treinamentos](https://www.youtube.com/@CloudTreinamentos) — Canal brasileiro de treinamentos em nuvem e DevOps, com vídeo dedicado a Packer e outros conteúdos de automação de infraestrutura.
- [LINUXtips](https://www.youtube.com/@linuxtips) — Um dos maiores canais brasileiros de Linux, DevOps e Cloud, com conteúdo sobre a stack HashiCorp e Infraestrutura como Código.
- [Código Fonte TV](https://www.youtube.com/@codigofontetv) — Canal brasileiro que explica ferramentas de infraestrutura e nuvem de forma didática e visual.

### Em inglês
- [HashiCorp](https://www.youtube.com/@HashiCorp) — Canal oficial da empresa criadora do Packer: palestras da HashiConf, demos de produto e tutoriais oficiais.
- [KodeKloud](https://www.youtube.com/@KodeKloud) — Canal da plataforma de labs práticos, com cursos completos gratuitos sobre Packer, Terraform e certificações DevOps.
- [TechWorld with Nana](https://www.youtube.com/@TechWorldwithNana) — Uma das referências mundiais em DevOps no YouTube, com conteúdo didático sobre Infraestrutura como Código e imagens de máquina.

## 📰 Sites, blogs e newsletters
- [Terraform Weekly (weekly.tf)](https://www.weekly.tf/) — Newsletter semanal e gratuita sobre o ecossistema HashiCorp (Terraform, Packer, Vault), com curadoria de artigos e novidades.
- [Spacelift Blog](https://spacelift.io/blog) — Blog com artigos técnicos frequentes sobre Packer, Terraform e boas práticas de Infraestrutura como Código.
- [dev.to — tag Packer](https://dev.to/t/packer) — Artigos da comunidade DEV sobre Packer, de iniciante a avançado.

## 🛠️ Ferramentas
### Núcleo
- [Packer CLI](https://developer.hashicorp.com/packer/docs/commands) — A ferramenta de linha de comando oficial: `init`, `build`, `validate`, `fmt`, `console`.
- [setup-packer (GitHub Action)](https://github.com/hashicorp/setup-packer) — Action oficial para instalar e rodar o Packer em pipelines de CI/CD no GitHub Actions.
- [HCP Packer](https://developer.hashicorp.com/hcp/docs/packer) — Registro gerenciado de imagens golden com versionamento, canais e revogação — tem camada gratuita.
- [Packer Plugin SDK](https://github.com/hashicorp/packer-plugin-sdk) — SDK oficial para desenvolver plugins próprios (builders, provisioners, post-processors).

### Builders (plugins de plataforma) oficiais
- [packer-plugin-amazon](https://github.com/hashicorp/packer-plugin-amazon) — Plugin oficial para construir AMIs na AWS.
- [packer-plugin-azure](https://github.com/hashicorp/packer-plugin-azure) — Plugin oficial para construir imagens no Microsoft Azure.
- [packer-plugin-googlecompute](https://github.com/hashicorp/packer-plugin-googlecompute) — Plugin oficial para construir imagens no Google Compute Engine.
- [packer-plugin-docker](https://github.com/hashicorp/packer-plugin-docker) — Plugin oficial para construir imagens Docker, ideal para praticar sem conta em nuvem.
- [packer-plugin-virtualbox](https://github.com/hashicorp/packer-plugin-virtualbox) — Plugin oficial para construir imagens VirtualBox (OVF/OVA), ótimo para uso local.
- [packer-plugin-vagrant](https://github.com/hashicorp/packer-plugin-vagrant) — Plugin oficial para gerar boxes do Vagrant a partir de uma build do Packer.
- [packer-plugin-qemu](https://github.com/hashicorp/packer-plugin-qemu) — Plugin oficial para construir imagens QEMU/KVM.
- [packer-plugin-hyperv](https://github.com/hashicorp/packer-plugin-hyperv) — Plugin oficial para construir imagens Hyper-V (Windows).
- [packer-plugin-openstack](https://github.com/hashicorp/packer-plugin-openstack) — Plugin oficial para construir imagens no OpenStack.
- [packer-plugin-proxmox](https://github.com/hashicorp/packer-plugin-proxmox) — Plugin oficial para construir imagens no Proxmox VE.
- [packer-plugin-vmware (VMware)](https://github.com/vmware/packer-plugin-vmware) — Plugin mantido pela VMware para construir imagens VMware (Workstation, Fusion, vSphere).
- [packer-plugin-parallels](https://github.com/hashicorp/packer-plugin-parallels) — Plugin oficial para construir imagens Parallels Desktop (macOS).

### Provisioners e integrações
- [packer-plugin-ansible](https://github.com/hashicorp/packer-plugin-ansible) — Plugin oficial que integra o Ansible como provisioner do Packer.
- [Provisioner Ansible — documentação](https://developer.hashicorp.com/packer/integrations/hashicorp/ansible/latest/components/provisioner/ansible) — Documentação oficial de como rodar playbooks Ansible durante a build da imagem.

### Ecossistema comunitário
- [awesome-packer](https://github.com/dchonch/awesome-packer) — Lista curada (awesome list) de recursos sobre Packer: plugins, exemplos e artigos, mantida pela comunidade.
- [HashiCorp Cloud Guide](https://github.com/mikeroyal/HashiCorp-Cloud-Guide) — Guia curado sobre toda a stack HashiCorp (Terraform, Packer, Vault, Consul, Nomad), com links para aprendizado e ferramentas.

## 🧪 Projetos práticos e desafios
- [learn-packer-getting-started (HashiCorp)](https://github.com/hashicorp-education/learn-packer-getting-started) — Repositório oficial de exercício: primeiros passos criando templates HCL do zero.
- [learn-packer-multicloud (HashiCorp)](https://github.com/hashicorp-education/learn-packer-multicloud) — Projeto guiado oficial: um único template Packer publicando a mesma imagem em múltiplos provedores de nuvem.
- [learn-packer-windows-ami (HashiCorp)](https://github.com/hashicorp-education/learn-packer-windows-ami) — Projeto guiado oficial: construir uma AMI Windows na AWS com Packer.
- [learn-packer-github-actions (HashiCorp)](https://github.com/hashicorp-education/learn-packer-github-actions) — Projeto guiado oficial: automatizar builds do Packer em um pipeline de GitHub Actions.
- [learn-hcp-packer-get-started (HashiCorp)](https://github.com/hashicorp-education/learn-hcp-packer-get-started) — Projeto guiado oficial: publicar sua primeira imagem no registro HCP Packer.
- [learn-packer-hcp-golden-image (HashiCorp)](https://github.com/hashicorp-education/learn-packer-hcp-golden-image) — Projeto guiado oficial: construir um pipeline completo de "imagem golden" com HCP Packer.
- [learn-hcp-packer-run-tasks (HashiCorp)](https://github.com/hashicorp-education/learn-hcp-packer-run-tasks) — Projeto guiado oficial: usar Run Tasks do HCP Packer para validar imagens antes da promoção.
- [learn-hcp-packer-revocation (HashiCorp)](https://github.com/hashicorp-education/learn-hcp-packer-revocation) — Projeto guiado oficial: revogar e restaurar versões de imagem no HCP Packer.
- [learn-packer-upgrade-json-template (HashiCorp)](https://github.com/hashicorp-education/learn-packer-upgrade-json-template) — Projeto guiado oficial: migrar um template legado em JSON para a sintaxe HCL atual.

## 🤖 IA na prática
Packer é declarativo (HCL, como o Terraform) e cada builder/provisioner tem seu próprio conjunto de argumentos versionado — é aí que a IA generativa mais erra: ela é ótima para gerar o esqueleto de um template, mas pode "inventar" um argumento que não existe na versão do plugin que você está usando.

**Para aprender**
- Peça para a IA **explicar a diferença entre um builder, um provisioner e um post-processor** com um exemplo do seu próprio template `.pkr.hcl`, e por que a imagem gerada é imutável (não se corrige uma imagem publicada, gera-se uma nova versão).
- Cole um erro de `packer build` (ex.: `Error: Unsupported argument` ou falha de conexão SSH/WinRM durante o provisionamento) e peça a causa raiz — mas sempre confira com `packer validate` antes de rodar de novo.
- Peça para a IA gerar um template simples (ex.: uma imagem Docker com um pacote instalado) e depois pergunte "quais argumentos desse builder você tem certeza que existem na versão atual do plugin, e quais está assumindo?" — isso expõe alucinações antes de você gastar tempo de build.
- Use a IA para transformar um template antigo em JSON no formato HCL atual, e compare o resultado com o guiado oficial [learn-packer-upgrade-json-template](https://github.com/hashicorp-education/learn-packer-upgrade-json-template).

**Para trabalhar**
- Use [GitHub Copilot](https://github.com/features/copilot), [Cursor](https://cursor.com/) ou [Claude Code](https://code.claude.com/docs/en/overview) para escrever blocos `source`/`build`, scripts de provisionamento shell/Ansible e a documentação de um template.
- O [terraform-mcp-server](https://github.com/hashicorp/terraform-mcp-server), oficial da HashiCorp, dá a agentes de IA acesso direto e atualizado ao Registry e à documentação de providers via Model Context Protocol — útil também quando seu fluxo combina Packer (para gerar a imagem) com Terraform (para provisionar a instância a partir dela), reduzindo a alucinação de argumentos porque o agente consulta o schema real.
- Depois de **qualquer** sugestão aceita, rode `packer validate` e `packer fmt`, e leia a saída do `packer build` linha por linha — principalmente os passos de provisionamento, que rodam comandos de verdade dentro da imagem.

**Limites e boas práticas**
- IA **inventa argumentos e blocos** de builders e plugins com frequência, principalmente em plugins de terceiros ou pouco documentados. Confirme sempre nas [Integrações oficiais](https://developer.hashicorp.com/packer/integrations) a versão exata do plugin que você está usando.
- **Nunca cole credenciais de nuvem** (chaves de acesso da AWS, service principal do Azure) em uma ferramenta de IA — mesmo em um `.pkr.hcl` de exemplo ou em um arquivo de variáveis.
- Nunca deixe um agente de IA rodar `packer build` sozinho e sem revisão contra um builder de produção; trate a saída do provisionamento como um log que você sempre audita antes de publicar a imagem no HCP Packer.
- Prefira sugestões que sigam os padrões do [HashiCorp Well-Architected Framework](https://developer.hashicorp.com/well-architected-framework) em vez de aceitar o primeiro template gerado sem questionar segurança (ex.: segredos gravados na imagem) e tamanho final da imagem.

## 💼 Carreira e vagas
Packer aparece com frequência em vagas de DevOps, SRE e Platform Engineering que praticam infraestrutura imutável, quase sempre ao lado de Terraform na mesma stack — é comum a vaga pedir "HashiCorp stack" (Terraform + Packer + Vault) em vez de citar cada ferramenta isoladamente.
- [Working Nomads — vagas de Infraestrutura como Código](https://www.workingnomads.com/remote-terraform-jobs) — Agregador de vagas remotas internacionais com filtro de IaC, onde Packer aparece como parte da stack.
- [DevOps-Brasil/Vagas](https://github.com/DevOps-Brasil/Vagas) — Vagas de DevOps/SRE publicadas como issues no GitHub, onde a stack HashiCorp é um dos requisitos comuns.
- [Programathor — vagas de tecnologia](https://programathor.com.br/) — Quadro de vagas de tecnologia no Brasil, incluindo DevOps e Infraestrutura.
- [Coodesh](https://coodesh.com/) — Vagas tech no Brasil com processos seletivos padronizados, incluindo DevOps e Cloud.
- [GeekHunter](https://www.geekhunter.com.br/) — Plataforma brasileira onde empresas fazem propostas a profissionais de tecnologia.

## 👥 Comunidades
- [HashiCorp Discuss — Packer](https://discuss.hashicorp.com/c/packer/33) — Fórum oficial da HashiCorp, categoria específica de Packer, para dúvidas e discussões técnicas.
- [HashiCorp Discuss](https://discuss.hashicorp.com/) — Fórum oficial de toda a stack HashiCorp (Terraform, Vault, Consul, Nomad, Packer).
- [r/hashicorp](https://www.reddit.com/r/hashicorp/) — Subreddit dedicado à stack HashiCorp, incluindo Packer.
- [r/devops](https://www.reddit.com/r/devops/) — Subreddit geral de DevOps, com discussões frequentes sobre Packer e imagens imutáveis.
- [DevOps Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — Comunidade brasileira de DevOps com canais sobre Infraestrutura como Código.
- [He4rt Developers](https://heartdevs.com/) — Comunidade brasileira open source com Discord ativo, incluindo canais de infraestrutura e Cloud.

## 🚨 Como contribuir
Achou um link quebrado, um curso novo ou uma ferramenta que merece estar aqui? Abra uma issue usando os templates do repositório ou envie um pull request. Critérios: link funcionando, conteúdo legal e gratuito ou claramente marcado como pago, com uma linha de descrição. Detalhes em [CONTRIBUTING.md](./CONTRIBUTING.md).

## 📄 Licença
Este projeto está sob a licença [MIT](./LICENSE). Feito com 💙 por [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) e pela comunidade do [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil).

## 💙 Apoie o projeto
Dê uma ⭐ neste repositório e no [guia principal](https://github.com/arthurspk/guiadevbrasil), compartilhe com quem está começando e siga o projeto nas redes:

[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/arthurspk/)
[<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">](https://x.com/manotoquinho)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">](https://www.instagram.com/arthurspk/)
[<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">](https://www.facebook.com/seixasqlc/)
