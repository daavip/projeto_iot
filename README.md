## 2. Arquitetura e Especificações

### a) Arquitetura Provável (V1)

**Link da arquitetura:** [Visualizar arquitetura](https://drive.google.com/file/d/1S72J5jAAGq2T988RhY3VVxYV8x4tBH0o/view?usp=sharing)

### b) Desenho (print) (V1)

<img width="615" height="565" alt="image" src="https://github.com/user-attachments/assets/519e2acd-8b9c-4f9a-888c-b245334d306d" />


---

## 3. Especificações Técnicas

### a) Ferramentas que serão usadas

- **Microfone analógico:** MAX9814
- **Microcontrolador:** ESP32
- **Componentes visuais:** LEDs

### b) Formato de Dados (JSON)

**PAYLOAD**

```json
{
  "musica_id": 1,
  "nome": "Asa Branca",
  "notas": [
    {
      "nota": "C4",
      "tempo_ms": 0
    },
    {
      "nota": "E4",
      "tempo_ms": 500
    },
    {
      "nota": "G4",
      "tempo_ms": 1000
    },
    {
      "nota": "C5",
      "tempo_ms": 1500
    }
  ]
}
```

### c) Banco de Dados de Persistência

**PostgreSQL**

### d) Tecnologia/Linguagem para API

**.NET / C#** (API)

### e) Plataforma de Prototipagem

**Circuito.io**
