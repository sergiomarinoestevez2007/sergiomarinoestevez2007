
<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=sergiomarinoestevez2007&show_icons=true&theme=gotham&hide_border=true&count_private=true" alt="Estadísticas de GitHub de Sergio Marino" />
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sergiomarinoestevez2007&layout=compact&theme=gotham&hide_border=true" alt="Lenguajes más usados por Sergio Marino" />

</div>

%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#0d1117',
      'primaryTextColor': '#c9d1d9',
      'primaryBorderColor': '#30363d',
      'lineColor': '#58a6ff',
      'secondaryColor': '#161b22',
      'tertiaryColor': '#21262d'
    }
  }
}%%

flowchart TD
    %% Estilos CSS con Animaciones
    classDef main fill:#1f6feb,stroke:#58a6ff,stroke-width:2px,color:#fff,font-weight:bold;
    classDef nodeStyle fill:#161b22,stroke:#30363d,stroke-width:1.5px,color:#c9d1d9;
    classDef highlight fill:#238636,stroke:#2ea043,stroke-width:2px,color:#fff,font-weight:bold;
    classDef animated stroke:#a371f7,stroke-width:2px,animation:pulse 2s infinite;

    %% Definición de Keyframes para animación de pulso
    linkStyle default stroke:#58a6ff,stroke-width:1.5px;

    %% Estructura
    ME(["🚀 Tu Nombre / Handle"]):::main
    
    ME --> ROLE["💻 Rol Principal<br/><i>Software Engineer / Fullstack</i>"]:::highlight
    ME --> STACK["⚡ Tech Stack"]:::nodeStyle
    ME --> GOALS["🎯 En lo que estoy trabajando"]:::nodeStyle
    ME --> CONNECT["📫 Contacto & Redes"]:::nodeStyle

    %% Detalle de Stack
    STACK --> S1["<b>Frontend:</b> React, Vue, Tailwind"]:::nodeStyle
    STACK --> S2["<b>Backend:</b> Node.js, Python, Go"]:::nodeStyle
    STACK --> S3["<b>Tools:</b> Docker, Git, CI/CD"]:::nodeStyle

    %% Detalle de Proyectos / Objetivos
    GOALS --> G1["📌 Proyecto A <i>(Breve descripción)</i>"]:::animated
    GOALS --> G2["🌱 Aprendiendo: <i>Rust / Cloud Architecture</i>"]:::nodeStyle

    %% Contacto
    CONNECT --> C1["💬 LinkedIn | X | Portfolio"]:::nodeStyle
