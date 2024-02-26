## Informações gerais
* Website: https://kubernetes.io/docs
* Repositório: [kubernetes/website](https://github.com/kubernetes/website)
* Papéis dentro da comunidade: https://github.com/kubernetes/community/blob/master/community-membership.md
* Orientações sobre abertura de PR: https://kubernetes.io/docs/contribute/new-content/open-a-pr/
* Guia geral sobre contribuições (em inglês): https://www.kubernetes.dev/docs/contributor-cheatsheet/
* A documentaçãoé escrita em markdown (`.md`) e o build feito com [GoHugo](https://gohugo.io/)

## Comunicação
* Slack do k8s: https://slack.k8s.io/
* Canal de documentação ptbr no slack: `#kubernetes-docs-pt`

## Prerequisitos
* Assinar o CLA: https://github.com/kubernetes/community/blob/master/CLA.md

## Estrutura do repositório
```shell
.
├── CONTRIBUTING.md
├── Dockerfile
├── LICENSE
  ...
├── content
│   ├── en
│   ...
│   └── pt-br -> Documentação em Português aqui!
  ...

```

## Passo a passo
1. Escolher página para traduzir
2. Atribuir na planilha com o seu usuário do github
4. Fazer o fork do projeto
5. Criar a branch para tradução e traduzir
6. (opcional) build e teste na máquina local
    - quando você abre um pull request é gerado um preview no Netlify, então não necessariamente precisa executar na sua máquina
7.  Criar o pull request
8. (opcional mas recomendado) Enviar o pull request no slack


## Links importantes

1. Planilha usada para rastreio das páginas e traduções:   
[https://docs.google.com/spreadsheets/d/1HiaVFJ7nRZo1MPNNYyq1u-L_N9xrJvzuUzkZ3GuJGNU/edit#gid=1462985556](https://docs.google.com/spreadsheets/d/1HiaVFJ7nRZo1MPNNYyq1u-L_N9xrJvzuUzkZ3GuJGNU/edit#gid=1462985556)

2. Guia de contribuição:
[https://github.com/kubernetes/community/blob/master/contributors/guide/contributor-cheatsheet/README-pt.md](https://github.com/kubernetes/community/blob/master/contributors/guide/contributor-cheatsheet/README-pt.md)

3. Guia de como usar o repositório de documentação (como clonar, executar...):   
[https://github.com/kubernetes/website/blob/main/README-pt.md](https://github.com/kubernetes/website/blob/main/README-pt.md)

4. Guia de estilo para tradução/criação da documentação (atualmente, sem tradução):    
[https://kubernetes.io/docs/contribute/style/style-guide/](https://kubernetes.io/docs/contribute/style/style-guide/)

## Outras perguntas

### Qual nome devo usar na branch que vou criar?
Não se tem uma regra quanto a isso, contanto que seja algo descritivo pra você, tá valendo :)

### Qual título devo usar quando abrir o PR?
Não se tem uma regra formal sobre isso também, na issue de tracking tem uma orientação sobre algo como:    
`[Add | Update] <path do arquivo>`, mas se não usar não é problema, o bot vai cuidar de adicionar as labels referente ao português :)

### Posso abrir um PR traduzindo mais de uma página de documentação?
É preferível abrir um PR por página (em alguns casos a página tem dependências de arquivos e exemplos e tals, então faz parte da página), isso ajuda bastante quem está fazendo a revisão :)

### Tenho dúvidas nos termos, preciso abrir o PR para esperar alguém revisar?
No! pode mandar no canal do slack que alguém vai ver e vai sugerir algo, não precisa esperar só a revisão do PR depois de aberto :)

### Abri um PR mas está a semanas sem revisão, o que fazer?
É importante lembrar que as pessoas revisoras são voluntárias que fazem isso no tempo livre, então infelizmente isso pode acontecer, o que você pode fazer é, caso demore assim, mande o PR no canal do slack e pergunte se alguém pode ajudar, ou chamar diretamente a pessoa que está atribuida como revisora no slack e perguntar se ela pode dar uma força :)
