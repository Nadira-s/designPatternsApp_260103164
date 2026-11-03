# Practical Design Patterns: Applied Engineering Lab

This repository contains standard Java SE 8+ implementations for all 5 multi-pattern architectural challenges from the Design Patterns Lab.

## Tasks Overview

1. **Task 1: Secure Data Exporter Pipeline** (`Strategy` + `Decorator`)
2. **Task 2: Legacy Stock Ticker with Rate Limiting & Caching** (`Adapter` + `Proxy`)
3. **Task 3: Cross-Platform Alert & Incident Engine** (`Bridge` + `Strategy`)
4. **Task 4: E-Commerce Surcharge & Customs Pipeline** (`Adapter` + `Decorator`)
5. **Task 5: Remote Cloud Asset Downloader & Security Gate** (`Bridge` + `Proxy`)

## Compilation & Execution

Compile all classes using standard Java:

```bash
javac -d bin src/task1/*.java src/task2/*.java src/task3/*.java src/task4/*.java src/task5/*.java
```

Run test runners for each task:

```bash
java -cp bin task1.Task1Runner
java -cp bin task2.Task2Runner
java -cp bin task3.Task3Runner
java -cp bin task4.Task4Runner
java -cp bin task5.Task5Runner
```
# designPatternsApp_260103164
