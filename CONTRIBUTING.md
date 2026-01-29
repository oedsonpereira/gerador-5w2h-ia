# 🤝 Contribuindo para o Gerador 5W2H com IA

Obrigado por considerar contribuir para este projeto! 🎉

Este documento contém diretrizes para contribuir com o projeto de forma eficiente e organizada.

## 📋 Código de Conduta

Este projeto segue um código de conduta. Ao participar, você concorda em manter um ambiente respeitoso e acolhedor para todos.

### Nossos Padrões

- Usar linguagem acolhedora e inclusiva
- Respeitar diferentes pontos de vista e experiências
- Aceitar críticas construtivas graciosamente
- Focar no que é melhor para a comunidade
- Mostrar empatia com outros membros da comunidade

## 🚀 Como Contribuir

### 1. Reportar Bugs

Encontrou um bug? Ajude-nos a melhorar!

**Antes de reportar:**
- Verifique se o bug já não foi reportado nas [Issues](https://github.com/oedsonpereira/gerador-5w2h-ia/issues)
- Certifique-se de estar usando a versão mais recente

**Como reportar:**
1. Abra uma nova [Issue](https://github.com/oedsonpereira/gerador-5w2h-ia/issues/new)
2. Use o template de bug report
3. Inclua:
   - Descrição clara do problema
   - Passos para reproduzir
   - Comportamento esperado vs atual
   - Screenshots (se aplicável)
   - Informações do ambiente (navegador, SO)

### 2. Sugerir Features

Tem uma ideia? Adoraríamos ouvir!

1. Verifique se não existe issue similar
2. Abra uma nova [Issue](https://github.com/oedsonpereira/gerador-5w2h-ia/issues/new)
3. Use o template de feature request
4. Descreva:
   - Problema que resolve
   - Solução proposta
   - Alternativas consideradas
   - Mockups (se tiver)

### 3. Contribuir com Código

#### Primeiros Passos

1. **Fork o repositório**
```bash
# Clique no botão "Fork" no GitHub
```

2. **Clone seu fork**
```bash
git clone https://github.com/seu-usuario/gerador-5w2h-ia.git
cd gerador-5w2h-ia
```

3. **Crie uma branch**
```bash
git checkout -b feature/nome-da-feature
# ou
git checkout -b fix/nome-do-bug
```

#### Diretrizes de Código

**HTML/CSS:**
- Indentação: 4 espaços
- Nomes de classes: kebab-case (`nome-da-classe`)
- Comentários em português
- Código semântico e acessível

**JavaScript:**
- Indentação: 4 espaços
- Nomes de variáveis: camelCase
- Nomes de funções: camelCase
- Nomes de constantes: UPPER_CASE
- Use `const` e `let`, evite `var`
- Comentários explicativos em lógicas complexas

**Exemplo:**
```javascript
// ✅ BOM
const apiKey = localStorage.getItem('api_key');
function generatePlan(problemDescription) {
    // Lógica aqui
}

// ❌ EVITAR
var api_key = localStorage.getItem('api_key');
function GeneratePlan(problem_description) {
    // Lógica aqui
}
```

#### Tipos de Contribuição

**🐛 Bug Fixes**
- Branch: `fix/descricao-curta`
- Commit: `fix: corrige problema com X`
- Inclua testes se possível

**✨ New Features**
- Branch: `feature/descricao-curta`
- Commit: `feat: adiciona funcionalidade X`
- Atualize documentação
- Adicione exemplos de uso

**📚 Documentation**
- Branch: `docs/descricao-curta`
- Commit: `docs: melhora documentação de X`
- Correções de português são bem-vindas!

**🎨 UI/UX**
- Branch: `ui/descricao-curta`
- Commit: `ui: melhora visual de X`
- Inclua screenshots antes/depois

**⚡ Performance**
- Branch: `perf/descricao-curta`
- Commit: `perf: otimiza X`
- Documente ganhos obtidos

#### Processo de Pull Request

1. **Atualize sua branch**
```bash
git fetch upstream
git rebase upstream/main
```

2. **Faça suas alterações**
```bash
# Desenvolva e teste localmente
```

3. **Commit suas mudanças**
```bash
git add .
git commit -m "feat: adiciona funcionalidade X"
```

Padrão de commits (Conventional Commits):
- `feat:` Nova funcionalidade
- `fix:` Correção de bug
- `docs:` Documentação
- `style:` Formatação (não afeta código)
- `refactor:` Refatoração
- `perf:` Melhoria de performance
- `test:` Testes
- `chore:` Tarefas diversas

4. **Push para seu fork**
```bash
git push origin feature/nome-da-feature
```

5. **Abra um Pull Request**
- Vá até o repositório original
- Clique em "New Pull Request"
- Descreva suas mudanças
- Referencie issues relacionadas

**Template de PR:**
```markdown
## Descrição
[Descreva o que foi feito]

## Motivação
[Por que essa mudança é necessária?]

## Tipo de mudança
- [ ] Bug fix
- [ ] Nova feature
- [ ] Breaking change
- [ ] Documentação

## Como testar
1. [Passo 1]
2. [Passo 2]
3. [Passo 3]

## Screenshots (se aplicável)
[Cole aqui]

## Checklist
- [ ] Código segue as diretrizes
- [ ] Comentei código complexo
- [ ] Atualizei documentação
- [ ] Testei localmente
```

### 4. Melhorar Documentação

A documentação é crucial! Contribuições aceitas:

- Corrigir typos e erros gramaticais
- Melhorar clareza das explicações
- Adicionar exemplos práticos
- Traduzir para outros idiomas
- Criar tutoriais em vídeo
- Escrever guias de uso

### 5. Contribuir com Exemplos

Tem um caso de uso interessante? Compartilhe!

1. Crie um arquivo em `/examples/`
2. Documente o problema e solução
3. Inclua o plano 5W2H gerado
4. Abra um PR

## 🎨 Estilo e Padrões

### Estrutura do Projeto

```
gerador-5w2h-ia/
├── 5w2h-generator-ai.html    # Arquivo principal
├── README.md                   # Documentação principal
├── LICENSE                     # Licença MIT
├── CONTRIBUTING.md            # Este arquivo
├── ESTRATEGIA-LINKEDIN.md     # Estratégia de marketing
├── ROTEIRO-VIDEO.md           # Roteiro para vídeos
└── examples/                  # Exemplos de uso
    └── caso-vendas.md
```

### Boas Práticas

**✅ FAZER:**
- Testar localmente antes de enviar PR
- Escrever código limpo e legível
- Documentar funções complexas
- Manter compatibilidade com navegadores modernos
- Ser respeitoso nos comentários
- Pedir ajuda quando necessário

**❌ EVITAR:**
- Fazer PRs muito grandes (divida em menores)
- Incluir código não relacionado
- Remover funcionalidades sem discussão
- Alterar estilo de código drasticamente
- Adicionar dependências desnecessárias

## 🐛 Reportar Problemas de Segurança

**NÃO** abra issues públicas para problemas de segurança.

Entre em contato diretamente:
- GitHub: [@oedsonpereira](https://github.com/oedsonpereira)
- LinkedIn: [@edson-pereira-oliveira](https://www.linkedin.com/in/edson-pereira-oliveira)

Responderemos em até 48h.

## 💡 Ideias para Contribuir

Não sabe por onde começar? Aqui estão algumas ideias:

### Iniciante (Good First Issue)
- [ ] Corrigir typos na documentação
- [ ] Adicionar exemplos de problemas
- [ ] Melhorar mensagens de erro
- [ ] Traduzir interface para inglês

### Intermediário
- [ ] Adicionar validação de campos
- [ ] Implementar modo escuro
- [ ] Melhorar responsividade mobile
- [ ] Adicionar mais templates de PDF

### Avançado
- [ ] Implementar histórico local de planos
- [ ] Adicionar export para Excel
- [ ] Criar sistema de compartilhamento
- [ ] Integração com APIs de gestão (Trello, Asana)

## 🏆 Reconhecimento

Todos os contribuidores serão adicionados ao [README.md](README.md) na seção "Contribuidores".

Contribuições significativas receberão:
- Menção especial no README
- Badge de contribuidor no GitHub
- Agradecimento nos posts do LinkedIn

## 📞 Dúvidas?

- 💬 Abra uma [Discussion](https://github.com/oedsonpereira/gerador-5w2h-ia/discussions)
- 🐛 [Issues](https://github.com/oedsonpereira/gerador-5w2h-ia/issues)
- 💼 LinkedIn: [@edson-pereira-oliveira](https://www.linkedin.com/in/edson-pereira-oliveira)

## 📚 Recursos Úteis

- [GitHub Guide](https://guides.github.com/)
- [Markdown Guide](https://www.markdownguide.org/)
- [Conventional Commits](https://www.conventionalcommits.org/)
- [Claude API Docs](https://docs.anthropic.com/)

---

**Obrigado por contribuir! 🎉**

Juntos estamos construindo uma ferramenta melhor para todos.

---

<div align="center">

Mantido por [@oedsonpereira](https://github.com/oedsonpereira)

[⬆ Voltar ao topo](#-contribuindo-para-o-gerador-5w2h-com-ia)

</div>
