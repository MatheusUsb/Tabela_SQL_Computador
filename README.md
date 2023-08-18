#Tabela_SQL_Computador

-- Criação da tabela
CREATE TABLE Computador (
    ID INT PRIMARY KEY,
    Nome VARCHAR(50),
    Processador VARCHAR(50),
    MemoriaRAM INT,
    ArmazenamentoGB INT
);

-- Inserção de dados fictícios
INSERT INTO Computador (ID, Nome, Processador, MemoriaRAM, ArmazenamentoGB)
VALUES
    (1, 'Computador A', 'Intel Core i5', 8, 256),
    (2, 'Computador B', 'AMD Ryzen 7', 16, 512),
    (3, 'Computador C', 'Intel Core i7', 16, 1024),
    (4, 'Computador D', 'AMD Ryzen 5', 8, 512),
    (5, 'Computador E', 'Intel Core i9', 32, 2048);

