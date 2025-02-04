# Instalação

Para instalar o **Apidog**, você pode seguir alguns passos simples, dependendo da plataforma que você está utilizando (Windows, macOS ou Linux). O **Apidog** oferece uma versão desktop para essas plataformas, o que facilita o uso e a integração com seu fluxo de trabalho de desenvolvimento.

Aqui está um passo a passo geral de como instalar o **Apidog**:

### 1. **Acesse o site oficial do Apidog**
   - Vá até o site oficial do Apidog: [https://apidog.net](https://apidog.net).

### 2. **Baixar o instalador**
   - Na página inicial, clique no botão de download, que geralmente oferece as opções para **Windows**, **macOS** e **Linux**.
   - Escolha a versão correspondente ao seu sistema operacional e inicie o download.

### 3. **Instalação no Windows**
   - Depois de baixar o instalador para Windows (arquivo `.exe`), clique duas vezes no arquivo para iniciar o processo de instalação.
   - Siga as instruções do assistente de instalação. Geralmente, você só precisa confirmar as opções padrão de instalação e clicar em **Instalar**.
   - Após a instalação, clique em **Finalizar** para concluir a instalação. O Apidog estará disponível no menu Iniciar.

### 4. **Instalação no macOS**
   - Baixe o instalador para macOS (arquivo `.dmg`).
   - Após o download, abra o arquivo `.dmg` e arraste o ícone do Apidog para a pasta **Aplicativos**.
   - Você pode agora abrir o Apidog diretamente da pasta **Aplicativos**.

### 5. **Instalação no Linux**
   - Para Linux, o processo pode variar dependendo da distribuição. Geralmente, o **Apidog** está disponível como um pacote **AppImage** ou pode ser instalado usando **snap**.
   
   **Usando AppImage**:
   - Baixe o arquivo **AppImage** para Linux.
   - Torne o arquivo executável com o comando:
     ```bash
     chmod +x apidog-x.x.x.AppImage
     ```
   - Execute o arquivo **AppImage**:
     ```bash
     ./apidog-x.x.x.AppImage
     ```

   **Usando Snap** (caso tenha suporte a Snap):
   - Em distribuições que suportam **Snap**, você pode instalar diretamente com o seguinte comando:
     ```bash
     sudo snap install apidog
     ```

### 6. **Abrir o Apidog**
   - Após a instalação, basta abrir o **Apidog** na sua plataforma:
     - **Windows**: Procure pelo Apidog no menu iniciar.
     - **macOS**: Abra o Apidog na pasta **Aplicativos**.
     - **Linux**: Execute o arquivo AppImage ou, se instalado via Snap, execute o comando `apidog` no terminal.

### 7. **Configuração inicial**
   - Ao abrir o Apidog pela primeira vez, você poderá ser solicitado a criar uma conta ou fazer login (caso já tenha uma conta).
   - Depois disso, você pode começar a criar e gerenciar suas APIs, definir endpoints, realizar testes, e gerar a documentação interativa.

---

### Observações:
- **Dependências**: O Apidog não exige dependências adicionais em sistemas operacionais modernos, mas certifique-se de ter as permissões necessárias para instalar software no seu sistema (especialmente em Linux).
- **Atualizações**: O Apidog geralmente verifica se há atualizações automaticamente, mas você também pode verificar a página oficial regularmente para baixar versões mais recentes.

Pronto! Agora você pode começar a usar o Apidog para gerenciar suas APIs de maneira fácil e eficiente.