# ca-sistema-juridico
Sistema jurídico desenvolvido em Python para gerenciamento de clientes, processos, pendências e consultas à API Pública do DataJud.

# CA Sistema Jurídico

Sistema desktop desenvolvido em Python para auxiliar pequenos escritórios
de advocacia na organização de clientes, processos e movimentações processuais.

## Sobre o projeto

O CA Sistema Jurídico nasceu a partir de uma necessidade real identificada
em um escritório de advocacia: reduzir o tempo gasto com organização de
processos, consultas manuais e acompanhamento de movimentações.

A aplicação permite cadastrar clientes, vincular processos, consultar dados
processuais por meio da API Pública do DataJud e registrar pendências
automaticamente quando novas movimentações são identificadas.

## Principais funcionalidades

- Cadastro, consulta, edição e exclusão de clientes
- Cadastro manual de processos
- Cadastro de processos pela API Pública do DataJud
- Identificação automática do tribunal
- Consulta local de processos cadastrados
- Atualização individual de processos
- Atualização de todos os processos
- Comparação de movimentações processuais
- Geração automática de pendências
- Persistência local em arquivos JSON
- Executável para Windows criado com PyInstaller

## Tecnologias utilizadas

- Python
- API REST
- API Pública do DataJud
- JSON
- Requests
- Git
- GitHub
- PyInstaller

## Fluxo principal

Cliente cadastrado
    ↓
Processo informado
    ↓
Identificação do tribunal
    ↓
Consulta ao DataJud
    ↓
Confirmação dos dados
    ↓
Armazenamento local
    ↓
Atualizações e geração de pendências

## Estrutura do projeto

```text
ca-sistema-juridico/
├── app.py
├── cliente.py
├── processos.py
├── pendencias.py
├── datajud.py
├── persistencia.py
├── menus.py
├── dados/
└── docs/
