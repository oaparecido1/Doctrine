# Curso de Doctrine da Alura- [x] Modelagem do Banco de dados utilizando SQLite    > Vale lembrar que o ORM funciona com qualquer Banco, seja relacional ou não relacional!- [x] Feito 100% com classes, 0% de código SQL na mão!### Connection do BD:```json $connection = [            'driver' => 'pdo_sqlite',            'path' => $rootDir . '/var/data/banco.sqlite'        ];```- path: Local onde será arquivo o banco!    > $rootDir simboliza o diretório raiz.                                    - driver: driver pdo a ser utilizado, neste caso o pdo sqlite!    > Se fosse ser utilizado o MySQL, por exemplo, teríamos o pdo_mysql.    - ## Meus agradecimentos a Alura!                                                                  