node{
    stage('Clonar repositorio'){
        git 'https://github.com/dayannamac/app-web2-backend'
    }
    
    stage ('Limpieza'){
        bat 'D:/Servidor/apache-maven-3.9.8/bin/mvn.cmd clean'
    }
    
    stage ('Construir'){
        bat 'D:/Servidor/apache-maven-3.9.8/bin/mvn.cmd package'
    }
}
