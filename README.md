```c#
public class DeveloperController : Controller
{
    [HttpGet("/developer")]
    public IActionResult GetDeveloperInfo()
    {
        Developer dev = new Developer(
            name: "Jhonatan Azevedo",
            role: "Developer",
            work: "Tributo Justo",
            academicEducation: "Análise e desenvolvimento de sistema",
            skills: new List<string>
            {
                "C#", "ASP.NET", "Entity Framework", ".Net 7", "Node JS", "TypeScript", "JavaScript", 
                "React JS", "React Native", "Vue JS", "Vuex", "HTML5", "CSS3", "Bootstrap", "Tailwind", "Figma",
                "SqlServer", "PostgresSql", "MySql"
            }
        );

        return Ok(dev);
    }
}
```

## Contact

<p align="left">
  <a href="https://www.linkedin.com/in/dev-azevedo/" alt="Linkedin Jhonatan Azevedo" target="_blank">
  <img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

  <a href="mailto:dev.azevedo@outlook.com" alt="Email Jhonatan Azevedo">
  <img src="https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" /></a>

<a href="https://drive.google.com/file/d/1BEsUXEV6YfbhXd8x4H6Y48YJoFAdEuja/view" alt="Curriculo Jhonatan Azevedo">📄 Curriculum ✌🏼</a>
</p>
