---
layout: default
title: d'antólogo
---

<div style="max-width: 700px; margin: 0 auto; font-family: Georgia, serif; line-height: 1.6;">

<p style="font-size: 1.2rem; text-align: center;">—</p>

<p>há um lampejo de respiro de algo que foge ao mundo real que atravessa a leitura de poesias. e não só poemas, como também prosas, crônicas, contos, escritos no geral que fazem esse mundo de carne e terra parecerem nada mais que lembranças de um tempo longínquo em uma terra de fantasia distinta. essa habilidade que alguns escritores têm, bem, eu não sei como se chama, mas acho muito curioso como se perder no mundo deles às vezes ajuda a nos encontrarmos no nosso — e só às vezes, mesmo.</p>

<p>acredito que quando uma letra se junta com outra letra — e um som se junta com outro som — e esse conjunto se junta a outros conjuntos parecidos — e esses sons se juntam com outros sons também — e esses maxi-conjuntos se juntam a outros maxi-conjuntos — juntando letra e som — e assim sucessivamente até formar um omni-conjunto — que é proposta e sentido —, algo mágico acontece. acredito que se embrenhar nesses emaranhados de palavras, versos, estrofes, ideias e coisas muito malucas de universos particulares é uma viagem mais alucinogênica que usar LSD chapado de maconha enquanto transa numa espaçonave rumo a Valhalla.</p>

<p>e eu digo isso só porque uma viagem lisérgico-canábica-orgástica-cósmica-nórdica é continuar na própria cabeça — mesmo que pareça que não — e ler algo que não vem de você é de fato tentar se imergir num universo que nunca será o mesmo que o seu.</p>

<p>talvez minhas palavras fatalistas possam acabar assustando a pessoa que, por curiosidade ou quaisquer que sejam seus miseráveis motivos, venha a entrar nesse blog. mas não se assuste, caro caramelo: nada do que está aqui como conteúdo de fato do que se propõe esse site fui eu que escrevi. ou seja, provavelmente estão melhor escritos do que essa introdução desnecessariamente longa.</p>

<p>eu sou apenas um organizador, um mensageiro. coloco aqui os textos de pessoas que talvez — ou não — entendam mais dessa coisa de viver do que eu. são textos que tenho na minha estante guardados e que coleciono como um pobre coitado que coleciona selos para dar um pouco de gosto à vida. e se eles tiverem um pouco difíceis de digerir, bem, nada que um whisky barato não ajude a descer. ou um doce. ou um baseado. ou um sexo com minha esposa que me traiu com meu melhor amigo — a gente já foi um trisal, mas enfim.</p>

<p>são aqui algumas coletâneas que eu mesmo procurei, organizei, cataloguei — “guei” kkk — e posto aqui junto a algumas análises que eu mesmo faço desses escritos. eventualmente eu faço umas análises de alguns outros textos de outros escritores que outras pessoas já tiveram a honra e a pressa de catalogar; até porque, se eu apenas lesse os textos desses escritores cujas antologias eu mesmo organizo, eu iria preferir me matar com uma faquinha de cortar pão.</p>

<p>esses poetas, artistas, filósofos e cientistas cujas obras disponibilizo bem arrumadinho nesse site são alguns dos meus favoritos, mas infelizmente nunca cheguei a conhecê-los. conheço, no entanto, todas suas histórias: Íris Miranda, Epifânia Estrada, Hebe Frênica, Candy Dies Irae, Santiague Ventura, Anne von Dotta e Geni Bat Papo. e sou deles apenas um fã. um admirador. um organizador. um mensageiro.</p>

<p style="text-align: center; margin-top: 2rem;">um antólogo. e esse é meu blog.</p>

<p style="text-align: center; font-size: 1.1rem;"><strong>antônio atônito</strong></p>

<hr>

<h2 style="text-align: center;">Antologias</h2>

<p style="text-align: center;">
  <a href="/d-antologo.blog/antologia/iris-miranda">Íris Miranda</a> • 
  <a href="/d-antologo.blog/antologia/epifania-estrada">Epifânia Estrada</a> • 
  <a href="/d-antologo.blog/antologia/hebe-frenica">Hebe Frênica</a> • 
  <a href="/d-antologo.blog/antologia/candy-dies-irae">Candy Dies Irae</a> • 
  <a href="/d-antologo.blog/antologia/santiague-ventura">Santiague Ventura</a> • 
  <a href="/d-antologo.blog/antologia/anne-von-dotta">Anne von Dotta</a> • 
  <a href="/d-antologo.blog/antologia/geni-bat-papo">Geni Bat Papo</a>
</p>

<hr>

<h2 style="text-align: center;">Poemas publicados</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>[{{ post.antologia | default: "Sem antologia" }}]</small>
    </li>
  {% endfor %}
</ul>

</div>
