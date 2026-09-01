# Projeto Dev em Dobro: Dragões

Uma página web interativa inspirada no universo de *House of the Dragon*. O projeto apresenta um carrossel visual com dragões da Casa Targaryen: ao selecionar um dos indicadores na parte inferior da tela, a imagem de fundo, o nome e a descrição exibidos são atualizados ao mesmo tempo.

## Demonstração

Acesse a versão publicada no GitHub Pages:

[Projeto Dev em Dobro: Dragões](https://lfbond.github.io/projeto_dev_em_dobro_dragoes/)

![Prévia do projeto](https://github.com/user-attachments/assets/c5cb90d0-b886-4c4e-8d19-f0293314e1fa)

## Dragões apresentados

O carrossel contém informações sobre:

- Balerion, o Terror Negro;
- Syrax;
- Arrax;
- Caraxes, o Wyrm de Sangue;
- Seasmoke;
- Vermax;
- Vhagar.

## Funcionalidades

- Seleção de dragões por indicadores clicáveis.
- Alteração sincronizada da imagem, do título e da descrição.
- Animação suave na troca das imagens.
- Layout responsivo para desktop, tablet e dispositivos móveis.
- Imagens em tela cheia com sobreposição escura para manter o texto legível.

## Tecnologias

- **HTML5** para a estrutura da página.
- **CSS3** para o layout, a responsividade, a animação e a aparência do carrossel.
- **JavaScript** para os eventos de clique e a alternância das classes ativas.
- **Google Fonts** para a fonte Poppins.
- Fonte local `GOT.ttf` para os títulos dos dragões.

## Estrutura do projeto

```text
.
├── index.html                 # Página principal
├── README.md                  # Documentação do projeto
└── src/
    ├── css/
    │   ├── reset.css          # Normalização dos estilos
    │   ├── estilos.css        # Estilos principais e animações
    │   └── responsivo.css     # Regras para telas menores
    ├── fontes/
    │   └── GOT.ttf            # Fonte usada nos títulos
    ├── imagens/               # Imagens dos sete dragões
    └── js/
        └── index.js           # Lógica de interação do carrossel
```

## Como executar localmente

O projeto não possui dependências ou etapa de compilação. Basta ter um navegador atualizado.

### Opção 1: abrir diretamente

1. Clone este repositório:

   ```bash
   git clone https://github.com/lfbond/projeto_dev_em_dobro_dragoes.git
   ```

2. Entre na pasta do projeto:

   ```bash
   cd projeto_dev_em_dobro_dragoes
   ```

3. Abra o arquivo `index.html` no navegador.

### Opção 2: usar um servidor local

Servir os arquivos localmente é útil para manter o mesmo comportamento de uma hospedagem web. Com Python instalado, execute na pasta do projeto:

```bash
python -m http.server 8000
```

Depois, acesse [http://localhost:8000](http://localhost:8000) no navegador. Para encerrar o servidor, pressione `Ctrl+C` no terminal.

## Como contribuir

1. Crie um fork do repositório.
2. Crie uma branch para sua alteração:

   ```bash
   git checkout -b minha-alteracao
   ```

3. Faça as mudanças e teste a página em diferentes tamanhos de tela.
4. Registre as alterações:

   ```bash
   git add .
   git commit -m "descreve a alteração"
   ```

5. Envie a branch e abra um pull request.

Correções, melhorias de acessibilidade, novas informações e ajustes visuais são bem-vindos. Para mudanças maiores, abra uma issue antes para alinhar a proposta.

## Licença

Licença Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
