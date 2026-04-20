# una-blazor-lista12

## Identificação

**Nome completo:** Arthur Cantarutti Caldeira  
**Curso:** Ciência da Computação  

## Heurísticas de Nielsen

### 1. Visibilidade do Status do Sistema
A aplicação mostra ao usuário, em tempo real, o total acumulado de pontos sempre que uma atividade é registrada. Isso garante um feedback imediato da ação realizada.

### 2. Consistência e Padronização
Os cards seguem o mesmo padrão visual e estrutural, com título, pontuação por ação, total acumulado e botão de registro. Isso facilita o entendimento e a navegação do usuário.

## Guia de Execução

1. Clone o repositório:

```bash
git clone https://github.com/guilhermeahs/una-blazor-lista12.git
```

2. Entre na pasta do projeto:

```bash
cd una-blazor-lista12
```

3. Restaure os pacotes:

```bash
dotnet restore
```

4. Execute a aplicação:

```bash
dotnet run
```

5. Abra no navegador o endereço exibido no terminal.

## Explicação Técnica

O componente foi pensado para ser reutilizável no Blazor por meio da passagem de dados por parâmetros. O uso de `[Parameter]` permite que informações como título da ação, quantidade de pontos e valor acumulado sejam recebidas dinamicamente pelo componente, evitando repetição de código e facilitando a manutenção. Dessa forma, o mesmo componente pode ser reutilizado para representar diferentes ações ambientais apenas alterando os valores recebidos.
