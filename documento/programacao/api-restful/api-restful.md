# Verificação de Conformidade RESTful para API

- [ ] **1. Arquitetura Cliente/Servidor**
  - A API segue uma arquitetura cliente/servidor, com clientes, servidores e recursos claramente definidos. As solicitações são gerenciadas por HTTP.

- [ ] **2. Comunicação Stateless**
  - A comunicação entre cliente e servidor é stateless. Nenhuma informação do cliente é armazenada entre solicitações GET, e cada solicitação é independente e desconectada.

- [ ] **3. Armazenamento em Cache**
  - Estratégias de armazenamento em cache são implementadas para otimizar as interações entre cliente e servidor.

- [ ] **4. Interface Uniforme**
  - [ ] Identificação de Recursos: Os recursos solicitados são identificáveis e separados das representações enviadas ao cliente.
  - [ ] Manipulação de Recursos: O cliente pode manipular recursos através das representações recebidas, com informações suficientes para realizar ações.
  - [ ] Mensagens Autodescritivas: As mensagens retornadas ao cliente são autodescritivas, contendo informações suficientes para descrever como processá-las.
  - [ ] Hipertexto e Hipermídia: Hipertexto e hipermídia estão disponíveis, permitindo que o cliente use hiperlinks para descobrir as ações disponíveis.

- [ ] **5. Sistema em Camadas**
  - A API é organizada em um sistema em camadas, onde diferentes tipos de servidores (por exemplo, segurança, carregamento de carga) estão envolvidos na recuperação de informações. Essas camadas são organizadas em hierarquias que o cliente não pode ver.

- [ ] **6. Código Sob Demanda (Opcional)**
  - A API oferece a capacidade opcional de enviar código executável do servidor para o cliente, ampliando a funcionalidade disponível.

---

**Conclusão:**
A API ainda precisa ser avaliada em relação aos critérios estabelecidos para ser considerada conformidade com os princípios RESTful.
