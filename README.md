<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=4000&pause=1000&color=BB86FC&center=true&vCenter=true&width=600&lines=Olá,+bem-vindo(a)+ao+meu+perfil+do+GitHub" alt="Typing SVG" />
  
  <p>
    <a href="https://github.com/Fmarzochi" target="_blank">
      <img src="https://img.shields.io/github/followers/Fmarzochi?label=Follow&style=for-the-badge&logo=github&logoColor=white&color=24292e" alt="Botão Seguir GitHub" />
    </a>
    &nbsp;
    <img src="https://komarev.com/ghpvc/?username=Fmarzochi&label=VISUALIZAÇÕES&color=BB86FC&style=for-the-badge&label_color=555555" alt="Profile Views"/>
  </p>
</div>

---

## 👤 Sobre Mim 

**Desenvolvedor Front-end** com experiência em React e TypeScript, atuando na construção de SPAs modernas, escaláveis e de alta performance em ambiente SaaS multi-tenant.

Atualmente trabalho com desenvolvimento de interfaces integradas a APIs REST, consumo de serviços backend e implementação de fluxos complexos de onboarding, garantindo organização de código, componentização e boas práticas de arquitetura no Front-end.

Além da especialização em Front-end, também atuo no backend com Node.js, desenvolvendo integrações, manipulando webhooks, estruturando APIs REST, trabalhando com PostgreSQL e MySQL, utilizando Docker para containerização e aplicando testes automatizados para garantir qualidade e confiabilidade das aplicações. Essa experiência amplia minha visão sobre arquitetura de aplicações, comunicação entre serviços e organização de sistemas em produção.

Paralelamente, estou aprofundando minha atuação em Backend Java com Spring Boot, aplicando conceitos de arquitetura em camadas, segurança com JWT, controle de acesso, persistência com JPA/Hibernate, modelagem relacional e integração com PostgreSQL, além de boas práticas de organização e estruturação de APIs.

Meu objetivo é consolidar uma atuação sólida em Backend (Node.js e Java), mantendo uma visão completa de produto, arquitetura, banco de dados e integração ponta a ponta.

---

## 💻 Tecnologias e Ferramentas

### 📚 Linguagens
<img alt="JavaScript" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"/>&nbsp;
<img alt="TypeScript" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg"/>&nbsp;
<img alt="Java" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg"/>&nbsp;
<img alt="Python" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg"/>

### ✨ Frameworks e Bibliotecas
<img alt="React" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg"/>&nbsp;
<img alt="NextJS" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg"/>&nbsp;
<img alt="Tailwind CSS" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg"/>&nbsp;
<img alt="NodeJS" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg"/>&nbsp;
<img alt="Spring Boot" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original.svg"/>&nbsp;
<img alt="Jest" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jest/jest-plain.svg"/>

### 💾 Bancos de Dados
<img alt="PostgreSQL" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg"/>&nbsp;
<img alt="MySQL" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg"/>&nbsp;
<img src="https://img.shields.io/badge/SQL-025E8C?style=flat&logo=mysql&logoColor=white" height="28"/>

### ⚙️ Ferramentas e Cloud
<img alt="Git" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg"/>&nbsp;
<img src="https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white" height="28"/>&nbsp;
<img alt="Docker" height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg"/>&nbsp;
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white" height="28"/>

---

## 📧 Contatos
<div align="center">
  <a href="mailto:fmarzochi@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/felipemarzochi/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/Fmarzochi" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
</div>

<br />

<div align="center">
  <small>© Desenvolvido por Felipe Marzochi.</small>
</div>
<-- Adiciona constraint UNIQUE na tag (se desejado)
ALTER TABLE instruments ADD CONSTRAINT uk_instruments_tag UNIQUE (tag);

-- Adiciona índices para consultas frequentes
CREATE INDEX idx_instruments_name ON instruments(name);
CREATE INDEX idx_instruments_location_id ON instruments(location_id);
CREATE INDEX idx_instruments_category_id ON instruments(category_id);
CREATE INDEX idx_instruments_periodicity_id ON instruments(periodicity_id);
CREATE INDEX idx_instruments_patrimony_code ON instruments(patrimony_code);

-- Adiciona índices em tb_categories e tb_locations (se necessário)
CREATE INDEX idx_categories_name ON tb_categories(name);
CREATE INDEX idx_locations_name ON tb_locations(name);
CREATE INDEX idx_locations_active ON tb_locations(active);

-- Adiciona índices em tb_movements
CREATE INDEX idx_movements_instrument_id ON tb_movements(instrument_id);
CREATE INDEX idx_movements_movement_date ON pair badge -->
<-- Adiciona constraint UNIQUE na tag (se desejado)
ALTER TABLE instruments ADD CONSTRAINT uk_instruments_tag UNIQUE (tag);

-- Adiciona índices para consultas frequentes
CREATE INDEX idx_instruments_name ON instruments(name);
CREATE INDEX idx_instruments_location_id ON instruments(location_id);
CREATE INDEX idx_instruments_category_id ON instruments(category_id);
CREATE INDEX idx_instruments_periodicity_id ON instruments(periodicity_id);
CREATE INDEX idx_instruments_patrimony_code ON instruments(patrimony_code);

-- Adiciona índices em tb_categories e tb_locations (se necessário)
CREATE INDEX idx_categories_name ON tb_categories(name);
CREATE INDEX idx_locations_name ON tb_locations(name);
CREATE INDEX idx_locations_active ON tb_locations(active);

-- Adiciona índices em tb_movements
CREATE INDEX idx_movements_instrument_id ON tb_movements(instrument_id);
CREATE INDEX idx_movements_movement_date ON badge 3 -->
