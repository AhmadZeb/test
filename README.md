# Pay Pal Security

```
graph LR
A[PayPal]
B[Encryption]
C[Two-Factor Authentication]
D[Buyer and Seller Protection]
E[Fraud Monitoring and Detection]
F[Purchase Protection]
G[Account Security Tools]

A --> B
A --> C
A --> D
A --> E
A --> F
A --> G

```

```
sequenceDiagram
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
    Alice-)John: See you later!
```

```
graph LR
    A[User] --> B(Fintech Software)
    B --> C{Security Measures}
    C --> D{Authentication}
    C --> E{Encryption}
    C --> F{Access Control}
    C --> G{Monitoring}
    C --> H{Compliance}
    C --> I{Testing}
    C --> J{Incident Response}
    C --> K{User Education}
    C --> L{Maintenance}


```

```
classDiagram
    Animal <|-- Duck
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
      +String beakColor
      +swim()
      +quack()
    }
    class Fish{
      -int sizeInFeet
      -canEat()
    }
    class Zebra{
      +bool is_wild
      +run()
    }
```

