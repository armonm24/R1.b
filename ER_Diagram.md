erDiagram
User ||..|{ reminder : sets
    timer ||--o{ User: "alerts"
    User ||--o{ timer : "turns off" 
reminder ||--|{ timer : contains
