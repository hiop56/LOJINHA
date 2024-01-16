<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>
        lojinha

    </title>


    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="stlye.css">
<script src="js/funcoes.js"></script>
</head>



<body>
    <div class="container">
        <h1><i id="cifrao" class="bi bi-currency-dollar"></i>LOJINHA DA UNIDADE</h1>

        <table class="table table-hover table-bordered">
            <thead>
                <tr>
                    <th>Imagem</th>
                    <th>Produto</th>
                    <th>Preço Unitário</th>
                    <th>Qtd</th>
                    <th>Total</th>
                </tr>
                <br>

            </thead>
            <tbody>
                <tr>
                    <td>
                        <img src="img/celular.jpg" alt="Produto 1" width="125px">
                    </td>
                    <td>
                        <div>
                            Celular Baratim
                        </div>

                        <div><span class="produto-item">Código do produto: 123</span></div>
                        <div> <span class="produto-item">Cor: vermelha</span></div>
                    </td>
                    <td id="valor_1"> R$ 1.000</td>
                    <td>
                        <span class="badge bg-danger" onclick="alterarQtd(1, '-')"><i class="bi bi-dash"></i> </i></span>
                        <span id="quantidade_1">0</span>
                        <span class="badge bg-success" onclick="alterarQtd(1, '+')"><i class="bi bi-plus-lg"></i></span>
                    </td>
                    <td id="total_1"> 0 </td>
                </tr>
                <tr>
                    <td>
                        <img src="img/PRODUTO2.jpg" alt="Produto 2 " width="200px">
                    </td>
                    <td>
                        <div>
                            NOTBOOK
                        </div>

                        <span class="produto-item">Código do produto: 12345</span></div>
                        <div> <span class="produto-item">Cor: prata</span></div>
                    </td>
                    </td>
                    <td id="valor_2">R$ 5.000</td>
                    <td>
                        <span class="badge bg-danger" onclick="alterarQtd(2,'-')"><i class="bi bi-dash"></i> </i></span>
                        <span id="quantidade_2">0</span>
                        <span class="badge bg-success" onclick="alterarQtd(2,'+')"><i class="bi bi-plus-lg"></i></span>
                    </td>
                    <td id="total_2"> 0 </td>
                </tr>
                <tr>
                    <td>
                        <img src="img/PRODUTO3.jpg" alt="Produto 3" width="200px">
                    </td>
                    <td>
                        <div>
                            TELEVISÃO
                        </div>

                        <span class="produto-item">Código do produto: 123456</span></div>
                        <div> <span class="produto-item">Cor: preto</span></div>
                    </td>
                    </td>
                    <td id="valor_3"> R$ 2.000</td>
                    <td>
                        <span class="badge bg-danger" onclick="alterarQtd(3,'-')"><i class="bi bi-dash"></i> </i></span>
                        <span id="quantidade_3">0</span>
                        <span class="badge bg-success" onclick="alterarQtd(3,'+')"><i class="bi bi-plus-lg"></i></span>
                    </td>
                    <td id="total_3">0</td>
                </tr>





            </tbody>

        </table>


        <br>
        <footer class="text-center"></i>
            <span class="bi bi-cart4"></i>Subtotal:<span id="subtotal"> R$ 0 </span>

        </footer>

    </div>
    <br>
</body>

</html>
