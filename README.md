
 2-) a-) Arquitetura provável (V1) 
 Link da arquitetura: https://drive.google.com/file/d/1S72J5jAAGq2T988RhY3VVxYV8x4tBH0o/view?usp=sharing

 b-) Desenho (print) (V1) Circuito
<img width="615" height="565" alt="image" src="https://github.com/user-attachments/assets/519e2acd-8b9c-4f9a-888c-b245334d306d" />

3) a) Ferramentas que serão usadas:
Microfonme analógico (MAX9814), ESP32, LED's

b) Formato de Dados (JSON)
PAYLOAD
{
  "musica_id": 1,
  "nome": "Asa Branca",
  "notas": [
    { "nota": "C4", "tempo_ms": 0 },
    { "nota": "E4", "tempo_ms": 500 },
    { "nota": "G4", "tempo_ms": 1000 },
    { "nota": "C5", "tempo_ms": 1500 }
  ]
}

c) Qual BD de Persistência? 
PostgreSQL
d) Qual Tecnologia/Linguagem para API?
Springboot/Java (API)
e) Qual plataforma de Prototipagem 
Circuito.io







