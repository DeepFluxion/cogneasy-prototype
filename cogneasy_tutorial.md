# 🎯 CognEasy - Tutorial de Navegação do Protótipo

## 📱 Visão Geral

Este protótipo demonstra as jornadas completas tanto do **paciente** quanto do **médico** no CognEasy, mostrando como cada tipo de usuário interage com o assistente virtual inteligente para gestão de tratamento oncológico.

---

## 🚀 Como Começar

### 1. **Tela de Login**
- **Localização**: Primeira tela do protótipo
- **Ação**: Escolha seu perfil de usuário

#### 👩 **Para testar como PACIENTE:**
1. Clique no cartão **"🤒 Paciente"**
2. O email mudará para `maria.santos@email.com`
3. Digite qualquer senha (ex: "123456")
4. Clique em **"Entrar"**

#### 👨‍⚕️ **Para testar como MÉDICO:**
1. Clique no cartão **"👨‍⚕️ Médico"**
2. O email mudará para `dr.silva@clinica.com`
3. Digite qualquer senha (ex: "123456")
4. Clique em **"Entrar"**

---

## 👩 JORNADA DO PACIENTE (Maria Santos)

### **🏠 Dashboard do Paciente**
**O que você verá:**
- **Cartão de boas-vindas** personalizado
- **Métricas importantes**:
  - 💊 Aderência atual: 94%
  - 📅 Dias até próxima consulta: 5
  - 😊 Como se sente: Bem
  - 🎯 Ciclo atual: 2º
- **Lista de medicamentos do dia** com status

### **💬 Chat do Paciente**
**Como navegar:**
1. Clique na aba **"💬 Chat"** na barra inferior
2. **Teste as ações rápidas** (recomendado para demo):

#### **💊 "Tomei remédio"**
- Clique no botão
- Veja a conversa: registra medicamento automaticamente
- Mostra aderência atualizada

#### **😷 "Registrar sintoma"**
- Clique no botão
- Simula registro de náusea
- Escala de 1-10
- Recebe orientações automáticas

#### **📅 "Ver agenda"**
- Mostra medicamentos de hoje
- Próximas consultas
- Exames agendados

#### **❓ "Tenho dúvida"**
- Simula dúvida sobre alimentação
- Recebe orientações baseadas na base de conhecimento

**💡 Dica**: Após testar as ações rápidas, digite suas próprias mensagens como:
- "Estou com dor"
- "Esqueci de tomar o remédio"
- "Posso comer chocolate?"

### **📅 Agenda do Paciente**
**O que você verá:**
- **Medicamentos de hoje** com horários
- **Consulta com Dr. Silva** amanhã
- **Exames laboratoriais**
- **Próxima sessão de quimioterapia**

---

## 👨‍⚕️ JORNADA DO MÉDICO (Dr. Silva)

### **🏠 Dashboard do Médico**
**O que você verá:**
- **Estatísticas da clínica**:
  - 28 pacientes ativos
  - 6 consultas hoje
  - 3 alertas importantes
  - 92% aderência média
- **Lista de pacientes críticos** que precisam atenção

**💡 Teste importante**: Clique em qualquer paciente da lista (ex: Maria Santos) para ver detalhes completos!

### **💬 Chat do Médico**
**Como navegar:**
1. Clique na aba **"💬 Chat"** 
2. **Teste as ações rápidas específicas para médicos**:

#### **📊 "Status geral"**
- Relatório completo do dia
- Pacientes por prioridade
- Ações sugeridas

#### **⚠️ "Alertas"**
- Mostra alertas críticos em tempo real
- Pacientes que precisam atenção imediata
- Ações automáticas já realizadas

#### **💊 "Prescrever"**
- Interface para nova prescrição
- Formato de comando natural
- Confirmação automática

#### **📅 "Ver agenda"**
- Agenda específica do médico
- Consultas com pacientes
- Horários e tipos de consulta

**💡 Teste avançado**: Digite comandos como:
- "Me mostre detalhes da Maria Santos"
- "Prescrever Metoclopramida 10mg 8/8h por 5 dias para Maria Santos"
- "Como está a aderência dos meus pacientes?"

### **📅 Agenda do Médico**
**O que você verá:**
- **Consultas de hoje**: Ana Lima, Pedro Oliveira
- **Consultas de amanhã**: João Costa, Maria Santos, Carla Mendes
- **Reuniões multidisciplinares**
- **Detalhes específicos**: tipo de consulta, sala, observações

---

## 🎯 FUNCIONALIDADES INTERATIVAS PRINCIPAIS

### **1. Chat Inteligente**
- **Cenários pré-programados** realistas
- **Respostas contextualizadas** por tipo de usuário
- **Ações automáticas** (prescrições, registros, alertas)

### **2. Navegação entre Seções**
- **Barra inferior**: Início, Chat, Agenda, Perfil
- **Headers dinâmicos**: Mudam conforme a seção
- **Botão voltar**: Aparece quando necessário

### **3. Diferenciação por Perfil**
- **Interface personalizada** para cada tipo de usuário
- **Dashboards específicos** com métricas relevantes
- **Agendas diferenciadas** (medicamentos vs consultas)

---

## 🎬 CENÁRIOS RECOMENDADOS PARA DEMO

### **📋 Sequência Paciente (5 minutos)**
1. **Login como paciente** → Ver dashboard
2. **Testar "💊 Tomei remédio"** → Ver registro automático
3. **Testar "😷 Registrar sintoma"** → Náusea 4/10
4. **Ver agenda** → Medicamentos e consultas
5. **Perguntar sobre alimentação** → Receber orientações

### **📋 Sequência Médico (5 minutos)**
1. **Login como médico** → Ver dashboard com alertas
2. **Clicar em "Maria Santos"** → Ver detalhes do paciente
3. **Testar "📊 Status geral"** → Relatório completo
4. **Testar prescrição** → Comando natural
5. **Ver agenda** → Consultas do dia

### **📋 Comparação (3 minutos)**
1. **Alternar entre perfis** (logout/login)
2. **Comparar agendas** → Medicamentos vs Consultas
3. **Comparar chat** → Ações rápidas diferentes
4. **Comparar dashboards** → Métricas específicas

---

## 💡 DICAS PARA MELHOR EXPERIÊNCIA

### **✅ O que funciona bem:**
- **Ações rápidas**: Sempre começe por elas
- **Cliques nos pacientes**: No dashboard médico
- **Navegação entre abas**: Use a barra inferior
- **Comandos naturais**: Digite como falaria normalmente

### **⚠️ O que é simulado:**
- **Autenticação**: Qualquer senha funciona
- **Dados em tempo real**: Dados de demonstração
- **Notificações**: Simuladas no chat
- **Integração**: Interface única (não integra sistemas externos)

### **🎯 Foco da demonstração:**
- **Interface conversacional** como ponto central
- **Diferenciação de experiência** por tipo de usuário
- **Automação inteligente** de tarefas repetitivas
- **Monitoramento em tempo real** de pacientes

---

## 🔄 RESETAR O PROTÓTIPO

**Para testar novamente:**
1. Recarregue a página (F5 ou Ctrl+R)
2. Volta automaticamente para tela de login
3. Escolha outro perfil de usuário
4. Teste diferentes cenários

---

## 🎉 PRINCIPAIS DIFERENCIAIS DEMONSTRADOS

### **Para Pacientes:**
✅ **Simplicidade**: Interface amigável e intuitiva
✅ **Suporte 24/7**: Assistente sempre disponível
✅ **Educação**: Orientações baseadas em evidências
✅ **Autonomia**: Controle do próprio tratamento

### **Para Médicos:**
✅ **Eficiência**: Informações organizadas e acessíveis
✅ **Monitoramento**: Alertas inteligentes em tempo real
✅ **Produtividade**: Comandos naturais para prescrições
✅ **Qualidade**: Dados estruturados para decisões

### **Para Ambos:**
✅ **Comunicação**: Canal direto médico-paciente
✅ **Aderência**: Melhoria comprovada no seguimento
✅ **Satisfação**: Interface moderna e responsiva
✅ **Resultados**: Dados concretos de evolução

---

## 📞 PRÓXIMOS PASSOS

Após navegar pelo protótipo, você terá uma visão completa de como o CognEasy revoluciona a gestão de tratamento oncológico através de IA conversacional.

**Este protótipo demonstra:**
- ✅ Viabilidade técnica
- ✅ Experiência do usuário
- ✅ Diferencial competitivo
- ✅ Valor agregado real

**Pronto para transformar o cuidado oncológico!** 🚀