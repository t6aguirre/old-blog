--- 
layout: post
title: "Introdução a utilidade e preferências"
date: 2020-4-14
---

**Observação: Este texto está sob desenvolvimento.**

A ciência econômica estuda a decisão de agentes. Na tentativa de modelar o comportamento desses agentes, assume-se uma série de hipóteses simplificadores de como eles tipicamente decisões.

Quando um agente tem a opção de escolher entre duas opções, <img src="https://tex.s2cms.ru/svg/A" alt="A" /> e <img src="https://tex.s2cms.ru/svg/B" alt="B" />, e ele escolhe <img src="https://tex.s2cms.ru/svg/B" alt="B" /> em vez de <img src="https://tex.s2cms.ru/svg/A" alt="A" />, dizemos que ele prefere <img src="https://tex.s2cms.ru/svg/B" alt="B" /> a <img src="https://tex.s2cms.ru/svg/A" alt="A" />. Matematicamente, denotamos: 
<img src="https://tex.s2cms.ru/svg/%20A%20%5Cprec%20B" alt=" A \prec B" />

Caso o agente seja indiferente a ambas opções, denotamos: <img src="https://tex.s2cms.ru/svg/A%20%5Csim%20B" alt="A \sim B" />

Normalmente,  assumimos, dado quaisquer opções <img src="https://tex.s2cms.ru/svg/A" alt="A" />, <img src="https://tex.s2cms.ru/svg/B" alt="B" />, e <img src="https://tex.s2cms.ru/svg/C" alt="C" />, temos: 

* <img src="https://tex.s2cms.ru/svg/A%20%5Cprec%20B%24%20ou%20%24A%20%5Csucc%20B%24%20ou%20%24A%20%5Csim%20B" alt="A \prec B$ ou $A \succ B$ ou $A \sim B" /> (**preferências completas**) 
* Se <img src="https://tex.s2cms.ru/svg/A%20%5Cprec%20B" alt="A \prec B" /> e <img src="https://tex.s2cms.ru/svg/B%20%5Cprec%20C" alt="B \prec C" />, então <img src="https://tex.s2cms.ru/svg/A%20%5Cprec%20C" alt="A \prec C" /> (**preferências transitivas**)

Essas opções podem ser qualquer coisa: em que votar no paredão do BBB, como reagir a um assalto, ou que linguagem de programação estudar. O escopo da economia é cada vez mais amplo do que é associado tipicamente a disciplina: dinheiro, mercados, produção, e consumo. 

No entanto, inicialmente estareremos focadas em situações que as opções <img src="https://tex.s2cms.ru/svg/A" alt="A" />, <img src="https://tex.s2cms.ru/svg/B" alt="B" /> e <img src="https://tex.s2cms.ru/svg/C" alt="C" /> são diferentes produtos que um consumidos pode escolher. O conjunto dos produtos escolhidos pelo consumidor é chamado de **cesta de produtos**.

De modo abstrato, entendemos que os agentes derivam utilidade da cesta de produtos que escolhem. Assim, há uma **função utilidade**, denotada <img src="https://tex.s2cms.ru/svg/u(x)" alt="u(x)" /> que, para cada, cada cesta de produtos, atribuí a utilidade que o consumidor deriva dela. Assim, podemos dizer que:

<img src="https://tex.s2cms.ru/svg/A%20%5Cprec%20B%20%5Ciff%20u(A)%20%3C%20u(B)" alt="A \prec B \iff u(A) &lt; u(B)" />

Assumiremos aqui que a função de utilidade é positivamente inclinada. Isto é, que para cada incremento de produto <img src="https://tex.s2cms.ru/svg/%5CDelta%20X" alt="\Delta X" />, o consumidor consegue uma variação de utilidade positiva, isto é, <img src="https://tex.s2cms.ru/svg/%5CDelta%20u(X)%20%5Cge%200" alt="\Delta u(X) \ge 0" />

Por exemplo, um indíviduo sempre escolherá uma cesta de produtos que possuí mais de pelo menos um produto. Por exemplo, <img src="https://tex.s2cms.ru/svg/3" alt="3" /> latas de cerveja e <img src="https://tex.s2cms.ru/svg/5" alt="5" /> pedaços de pizza são preferíveis <img src="https://tex.s2cms.ru/svg/2" alt="2" /> lata de cerveja e <img src="https://tex.s2cms.ru/svg/3" alt="3" /> pedaços de pizza. Isso claramente não é verdade em todos os casos práticos. Indivíduos podem atingir pontos de saciedade, e podemos modelar funções de utilidade assim. No entanto, de modo introdutório, assumiremos que mais sempre é melhor para o consumidor. Isso significa que a primeira derivada da função utilidade é positiva, isto é, <img src="https://tex.s2cms.ru/svg/u'(X)%3E0" alt="u'(X)&gt;0" />. 

Outro propriedade que assumiremos das funções de utilidade é que, a cada incremento do produto <img src="https://tex.s2cms.ru/svg/%5CDelta%20X" alt="\Delta X" />, o consumidor consegue uma menor variação <img src="https://tex.s2cms.ru/svg/%5CDelta%20u(X)" alt="\Delta u(X)" />. Isso é que denominamos de **lei da utilidade marginal decrescente**. Isso significa que a segunda derivada da função utilidade é negativa, isto é, <img src="https://tex.s2cms.ru/svg/u''(X)%3C0" alt="u''(X)&lt;0" />. 

Há muitos exemplos cotidianos da lei da utilidade marginal descrescente. É muito importante para uma família uma geladeira. A segunda geladeira já tem uma importância muito menos significativa. Comprar uma terceira geladeira então seria um grande exagero para a larga maioria das famílias.  

Supomos, também, que um agente tenta maximizar a função utilidade esperada <img src="https://tex.s2cms.ru/svg/u_e(x)" alt="u_e(x)" /> ao tomar decisões. Ou seja, o agente racional atribui utilidades para diferentes cenários e também atribui probabilidades para que cada cenário ocorra, dada sua tomada de decisões. 

Assim, ao se decidir por <img src="https://tex.s2cms.ru/svg/A" alt="A" /> ou <img src="https://tex.s2cms.ru/svg/B" alt="B" />, o agente racional refletiria: "Caso eu decida <img src="https://tex.s2cms.ru/svg/A" alt="A" />, os cenários <img src="https://tex.s2cms.ru/svg/A_1" alt="A_1" /> e <img src="https://tex.s2cms.ru/svg/A_2" alt="A_2" /> podem acontecer, com probablidade <img src="https://tex.s2cms.ru/svg/p(A_1)" alt="p(A_1)" /> e <img src="https://tex.s2cms.ru/svg/p(A_2)" alt="p(A_2)" /> e utilidades <img src="https://tex.s2cms.ru/svg/u(A_1)" alt="u(A_1)" /> e <img src="https://tex.s2cms.ru/svg/u(A_1)" alt="u(A_1)" />. Logo, a minha utilidade esperada é de <img src="https://tex.s2cms.ru/svg/u_e(A)%20%3D%20p(A_1)*u(A_1)%20%2B%20p(A_2)*u(A_2)" alt="u_e(A) = p(A_1)*u(A_1) + p(A_2)*u(A_2)" />. De modo análogo, <img src="https://tex.s2cms.ru/svg/u_e(B)%20%3D%20p(B_1)*u(B_1)%20%2B%20p(B_2)*u(B_2)" alt="u_e(B) = p(B_1)*u(B_1) + p(B_2)*u(B_2)" />. Como eu observo que <img src="https://tex.s2cms.ru/svg/u_e(A)%20%3C%20u_e(B)%20" alt="u_e(A) &lt; u_e(B) " />, então <img src="https://tex.s2cms.ru/svg/A%20%5Cprec%20B" alt="A \prec B" />."

Portanto, um **agente racional** tem preferências completas, transitivas e que maximizam a utilidade esperada.
