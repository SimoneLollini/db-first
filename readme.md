Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
# Cars: #
  *  id | BIGINT PK AI NOTNULL UNIQUE
  *  brand | VARCHAR(20) | NOTNULL
  *  model | VARCHAR(40) | NOTNULL
  *  price | DECIMAL(7, 2) | NULL
  *  km | DECIMAL(7, 1) | NULL
  *  year | YEAR | NULL
  *  engine | VARCHAR(10) | NULL
  *  color | VARCHAR(15) | NULL
  *  image| VARCHAR(255) |NULL
  *  description | TEXT | NULL


