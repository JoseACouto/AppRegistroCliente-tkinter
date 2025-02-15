```markdown

# Sistema de Gestão de Clientes

Este é um sistema simples de cadastro de clientes, desenvolvido em Python, utilizando a biblioteca `customtkinter` para a criação da interface gráfica. O objetivo principal é permitir o registro de informações essenciais sobre os clientes, como nome, contato, idade, gênero, endereço e observações adicionais, além de armazenar esses dados em um arquivo Excel.

## Funcionalidades

- **Cadastro de clientes**: Preencha os campos obrigatórios e salve os dados em uma planilha Excel.
- **Alteração de tema**: O sistema permite a troca de temas (Claro, Escuro, ou Automático) para atender às preferências visuais do usuário.
- **Validação de dados**: Verificação de campos obrigatórios antes do envio para garantir que todos os dados essenciais foram preenchidos.
- **Armazenamento de dados**: Os dados dos clientes são armazenados em um arquivo Excel (`Clientes.xlsx`), permitindo fácil acesso e manipulação.

## Tecnologias Utilizadas

- **Python 3.11.1**: A versão utilizada para o desenvolvimento.
- **CustomTkinter**: Biblioteca para criar interfaces gráficas com aparência moderna e customizável.
- **OpenPyXL**: Utilizado para ler e escrever dados em arquivos Excel.
- **Tkinter**: Biblioteca padrão para interface gráfica do Python.

## Requisitos

Para rodar este sistema, você precisa ter o Python instalado em sua máquina, além das bibliotecas abaixo:

- `customtkinter`
- `openpyxl`

Você pode instalar essas bibliotecas utilizando o `pip`:

```bash
pip install customtkinter openpyxl
```

## Como Usar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/sistema-gestao-clientes.git
    ```

2. Navegue até a pasta do projeto:
    ```bash
    cd sistema-gestao-clientes
    ```

3. Execute o script Python:
    ```bash
    python app.py
    ```

4. Preencha os campos do formulário e clique em "Salvar dados" para registrar as informações no arquivo `Clientes.xlsx`.

## Estrutura do Arquivo Excel

Ao salvar os dados, o sistema cria um arquivo Excel chamado `Clientes.xlsx` (se ele ainda não existir), com a seguinte estrutura:

| Nome Completo | Contato | Idade | Gênero | Endereço | Observações |
|---------------|---------|-------|--------|----------|-------------|
| João Silva    | 123456  | 30    | Masculino | Rua ABC, 123 | Nenhuma observação |

## Personalização de Tema

O sistema permite a escolha entre três temas:

- **Light**: Tema claro.
- **Dark**: Tema escuro.
- **System**: Tema baseado nas configurações do sistema.

Você pode escolher o tema preferido no canto inferior da interface.

## Contribuindo

Se você deseja contribuir para este projeto, siga as etapas abaixo:

1. Faça um fork deste repositório.
2. Crie uma nova branch (`git checkout -b feature/nova-funcionalidade`).
3. Realize suas alterações e commit (`git commit -am 'Adicionando nova funcionalidade'`).
4. Envie suas alterações (`git push origin feature/nova-funcionalidade`).
5. Abra um Pull Request.

Link da aula do projeto : https://www.youtube.com/watch?v=Oq2ekGfKmx8
