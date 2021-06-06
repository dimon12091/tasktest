node{

stage ("scm_checkout") {

git branch: 'master',
    credentialsId: 'github',
    url: 'git@github.com:dimon12091/tasktest.git'

}

stage ("Checkout to different branch") {

sh “git branch -r”


}

stage ("package stage") {

sh label: ‘’, script: ‘mvn clean package ‘

}

}