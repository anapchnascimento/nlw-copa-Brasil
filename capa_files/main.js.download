function createGame(player1, country1, hour, player2, country2) {
  return `
  <li>
        <img src="./assets/icon-${player1}.svg" alt="Bandeira do ${player1}">
        <span>${country1}</span>
      <strong>${hour}</strong>
        <img src="./assets/icon-${player2}.svg" alt="Bandeira da ${player2}">
        <span>${country2}</span>
  </li>
  `
}


function createCard(date, day, games, country) {

  return `
        <div class="card">
            <h2>${date}<span>${day}</span></h2>
            <ul>
            ${games}
            </ul>
        </div>
  `
}

document.querySelector("#cards").innerHTML =
  createCard(
    "24/11",
    "quinta",
    createGame("brazil", "Brasil", "16:00", "serbia", "Servia")
  ) +
  createCard(
    "28/11",
    "segunda",
    createGame("brazil", "Brasil", "13:00", "switzerland", "Suiça") 
  ) +
  createCard(
    "02/12",
    "sexta",
    createGame("brazil", "Brasil", "16:00", "cameroon", "Camarões") 
  )
  