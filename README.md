<h1 align="center">REACT'I TIC-TAC-TOE MÄNG DOCKERIS.</h1>

See projekt on lihtne trips-traps-trull mäng, mis on loodud Reacti abil ja dockeriseeritud.

## Rakenduse käivitamine Dockeris

1. Veenduge, et Docker on Teie arvutisse installitud.

2. Kloonige see repositoorium:

 `$ git clone https://github.com/jmrtechnnn/TIC-TAC-TOE-GAME.git`

` $ cd TIC-TAC-TOE-GAME `

3. Ehitage Docker image(pane nimeks näiteks tic-tac-toe-react ):

` $ docker build -t tic-tac-toe-react .`

4. Käivitage konteiner:

` $ docker run -p 8080:80 tic-tac-toe-react `

5. Avage veebibrauser ja minge aadressile `http://localhost:8080`

6. Mängige



Originaal: https://github.com/ucfx/TIC-TAC-TOE-GAME

