**Sprint 01:**  

**Exploração e Planejamento do Chatbot GoodWe**



**Nome do projeto:** AsterCharge 

**Integrantes:**  
Andrey Crence Fernandes - RM 573840 
Giulliana Maistro Brasolin - RM 569381 
Mikaella Mirela Dos Santos Lucindo - RM 573775 
Lana Namie Kano Ozeki - RM 569795 
Lara Dos Santos Cândido Alves - RM 573827 
Lucas Parkin Devito - RM 573251 

 

**Problema abordado:** 
No EV Challenge 2026, nos foi apresentado o problema de que os eletropostos ainda apresentam limitações no atendimento e suporte aos clientes, dificultando o acesso rápido a informações sobre recarga, consumo de energia, cobrança e funcionamento do sistema. A ausência de um atendimento automatizado e inteligente pode gerar uma demora na resolução de dúvidas e impactar na experiência do usuário. 

 

**Proposta do chatbot:** 
Nosso projeto propõe o desenvolvimento de um chatbot para atendimento de clientes de eletropostos comerciais ChargeGrid. A persona atendida é o usuário que utilizará os carregadores e precisa de suporte durante ou após a sessão de recarga. O sistema utilizará a inteligência artificial para responder dúvidas relacionadas à recarga, consumo de energia, tempo de carregamento, cobrança, utilização dos eletropostos e procedimentos em caso de falhas, oferecendo suporte rápido e acessível para os usuários.  



**Tecnologias selecionadas:** 
Python (Google Colab)  
OpenAI API  
RAG (Retrieval-Augmented Generation) 

 

 
**Justificativa Técnica:** 
A escolha do Python no Google Colab foi feita por ser uma ferramenta acessível e utilizada em aula para desenvolvimento de projetos com IA. A OpenAI API será utilizada para permitir que o chatbot compreenda e responda às dúvidas dos clientes de forma mais natural. Já o RAG foi escolhido para tornar as respostas mais precisas e contextualizadas com informações dos eletropostos. 

 

 
**Fluxograma:** 


<img width="637" height="707" alt="Captura de tela 2026-05-21 221227" src="https://github.com/user-attachments/assets/775a60d6-10da-4e8d-8381-088083a6d2d4" />



 


 

**Modelo teste:** 
**Pergunta 1:** Como posso iniciar uma recarga no eletroposto? 
Resposta esperada:	Para iniciar a recarga, conecte o cabo do carregador ao veículo e aguarde a conexão ser estabelecida. Em seguida, siga as instruções exibidas no painel do eletroposto. 

 

**Pergunta 2:** Quanto de energia meu veículo consumiu? 
Resposta esperada:	O sistema registra o consumo total ao longo de toda sessão de recarga, esses dados estarão disponíveis pelo aplicativo ou pelo recibo digital gerado após a finalização da sessão. 

 

**Pergunta 3:** Quanto tempo falta para concluir a recarga? 
Resposta esperada	O tempo estimado para a conclusão da recarga varia de acordo com o nível atual da bateria, a potência do carregador utilizado e a capacidade máxima do veículo. Você pode acompanhar o progresso pelo painel do eletroposto. 

 

**Pergunta 4:** Como funciona a cobrança da recarga? 
Resposta esperada	A cobrança é calculada com base no consumo de energia registrado durante a sessão de recarga. O valor é exibido ao encerrar a sessão e poderá ser pago pelo aplicativo ou pelos meios de pagamento disponíveis no painel do eletroposto. 



**Pergunta 5:** O que devo fazer se o carregador apresentar uma falha ou erro? 
Resposta esperada: Em caso de falha ou erro no carregador, interrompa a sessão e desconecte o cabo com segurança. Registre o código de erro exibido e entre em contato com o suporte. 

 

 

**System Prompt:** 
Você é um chatbot inteligente de atendimento para clientes de eletropostos de veículos elétricos. Seu objetivo é responder dúvidas relacionadas à recarga de veículos, consumo de energia, tempo de carregamento, cobrança, funcionamento dos eletropostos e suporte básico ao usuário. 
Responda de forma clara, objetiva e educada, utilizando linguagem simples e acessível. Sempre forneça informações úteis e contextualizadas ao ambiente ChargeGrid para o cliente. Quando necessário, explique termos técnicos de maneira fácil de entender. Caso a dúvida esteja fora do seu contexto de atuação, encaminhe o usuário para o canal de suporte humanizado. Nunca invente informações que não estejam disponíveis no sistema. 

 

 

  
