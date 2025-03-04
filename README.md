<h1>Consulta CEP - Busca de Endereços</h1>
        <p>Este projeto permite buscar endereços através do CEP utilizando a API do viaCEP. Os endereços buscados podem ser salvos localmente e exibidos em uma lista.</p>

<h2>📌 Sobre o Projeto</h2>
        <p>O <strong>Consulta CEP</strong> é uma aplicação web que facilita a busca de endereços a partir de um CEP. Ele utiliza a API pública do  viaCEP para obter os dados e permite que os usuários salvem os endereços localmente para consultas futuras. A aplicação é construída com React, TypeScript e outras tecnologias modernas para garantir uma experiência de usuário fluida e eficiente.</p>

<h2>🚀 Tecnologias Utilizadas</h2>
        <ul>
            <li><strong>React</strong>: Biblioteca para construção da interface do usuário.</li>
            <li><strong>TypeScript</strong>: Adiciona tipagem estática para maior segurança no desenvolvimento.</li>
            <li><strong>Axios</strong>: Cliente HTTP para consumo da API viaCEP.</li>
            <li><strong>TanStack Query</strong>: Gerenciamento de estado assíncrono para requisições à API.</li>
            <li><strong>Tailwind CSS</strong>: Framework CSS para estilização eficiente e responsiva.</li>
            <li><strong>LocalStorage</strong>: Armazenamento local para persistência dos endereços buscados.</li>
        </ul>

 <h2>🛠️ Decisões Técnicas</h2>
        <h3>1️⃣ Uso do TanStack Query</h3>
        <ul>
            <li><strong>Cacheamento de requisições</strong>: Reduz chamadas desnecessárias à API.</li>
            <li><strong>Revalidação automática</strong>: Mantém os dados atualizados.</li>
            <li><strong>Gerenciamento de estados</strong>: Facilita o tratamento de estados de carregamento e erro.</li>
        </ul>

 <h3>2️⃣ Uso do Axios</h3>
        <ul>
            <li><strong>Flexibilidade</strong>: Mais fácil de configurar do que o <code>fetch</code> nativo.</li>
            <li><strong>Interceptores</strong>: Permite tratamento global de erros e requisições.</li>
        </ul>
 <h3>3️⃣ Gerenciamento de Endereços</h3>
        <ul>
            <li><strong>LocalStorage</strong>: Os endereços são armazenados localmente para persistência.</li>
            <li><strong>Atualização dinâmica</strong>: A lista de endereços é atualizada sem recarregar a página.</li>
        </ul>

   <h2>📦 Instalação e Execução</h2>
        <h3>Requisitos</h3>
        <ul>
            <li>Node.js 18+ instalado.</li>
            <li>Gerenciador de pacotes npm ou yarn.</li>
        </ul>
  <h3>Passos</h3>
        <ol>
            <li>Clone o repositório:
                <pre><code>git clone https://github.com/LeoImenes/consulta-cep.git
cd consulta-cep </code></pre>
            </li>
            <li>Instale as dependências:
                <pre><code>npm install
# ou
yarn install</code></pre>
            </li>
            <li>Inicie o projeto:
                <pre><code>npm run dev
# ou
yarn dev</code></pre>
            </li>
            <li>Acesse a aplicação:
                <p>Abra o navegador e acesse <a href="http://localhost:5173" target="_blank">http://localhost:5173</a>.</p>
            </li>
        </ol>
