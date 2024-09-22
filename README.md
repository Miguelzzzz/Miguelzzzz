<!-- Título e descrição -->
# Olá! Eu me chamo Miguel Marcondes!

> Desenvolvedor Full-Stack

<!-- Descrição pessoal e conquistas -->
- 🎓 Estou atualmente finalizando o ultimo semestre do Ensino Médio com Habilitação Profissional de Técnico Em Informática para Internet pela ETEC de Franco da Rocha.
- 💻 Realizo de forma autônoma estudos sobre programação em meu tempo livre.

<!-- Ferramentas e tecnologias -->
### Tecnologias Utilizadas

<p align="left">
    <a href="https://www.w3schools.com/html/" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain.svg" alt="HTML" width="40" height="40"/>
    </a>
    <a href="https://www.w3schools.com/css/" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain.svg" alt="CSS" width="40" height="40"/>
    </a>
    <a href="https://www.javascript.com/" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" alt="JavaScript" width="40" height="40"/>
    </a>
    <a href="https://www.java.com/" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-plain.svg" alt="Java" width="40" height="40"/>
    </a>
    <a href="https://www.php.net/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" width="40" height="40"/>
    </a>
    <a href="https://www.mysql.com/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" alt="MySQL" width="40" height="40"/>
    </a>
    <a href="https://getbootstrap.com/" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap" width="40" height="40"/>
    </a>
    <a href="https://laravel.com/" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-original.svg" alt="Laravel" width="40" height="40"/>
    </a>
    <a href="https://git-scm.com/" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg" alt="Git" width="40" height="40"/>
    </a>
    <a href="https://developer.android.com/studio" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/androidstudio/androidstudio-original.svg" alt="Android Studio" width="40" height="40"/>
    </a>
    <a href="https://insomnia.rest/" target="_blank">
        <img src="https://github.com/get-icon/geticon/raw/master/icons/insomnia.svg" alt="Insomnia" width="40" height="40"/>
    </a>
    <a href="https://code.visualstudio.com/" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="VS Code" width="40" height="40"/>
    </a>
</p>

<!-- Gráfico de Estatísticas -->
<h3>📊 Minhas Estatísticas de Linguagens</h3>
<canvas id="languageChart" width="400" height="400"></canvas>

<!-- Adicionando o Chart.js via CDN -->
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<script>
    // Gráfico de Pizza das linguagens mais utilizadas
    const ctx = document.getElementById('languageChart').getContext('2d');
    const languageChart = new Chart(ctx, {
        type: 'pie',
        data: {
            labels: ['PHP', 'JavaScript', 'HTML', 'CSS', 'Java', 'MySQL'],
            datasets: [{
                label: 'Languages',
                data: [40, 25, 15, 10, 5, 5], // Exemplo de dados, você pode substituir pelos seus
                backgroundColor: [
                    'rgba(75, 192, 192, 0.2)',
                    'rgba(255, 206, 86, 0.2)',
                    'rgba(255, 99, 132, 0.2)',
                    'rgba(54, 162, 235, 0.2)',
                    'rgba(153, 102, 255, 0.2)',
                    'rgba(201, 203, 207, 0.2)'
                ],
                borderColor: [
                    'rgba(75, 192, 192, 1)',
                    'rgba(255, 206, 86, 1)',
                    'rgba(255, 99, 132, 1)',
                    'rgba(54, 162, 235, 1)',
                    'rgba(153, 102, 255, 1)',
                    'rgba(201, 203, 207, 1)'
                ],
                borderWidth: 1
            }]
        },
        options: {
            responsive: true,
            plugins: {
                legend: {
                    position: 'top',
                },
            }
        }
    });
</script>
