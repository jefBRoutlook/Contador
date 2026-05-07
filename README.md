## ⏱️ PAUSE - Controle Total
Um temporizador visual minimalista e funcional projetado para gerenciar intervalos de pausa ou sequências de atividades. Com uma interface de alto contraste e feedback sonoro, o PAUSE ajuda a manter o foco e a organização do tempo de forma intuitiva.
## 🚀 Utilização
Para utilizar a página, basta abrir o arquivo index.html em qualquer navegador moderno.

   1. Início: Ao carregar, clique em qualquer lugar da tela para ativar o sistema de voz (exigência dos navegadores para reprodução de áudio).
   2. Ajuste de Tempo: No canto inferior direito, você encontrará um painel flutuante (ele ganha destaque ao passar o mouse). Insira o tempo desejado em minutos e clique em "OK".
   3. Navegação: Você pode avançar ou retroceder os números manualmente utilizando os botões "Anterior" e "Próximo".
   4. Automação: O sistema alternará os números automaticamente conforme o intervalo definido.

## ✨ Recursos

* 🕒 Timer Customizável: Defina intervalos de tempo específicos de acordo com sua necessidade.
* 🎙️ Feedback por Voz: Utiliza a API de síntese de voz para anunciar o número atual, permitindo o acompanhamento sem precisar olhar para a tela.
* 📊 Barra de Progresso Visual: Uma linha sutil no topo da tela indica visualmente quanto tempo resta para a próxima transição.
* 📱 Design Responsivo: Números em escala vw (viewport width) que se adaptam perfeitamente a qualquer tamanho de monitor ou dispositivo móvel.
* 🌓 Interface High-Contrast: Estética moderna utilizando a paleta Slate e Sky Blue para reduzir a fadiga ocular.
* Controle Manual: Flexibilidade para pular etapas ou retornar a números anteriores instantaneamente.

## 📢 Retorno Informativo
O sistema comunica o status ao usuário de três formas principais:

   1. Visual Dinâmico: O número central e a barra de progresso superior atualizam-se em tempo real.
   2. Voz (Speech Synthesis):
   * Anuncia "Sistema iniciado" no primeiro clique.
      * Lê o número atual a cada transição (automática ou manual).
      * Confirma alterações de configuração (ex: "Tempo alterado para 15 minutos").
   3. Transições Suaves: Efeitos de opacidade indicam a mudança de estado, tornando a experiência menos brusca.

------------------------------
## 🛠️ Tecnologias Utilizadas

* HTML5
* CSS3 (Flexbox e Animações)
* JavaScript Vanilla (Web Speech API e Timers)

------------------------------
Dica de customização: Para alterar a sequência de números, basta editar o array numeros dentro da tag <script> no arquivo HTML.
ativo!

Link (https://pausesamu.netlify.app/)[https://pausesamu.netlify.app/]

