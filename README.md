```csharp
var profile = new DeveloperProfile()
{
    Name = "Jay Russell",
    Role = "Aspiring Full-Stack Software Developer",

    Passion = "Passionate about continuous learning through reading, watching educational resources, and hands-on project building",

    Learning = 
    [
        "All the time", 
        "ASP.NET", 
        "Blazor", 
        "Vue & Web Frameworks", 
        "TypeScript", 
        "Piano"
    ],

    CurrentFocus = 
    [
        "Learning",
        "Finding Job Opportunities",
        "Building a Portfolio to showcase practical projects",
        "Strengthening skills in ASP.NET, Blazor, and Modern Front-End Frameworks",
        "Preparing for software developer roles"
        "Learning DevOps",
    ],

    TechStack = new TechnologyStack()
    {
        Languages =
        [
            "C#",
            "C++",
            "HTML",
            "CSS",
            "TypeScript",
            "JavaScript",
            "SQL"
        ],
        Tools = 
        [
            "Visual Studio",
            "GitHub",
            "Git",
            "Docker",
            "WSL",
            "XUnit"
        ],
        Frameworks =
        [
            ".NET Core",
            "ASP.NET API/Minimal",
            ".NET Blazor",
            "Entity Framework",
            "RabbitMQ",
            "Vue",
            "Angular",
            "Bootstrap"
        ],
        Databases =
        [
            "PostgreSQL",
            "MySQL",
            "Redis"
        ]
    },

    Background = new Background()
    {
        Education = ["Self Taught", "College Educated"],
        Experience = "15+ years of self-driven development with an IT background",
        Philosophy = "Learning is the key to endless possibilities",
        Hobbies = ["Piano", "Learning", "Debugging", "Optimizing", "Gaming"],
        WorkExperience = [];
    },

    Contact = new Contact()
    {
        Email = string.Empty,
        LinkedIn = "https://linkedin.com/in/rusjaellgo",
        Portfolio = "https://rusjaell.github.io"
    }
};
