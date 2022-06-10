# Desafio Desenvolvedor Front-End

Chegou a hora do desafio! 
Neste desafio você deverá **desenvolver uma página Web para apresentar um produto digital**.

## Instruções
Desenvolva uma página Web (landing page), responsiva, para apresentar uma API que utiliza Inteligência Artificial para conversão e interpretação de falas.

### O produto

#### Nome
CheckSpeech AI

#### Breve descrição
O CheckSpeech AI é um conjunto de APIs de conversão de fala em textos, bem como a interpretação do sentimento dominante nos dizeres. Nossa solução é treinada em mais de 500.000 horas de áudios, transcritos por humanos de uma ampla variedade de idades, nacionalidades, sotaques e níveis de instruções A API é comercializada no modelo SAAS (software as a service).

#### Soluções
Nosso produto é composto pelas seguintes soluções:
* Transcrição de Áudio Assíncrono (áudio pré-gravado):
API de transcrição de voz assíncrona para áudio pré-gravado. Temos uma das melhores engines de reconhecimento de fala do mundo! O recurso speech-to-text assíncrono é um parceiro estratégico para o seu negócio. Esteja você extraindo insights de áudio ou transcrevendo conteúdo em escala.

* Transcrição de Áudio em tempo real (streaming):
O recurso live-speech-to-text de transcrição ao vivo possibilita o uso de legendas em tempo real para o seu negócio. Nossas legendas garantem que as palestras e treinamentos ao vivo sejam acessíveis e possam ser arquivadas para uso futuro.

* Identificação de Idiomas em áudios:
Obtendo fala e insights a nível global. Nossa solução tem suporte a 52 idiomas.

* Análise de sentimento a partir do áudio (áudio pré-gravado):
Encontre os momentos mais importantes em trechos de falas, diferencie falas positivas e negativas e tome decisões de negócios mais assertivas com uma compreensão mais profunda.

#### Seções sugeridas
Para a página de apresentação do CheckSpeech AI, sugerimos as seguintes seções:

1. Top menu contendo os links abaixo, que direcionam o utilizador para as respectivas seções na mesma página:
  - Logo (que direciona para a mesma página)
  - Soluções
  - Clientes
  - Preços
  - Contato

2. Seção inicial que traz uma breve apresentação do produto… Use sua criatividade e atraia a atenção do utilizador com o uso de imagens,  infográficos e/ou vídeos.

3. Clientes: mostre quem já utiliza a solução! Utilize logos fictícias que podem ser encontradas em sites como: [logotouse.com](https://logotouse.com/), [freepik.com](https://freepik.com/) e [vecteezy.com](https://vecteezy.com/). 

4. Soluções: apresente de forma objetiva os principais recursos do produto.

5. Preços: apresente os preços de venda da solução, organizadas em três tipos de pacote, de forma tabelada: 
  - Beginner: R$29 por mês ou R$328 para uma compra anual.
    - Transcrição de Áudio Assíncrono  - 120 minutos (R$0,20 / minuto excedente)
    - Transcrição de Áudio em tempo real  - 90 minutos (R$0,40 / minuto excedente)
    - Identificação de Idiomas em áudios - 200 minutos (R$0,05 / minuto excedente)
    - Análise de sentimento a partir do áudio (áudio pré-gravado) - 120 minutos (R$0,40 / minuto excedente)
  - Business: R$44 por mês ou R$499 para uma compra anual.
    - Transcrição de Áudio Assíncrono - 200 minutos (R$0,15 / minuto excedente)
    - Transcrição de Áudio em tempo real  - 120 minutos (R$0,40 / minuto excedente)
    - Identificação de Idiomas em áudios - 500 minutos (R$0,03 / minuto excedente)
    - Análise de sentimento a partir do áudio (áudio pré-gravado) - 200 minutos (R$0,35 / minuto excedente)
  - Enterprise: preço sob consulta. Link para form de contato.
    - Preços especiais para grandes volumes.
    - Prioridade no suporte técnico.
    - Gestor de conta dedicado.

6. Form de contato contendo os campos devidamente tratados (obrigatoriedades, máscaras, validações): 
  - Nome*
  - E-mail*
  - Telefone (que permita a inserção de telefones nacionais e internacionais)
  - Combo de país*
  - Mensagem
  - Check ou radio button de consentimento relacionado à LGPD*, com o texto “Eu concordo com a Política de Privacidade.” A pessoa só deve conseguir enviar o form preenchido caso selecione este item
  - Captcha* (a sua escolha)
  - Botão enviar

7. Footer: contendo copyright, os mesmos menus do top menu, ícones para redes sociais (pode colocar o link para a área de login de cada rede).

### Itens obrigatórios
* Desenvolver no mínimo 5 das 7 seções sugeridas no item anterior.
* Barra de consentimento de cookies.
* Componente dinâmico, no mínimo em uma seção, como por exemplo um slider, accordion, rotate, sticky.  
* Dois botões (CTA), em diferentes locais da página, que direcione para um form de contato no final da página (acima do footer).
* Form de contato.

### Itens desejáveis (bônus)
* Multilíngue: Página multi idiomas com componente que permita ao utilizador selecionar o idioma desejado, e que consequentemente os componentes e conteúdos da página sejam devidamente traduzidos.
* Top menu flutuante: Manter o top menu sempre visível, à medida que o utilizador realize scroll da página.
* Pontuação Core Web Vitals: Que a sua página fique com no mínimo dois indicadores verdes para a versão Mobile, e no mínimo três indicadores verdes na versão Desktop; em relação às principais métricas da Web (LCP, FID, CLS, FCP, INP, TTFB), ao se avaliar a página em:  [pagespeed.web.dev](https://pagespeed.web.dev/) 
* Desejável o uso de um dos seguintes frameworks/bibliotecas: Angular, Bootstrap, React,  Vue.js.

**Atenção:** Todos os itens devem ser responsivos! Durante a apresentação desejamos ver a página nas versões Desktop e Mobile.
