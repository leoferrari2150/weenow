# weenow

<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Cadastro</title>
    <link 
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
        rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
        crossorigin="anonymous">
    <link 
        rel="stylesheet"
        href="https://use.fontawesome.com/releases/v5.12.1/css/all.css"
        crossorigin="anonymous">
    <style>
        .center-container {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: linear#470b96 ;
        }
        .form-box {
            background-color: linear #470b96 , #3c0980, #640dd4);
            padding: 30px;
            border: 1px solid #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .form-box h3 {
            margin-bottom: 20px;
            color: #470b96;
        }
        .btn-primary {
            width: 100%;
        }
        .modal-content {
            border-radius: 8px;
            border: 1px solid #470b96;
        }
    </style>
</head>
<body>
    <!-- Barra de Navegação -->
    <nav class="navbar bg-body-tertiary">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">
                WEENOW | STUDY
            </a>
        </div>
    </nav>
    
    <!-- Container Principal Centralizado -->
    <div class="container center-container">
        <div class="form-box w-50">
            <!-- Título -->
            <div class="text-center">
                <h3>Cadastro</h3>
            </div>
            
            <!-- Formulário de Cadastro -->
            <div class="mb-3">
                <input type="text" class="form-control" placeholder="Nome Completo">
            </div>
            <div class="mb-3">
                <input type="email" class="form-control" placeholder="Email">
            </div>
            <div class="mb-3">
                <input type="text" class="form-control" placeholder="CPF">
            </div>
            <div class="mb-3">
                <input type="text" class="form-control" placeholder="Curso">
            </div>
            
            <!-- Botão Enviar -->
            <div class="text-center">
                <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#addNewProduct">
                    Enviar

                </button>
            </div>
        </div>
    </div>
    <script 
        src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" 
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" 
        crossorigin="anonymous"></script>
</body>
</html>
