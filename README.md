# Validacoes.Documentos

**Biblioteca simples para validação de CPF e CNPJ em .NET**

[![NuGet](https://img.shields.io/nuget/v/Validacoes.Documentos.svg)](https://www.nuget.org/packages/Validacoes.Documentos/)

---

## 📦 Instalação

Instale o pacote via .NET CLI:

dotnet add package Validacoes.Documentos
Ou via Package Manager:

Install-Package Validacoes.Documentos

---

✨ Como usar
Validar CPF

using Validacoes.Documentos;

bool cpfValido = CPFValidator.IsValid("12345678909");
Console.WriteLine(cpfValido); // True ou False
Validar CNPJ

using Validacoes.Documentos;

bool cnpjValido = CNPJValidator.IsValid("11222333000181");
Console.WriteLine(cnpjValido); // True ou False

---

📋 Métodos Disponíveis

Classe	Método	Descrição
CPFValidator	IsValid	Valida se um CPF é válido
CNPJValidator	IsValid	Valida se um CNPJ é válido

---

🔥 Exemplos Avançados
Você também pode validar documentos limpando caracteres especiais:


string cpf = "123.456.789-09";
bool valido = CPFValidator.IsValid(cpf); // true ou false

---

📄 Licença
Este projeto está licenciado sob a licença MIT.

👨‍💻 Autor
Desenvolvido por Washington Gomes.


---

### 📋 Instruções:
1. Crie (ou edite) o arquivo `README.md` na **raiz** do seu projeto
2. Cole exatamente esse conteúdo acima
3. Salve, faça `git add README.md`, `git commit -m "Adiciona README.md completo"`, e `git push`

**🔵 Dica:**  
Quando o seu pacote realmente aparecer no NuGet, o badge `[![NuGet](https://img.shields.io/nuget/v/Validacoes.Documentos.svg)]` vai automaticamente mostrar a versão disponível!

---

**Quer que agora a gente vá para a parte bônus e já configure o GitHub Actions para publicar o pacote automaticamente quando você fizer push de uma nova versão?**  
(Fica super profissional e prático também!) 🚀🎯
