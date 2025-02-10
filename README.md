```c#
namespace DevAzevedo.Controllers;

[Route("api/[controller]")]
[ApiController]
public class DeveloperController : ControllerBase
{
    [HttpGet]
    public IActionResult GetDeveloperInfo()
    {
        Developer dev = new Developer(
            name: "Jhonatan Azevedo",
            role: "FullStack Developer",
            work: "Tributo Justo",
            academicEducation: new List<string> 
            { 
                "Análise e Desenvolvimento de Sistemas", 
                "Ciência de Dados e Inteligência Artificial" 
            },
            skills: new List<string>
            {
                "C#", ".Net", "ASP.NET", "Entity Framework", "Identity Framework", 
                "NodeJs", "ExpressJs", "NestJs", "TypeScript", "JavaScript", "TypeORM", "Prisma",
                "Python", "Django", "FastAPI", "Flask", "SQLAlchemy", "Pandas", 
                "ReactJs", "React Native", "VueJs", "Vuex", "HTML5", "CSS3", "Bootstrap", "Tailwind",
                "SqlServer", "PostgresSql", "MySql", "SqLite", "MongoDb",
                "Docker", "Docker-compose", "GIT/GitHub", "RabbitMQ", "Figma"
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

  <a href="mailto:dev.azevedo@outlook.com" alt="Email Jhonatan Azevedo" target="_blank">
  <img src="https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" /></a>

 <a href="https://drive.google.com/file/d/1NHg3RAuSjHA8FPb1SKxSu9xxhbeDL7Z5/view" alt="Curriculo Jhonatan Azevedo" target="_blank">📄 Curriculum ✌🏼</a>

</p>
