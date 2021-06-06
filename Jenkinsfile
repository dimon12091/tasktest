node{

stage ("scm_checkout") {

checkout scm: [$class: 'MercurialSCM', source: 'git@github.com:dimon12091/tasktest.git', clean: true, credentialsId: 'github'], poll: false

}

}