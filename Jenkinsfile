node
{
	checkout scm
	stage('Kopiuj'){
		
		sh 'ssh kacper@localhost mkdir projektfinished'
		sh 'ssh kacper@localhost git clone git://github.com/slay1337pl/projekt projektfinished'
		
			}
	stage('uruchom dockera'){sh 'ssh kacper@localhost docker-compose -f projektfinished/docker-compose.yml up'
			}
}
