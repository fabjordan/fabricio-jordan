<template>
  <div>
    <section class="experiences" id="experiences">
      <b-container>
        <b-row class="mt-5 pb-5">
          <b-col>
            <h1 class="big-font big-font-1 text-white">Timeline</h1>
            <h2 class="big-font big-font-2 mb-4">Timeline</h2>
          </b-col>
        </b-row>
        <b-row class="d-flex mt-5">

          <b-col md="12" sm="12" xs="12" class="mb-5">
            <div class="bg-1 p-4 rounded">
              <h4 class="text-white mt-3 font-weight-bold">2022</h4>
              <hr class="bg-secondary">
              <p class="text-white mt-5">
                Entre 2021 e 2022, atuei como responsável técnico pelo contrato 074/2021 de Fábrica de Software da
                Codions Tecnologia com o Ministério Público do Estado do Rio de Janeiro.
                Atuei como interlocutor técnico junto ao MPRJ, incumbido de receber, diligenciar, encaminhar e responder
                por questões técnicas. Liderei as equipes técnicas (analistas de requisitos, designs, desenvolvedores e
                QA),
                supervisionando o planejamento e gestão dos projetos, além de também atuar no desenvolvimento das
                aplicações utilzando Spring Boot, React.js e OracleDB. Implementei esquemas de CI/CD para funcionar em
                multiplos ambientes (desenvolvimento, testes e homologação) na plataforma de implantação e gerenciamento
                de containers, Openshift.
              </p>
            </div>
          </b-col>

          <b-col md="12" sm="12" xs="12" class="mb-5">
            <div class="bg-1 p-4 rounded">
              <h4 class="text-white mt-3 font-weight-bold">2021</h4>
              <hr class="bg-secondary">
              <p class="text-white mt-5">
                Em 2021 desenvolvemos um software de monitoramento de recursos computacionais chamado Cubed Server. O
                sistema permitia monitorar a infraestrutura de servidores on-premises da empresa, de clientes e
                parceiros, além de estações de trabalhos (Windows, Linux e macOS). O software identificava anomalias
                (nas métricas sobre uso de processador, memória RAM, HD/SSD e processos em execução) de acordo com as
                regras definindas pelo usuário e enviava notificações nos canais configurados pelo usuário, como: Slack,
                Discord, Telegram, E-mail e etc. Foram feitas versões desktop com Electron e os clients feitos em GO e
                bash para servidores Linux.
              </p>
            </div>
          </b-col>

          <b-col md="12" sm="12" xs="12" class="mb-5">
            <div class="bg-1 p-4 rounded">
              <h4 class="text-white mt-3 font-weight-bold">2020</h4>
              <hr class="bg-secondary">
              <p class="text-white mt-5">
                No ano de 2020, junto de uma das equipes da Codions, aperfeiçoamos o sistema Bluee Live, com a criação
                de novas ferramentas, incluindo aplicações para desktop para transmissão de áudio e vídeo via IP
                Multicast, que foi vendida para uma empresa de telecomunicações amazonense.
                <br>
                Neste mesmo ano, recebi uma grande oportunidade de virar um sócio da empresa e logo aceitei o desafio.
                Direcionei meus esforços na criação de novos produtos, sendo um deles o Blueead, uma família de soluções
                focada em educação a distância, que poderiam ser utilizadas em conjunto a partir de integrações.
                <br>
                Desenvolvemos o Conttas, um sistema de gestão modular e multitenancy completo, com diversos módulos
                como: financeiro, CRM, gestão de projetos, contabilidade, orçamentos, portal do cliente e etc.
              </p>
            </div>
          </b-col>

          <b-col md="12" sm="12" xs="12" class="mb-5">
            <div class="bg-1 p-4 rounded">
              <h4 class="text-white mt-3 font-weight-bold">2019</h4>
              <hr class="bg-secondary">
              <p class="text-white mt-5">
                Em 2019 sai da Cartórios Maranhão e fui trabalhar na Codions Tecnologia como Software Engineer.
                trabalhei em diversas versões do AcademicPro, um AVA (Ambiente Virtual de Aprendizagem) desenvolvido de
                forma monolítica com Laravel, Mysql e Memcached, sendo utilizado por diversas empresas e instituições
                públicas como VAT Tecnologia, Ministério Público do Pará, Cena2 Produções e outros. Surgiu uma situação
                onde precisavamos escalar a plataforma, fizemos diversas refatorações e otimizações em toda a aplicação,
                tivemos que transformar certos módulos em microserviços com Node.js, adotamos o RabbitMQ para
                mensageria, substituimos o Memcached pelo Redis e usamos o MongoDB para documentos JSON.
                <br>
                Adotamos a Cloudflare para gerenciar configurações de DNS e CDN de assets. Utilizamos os VPS da
                DigitalOcean para hospedar os projetos e o Docker Swam para fazer a orquestração dos conteiners.
                O fato dos VPS serem mais limitados, trouxe uma serie de problemas com indisponibilidade dos sistemas,
                então começamos a estudar algumas soluções da AWS e que no final acabamos optando pelo EKS (o serviço de
                Kubernetes gerenciado da AWS), que por fim resolveu nossos problemas de indisponibilidade.
                <br>
                Junto da minha equipe na Codions, desenvolvemos um conjunto de soluções para webconferências chamada
                Bluee Live (uma Interface de Gerenciamento para o software BigBlueButton, com algumas ferramentas
                adicionais), que depois foi licenciado para o SEBRAE-SP e com a Pandemia de covid-19 no início de 2020,
                passou a ser usado também pela Faculdade Sebrae e diversas outras organizações do setor público e
                privado.
              </p>
            </div>
          </b-col>

          <b-col md="12" sm="12" xs="12" class="mb-5">
            <div class="bg-1 p-4 rounded">
              <h4 class="text-white mt-3 font-weight-bold">2018</h4>
              <hr class="bg-secondary">
              <p class="text-white mt-5">
                Em 2018 fui contrato pela Associação dos Titulares de Cartório do meu estado (Maranhão), como Full-Stack
                Developer, onde atuei no desenvolvimento e manutenção de novas funcionalidades, além de refatoração de
                códigos legados na plataforma Cartórios Maranhão. Propus e desenvolvi um sistema para chamados de
                atendimento e suporte técnico, o que melhorou muito na velocidade de resolução de problemas tanto dos
                cartórios quanto dos usuários da plataforma.
                Fui um dos responsáveis pelo desenvolvimento da plataforma Cartórios Roraima, conseguindo realizar a
                entrega e implementação em tempo recorde.
                <br>
                Fui selecionado pelo presidente da associação para realizar o planejamento, levantamento dos requisitos
                e desenvolver o "Indexador", um sistema de indexação para livros de cartórios, cujo objetivo era a
                facilitar e modernizar a busca de registros e informações por meio eletrônico.
                <br>
                As tecnologias que mais
                utilizei durante esse período foram: PHP/Laravel, Node.js, Jquery, Vue.js, Mysql, Redis, Docker, aprendi
                a provisionar servidores Linux (Debian/Ubuntu Server), automatizar processos com Shell Script (como
                backups de banco de dados e storages), fazer deploy de aplicações com o Deployer dentre diversas outras
                coisas.
              </p>
            </div>
          </b-col>

          <b-col md="12" sm="12" xs="12" class="mb-5">
            <div class="bg-1 p-4 rounded">
              <h4 class="text-white mt-3 font-weight-bold">2017</h4>
              <hr class="bg-secondary">
              <p class="text-white mt-5">
                Em 2017 tive minha primeira experiência profissional como programador, em uma empresa local, focada em
                manutenção de computadores e criação de websites. Começei projetando sites com Wordpress (levei quase 2
                meses para aprender a criar sites com ele) e rapidamente fui evoluindo. Começei a visitar alguns
                clientes e fazer a parte de levantamento de requisitos, modelagem de dados e o desenvolvimento de sites
                e sistemas (geralmente feitos com codeigniter).
                Durante esse tempo participei de diversos eventos como o Game Jam Plus, onde eu e minha equipe tivemos
                que desenvolver um jogo completamente do zero em até 48 horas. Estudei Java para Android, criei alguns
                aplicativos básicos de estudo, incluindo clone de jogos como o Flappy Bird, clone do WhatsApp, Instagram
                e outros.
              </p>
            </div>
          </b-col>

          <b-col md="12" sm="12" xs="12" class="mb-5">
            <div class="bg-1 p-4 rounded">
              <h4 class="text-white mt-3 font-weight-bold">2016</h4>
              <hr class="bg-secondary">
              <p class="text-white mt-5">
                Em 2015 com 16 anos, entrei na faculdade de Ciência da Computação, onde tive contato com a minha
                primeira linguagem de programação, a linguagem C. Criei diversos projetos de estudo como: calculadoras,
                conversores de temperatura, tradutor de código morse, sistema de locadora de filmes e vários outros.
              </p>
            </div>
          </b-col>

          <b-col md="12" sm="12" xs="12" class="mb-5">
            <div class="bg-1 p-4 rounded">
              <h4 class="text-white mt-3 font-weight-bold">2015</h4>
              <hr class="bg-secondary">
              <p class="text-white mt-5">
                Em 2015 com 16 anos, entrei na faculdade de Ciência da Computação, onde tive contato com a minha
                primeira linguagem de programação, a linguagem C. Criei diversos projetos de estudo como: calculadoras,
                conversores de temperatura, tradutor de código morse, sistema de locadora de filmes e vários outros.
              </p>
            </div>
          </b-col>


          <b-col md="12" sm="12" xs="12" class="mb-5">
            <div class="bg-1 p-4 rounded">
              <h4 class="text-white mt-3 font-weight-bold">2014</h4>
              <hr class="bg-secondary">
              <p class="text-white mt-5">
                Eu conheci programação no ano de 2014, como qualquer adolescente, eu gostava muito de jogar jogos pelo
                computador e um dia tive a curiosidade de saber como criar um jogo para o facebook e foi quando conheci
                a programação de computadores.
                <br>
                Animado com a ideia de poder criar meu próprio jogo, tentei seguir alguns tutoriais na época, porém não
                tive sucesso. Deixei a parte de jogos de lado e fui estudar sobre como criar um site para internet e foi
                quando conheci o HTML e CSS.
              </p>
            </div>
          </b-col>

        </b-row>
      </b-container>
    </section>
  </div>
</template>

<script>
export default {
  name: "Techs"
};
</script>

<style scoped lang="scss">
@import "../assets/scss/_variables.scss";

.experiences {
  padding-bottom: 10%;

  .card-body {
    @media screen and (min-width: $display-sm) and (max-width: $display-lg) {
      height: 400px;
    }

    .h-img {
      height: 100px !important;
    }
  }
}
</style>