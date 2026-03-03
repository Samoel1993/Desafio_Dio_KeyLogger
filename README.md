1. Objetivo do Projeto

  Este repositório documenta um laboratório acadêmico voltado ao estudo do funcionamento de dois tipos comuns de malware:
  Ransomware
  Keylogger
  O projeto tem finalidade exclusivamente educacional, com foco em:
  Entender como essas ameaças operam
  Compreender seus impactos técnicos
  Estudar como vulnerabilidades são exploradas
  Documentar estratégias eficazes de prevenção e defesa
  Nenhum código com finalidade ofensiva real foi desenvolvido. O foco está na análise técnica e na perspectiva defensiva.
  
2. Ambiente de Laboratório
  Todos os testes e estudos foram realizados em ambiente isolado, utilizando:
  Ambiente controlado sem conexão com redes corporativas
  O isolamento é essencial para evitar riscos e garantir prática segura.

3. Parte 1 – Análise de Ransomware
  3.1 O que é Ransomware
    Ransomware é um tipo de malware que criptografa arquivos da vítima e exige pagamento para restaurar o acesso.
    Ele explora tanto vulnerabilidades técnicas quanto falhas humanas, como cliques em links maliciosos ou execução de anexos suspeitos.

  3.2 Ciclo de Funcionamento

  Um ransomware típico segue as etapas abaixo:
  Vetor de infecção
  Phishing
  Exploração de vulnerabilidades
  Downloads maliciosos
  Execução inicial
  Criação de persistência
  Modificação de chaves de registro
  Descoberta de arquivos
  Varredura por extensões específicas
  Criptografia
  Uso de criptografia simétrica para arquivos
  Uso de criptografia assimétrica para proteger a chave
  Nota de resgate
  Mensagem exigindo pagamento
  
4. Parte 2 – Análise de Keylogger
  4.1 O que é Keylogger
    Keylogger é um software que registra entradas de teclado com o objetivo de capturar:
    Senhas
    Credenciais bancárias
    Dados confidenciais
    Pode ser utilizado para espionagem digital ou fraude.
4.2 Funcionamento Geral
  O comportamento típico inclui:
  Captura de eventos do teclado
  Armazenamento em arquivo local
  Envio dos dados para servidor externo
  Execução oculta em segundo plano

4.3 Estudo Técnico
  Neste projeto não foi implementada captura real de teclado.
  Foi desenvolvido apenas um simulador de geração de logs fictícios, com finalidade de:
  Entender como dados são estruturados
  Analisar possíveis padrões de exfiltração
  Estudar como ferramentas defensivas detectam comportamento suspeito

5. Estratégias de Defesa
  A parte mais importante do estudo é a prevenção.

  5.1 Antivírus e EDR
    Mecanismos utilizados:
    Detecção por assinatura
    Análise heurística
    Monitoramento comportamental
    Bloqueio de processos suspeitos
    Soluções modernas utilizam análise comportamental para detectar criptografia em massa de arquivos.

5.2 Firewall
  Funções relevantes:
  Bloqueio de conexões externas suspeitas
  Restrição de tráfego de saída
  Controle de portas e protocolos
  Isso reduz a comunicação com servidores de comando e controle.
