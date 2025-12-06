---
layout: default
title: GeOP - Gerenciamento de Operações
---

# GeOP

**Aplicativo de Gerenciamento de Operações com Rastreamento em Tempo Real**

GeOP é uma aplicação desenvolvida em Flutter para gerenciamento de operações, oferecendo recursos de compartilhamento de localização em tempo real, gestão de integrantes, equipes, registros e alertas.

---

## 🗺️ Localização e Mapeamento

- **Rastreamento de localização em tempo real** com modos em primeiro e segundo plano
- **Compartilhamento de posição ao vivo** entre membros da operação
- **Mapas offline** com suporte ao formato GeopDB
- **Múltiplas opções de mapas base** para diferentes terrenos e cenários
- **Integração com navegação** compatível com 20+ apps (Google Maps, Waze, Apple Maps, HERE, Sygic e mais)
- **Bússola e indicador de direção** para orientação
- **Sessões de rastreamento** com gravação de rota, distância e métricas de velocidade
- **Visualização de perfil de elevação** para rotas rastreadas

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/mapa-01.png" alt="Mapa com rastreamento" width="200">
  <img src="screenshots/mapa-02.png" alt="Navegação no mapa" width="200">
  <img src="screenshots/mapa-03. png" alt="Perfil de elevação" width="200">
</div>

---

## 👥 Gestão de Operações e Equipes

- **Criar e gerenciar operações** com tipos de atividade personalizáveis
- **Organização de equipes** com estrutura hierárquica (líderes e membros)
- **Gestão de integrantes** com permissões baseadas em funções
- **Sistema de convites** para adicionar novos integrantes às operações
- **Acompanhamento de status** da operação (planejamento, ativa, concluída)
- **Agendamento de datas** de início e término das operações

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/operacoes-01.png" alt="Lista de operações" width="200">
  <img src="screenshots/operacoes-02.png" alt="Detalhes da operação" width="200">
  <img src="screenshots/operacoes-03.png" alt="Gestão de equipes" width="200">
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
- **Autenticação segura** via Firebase
- **Configurações de privacidade** com controles de visibilidade baseados em contatos
- **Armazenamento local criptografado** (Hive com criptografia)

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/permissoes-01. png" alt="Configurações de permissões" width="200">
  <img src="screenshots/permissoes-02.png" alt="Privacidade" width="200">
  <img src="screenshots/permissoes-03.png" alt="Autenticação" width="200">
</div>

---

## 📋 Registros e Gestão de Dados

- **Modelos de registro personalizáveis** para entrada estruturada de dados
- **Rastreamento de recursos** com modelos de recursos
- **Captura de fotos como evidência** com integração à câmera
- **Importação de arquivos KML/GPX** para dados geográficos externos
- **Suporte à importação de GeoPDF**
- **Exportação de dados** em múltiplos formatos
- **Links** para conectar registros e entidades relacionadas

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/registros-01.png" alt="Lista de registros" width="200">
  <img src="screenshots/registros-02.png" alt="Novo registro" width="200">
  <img src="screenshots/registros-03.png" alt="Detalhes do registro" width="200">
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
  <img src="screenshots/feicoes-01.png" alt="Camadas do mapa" width="200">
  <img src="screenshots/feicoes-02.png" alt="Edição de feição" width="200">
  <img src="screenshots/feicoes-03.png" alt="Gerenciamento de visibilidade" width="200">
</div>

---

## 🔔 Alertas e Notificações

- **Notificações push** via Firebase Cloud Messaging
- **Alertas de emergência** para situações críticas
- **Notificações de atualizações** da operação
- **Sistema de gerenciamento** de alertas

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/alertas-01.png" alt="Lista de alertas" width="200">
  <img src="screenshots/alertas-02.png" alt="Alerta de emergência" width="200">
  <img src="screenshots/alertas-03.png" alt="Notificações" width="200">
</div>

---

## ☁️ Nuvem e Sincronização

- **Sincronização com a nuvem** via Firebase Firestore
- **Atualizações de dados em tempo real** entre dispositivos
- **Arquitetura offline-first** com cache local
- **Timestamps baseados em NTP** para sincronização precisa de horário
- **Sincronização de fotos** para armazenamento em nuvem

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/sync-01. png" alt="Status de sincronização" width="200">
  <img src="screenshots/sync-02. png" alt="Modo offline" width="200">
  <img src="screenshots/sync-03.png" alt="Sincronização de fotos" width="200">
</div>

---

## 📱 Planos de Assinatura

| Plano | Recursos |
|-------|----------|
| **Offline** | Modo local apenas, sem sincronização com a nuvem |
| **Online** | Sincronização com a nuvem, intervalos de rastreamento de 5 minutos |
| **Realtime** | Todos os recursos, todos os intervalos de rastreamento |

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/assinaturas-01. png" alt="Planos de assinatura" width="200">
  <img src="screenshots/assinaturas-02.png" alt="Detalhes do plano" width="200">
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
| **KML** | Formato Google Earth |
| **GPX** | Formato de intercâmbio GPS |
| **JSON** | Exportação de dados da operação |

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/importar-01.png" alt="Importar arquivo" width="200">
  <img src="screenshots/exportar-01.png" alt="Exportar dados" width="200">
</div>

---

## 🎨 Interface do Usuário

- **Interface moderna** com Material Design
- **Navegação inferior** para acesso rápido a Recursos, Mapa e Registros
- **Botões de ação flutuantes** para ações comuns
- **Cores personalizáveis** para integrantes no mapa
- **Suporte a modo escuro** via tema do sistema

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin: 20px 0;">
  <img src="screenshots/ui-01.png" alt="Navegação principal" width="200">
  <img src="screenshots/ui-02.png" alt="Menu lateral" width="200">
  <img src="screenshots/ui-03.png" alt="Modo escuro" width="200">
</div>

---

## 📲 Baixe Agora

<div style="display: flex; gap: 20px; justify-content: center; margin: 30px 0;">
  <a href="https://play.google.com/store/apps/details?id=com.hsmartin.geop">
    <img src="https://play.google. com/intl/en_us/badges/static/images/badges/pt-br_badge_web_generic.png" alt="Disponível no Google Play" height="60">
  </a>
</div>

---

## 📧 Contato

Para dúvidas, sugestões ou suporte, entre em contato conosco. 

---

<p style="text-align: center; color: #666; margin-top: 40px;">
  © 2025 GeOP - Todos os direitos reservados
</p>