html:<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo - Gabriel Santos de Oliveira</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav>
        <ul>
            <li><a href="#apresentacao">Apresentação</a></li>
            <li><a href="#educacao">Educação</a></li>
            <li><a href="#certificacoes">Certificações</a></li>
            <li><a href="#experiencia">Experiência</a></li>
            <li><a href="#habilidades">Habilidades</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>
    
    <header>
        <h1>Gabriel Santos de Oliveira</h1>
    </header>
    
    <main>
        <section id="apresentacao">
            <h2>Apresentação</h2>
            <img src="sua_foto.jpg" alt="Sua Foto" class="foto-perfil">
            <p><strong>Email:</strong> gabriel.oliveira@pditabira.com</p>
            <p><strong>Cidade:</strong>Itabira</p>
            <p>Procuro cada vez mais buscar aprendizado e melhorar o meu curriculo profissional</p>
        </section>
        
        <section id="educacao">
            <h2>Educação</h2>
            <div>
                <h3>Escola Estadual Trajano Procopio</h3>
                <p><strong>Curso:</strong>Projeto desenvolve</p>
                <p><strong>Ano de Conclusão:</strong>2026</p>
            </div>
        </section>
        
        <section id="certificacoes">
            <h2>Certificações</h2>
            <div>
                <p><strong>excel intermediario senai</strong></p>
                <p><strong>excel</strong>40 horas</p>
                <p><strong>ano:</strong> 2024</p>
            </div>
        </section>
        
        <section id="experiencia">
            <h2>Experiência</h2>
            <div>
                <h3>no momento ainda nn tenho</h3>
                <p><strong>Empresa:</strong> Nome da Empresa</p>
                <p><strong>Período:</strong> XX/XXXX - XX/XXXX</p>
                <p>Responsabilidades e realizações.</p>
            </div>
        </section>
        
        <section id="habilidades">
            <h2>habilidades</h2>
            <ul>
                <li>digitação</li>
                <li>boa comunicação</li>
                <li>focado</li>
            </ul>
        </section>
    </main>
    
    <footer>
        <h2 id="contato"31 91234-5678</h2>
        <ul>
            <li><a href="#">LinkedIn</a></li>
            <li><a href="#">GitHub</a>https://github.com/desenvolveintroducaoweb</li>
        </ul>
        <p>&copy; 2025 - Última atualização</p>
    </footer>
</body>
</html>


css:/* Estilos gerais */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

/* Estilizando o menu de navegação */
nav {
    background-color: #333;
    color: white;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
}
nav ul {
    list-style: none;
    padding: 0;
    text-align: center;
}
nav ul li {
    display: inline;
    margin: 0 15px;
}
nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

/* Cabeçalho */
header {
    text-align: center;
    padding: 60px 20px 20px;
    background-color: #444;
    color: white;
}

/* Seções principais */
main {
    padding: 20px;
    margin-top: 60px;
}
section {
    background: white;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

/* Foto de perfil */
.foto-perfil {
    display: block;
    margin: 10px auto;
    border-radius: 50%;
    width: 150px;
    height: 150px;
    object-fit: cover;
    border: 3px solid #444;
}

/* Rodapé */
footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
}
footer ul {
    list-style: none;
    padding: 0;
}
footer ul li {
    display: inline;
    margin: 0 10px;
}
footer ul li a {
    color: white;
    text-decoration: none;
}

/* Responsividade */
@media (max-width: 600px) {
    nav ul {
        display: block;
        text-align: center;
    }
    nav ul li {
        display: block;
        margin-bottom: 10px;
    }
}
