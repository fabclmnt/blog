---
title: "Cluster de Kubernetes gratuito"
summary: "KubeSail é uma plataforma que permite que você cria sua própria nuvem, contando com um plano de uso gratuito."
tagline: "Conheça o KubeSail e comece a usar hoje mesmo"
date: 2020-09-08 08:00:00
slug: kubesail-cluster-kubernetes-gratuito
authors:
  - alexandrevicenzi
categories:
  - cloud-computing
tags:
  - kubernetes
  - servicos
  - kubesail
resources:
- name: thumbnail
  src: kubesail-logo.png
- name: thumbnail-wide
  src: kubesail-logo-wide.jpeg
---

{{<figure src="thumbnail-wide" alt="KubeSail">}}

{{<alert text="O plano gratuito não está mais disponível para novos usuários." color="warning">}}

[KubeSail][kubesail] é uma plataforma que permite que você crie sua própria nuvem. Você pode usar a hospedagem gratuita ou paga, conectar seus próprios computadores ou operar nos maiores data centers do mundo, tudo pela mesma plataforma.

Reunindo o melhor da tecnologia de código aberto para que seus usuários aprendam tecnologias de mercado, sem *vendor lock-in* e ao oferecer um limite gratuito, além de permitir “Trazer o seu cluster” sem custo são alguns dos principais diferenciais.

No plano gratuito você tem direito à:

* 1 CPU Core (compartilhado)
* 512 MB de memória
* 100 MB de armazenamento
* 1 domínio customizado

*Planos dedicados começam em 7 dólares.*

Nós utilizamos o plano gratuito para nosso site de [estatísticas][stats] e o serviço tem nos atendido bem.

É relativamente fácil de usar a plataforma. Após criar uma conta você terá acesso a um dashboard similar ao do Kubernetes, mas com um pouco menos informação e mais direto ao ponto. Também é possível interagir facilmente com a plataforma através do *kubectl* (linha de comando do Kubernetes), basta configurar os dados do cluster (disponíveis [aqui][kubesail-cfg]) com o comando *kubectl config*.

O fato de ser gratuito é útil para aqueles que estão iniciando nos estudos do [Kubernetes][k8s] e talvez possa ser útil a você para algum pequeno de pequeno porte, como é o nosso caso.

[KubeSail][kubesail] ainda está em uma fase inicial e trabalhando na construção de sua plataforma, fique atento às atualizações e funcionalidades futuras.

Deixe um comentário de como você pretende utilizar o [KubeSail][kubesail], até a próxima.

[kubesail]: https://kubesail.com/?utm_source=ButecoTecnologico&utm_medium=Blog&utm_campaign=PromoPartner
[kubesail-cfg]: https://kubesail.com/config?utm_source=ButecoTecnologico&utm_medium=Blog&utm_campaign=PromoPartner
[stats]: https://estatisticas.buteco.me/
[k8s]: /tags/kubernetes/
