# Sistema de Pagamento - Xandinho

Sistema de rastreamento de pagamentos com design moderno e funcionalidades avançadas.

## 🚀 Funcionalidades

- ✅ Rastreamento de dívida (R$ 124.800,00)
- ✅ Confirmação de pagamentos com senha (891372)
- ✅ Histórico de pagamentos com status pendente/confirmado
- ✅ Exclusão de pagamentos
- ✅ Aba de favorecido com informações completas
- ✅ Formatação de valores com centavos em superscript
- ✅ Design dark theme moderno com Lucide icons
- ✅ Persistência de dados com localStorage
- ✅ Interface mobile-first responsiva

## 📦 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/alexandre-dpaula/folhaPG.git
cd folhaPG
```

2. Adicione a foto de perfil:
   - Salve sua foto de perfil como `alexandre-profile.jpg` na pasta raiz
   - Ou use qualquer URL de imagem no código

3. Abra o arquivo `index.html` em qualquer navegador

## 🖼️ Foto de Perfil

Para adicionar sua foto de perfil:

1. **Opção 1 - Arquivo Local:**
   - Salve a imagem como `alexandre-profile.jpg` na mesma pasta do `index.html`

2. **Opção 2 - URL Online:**
   - Edite o arquivo `index.html` na linha 1049
   - Substitua `src="alexandre-profile.jpg"` pela URL da sua imagem

3. **Fallback Automático:**
   - Se a imagem não for encontrada, será exibido um avatar gerado automaticamente

## 🎨 Tecnologias

- HTML5
- CSS3 (Glass morphism, Gradients, Animations)
- JavaScript (ES6+)
- Lucide Icons
- Google Fonts (Inter)

## 💾 Persistência de Dados

O sistema salva automaticamente todos os dados no localStorage do navegador:
- Histórico de pagamentos
- Status de confirmação
- Resumo mensal

## 🔐 Senha de Confirmação

A senha padrão para confirmar pagamentos é: **891372**

Para alterá-la, edite a constante `SENHA_CONFIRMACAO` no JavaScript.

## 📱 Compatibilidade

- ✅ Chrome/Edge (versão mais recente)
- ✅ Firefox (versão mais recente)
- ✅ Safari (versão mais recente)
- ✅ Mobile (iOS/Android)

## 🤝 Como Contribuir

Este projeto foi criado com Claude Code. Para fazer alterações:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto é de uso pessoal.

---

🤖 Generated with [Claude Code](https://claude.com/claude-code)
