# **Design System — Havan**

Versão 1.0  
Site institucional

**Objetivo:** estabelecer padrões visuais e funcionais para o site institucional da Havan, garantindo consistência entre as páginas, facilidade de manutenção, acessibilidade e boa experiência em computadores, tablets e celulares.

O sistema utiliza exatamente a identidade visual informada, sem modificar o logotipo ou propor novas cores e tipografias.

## **1\. Paleta de cores**

Cores principais e complementares com seus códigos HEX.

**Azul-marinho**

\#002D72 · Primária

**Branco**

\#FFFFFF · Secundária

**Azul vibrante**

\#1E64F0 · Complementar

**Amarelo**

\#FFD200 · Destaques

**Cinza-claro**

\#F5F6FA · Fundos

**Grafite**

\#1F2937 · Textos

### **Aplicação das cores**

| Elemento | Cor |
| ----- | ----- |
| Cabeçalho | Azul-marinho |
| Rodapé | Azul-marinho |
| Botão principal | Azul-marinho |
| Botão secundário | Branco |
| Links | Azul vibrante |
| Promoções | Amarelo |
| Fundo de seções | Cinza-claro |
| Textos principais | Grafite |
| Fundo geral | Branco |

**Regra:** o amarelo deve ser utilizado em destaques pontuais, evitando seu uso em grandes áreas de texto. Verificar o contraste das combinações antes da implementação.

## **2\. Tipografia**

O projeto utilizará duas famílias tipográficas:

* **Montserrat:** títulos e chamadas de destaque.  
* **Roboto:** parágrafos, menus, formulários e informações gerais.

### **Hierarquia tipográfica**

| Elemento | Fonte | Tamanho | Peso |
| ----- | ----- | ----- | ----- |
| H1 | Montserrat | 36 px | 700 |
| H2 | Montserrat | 28 px | 700 |
| H3 | Montserrat | 24 px | 600 |
| H4 | Montserrat | 20 px | 600 |
| H5 | Montserrat | 18 px | 600 |
| H6 | Montserrat | 16 px | 600 |
| Parágrafo | Roboto | 16 px | 400 |
| Texto auxiliar | Roboto | 14 px | 400 |
| Legenda | Roboto | 12 px | 400 |
| Botões | Roboto | 16 px | 600 |

### **Regras tipográficas**

* Utilizar títulos com hierarquia clara.  
* Evitar parágrafos muito longos.  
* Manter espaçamento confortável entre linhas.  
* Não utilizar muitas variações de peso na mesma seção.  
* Garantir legibilidade em dispositivos móveis.

## **3\. Botões e estados**

Serão utilizados três estilos principais.

**Botão primário**

**CONHEÇA A HAVAN**

Fundo azul-marinho, texto branco e bordas arredondadas.

**Botão secundário**

**SAIBA MAIS**

Fundo branco, texto e borda azul-marinho.

**Botão de destaque**

**VER OFERTAS**

Fundo amarelo e texto grafite.

### **Estados dos botões**

| Estado | Comportamento |
| ----- | ----- |
| Normal | Aparência padrão |
| Hover | Alteração sutil de fundo |
| Focus | Contorno visível |
| Active | Indicação visual de pressionamento |
| Disabled | Opacidade reduzida e sem interação |
| Loading | Indicador de carregamento |

**Dimensões recomendadas:**

* Altura: 44 a 48 px.  
* Padding horizontal: 20 a 24 px.  
* Border-radius: 6 px.  
* Texto: 16 px.

## **4\. Formulários**

Os formulários devem ser simples, organizados e fáceis de preencher.

**Exemplo — Formulário de contato**

Nome completo

Digite seu nome

E-mail

Digite seu e-mail

Assunto

Selecione um assunto

Mensagem

Digite sua mensagem

**ENVIAR MENSAGEM**

### **Padrões dos campos**

| Propriedade | Definição |
| ----- | ----- |
| Altura | 44 a 48 px |
| Borda | 1 px solid |
| Cor da borda | Cinza neutro |
| Fundo | Branco |
| Texto | Grafite |
| Border-radius | 6 px |
| Espaçamento | 16 px |

### **Estados dos campos**

* Normal: borda neutra.  
* Focus: borda azul vibrante e indicação visual de foco.  
* Error: borda de erro e mensagem explicativa.  
* Success: indicação de preenchimento válido.  
* Disabled: campo visualmente desabilitado.

Os rótulos devem permanecer visíveis mesmo depois que o usuário preencher os campos.

## **5\. Cards e elementos reutilizáveis**

Os cards serão utilizados para organizar produtos, departamentos, ofertas e informações institucionais.

**Card de produto**

Nome, descrição e preço.

**VER DETALHES**

**Card de departamento**

Imagem e nome da categoria.

**ACESSAR**

**Card de oferta**

Campanha e informações promocionais.

**CONFERIR**

**Card de loja**

Nome, endereço e horário.

**VER LOCALIZAÇÃO**

### **Padrão dos cards**

* Fundo branco.  
* Bordas discretas.  
* Border-radius de 8 px.  
* Imagem na parte superior.  
* Conteúdo organizado abaixo.  
* Botão ou link na parte inferior.  
* Espaçamento interno de 16 px.

## **6\. Bordas, sombras e espaçamentos**

### **Bordas**

| Elemento | Border-radius |
| ----- | ----- |
| Botões | 6 px |
| Campos | 6 px |
| Cards | 8 px |
| Banners | 8 px |
| Imagens | 6 px |

### **Sombras**

| Tipo | Aplicação |
| ----- | ----- |
| Sem sombra | Elementos simples |
| Sombra leve | Cards |
| Sombra média | Menus suspensos |
| Sombra destacada | Modais e janelas sobrepostas |

Sugestão de sombras em CSS:

```
--shadow-sm: 0 1px 3px rgba(0, 0, 0, 0.08);
--shadow-md: 0 4px 12px rgba(0, 0, 0, 0.10);
--shadow-lg: 0 8px 24px rgba(0, 0, 0, 0.14);
```

### **Escala de espaçamento**

| Token | Valor |
| ----- | ----- |
| space-1 | 4 px |
| space-2 | 8 px |
| space-3 | 12 px |
| space-4 | 16 px |
| space-5 | 24 px |
| space-6 | 32 px |
| space-7 | 48 px |
| space-8 | 64 px |

## **7\. Responsividade**

O site deverá adaptar sua estrutura conforme o tamanho da tela.

**Desktop**

1200 px ou mais

LOGO \| MENU \| PESQUISA

BANNER PRINCIPAL

**Tablet**

768–1199 px

LOGO \| MENU \| PESQUISA

BANNER ADAPTADO

**Mobile**

Até 767 px

☰　LOGO　⌕

BANNER

### **Regras responsivas**

* Desktop: menu completo e conteúdo em múltiplas colunas.  
* Tablet: redução das colunas e adaptação dos espaçamentos.  
* Mobile: menu recolhido, conteúdo vertical e botões adequados ao toque.  
* Imagens: utilizar dimensões flexíveis e `object-fit` adequado.  
* Evitar rolagem horizontal.  
* Preservar a hierarquia dos títulos em todas as resoluções.

## **8\. Componentes reutilizáveis nas páginas**

| Componente | Páginas |
| ----- | ----- |
| Cabeçalho | Todas |
| Menu de navegação | Todas |
| Rodapé | Todas |
| Barra de pesquisa | Início, produtos, lojas e atendimento |
| Banner | Início e ofertas |
| Card de produto | Produtos e ofertas |
| Card de departamento | Início e departamentos |
| Card de loja | Nossas lojas |
| Breadcrumb | Páginas internas |
| Formulário | Contato |
| Accordion | Atendimento e perguntas frequentes |
| Paginação | Listagem de produtos |
| Botões | Todas |
| Modal | Quando necessário |
| Mensagens de feedback | Formulários e interações |

## **9\. Organização técnica para CSS ou Tailwind**

### **Tokens CSS**

```
:root {
  /* Cores */
  --color-primary: #002D72;
  --color-secondary: #FFFFFF;
  --color-blue: #1E64F0;
  --color-yellow: #FFD200;
  --color-gray-light: #F5F6FA;
  --color-text: #1F2937;

  /* Tipografia */
  --font-heading: "Montserrat", sans-serif;
  --font-body: "Roboto", sans-serif;

  /* Tamanhos */
  --text-xs: 12px;
  --text-sm: 14px;
  --text-base: 16px;
  --text-lg: 18px;
  --text-xl: 20px;
  --text-2xl: 24px;
  --text-3xl: 28px;
  --text-4xl: 36px;

  /* Espaçamentos */
  --space-1: 4px;
  --space-2: 8px;
  --space-3: 12px;
  --space-4: 16px;
  --space-5: 24px;
  --space-6: 32px;
  --space-7: 48px;
  --space-8: 64px;

  /* Bordas */
  --radius-sm: 6px;
  --radius-md: 8px;

  /* Sombras */
  --shadow-sm: 0 1px 3px rgba(0,0,0,.08);
  --shadow-md: 0 4px 12px rgba(0,0,0,.10);
}
```

### **Exemplo de configuração Tailwind CSS**

```
export default {
  theme: {
    extend: {
      colors: {
        havan: {
          primary: "#002D72",
          secondary: "#FFFFFF",
          blue: "#1E64F0",
          yellow: "#FFD200",
          gray: "#F5F6FA",
          text: "#1F2937",
        },
      },
      fontFamily: {
        heading: ["Montserrat", "sans-serif"],
        body: ["Roboto", "sans-serif"],
      },
      borderRadius: {
        havan: "6px",
        card: "8px",
      },
    },
  },
};
```

*O exemplo de Tailwind usa a configuração tradicional com `theme.extend`; a sintaxe poderá ser adaptada conforme a versão instalada.*

## **10\. Checklist de implementação**

* Cadastrar todas as cores como tokens.  
* Configurar Montserrat e Roboto.  
* Definir a hierarquia tipográfica.  
* Criar botões e seus estados.  
* Padronizar formulários.  
* Criar cards reutilizáveis.  
* Configurar bordas e sombras.  
* Definir espaçamentos.  
* Implementar os breakpoints.  
* Criar cabeçalho e rodapé compartilhados.  
* Testar acessibilidade e responsividade.  
* Conferir a preservação do logotipo oficial.

## **11\. Conclusão**

O Design System da Havan estabelece uma linguagem visual consistente para todas as páginas do site institucional. Com padrões definidos de cores, tipografia, componentes, espaçamentos e responsividade, o desenvolvimento poderá ser realizado de maneira organizada, reutilizável e escalável.

## **12\. Próxima etapa**

A implementação deve começar pela criação dos tokens e componentes globais no Figma ou no código. Depois, esses componentes serão aplicados às páginas: início, departamentos, produtos, ofertas, institucional, lojas, contato e atendimento.

