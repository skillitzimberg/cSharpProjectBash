ProjectName.Solution
├── ProjectName
│   ├── ProjectName.csproj
│   ├── Models
│   │   └── ClassName.cs
│   └── obj
│        └── (omitted for brevity)
└── ProjectName.Tests
    ├── ProjectName.Tests.csproj
    ├── ModelTests
    │   └── ClassNameTests.cs
    └── obj
        └── (omitted for brevity)

mkdir ProjectName.Solution
cd ProjectName.Solution
touch README.md
mkdir ProjectName ProjectName.Tests
touch ProjectName/ProjectName.csproj ProjectName.Tests/ProjectName.Tests.csproj
mkdir ProjectName/Models ProjectName.Tests/ModelTests
touch ProjectName/Models/ClassName.cs ProjectName.Tests/ModelTests/ClassNameTests.cs
