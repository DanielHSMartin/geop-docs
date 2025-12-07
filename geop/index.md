<div style="text-align: center; margin-bottom: 30px;">
  <img src="assets/logo.png" alt="GeOP Logo" width="150">
  <h1 style="margin-top: 15px; margin-bottom: 5px;">GeOP Maps</h1>
  <p style="font-size: 1.2em; color: #666;"><strong>Aplicativo de Gerenciamento de Operações com Rastreamento em Tempo Real</strong></p>
</div>

GeOP é uma aplicação desenvolvida para auxiliar planejamento, gerenciamento e execução de operações policiais, oferecendo recursos de compartilhamento de localização em tempo real, gestão de integrantes, equipes, recursos, registros e alertas. 

---

## 🗺️ Localização e Mapeamento

- **Rastreamento de localização em tempo real** com modos em primeiro e segundo plano
- **Compartilhamento de posição ao vivo** entre membros da operação
- **Mapas offline** com suporte ao formato GeopDB
- **Múltiplas opções de mapas base** para diferentes terrenos e cenários
- **Integração com navegação** compatível com 20+ apps (Google Maps, Waze, Apple Maps, HERE, Sygic e mais)
- **Bússola e indicador de direção** para orientação
- **Sessões de rastreamento** com gravação de local, distância e métricas de velocidade
- **Visualização de curvas de nível** em arquivos GeopDB
- **Roteamento fluvial** utilizando dados do OpenStreetMaps
- **Importação de arquivos PDF/KML/GPX** para dados geográficos externos

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/rastreamento.jpeg" alt="Mapa com rastreamento" width="200">
  <img src="screenshots/navegacao.jpeg" alt="Navegação no mapa" width="200">
  <img src="screenshots/curvaNivel.jpeg" alt="Curvas de Nível" width="200">
</div>

---

## 👥 Gestão de Operações e Equipes

- **Criar e gerenciar operações** com tipos de atividade personalizáveis
- **Organização de equipes** com estrutura hierárquica (líderes e membros)
- **Definição de funções** dos membros das equipes 
- **Gestão de integrantes** com permissões baseadas em funções
- **Sistema de convites** para adicionar novos integrantes às operações
- **Acompanhamento de status** da operação (planejamento, ativa, concluída)
- **Agendamento de datas** de início e término das operações

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/listaOperacoes.jpeg" alt="Lista de operações" width="200">
  <img src="screenshots/detalheOperacao.jpeg" alt="Detalhes da operação" width="200">
  <img src="screenshots/equipe.jpeg" alt="Gestão de equipes" width="200">
</div>

---

## 🔐 Permissões e Segurança

- **Sistema granular de permissões** incluindo:
  - Visualizar/Editar Integrantes
  - Visualizar/Editar Equipes
  - Visualizar/Editar Registros
  - Visualizar/Editar Recursos
  - Visualizar/Editar Feições
  - Editar configurações da Operação
- **Autenticação segura** via Firebase Authentication
- **Configurações de privacidade** com controles de visibilidade baseados em contatos
- **Armazenamento local criptografado**

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/permissoes.jpeg" alt="Configurações de permissões" width="200">
  <img src="screenshots/contatos.jpeg" alt="Privacidade" width="200">
  <img src="screenshots/login.jpeg" alt="Autenticação" width="200">
</div>

---

## 📋 Registros e Gestão de Dados

- **Modelos de registro personalizáveis** para entrada estruturada de dados
- **Gestão de recursos** com modelos de recursos e alocação a integrantes e equipes
- **Captura de fotos como evidência** com integração à câmera
- **Exportação de dados** em múltiplos formatos para análise por IA
- **Vínculos** para conectar registros e entidades relacionadas

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/registros.jpeg" alt="Lista de registros" width="200">
  <img src="screenshots/recursos.jpeg" alt="Recursos" width="200">
  <img src="screenshots/novoRegistro.jpeg" alt="Detalhes do registro" width="200">
</div>

---

## 🗂️ Feições e Camadas do Mapa

- **Camadas vetoriais** para organização de elementos do mapa
- **Feições de camada** (pontos, linhas, polígonos) com estilização personalizada
- **Alvos e pontos de referência** no mapa
- **Gerenciamento de visibilidade** de elementos por usuário
- **Ordenação e agrupamento** de elementos
- **Detalhes das feições** com descrições e metadados

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/camadas.jpeg" alt="Camadas do mapa" width="200">
  <img src="screenshots/editarGeometria.jpeg" alt="Edição de feição" width="200">
  <img src="screenshots/visibilidade.jpeg" alt="Gerenciamento de visibilidade" width="200">
</div>

---

## 🔔 Alertas e Notificações

- **Notificações** via push notifications
- **Alertas de emergência** para situações críticas
- **Notificações de atualizações** da operação
- **Sistema de gerenciamento** de alertas

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/alerta.jpeg" alt="Alerta" width="200">
  <img src="screenshots/emergencia.jpeg" alt="Alerta de emergência" width="200">
  <img src="screenshots/notificacao.jpeg" alt="Notificações" width="200">
</div>

---

## ☁️ Nuvem e Sincronização

- **Sincronização com a nuvem** via Google Firebase
- **Atualizações de dados em tempo real** entre dispositivos
- **Arquitetura offline-first** com cache local
- **Timestamps baseados em NTP** para sincronização precisa de horário
- **Sincronização de fotos** para armazenamento em nuvem

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/sincronizacao.jpeg" alt="Status de sincronização" width="200">
  <img src="screenshots/fotos.jpeg" alt="Sincronização de fotos" width="200">
</div>

---

## 📱 Planos de Assinatura

| Plano | Recursos |
|-------|----------|
| **Offline** | Modo local apenas, sem sincronização com a nuvem |
| **Online** | Sincronização com a nuvem, intervalos de comunicação de 5 minutos |
| **Realtime** | Todos os recursos, comunicação em tempo real |

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/planos.jpeg" alt="Planos de assinatura" width="200">
  <img src="screenshots/assinatura.jpeg" alt="Detalhes do plano" width="200">
</div>

---

## 🌐 Suporte Multiplataforma

<div style="display: flex; gap: 40px; justify-content: center; margin: 30px 0;">
  <div style="text-align: center;">
    <span style="font-size: 64px;">🤖</span>
    <h3>Android</h3>
    <p>Suporte completo com serviços<br>de localização em segundo plano</p>
  </div>
  <div style="text-align: center;">
    <span style="font-size: 64px;">🍎</span>
    <h3>iOS</h3>
    <p>Suporte completo com rastreamento<br>nativo de localização</p>
  </div>
</div>

---

## 📤 Importação e Exportação

| Formato | Descrição |
|---------|-----------|
| **GeopDB** | Formato personalizado para mapas offline |
| **GeoPDF** | Formato de mapas georeferenciados |
| **KML** | Formato Google Earth |
| **GPX** | Formato de intercâmbio GPS |
| **JSON** | Exportação de dados da operação |

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/importar.jpeg" alt="Importar arquivo" width="200">
  <img src="screenshots/exportar.jpeg" alt="Exportar dados" width="200">
</div>

---

## 📲 Baixe Agora

<div style="display: flex; gap: 20px; justify-content: center; align-items: center; margin: 30px 0;">
  <a href="https://play.google.com/store/apps/details?id=com.hsmartin.geop">
    <img src="https://play.google. com/intl/en_us/badges/static/images/badges/pt-br_badge_web_generic. png" alt="Disponível no Google Play" height="60">
  </a>
</div>

---

## 📧 Contato

Para dúvidas, sugestões ou suporte, entre em contato conosco.
danielhsmartin@gmail.com
---

<div style="text-align: center; margin-top: 40px;">
  <img src="assets/logo.png" alt="GeOP Logo" width="60" style="opacity: 0.6;">
  <p style="color: #666; margin-top: 10px;">© 2025 GeOP - Todos os direitos reservados</p>
</div>
