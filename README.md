# Correção do exercício da Aula03 - Coleções

Neste repositório encontra-se a correção do exercício realizado na Aula 03, com os devidos métodos

## Exemplo de implantação switch/case com letras

Na resolução do exerício foi inserido um *switch/case* com letras, como segue no exemplo

```csharp
//Trecho de código switch/case com letras.
switch (opcaoEscolhida)
{
    case "a":
        ObterPorTipo();
        break;
    case "b":
        ObterPorNome();
        break;
    case "c":
        ObterFuncionariosRecentes();
        break;
    case "d":
        ObterEstatisticas();
        break;
    case "e":
        ValidarSalarioAdmissao();
        break;
    case "f":
        ValidarNome();
        break;
    default:
        Console.WriteLine("Saindo do sistema....");
        break;
}
```

**Referências - Coleções**  
[Referências 1 - listas](https://www.tutorialsteacher.com/csharp/csharp-list)  
[Referências 2 - listas](https://www.dotnetperls.com/list)  
