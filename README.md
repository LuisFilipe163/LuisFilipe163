<h1 align="center">Oi 👋, eu sou o Luis Filipe Rezende</h1>

<p align="center">Desenvolvedor back-end .NET · Tecnólogo em Análise e Desenvolvimento de Sistemas</p>

<p align="center">
  <a href="https://luisfiliperezende.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfólio-luisfiliperezende.vercel.app-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfólio"/>
  </a>
  <a href="https://www.linkedin.com/in/luis-filipe-rezende/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=LuisFilipe163&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
</p>

---

### Sobre mim

Sou formado em Análise e Desenvolvimento de Sistemas e fiz dois anos de estágio na VidrosRio mantendo um ERP em C# em produção, onde adequei a NF-e à Reforma Tributária. Fora do trabalho, construí o Fatura Social: uma API em ASP.NET Core que atende um app Android e um app Windows.

- Aberto a vagas de **desenvolvedor back-end .NET júnior**, remotas ou no Rio de Janeiro
- Inglês avançado (C1, EF SET)
- Contato: [luis.filipe16301@gmail.com](mailto:luis.filipe16301@gmail.com)

<br>

### Experiência

**VidrosRio** · Estagiário de Desenvolvimento de Software · ago/2024 a jul/2026

ERP em **C# .NET Framework 4.8**, com Windows Forms (DevExpress) e MySQL.

- Manutenção e evolução do sistema em produção: correção de falhas em código legado e otimização de consultas
- Adequação da NF-e à **Reforma Tributária (IBS/CBS, NT 2025.002)**, com regras fiscais por operação e validação dos XMLs em testes
- API REST para emissão de NF-e, construída com um desenvolvedor sênior, integrando as DLLs nativas do ACBr

<br>

### Projeto em destaque: [Fatura Social](https://github.com/LuisFilipe163/FaturaSocial)

Dois apps, um Core, uma API. Registra dívidas entre amigos, contas divididas e cobranças por Pix: quem deve aceita a cobrança e informa o pagamento, e quem recebe confirma.

- API em **ASP.NET Core (.NET 10)** com 73 endpoints e **EF Core** sobre SQLite, num servidor Ubuntu atrás do Apache
- App Android em **.NET MAUI com Blazor** e app Windows em **WPF**, dividindo a mesma biblioteca Core
- JWT ligado a uma sessão no banco, revogável por aparelho, com refresh token em rotação e senha em BCrypt
- Avisos em tempo real pelo **SignalR**, e push pelo Firebase no Android quando o app está fechado
- Funciona sem internet nos dois apps: as mudanças entram numa fila no SQLite, e a sincronização junta edições de aparelhos diferentes campo a campo
- Pix no padrão BR Code (EMV, com CRC16), montado no próprio aparelho
- **658 testes** com xUnit em 3 projetos

Fase alfa (v0.1.0). O código-fonte é privado; o link acima leva ao repositório público de apresentação, e os detalhes estão no [portfólio](https://luisfiliperezende.vercel.app/).

<br>

### Linguagens e ferramentas

<p align="left">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET"/>
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core"/>
  <img src="https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white" alt="Blazor"/>
  <img src="https://img.shields.io/badge/.NET_MAUI-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET MAUI"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
</p>
