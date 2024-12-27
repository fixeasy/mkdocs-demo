<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Compétences Techniques</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f9;
      color: #333;
    }

    .container {
      max-width: 1200px;
      margin: 20px auto;
      padding: 20px;
    }

    h1, h2 {
      text-align: center;
      color: #444;
    }

    .note, .tip {
      background-color: #e8f4fd;
      border-left: 4px solid #2196F3;
      padding: 10px 15px;
      margin: 20px 0;
      border-radius: 5px;
    }

    .tip {
      background-color: #fdf4e4;
      border-left-color: #FFC107;
    }

    .skills-section {
      margin-bottom: 40px;
    }

    .skills-category {
      background: #ffffff;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      padding: 20px;
      margin-bottom: 20px;
    }

    .skills-category h3 {
      color: #333;
      border-bottom: 2px solid #eee;
      padding-bottom: 10px;
      margin-bottom: 20px;
    }

    .skill {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 15px;
    }

    .skill-name {
      font-size: 1.1em;
      font-weight: 600;
      color: #555;
    }

    .gauge {
      flex: 1;
      height: 10px;
      background-color: #e0e0e0;
      border-radius: 5px;
      margin: 0 15px;
      position: relative;
    }

    .gauge .level {
      height: 100%;
      border-radius: 5px;
    }

    .gauge .level-5 {
      width: 100%;
      background-color: #4caf50;
    }

    .gauge .level-4 {
      width: 80%;
      background-color: #8bc34a;
    }

    .gauge .level-3 {
      width: 60%;
      background-color: #ffc107;
    }

    .gauge .level-2 {
      width: 40%;
      background-color: #ff9800;
    }

    .gauge .level-1 {
      width: 20%;
      background-color: #f44336;
    }

    .level-label {
      font-size: 0.9em;
      color: #888;
    }

    .legend {
      margin-top: 30px;
      background-color: #fff;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .legend table {
      width: 100%;
      border-collapse: collapse;
    }

    .legend th, .legend td {
      text-align: left;
      padding: 8px;
    }

    .legend th {
      background-color: #f4f4f4;
    }

    .legend td {
      border-top: 1px solid #eee;
    }
    
  </style>
</head>

<body>
  <div class="container">
    <h1>Compétences Techniques</h1>

    <div class="note">
      <strong>🔑 Note importante :</strong> La légende des niveaux de compétence se trouve <strong>en bas de cette page</strong>. N'oubliez pas d'y jeter un œil pour comprendre les critères de chaque niveau !
    </div>

    <div class="tip">
      <strong>💡 Astuce :</strong> Cliquez sur une compétence pour découvrir plus de détails !
    </div>

    <div class="skills-section">
      <div class="skills-category">
        <h3>🛠️ Cloud Computing</h3>
        <div class="skill">
          <span class="skill-name">Azure</span>
          <div class="gauge"><div class="level level-4"></div></div>
          <span class="level-label">4/5</span>
        </div>
        <div class="skill">
          <span class="skill-name">AWS</span>
          <div class="gauge"><div class="level level-4"></div></div>
          <span class="level-label">4/5</span>
        </div>
      </div>

      <div class="skills-category">
        <h3>⚙️ Infrastructure as Code (IaC)</h3>
        <div class="skill">
          <span class="skill-name">Terraform</span>
          <div class="gauge"><div class="level level-5"></div></div>
          <span class="level-label">5/5</span>
        </div>
        <div class="skill">
          <span class="skill-name">Ansible</span>
          <div class="gauge"><div class="level level-4"></div></div>
          <span class="level-label">4/5</span>
        </div>
        <div class="skill">
          <span class="skill-name">Helm</span>
          <div class="gauge"><div class="level level-3"></div></div>
          <span class="level-label">3/5</span>
        </div>
      </div>

      <div class="skills-category">
        <h3>🚀 CI/CD Pipelines</h3>
        <div class="skill">
          <span class="skill-name">GitLab CI</span>
          <div class="gauge"><div class="level level-5"></div></div>
          <span class="level-label">5/5</span>
        </div>
        <div class="skill">
          <span class="skill-name">Jenkins</span>
          <div class="gauge"><div class="level level-4"></div></div>
          <span class="level-label">4/5</span>
        </div>
        <div class="skill">
          <span class="skill-name">GitHub Actions</span>
          <div class="gauge"><div class="level level-3"></div></div>
          <span class="level-label">3/5</span>
        </div>
      </div>

      <div class="skills-category">
        <h3>🐳 Conteneurs et Orchestrateurs</h3>
        <div class="skill">
          <span class="skill-name">Docker</span>
          <div class="gauge"><div class="level level-5"></div></div>
          <span class="level-label">5/5</span>
        </div>
        <div class="skill">
          <span class="skill-name">Kubernetes</span>
          <div class="gauge"><div class="level level-4"></div></div>
          <span class="level-label">4/5</span>
        </div>
        <div class="skill">
          <span class="skill-name">ArgoCD</span>
          <div class="gauge"><div class="level level-3"></div></div>
          <span class="level-label">3/5</span>
        </div>
      </div>
    </div>

    <div class="legend">
      <h3>Légende des niveaux de compétence</h3>
      <table>
        <tr>
          <th>Niveau</th>
          <th>Description</th>
        </tr>
        <tr>
          <td>1</td>
          <td>Connaissance théorique uniquement.</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Utilisation basique : besoin d’être accompagné pour approfondir.</td>
        </tr>
        <tr>
          <td>3</td>
          <td>Fonctionnel : déjà utilisé dans un projet, mais avec quelques limites.</td>
        </tr>
        <tr>
          <td>4</td>
          <td>Maîtrise : utilisation autonome, capable de gérer des projets complexes.</td>
        </tr>
        <tr>
          <td>5</td>
          <td>Expert : maîtrise complète, capable de former d’autres personnes.</td>
        </tr>
      </table>
    </div>
  </div>
</body>
</html>
