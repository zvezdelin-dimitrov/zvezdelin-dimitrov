<h1>
  Hello, I'm Zvezdo
  <sub>
    <a href="https://www.linkedin.com/in/zvezdelin-dimitrov-a143b4136/" target="_blank">
      <img alt="LinkedIn" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="30"/>
    </a>
  </sub>
</h1>

```c#
public class Zvezdo
{
    public string About { get; } = "Result-driven software engineer with 10+ years of experience";

    public string Focus { get; } = "Proficient in C# and .NET";

    public IEnumerable<string> Web { get; } =
    [
        "ASP.NET Core", "Blazor", "SignalR"
    ];    

    public IEnumerable<string> Azure { get; } =
    [
        "App Services", "Functions", "Static Web Apps", "Storage", "Entra ID"
    ];        

    public IEnumerable<string> Databases { get; } =
    [
        "SQL", "SQL Server", "PostgreSQL", "MySQL", "SQLite", "Entity Framework", "ADO.NET"
    ];

    public IEnumerable<string> Client { get; } =
    [
        "XAML", "MAUI", "WinUI 3", "Xamarin", "WPF", "UWP"
    ];

    public IEnumerable<string> FrontEnd { get; } =
    [
        "HTML", "CSS", "Bootstrap", "Tailwind", "JavaScript", "jQuery", "TypeScript"
    ];

    public IEnumerable<string> Certifications { get; } =
    [
        "Azure Developer Associate", "Azure AI Engineer Associate", "CAPM", "TOGAF", "ITIL Foundation", "PSM I"
    ];
}
