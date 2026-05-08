# Contribuindo para o Kit Fusion

Obrigado por considerar contribuir para o Kit Fusion! Este documento fornece diretrizes e instruções para ajudar você a contribuir de forma efetiva.

## 📋 Índice

- [Código de Conduta](#código-de-conduta)
- [Como Contribuir](#como-contribuir)
- [Processo de Pull Request](#processo-de-pull-request)
- [Guia de Estilo](#guia-de-estilo)

## 🤝 Código de Conduta

Por favor, note que este projeto é lançado com um [Contributor Code of Conduct](CODE_OF_CONDUCT.md). Ao participar deste projeto você concorda em respeitar seus termos.

## 💡 Como Contribuir

### Reportando Bugs

Antes de criar um relatório de bug, verifique a lista de issues pois você pode descobrir que não precisa criar um novo. Quando estiver criando um relatório de bug, inclua o máximo de detalhes possível:

* **Use um título claro e descritivo** para a issue
* **Descreva os passos exatos** que reproduzem o problema
* **Forneça exemplos específicos** para demonstrar os passos
* **Descreva o comportamento observado** e aponte o que está errado com ele
* **Explique qual é o comportamento esperado** e por quê
* **Inclua screenshots/GIFs** se possível

### Sugestões de Melhorias

Sugestões de melhorias são sempre bem-vindas. Para enviar uma sugestão:

* **Use um título claro e descritivo**
* **Forneça uma descrição passo a passo** da sugestão
* **Forneça exemplos específicos** para demonstrar os passos
* **Descreva o comportamento atual** e o comportamento esperado
* **Explique o porquê** dessa melhoria seria útil

## 🔄 Processo de Pull Request

1. **Fork o repositório** e crie uma branch para sua feature/fix
   ```bash
   git checkout -b feature/minha-feature
   ```

2. **Faça suas alterações** seguindo o guia de estilo

3. **Teste suas alterações** em diferentes navegadores

4. **Commit suas alterações** com mensagens claras
   ```bash
   git commit -m "Add/Fix: Descrição clara da mudança"
   ```

5. **Push para sua branch**
   ```bash
   git push origin feature/minha-feature
   ```

6. **Abra um Pull Request** com:
   - Título claro descrevendo a mudança
   - Descrição detalhada do que foi alterado e por quê
   - Screenshots/GIFs se relevante
   - Referência a issues relacionadas

## 🎨 Guia de Estilo

### HTML
- Use tags semânticas HTML5
- Mantenha indentação consistente (2 espaços)
- Use classes Tailwind CSS para estilização

### CSS/Tailwind
- Use classes utilitárias do Tailwind quando possível
- Evite CSS customizado dentro de `<style>` tags
- Mantenha consistência com o design system existente

### JavaScript
- Use JavaScript vanilla (sem dependências desnecessárias)
- Comente código complexo
- Siga as convenções de nomenclatura camelCase

### Commits
- Use prefixos descritivos: `Add:`, `Fix:`, `Update:`, `Remove:`, `Refactor:`
- Mensagens em inglês preferencialmente
- Seja conciso mas descritivo
- Exemplo: `Fix: Corrigir renderização de ícones no mobile`

### Variáveis de Cor
Use o design system definido:
```javascript
brand: "#E11D24"           // Vermelho principal
brandDark: "#B91C1C"       // Vermelho escuro
surface: "#111111"         // Superfície escura
card: "#1A1A1A"            // Cor de cards
```

### Tipografia
Use as fontes definidas:
- **Headings**: Oswald
- **Body**: Source Sans 3

## 📋 Checklist para Pull Request

- [ ] Testei em navegadores modernos (Chrome, Firefox, Safari, Edge)
- [ ] Testei em dispositivos mobile
- [ ] Minhas alterações seguem o guia de estilo do projeto
- [ ] Adicionei comentários no código quando necessário
- [ ] Atualizei a documentação se necessário
- [ ] Minhas alterações não geram warnings no console

## 🚀 Tipos de Contribuição Bem-Vindos

- 🐛 Bug fixes
- ✨ Novas features
- 📝 Melhorias na documentação
- 🎨 Melhorias de design
- 📱 Melhorias de responsividade
- ♿ Melhorias de acessibilidade
- ⚡ Otimizações de performance

## ❓ Dúvidas?

Sinta-se livre para abrir uma issue com a tag `question` se tiver dúvidas!

---

Obrigado por contribuir para tornar o Kit Fusion ainda melhor! 🎉
