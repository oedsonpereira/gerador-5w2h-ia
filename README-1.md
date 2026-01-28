# 🤖 Gerador de Plano de Ação 5W2H com IA

> Ferramenta inteligente que usa IA para transformar problemas em planos de ação estruturados e acionáveis

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Powered by Claude](https://img.shields.io/badge/Powered%20by-Claude%20AI-purple)](https://www.anthropic.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📋 Sobre o Projeto

O **Gerador 5W2H com IA** é uma ferramenta web que utiliza Inteligência Artificial (Claude da Anthropic) para analisar problemas e gerar automaticamente planos de ação completos seguindo a metodologia 5W2H.

### 🎯 O que é 5W2H?

5W2H é uma metodologia de gestão utilizada para planejamento estratégico e análise de problemas. O nome vem das iniciais em inglês:

- **What** (O quê) - O que será feito?
- **Why** (Por quê) - Por que será feito?
- **Where** (Onde) - Onde será executado?
- **When** (Quando) - Quando será feito?
- **Who** (Quem) - Quem será responsável?
- **How** (Como) - Como será feito?
- **How much** (Quanto custa) - Quanto vai custar?

## ✨ Funcionalidades

- 🤖 **Análise por IA**: Claude AI analisa o problema e gera plano estruturado
- 📊 **Plano Completo**: Gera todas as 7 dimensões do 5W2H automaticamente
- 📥 **Export PDF**: Baixe o plano em formato profissional
- 💡 **Exemplos Práticos**: 4 problemas de exemplo prontos para testar
- 🔐 **Seguro**: API Key armazenada localmente no navegador
- 🎨 **Interface Moderna**: Design limpo e responsivo
- ⚡ **Rápido**: Gera planos em 5-10 segundos

## 🚀 Demo

![Demo do Gerador 5W2H](./assets/demo.gif)

**[▶️ Ver Vídeo Demo no YouTube](#)** | **[🔗 Testar Online](#)**

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura
- **CSS3** - Estilização e responsividade
- **JavaScript (Vanilla)** - Lógica e interações
- **Claude API (Anthropic)** - Inteligência Artificial
- **jsPDF** - Geração de PDFs
- **LocalStorage** - Armazenamento seguro da API Key

## 📦 Instalação

### Opção 1: Download Direto

1. Baixe o arquivo `5w2h-generator-ai.html`
2. Abra no seu navegador
3. Configure sua API Key (veja abaixo)
4. Pronto para usar!

### Opção 2: Clone o Repositório

```bash
git clone https://github.com/seu-usuario/gerador-5w2h-ia.git
cd gerador-5w2h-ia
```

Abra o arquivo `5w2h-generator-ai.html` no navegador.

## 🔑 Configuração da API Key

### 1. Obter API Key da Anthropic

1. Acesse [console.anthropic.com](https://console.anthropic.com/)
2. Crie uma conta gratuita
3. Vá em **API Keys**
4. Clique em **Create Key**
5. Copie sua chave (começa com `sk-ant-`)

### 2. Configurar na Ferramenta

1. Abra a ferramenta no navegador
2. Cole sua API Key no campo indicado
3. Clique em **Salvar**
4. Status mudará para "API Key configurada ✓"

> **⚠️ Importante:** A API Key fica armazenada apenas no seu navegador (localStorage) e nunca é enviada para outros servidores além da Anthropic.

### 💰 Custos da API

- Anthropic oferece **$5 em créditos gratuitos** para novos usuários
- Cada geração de plano custa aproximadamente **$0.01 - $0.02**
- Com os créditos gratuitos você pode gerar **250-500 planos**

## 📖 Como Usar

### Passo a Passo

1. **Configure sua API Key** (apenas uma vez)
2. **Descreva o problema** em detalhes no campo de texto
   - Seja específico
   - Inclua dados quantitativos se possível
   - Explique o contexto
3. **Clique em "Gerar Plano 5W2H com IA"**
4. **Aguarde 5-10 segundos** enquanto a IA analisa
5. **Revise o plano gerado**
6. **Baixe o PDF** para apresentar ou compartilhar

### Exemplos de Problemas

**✅ Bom exemplo:**
```
Nossa equipe de vendas não está batendo as metas mensais. 
As vendas caíram 30% nos últimos 3 meses, a motivação está 
baixa e perdemos 2 clientes importantes. O time reclama de 
falta de treinamento e ferramentas inadequadas. Precisamos 
reverter essa situação urgentemente.
```

**❌ Exemplo vago:**
```
Vendas estão ruins.
```

## 🎯 Casos de Uso

### Para Gestores
- Estruturar problemas complexos
- Criar planos de ação para a equipe
- Documentar decisões estratégicas

### Para Consultores
- Gerar planos de ação para clientes
- Documentar análises de problemas
- Criar relatórios profissionais

### Para Analistas
- Estruturar projetos de melhoria
- Criar planos de qualidade
- Documentar processos

### Para Estudantes
- Aprender metodologia 5W2H
- Realizar trabalhos acadêmicos
- Praticar análise de problemas

## 📊 Exemplos de Planos Gerados

<details>
<summary><strong>Problema: Queda nas Vendas</strong></summary>

**What:** Implementar programa de capacitação em vendas consultivas e renovar ferramentas de CRM

**Why:** Para recuperar a performance da equipe, aumentar a motivação e reconquistar clientes perdidos, visando reverter a queda de 30% nas vendas

**Where:** Sede da empresa (treinamentos presenciais) e plataforma online para acompanhamento contínuo

**When:** Início imediato, com programa de 90 dias (Janeiro a Março 2025)

**Who:** Gerente de Vendas (coordenação), Consultoria externa de vendas (treinamento), Equipe de TI (ferramentas)

**How:** 
1. Contratar consultoria especializada em vendas B2B
2. Realizar diagnóstico individual com cada vendedor
3. Implementar treinamento intensivo (40h)
4. Adquirir e configurar novo sistema de CRM
5. Estabelecer acompanhamento semanal de resultados

**How Much:** R$ 45.000 (consultoria R$ 25.000 + CRM R$ 15.000 + materiais R$ 5.000)

</details>

<details>
<summary><strong>Problema: Alta Rotatividade de Funcionários</strong></summary>

**What:** Reestruturar política de recursos humanos com foco em retenção de talentos

**Why:** Para reduzir turnover de 40% para 15%, diminuir custos com recrutamento e melhorar clima organizacional

**Where:** Toda a empresa, com foco inicial nos departamentos com maior rotatividade

**When:** Implementação gradual em 6 meses (Fevereiro a Julho 2025)

**Who:** Diretoria de RH, Gestores de cada área, Consultoria de clima organizacional

**How:**
1. Realizar pesquisa de clima organizacional
2. Reestruturar plano de cargos e salários
3. Criar programa de desenvolvimento de carreira
4. Implementar política de benefícios flexíveis
5. Estabelecer programa de reconhecimento

**How Much:** R$ 180.000 (ajustes salariais R$ 120.000 + consultoria R$ 40.000 + benefícios R$ 20.000)

</details>

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Veja como você pode ajudar:

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a Branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um Pull Request

### Ideias de Contribuição

- 🌍 Tradução para outros idiomas
- 🎨 Melhorias no design
- 📱 Versão mobile app
- 📊 Gráficos e visualizações
- 🔧 Novas funcionalidades
- 📝 Mais exemplos práticos

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👤 Autor

**Seu Nome**

- LinkedIn: [@seu-perfil](https://linkedin.com/in/seu-perfil)
- GitHub: [@seu-usuario](https://github.com/seu-usuario)
- Email: seu.email@exemplo.com

## 🙏 Agradecimentos

- [Anthropic](https://www.anthropic.com/) pela API do Claude
- [jsPDF](https://github.com/parallax/jsPDF) pela biblioteca de geração de PDFs
- Comunidade open source

## 📞 Suporte

Encontrou um bug? Tem uma sugestão?

- 🐛 [Reporte um Bug](https://github.com/seu-usuario/gerador-5w2h-ia/issues)
- 💡 [Sugira uma Feature](https://github.com/seu-usuario/gerador-5w2h-ia/issues)
- 📧 Entre em contato: seu.email@exemplo.com

## ⭐ Mostre seu Apoio

Se este projeto te ajudou, deixe uma ⭐!

## 📈 Roadmap

- [ ] Salvar histórico de planos gerados
- [ ] Exportar para Excel/CSV
- [ ] Compartilhar planos por link
- [ ] Versão em inglês e espanhol
- [ ] Integração com Trello/Asana
- [ ] Análise de viabilidade do plano
- [ ] Sugestões de métricas de acompanhamento
- [ ] Modo escuro

---

<div align="center">

**Desenvolvido com ❤️ e ☕ usando IA**

[⬆ Voltar ao topo](#-gerador-de-plano-de-ação-5w2h-com-ia)

</div>
