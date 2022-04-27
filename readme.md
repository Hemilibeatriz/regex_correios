Padrão Regex para o os dados do Correios em Python

A partir de uma lista de códigos e os seus significados, o código:
    com os dados de entrada verifica se o padrão regex é satisfeito,
        caso negativo: ele gera um "Código de Entrada Inválido"
        caso positivo:
            verifica as duas primeiras letras para ver qual a classificação:
                caso negativo : faz parte do padrão, mas sem classificação
                caso positivo:
                    verifica o pais de origem (duas últimas letras)