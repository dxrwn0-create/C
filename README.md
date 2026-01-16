graph TD
    A["REGISTROS CONTABLES<br/>CONTAC S.A."] --> B["LIBROS PRINCIPALES<br/>Obligatorios - Código Comercio"]
    A --> C["LIBROS AUXILIARES<br/>Detallados"]
    
    B --> B1["📖 Libro Diario<br/>Cronológico<br/>Todas transacciones"]
    B --> B2["📖 Libro Mayor<br/>Clasificado por cuentas"]
    B --> B3["📖 Libro Balances<br/>Patrimonio en fecha"]
    B --> B4["📖 Libro Copiador<br/>Cartas"]
    
    C --> C1["📋 Libro Compras<br/>Facturas proveedores<br/>restaurantes"]
    C --> C2["📋 Libro Ventas<br/>Boletas/facturas<br/>clientes"]
    C --> C3["📋 Libro Remuneraciones<br/>6 colaboradores"]
    C --> C4["📋 Libro Banco<br/>Flujos restaurantes"]
    
    B1 -.->|Base| B2
    C1 -.->|Detalles| B2
    B3 -.->|Genera| D["📊 ESTADOS FINANCIEROS<br/>NIIF"]
    
    D --> D1["Estado Situación Financiera<br/>Activos/Pasivos/Patrimonio"]
    D --> D2["Estado Resultados Integral<br/>Ingresos/Gastos"]
    
    style A fill:#2196F3,color:#fff
    style B fill:#9C27B0,color:#fff
    style C fill:#9C27B0,color:#fff
    style D fill:#4CAF50,color:#fff
    style B1 fill:#E1BEE7
    style C1 fill:#E1BEE7
