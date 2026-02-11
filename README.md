# projeto_iot

Projeto de Afinador de Ukelele, possuindo o feature de reproduzir uma música, e validar se o usuário acertou as notas
2) Link da arquitetura: https://drive.google.com/file/d/1S72J5jAAGq2T988RhY3VVxYV8x4tBH0o/view?usp=sharing

3) a) Microfonme analógico (MAX9814), ESP32, LED's
b) PAYLOAD
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

c) PostgreSQL
d) Springboot/Java (API)
e) Circuito.io
