<p align="center">
  <img src="https://i.imgur.com/TY4wKsk.png" height="260" width="320" />
  <img src="https://conteudos.xpi.com.br/wp-content/uploads/2019/10/ccr-logo-nobo.png" height="290" width="320">
</p>

<p align="center">
  <a href="./LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue" alt="Caminho Certo is released under the MIT license" />
  </a>
  <a href="https://GitHub.com/Silvio-Ronaldo/Caminho_Certo/graphs/commit-activity">
    <img src="https://img.shields.io/badge/Maintained%3F-yes-brightgreen" alt="Caminho Certo is currently maintained by Silvio Ronaldo" />
  </a>
  <a href="https://GitHub.com/Silvio-Ronaldo/Caminho_Certo/network/">
    <img src="https://img.shields.io/github/forks/Silvio-Ronaldo/Caminho_Certo?style=social" alt="This is the number of forks in this repository" />
  </a>
  <a href="https://GitHub.com/Silvio-Ronaldo/Caminho_Certo/stargazers/">
    <img src="https://img.shields.io/github/stars/Silvio-Ronaldo/Caminho_Certo?style=social" alt="This is the number of stars in this repository" />
  </a>
  <a href="https://github.com/Naereen/badges">
    <img src="https://img.shields.io/badge/badge-awesome-brightgreen" alt="Badges are awesome" />
  </a>
</p></br>


<h1>🚛 Caminho Certo | Hackathon CCR</h1>
<p>Caminho Certo é o aplicativo desenvolvido para ajudar a vida dos caminhoneiros nesse Brasil a fora.</p>
<p><strong>Projetado no hackathon CCR 2020</strong></p></br>


<h2>📯 Introdução</h2>
<p>Com uma das maiores frotas de caminhões do mundo o Brasil se movimenta pelas estradas e rodovias, carregando praticamente tudo, e mesmo em tempos de pandemia essa circulação não pode parar.</p></br>


<h2>💡 A Ideia</h2>
<p>O aplicativo "Caminho Certo", nasceu com a intenção de ajudar o caminhoneiro no planejamento de suas rotas e com isso, diminuir seus custos de viagem, previnir de possiveis imprevistos e com isso tornar a viagem menos desgastante. O aplicativo planeja sua rota e te mostra os locais confiáveis para a sua parada, seja para descansar, almoçar ou apenas esticar as pernas.</p></br>


<h2>⛓️ Como Funciona</h2>
<p>O aplicativo Caminho Certo é uma mão na roda para o caminhoneiro. Basta baixar o aplicativo e acessá-lo. Você precisa efetuar um login rápido com uma conta do Google e pronto. Você já pode usar nossos serviços!</p>

<p align="center">
  <img src="https://i.imgur.com/B8MPEEw.png" height="400" width="200">
</p></br>

<p>Feito isso, aparece um mapa e você pode escolher um ponto de destino digitando na barra de pesquisa acima do mapa.</p>

<p align="center">
  <img src="https://i.imgur.com/KnIDHEo.png" height="400" width="200">
</p></br>

<p>A partir do momento que escolher o endereço final, clique na lupa. O aplicativo Caminho Certo traça a melhor rota da sua localização atual até o ponto desejado. Uma tela mostrando alguns dados básicos como Tempo, Distância e Número de Paradas será disparada. Se você deseja confirmar essa rota, clique em Confirmar.</p>

<p align="center">
  <img src="https://i.imgur.com/MbMrzaF.png" height="400" width="200">
</p></br>

<p>Agora com sua rota confirmada, você pode visualizar no mapa o trajeto certinho, interagindo com ele e visualizando os pontos/postos de parada que o aplicativo Caminho Certo escolheu pra você! Não se preocupe, só escolhemos pontos seguros e que vão aumentar a eficiência da sua rota.</p>

<p align="center">
  <img src="https://i.imgur.com/VHWMplu.png" height="400" width="200">
</p></br>

<p>Se você já está pronto para partir, clique em Iniciar e o aplicativo Caminho Certo vai acompanhar sua viagem, garantindo assim amplo suporte e mais segurança!
Além disso, a qualquer momento você pode clicar em um dos postos escolhidos para parada que estão no mapa. Ali, você encontrará dados básicos sobre quanto falta pra chegar nesse ponto, se é possível comer, ou até dormir por lá. Com a ajuda da comunidade de caminhoneiros, você pode visualizar a avaliação do posto também, pra verificar se ele é um posto de qualidade.</p>

<p align="center">
  <img src="https://i.imgur.com/R8PllMR.png" height="400" width="200">
</p></br>

<p>Mesmo assim, se você tiver qualquer dúvida, seja sobre sua rota, sobre nossos serviços, sobre postos, como usar o aplicativo ou qualquer outro tipo de questão, basta clicar no ícone de WhatsApp no canto inferior direito. Ali você será redirecionado para falar com bot Caminho Certo. Iremos te atender sempre da melhor maneira e sanar suas dúvidas!</p>

<p align="center">
  <img src="https://i.imgur.com/B670NXU.png" height="400" width="200">
</p></br>



<h2>⚒️ Ferramentas Utilizadas</h2>

### [Twilio]("https://www.twilio.com/")
<p>Serviço que possibilita a troca de mensagens através do Whatsapp. No projeto utilizamos para fazer a troca de mensagem entre o Watson Assistant e o usuário.</p>

### [IBM Watson Assistant:]("https://www.ibm.com/cloud/watson-assistant/")
<p>Serviço que auxilia na criação de assistants inteligentes. No projeto utilizamos para reconhecer a intenção do usuário, onde o mesmo faz perguntas relacionadas ao aplicativo ou a rota que ele está fazendo.</p>

<p>O dashboard que usamos dentro do Watson Assistant  apresentado a seguir:</p>
<p align="center">
<img src="https://i.imgur.com/IppLYlp.png" height="460" width="920">
</p></br>

### [IBM Cloud Functions:]("https://developer.ibm.com/api/view/cloudfunctions-prod:cloud-functions#Overview")

<p>Para unir o Watson Assistant ao nosso backend e aos serviços da Twilio, criamos duas actions em NodeJS e hospedamos na Cloud Functions da IBM. Link do serviço:</p>

<p>https://us-south.functions.cloud.ibm.com/api/v1/web/joedunicamp%40gmail.com_dev/default/watson-web</p>

<p>https://us-south.functions.cloud.ibm.com/api/v1/web/joedunicamp%40gmail.com_dev/default/whatsapp-two</p></br>



<h2>🤝 Contribuidores</h2>
<table>
  <tr>
    <td align="center"><a href="https://github.com/JoedSilva18"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/41526188?v=4" width="100px;" alt="Joed Silva"/><br /><sub><b>Joed Silva</b></sub></a><br /><a href="https://github.com/JoedSilva18" title="Joed Silva">☕</a></td>
  </tr>
</table></br>



<h2>👽 Autor</h2>
<table>
  <tr>
    <td align="center"><a href="https://github.com/Silvio-Ronaldo"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/48893927?v=4" width="100px;" alt="Silvio Ronaldo"/><br /><sub><b>Silvio Ronaldo</b></sub></a><br /><a href="https://github.com/Silvio-Ronaldo" title="Silvio Ronaldo">🍀</a></td>
  </tr>
</table>

<p>Leave your star, fork the project or open a pull request ❤️</p>
<p>Contact me on social networks: </p>
<p><a href="https://twitter.com/sivirinoo"><img src="https://img.shields.io/twitter/follow/sivirinoo?style=social" alt="Silvio Ronaldo's Twitter" /></a>
<a href="https://br.linkedin.com/in/silvio-ronaldo77"><img src="https://img.shields.io/badge/-Silvio-blue?style=flat&logo=Linkedin&logoColor=white" alt="Silvio Ronaldo's LinkedIn" /></a></p></br>


<h2>⚖️ Licença</h2>
<p><strong>Caminho Certo is MIT licensed, as found in the <a href="./LICENSE">LICENSE file</a>.</strong></p>
