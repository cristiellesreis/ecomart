# EcoMart - Integração com a OpenAI 🤖

Projeto simples desenvolvido em Java como primeiro teste de integração com a API da OpenAI. O objetivo é explorar recursos de **IA generativa** aplicados a um e-commerce fictício, incluindo categorização de produtos, contagem de tokens e geração de imagens.

---
## Funcionalidades
- **Categorização automática de produtos** usando *prompt engineering*.
- **Contagem de tokens** para monitorar o uso da API.
- **Geração de imagens** a partir de descrições textuais.

---
## Tecnologias utilizadas
- **Java 17+**
- **Maven**
- **API da [OpenAI](https://platform.openai.com/docs/overview)**
---

## 🚀 Como executar

**Clonar o repositório**
   
 ```bash
 git clone https://github.com/cristiellesreis/ecomart.git
 ```

**Acessar a pasta do projeto**

```bash
cd ecomart
```
---
## Configurar a chave da OpenAI

Crie um arquivo .env na raiz do projeto ou configure diretamente no código (dependendo da implementação):

```
OPENAI_API_KEY=sua_chave_aqui
```
---
## Compilar e executar com Maven

```
mvn clean install
mvn exec:java
```

---
## Exemplo de uso

Entrada (prompt para categorização de produto):

```
Camisa social masculina azul, tamanho M
```

Saída esperada:

```
Categoria: Vestuário Masculino > Camisas
Tokens usados: 25
```

Entrada (prompt para geração de imagem):

```
Uma sacola de compras ecológica feita de tecido reutilizável, com logotipo minimalista
```

Saída:

```
Link ou arquivo da imagem gerada.
```
---
## Observações

Este projeto foi criado para fins de aprendizado e experimentação.É necessário ter uma conta na OpenAI para obter a chave de API. A contagem de tokens e a geração de imagens podem gerar custos na sua conta da OpenAI.

## Licença
Projeto de uso educacional, livre para estudos e modificações.

Desenvolvido com ☕ por Cristielle Reis
