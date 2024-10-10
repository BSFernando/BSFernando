<div>
  <canvas id="myChart"></canvas>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<script>
  const ctx = document.getElementById('myChart');

  new Chart(ctx, {
    type: 'bar',
    data: {
      labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
      datasets: [{
        label: '# of Votes',
        data: [12, 19, 3, 5, 2, 3],
        borderWidth: 1
      }]
    },
    options: {
      scales: {
        y: {
          beginAtZero: true
        }
      }
    }
  });
</script>

## Hi there 👋 sobre projetos privados entrar em contato...

* [Projeto cat API](https://github.com/BSFernando/Portfolio/tree/main/projeto_api_cat) 
* [Projeto lamna nasus](https://github.com/BSFernando/Portfolio/tree/main/projeto_lamna_nasus)
* [Projeto automação mapas](https://github.com/BSFernando/Portfolio/tree/main/projeto_mapa)
* [Projeto envio mensagens](https://github.com/BSFernando/Portfolio/tree/main/projeto_msgs)
* [Projeto deslizamento de terra U-NET](https://github.com/BSFernando/Portfolio/tree/main/projeto_satelite)
