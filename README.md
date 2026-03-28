# 📱 Gerador de Mensagem RH - BGP

Uma ferramenta web moderna e intuitiva para profissionais de RH criarem mensagens personalizadas de convite para candidatos, com formatação pronta para WhatsApp.

## ✨ Funcionalidades

- 🎨 **Interface Dark Mode** - Design moderno e agradável com tema escuro
- 📝 **Campos Personalizáveis** - Nome do candidato, referência, função, salário e local do projeto
- 🎁 **Benefícios Dinâmicos** - Adicione, remova ou edite benefícios com um clique
- 📋 **Visualização em Tempo Real** - A mensagem é atualizada instantaneamente enquanto você digita
- 💬 **Cópia para WhatsApp** - Botão especial que copia a mensagem formatada diretamente para a área de transferência
- 📱 **Responsivo** - Funciona perfeitamente em desktop, tablet e dispositivos móveis

## 🚀 Como Usar

1. **Preencha os dados do candidato:**
   - Nome do candidato
   - Referência (quem indicou)
   - Função desejada
   - Salário base
   - Local do projeto

2. **Personalize os benefícios:**
   - Clique em qualquer badge de benefício para editar o texto
   - Use o botão "+ Adicionar Benefício" para incluir novos itens
   - Passe o mouse sobre um benefício e clique em "✖" para removê-lo
   - Utilize "↺ Resetar" para restaurar a lista padrão

3. **Copie a mensagem:**
   - Visualize a mensagem pronta na área de pré-visualização
   - Clique em "💬 Copiar para WhatsApp"
   - Cole no WhatsApp e envie para o candidato

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização moderna com flexbox, grid e animações
- **JavaScript (Vanilla)** - Lógica interativa sem dependências externas
- **Font Inter** - Tipografia moderna e legível

## 📦 Estrutura do Projeto
```
├── index.html # Arquivo principal da aplicação
└── README.md # Documentação do projeto
```

text

## 🎯 Exemplo de Uso

**Entrada:**
- Candidato: João Silva
- Referência: Mecânico de Vibro (Juninho)
- Função: OPERADOR DE VIBROS
- Salário: R$ 4.638,56
- Local: Projeto no Paraná em Santa Maria do Oeste

**Saída:**

```
Bom dia, João Silva!

Meu nome é Lucas, sou do RH da BGP. Recebi seu contato através do Mecânico de Vibro (Juninho) e gostaria de saber se você tem interesse em atuar no Projeto no Paraná em Santa Maria do Oeste, para a função de OPERADOR DE VIBROS.

O salário base é de R$ 1.621,00.

Benefícios:

✅ Plano de saúde SulAmérica

🦷 Plano Odontológico SulAmérica

🛡️ Seguro de vida

🏠 Alojamento

🥧 Alimentação

👔 Lavanderia

💲 Ajuda de custo viagem

Aguardo seu retorno.
```



## 💡 Dicas de Uso

- **Edição rápida:** Clique diretamente nos badges de benefícios para alterar o texto
- **Remoção:** Passe o mouse sobre o benefício e clique no "✖" que aparece
- **Adição:** Use o botão "+ Adicionar Benefício" para incluir itens personalizados
- **Reset:** Se quiser voltar à lista original, clique em "↺ Resetar"

## 🎨 Personalização

Você pode facilmente personalizar:
- Cores e estilos no `<style>` do documento
- Mensagem padrão editando a função `generateMessage()`
- Benefícios padrão alterando o array `defaultBenefits` no script

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se à vontade para usar, modificar e distribuir conforme necessário.

## 👨‍💻 Autor

Desenvolvido para otimizar o processo de recrutamento e seleção da BGP.

---

**✨ Dica:** A ferramenta é totalmente offline e não requer servidor - basta abrir o arquivo HTML em qualquer navegador moderno!
