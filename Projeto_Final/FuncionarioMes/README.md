# Projeto_FuncionarioMes


2)

a - 

    CAMPOS:
        foto
        func
        valor

b -
    
3 - 


4-

    CREATE TABLE tbfuncmes (
        codigo INTEGER(11) NOT NULL AUTO_INCREMENT PRIMARY KEY,
        nome varchar(255) NOT NULL,
        vrvenda FLOAT NOT NULL,
        vrbonus FLOAT NOT NULL,
        caminhoimg VARCHAR(255) NOT NULL,
        mes VARCHAR(50) NOT NULL,
        ano INTEGER(4) NOT NULL
        );