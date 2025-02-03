# Hello, I'm Wan :wave:

<img align="right" width="260" src="octocat.png">

🧑‍💻 Computer science student and aspiring data engineer with  
a passion for building data solutions to drive user engagement.

🛸 Wanderer in the vast virtual space of the internet.

Let's connect with me at [nauqh.dev](https://nauqh.dev) 🌟

Visit my recent launched website at [keleidoscope.app](https://keleidoscope.vercel.app/) 🚀

[![Version](https://img.shields.io/badge/Portfolio-V2.0.0-blue?colorA=363a4f&colorB=b7bdf8&style=for-the-badge&logo=github&logoColor=cad3f5)](https://nauqh.dev)
[![Version](https://img.shields.io/github/stars/nauqh/resonance?colorA=363a4f&colorB=b7bdf8&style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNTYgMjU2Ij4KPHBhdGggZD0iTTIzNS4yNCw4NC4zOGwtMjguMDYsMjMuNjgsOC41NiwzNS4zOWExMy4zNCwxMy4zNCwwLDAsMS01LjA5LDEzLjkxLDEzLjU0LDEzLjU0LDAsMCwxLTE1LC42OUwxNjQsMTM5bC0zMS42NSwxOS4wNmExMy41MSwxMy41MSwwLDAsMS0xNS0uNjksMTMuMzIsMTMuMzIsMCwwLDEtNS4xLTEzLjkxbDguNTYtMzUuMzlMOTIuNzYsODQuMzhhMTMuMzksMTMuMzksMCwwLDEsNy42Ni0yMy41OGwzNi45NC0yLjkyLDE0LjIxLTMzLjY2YTEzLjUxLDEzLjUxLDAsMCwxLDI0Ljg2LDBsMTQuMjEsMzMuNjYsMzYuOTQsMi45MmExMy4zOSwxMy4zOSwwLDAsMSw3LjY2LDIzLjU4Wk04OC4xMSwxMTEuODlhOCw4LDAsMCwwLTExLjMyLDBMMTguMzQsMTcwLjM0YTgsOCwwLDAsMCwxMS4zMiwxMS4zMmw1OC40NS01OC40NUE4LDgsMCwwLDAsODguMTEsMTExLjg5Wm0tLjUsNjEuMTlMMzQuMzQsMjI2LjM0YTgsOCwwLDAsMCwxMS4zMiwxMS4zMmw1My4yNi01My4yN2E4LDgsMCwwLDAtMTEuMzEtMTEuMzFabTczLTEtNTQuMjksNTQuMjhhOCw4LDAsMCwwLDExLjMyLDExLjMybDU0LjI4LTU0LjI4YTgsOCwwLDAsMC0xMS4zMS0xMS4zMloiIHN0eWxlPSJmaWxsOiAjQ0FEM0Y1OyIvPgo8L3N2Zz4=)](https://keleidoscope.vercel.app)
![Discord](https://img.shields.io/discord/574921006817476608.svg?style=for-the-badge&color=c6a0f6&labelColor=363a4f&logo=discord&logoColor=cad3f5)

## A little more about me..

```typescript
import { useState, useEffect } from "react";

const Wan = ({ 
    name = "Wan",
    pronouns = "He/Him", 
    askMeAbout = ["data engineering", "data analysis", "software development"] 
}) => {
    const [currentFocus, setCurrentFocus] = useState("I'm building an AI Assistant for Data Science courses");

    useEffect(() => {
        console.log("Fun Fact: I love movies 🎬 and music 🎵");
    }, []);

    const technologies = {
        software: {
            typescript: ["React", "Nextjs"],
            python: ["Django", "Fastapi", "Streamlit"],
        },
        data: {
            ml: ["Pandas", "Numpy", "Pytorch",  "Langchain"],
            engineering: ["PySpark", "Databricks"],
            databases: ["PostgreSQL", "MongoDB", "SQLite"],
        },
        visualization: ["Plotly", "Tableau", "PowerBI"]
    };

    return (
        <>
            <Name>{name}</Name>
            <Pronouns>{pronouns}</Pronouns>
            
            <Language>
                Python, TypeScript, SQL, Java
            </Language>
            
            <AskMeAbout>{askMeAbout}</AskMeAbout>
            
            <Technologies>
                {Object.entries(technologies).map(([category, techs]) => (
                    <div key={category}>
                        <h3>{category}</h3>
                        <p>{Object.entries(techs).map(([tech, tools]) => `${tech}: ${tools.join(", ")}`).join(" | ")}</p>
                    </div>
                ))}
            </Technologies>
            
            <Readings books={[
                "The Data Warehouse Toolkit",
                "Solution Architect's Handbook",
                "Storytelling with Data"
            ]} />
            
        </>
    );
};

export default Wan;
```

## Languages & Tools
![Python](https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white&colorB=00b4d8)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white&colorB=0096c7)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=white&&colorB=a594f9)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white&&colorB=9d4edd)
![Fastapi](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white&colorB=6f2dbd)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-59666C?style=for-the-badge&logo=Prisma&logoColor=white)

![Chakra](https://img.shields.io/badge/chakra-%234ED1C5.svg?style=for-the-badge&logo=chakraui&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white&colorB=52b788)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white&colorB=40916c)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&colorB=ffdd00)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=power-bi&logoColor=white&colorB=ffc300)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-web-services&logoColor=white)

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white&colorB=ff758f)
![Streamlit](https://img.shields.io/badge/Streamlit%20-%2300599C.svg?&style=for-the-badge&logo=streamlit&colorB=ff4d6d&logoColor=white)
![Tensorflow](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=TensorFlow&logoColor=white&colorB=c9184a)

## Achievements
<!-- [![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=nauqh&repo=resonance&show_owner=true)](https://github.com/nauqh/resonance)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=nauqh&repo=porobot&show_owner=true)](https://github.com/nauqh/porobot) -->

![Visitors](https://komarev.com/ghpvc/?username=nauqh&label=Profile+views&style=for-the-badge)

[![Github Stats](https://github-readme-stats.vercel.app/api?username=nauqh&count_private=true&show_icons=true&rank_icon=github)](https://github.com/nauqh/nauqh)
