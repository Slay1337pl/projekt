node
{
	checkout scm
	stage('Kopiuj i uruchom'){
		sh 'ssh kacper@localhost mkdir projektfinished'
		sh 'ssh kacper@localhost cd projektfinished'
		sh 'ssh kacper@localhost git clone git://github.com/slay1337pl/projekt'
		sh 'ssh kacper@localhost docker-compose up'
			}

}
