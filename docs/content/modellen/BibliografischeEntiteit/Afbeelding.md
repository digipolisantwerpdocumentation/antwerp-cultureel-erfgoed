```mermaid
graph LR
22[MensgemaaktObject]-->|Entiteit.wordtVoorgesteldDoor|37[VisueelItem]
91[PublicatieExpressie]-->|Entiteit.wordtVoorgesteldDoor|123[VisueelItem]
91[PublicatieExpressie]-->|InformatieObject.drager|22[MensgemaaktObject]
37[VisueelItem]-.-37_s([uri])
123[VisueelItem]-.-123_s([uri])
style 37_s stroke-dasharray: 5
style 123_s stroke-dasharray: 5
style 123 fill:#ffff00
style 22 fill:#B0927A
style 37 fill:#ffff00
style 91 fill:#ffff00
```
